# Entrega 8 — Ciclo de vida e engenharia de usabilidade

**Data:** 22/10/2026 <br> 
**Status:** 🟨 em andamento<br> 
**Responsabilidade:** 1 solução por equipe<br> 

## Objetivo da atividade

Transformar o conhecimento acumulado sobre usuários, tarefas, plataforma e contexto em princípios e **metas de usabilidade verificáveis**, mantendo o caráter iterativo do projeto.

## Delimitação do sistema interativo <!-- perg sobre integrações/dados simulados -->

Antes das características da plataforma, separe:

| Camada | O que pertence ao projeto | O que será avaliado em IHC |
|---|---|---|
| contribuição técnica do TCC | algorítmo de análise do impacto do formato das avaliações no desempenho dos candidatos | a aplicação que permite os docentes submeterem uma avaliação e obter métricas sobre ela.|
| camada de interação da disciplina | interface | análise da compreensão e clareza das métricas, bem como o impacto potencial da estrutura das questões no desempenho da prova. |
| integrações/dados simulados | as integração usadas para a realização das análises são: Bert para analise dos distraotres e XLM-RoBERTa para análise do formalismo | {{limites do protótipo}} ???????|

<!-- Em um protótipo de disciplina, é aceitável simular processamento ou resultados quando a implementação técnica não estiver integrada, desde que isso seja declarado e a simulação seja suficiente para avaliar a interação. -->

## 1. Características da plataforma
<!-- olhar anotacao aula topico 8-->
| Característica | Descrição | Consequência para IHC |
|---|---|---|
| Software | Vue.js 3 (frontend), Node.js (backend), Python (scripts de análise). Navegador web (Chrome, Firefox, Safari, Edge). Requer npm/Node.js instalado localmente. | Design deve ser web-responsivo, suportar diferentes navegadores. Interface adaptável caso falte alguma dependência. |
| Hardware/dispositivos | Servidor cloud hospeda frontend + backend + modelos de IA. Cliente (docente) acessa via navegador em qualquer desktop/notebook com internet e Servidor requer 4+ GB RAM para carregar modelos (XLM-RoBERTa e Sentence-BERT)| Servidor gerencia restrições e deve mostrar mensagem se servidor está sobrecarregado (muitos uploads simultâneos), e permitir retry automático em caso de timeout.|
| Capacidades | (1) Análise em tempo real de 5 métricas (formalismo, similaridade, tempo, distratores, imagens); (2) Processamento no servidor backend (não envia dados para plataformas externas); (3) Interface intuitiva sem necessidade de conhecimento técnico; (4) Exportação em PDF/CSV com filtros visuais para exploração dos dados; (5) Sem persistência: cada análise é isolada e independente. | Interface deve exibir claramente o escopo das 5 análises disponíveis. Permitir seleção individual de cada métrica e disponibilizar botões export destacados após resultados. Indicador visual de que PDFs não são salvos. |
| Restrições | (1) Primeira análise: tempo depende de fila do servidor (pode haver delay em picos de uso); (2) Limite de tamanho de upload (configurável); (3) Processamento pode demorar 10-30 seg dependendo servidor + prova; (4) MVP da análise em comparação com ENEM, não é análise totalmente com base na prova e suas informações; (5) Depende de uptime do servidor; (6) Internet obrigatória (não funciona offline); (7) sistema só aceita upload de um tipo específico de prova (pdf no mesmo formato do ENEM). | Interface deve: (1) Avisar limite de tamanho ao fazer upload com progresso, (2) Mostrar progresso durante análise com spinner + etapas, (3)Mostrar mensagem se servidor offline, (4) Requer internet (indicar no início) |
| Conectividade/latência | Usuário: deve ter conexão internet estável, velocidade de upload de PDF depende internet do usuário + conexão servidor. Servidor pode ter fila em picos (análises podem aguardar alguns minutos). | Interface deve: (1) Mostrar que a análise está sendo realizada (spinner) e progresso de velocidade, (2) Timeout para upload: se >5 min sem resposta |
| Segurança/privacidade | Processamento no servidor, transmissão via HTTPS, sem persistência padrão de PDFs (deletados após análise, não necessita de autenticação. LGPD: informar processamento de dados educacionais. | Interface deve: (1) Mostrar cadeado HTTPS e avisar "Conexão segura", (2) Avisar: "PDFs não são salvos, apenas análise realizada", (3) Mostrar política de privacidade/LGPD no rodapé com checkbox "Concordo com termos" |
| Volume de dados/histórico | MVP sem persistência, cada análise é isolada, sem histórico e sem limite de análises. | Interface não precisa busca histórico nem paginação de análises antigas. Mas mostraremos filtros para os gráficos de resultados da análise (como filtrar por mínimo, máximo, mediana, maior tempo de leitura...) Esses filtros permitem exploração visual dos dados sem precisar de histórico.|
| Tempo de processamento | Upload: 1-5 segundo(depende tamanho + internet usuário). Carregamento servidor: instantâneo (modelos já em memória). Processamento: 10-30 seg (CPU-bound no servidor).  | Interface deve: (1) fornecer opção de remover arquivo do upload (2) Processamento: spinner e progresso na análise (3) Resultado carrega automático quando pronto (com notificação).|
| Papéis/permissões | Acesso irrestrito e sem necessidade de login. Funcionalidades homogêneas para todos os usuários, dependendo apenas do upload de um PDF válido. | Simplifica o fluxo de navegação por não exigir cadastro/login, mas demanda foco na prevenção de erros: torna necessário o uso de orientações claras sobre o formato do PDF, validação prévia no envio e feedback explicativo de falhas. |

## 2. Princípios gerais do projeto

Inclua apenas normas, leis, padrões e princípios realmente relevantes, explicando **como** afetam o projeto. Não transforme esta seção em lista de links.

| Princípio/norma | Aplicabilidade ao contexto | Decisão/requisito decorrente | Fonte |
|---|---|---|---|
| Contexto de uso | O sistema é destinado a professores que precisam enviar PDFs de provas existentes, consultar métricas estruturais e interpretar os resultados para apoiar a revisão das provas. É necessário considerar suas tarefas, conhecimentos prévios, familiaridade com ferramentas digitais e condições de uso. | Organizar o fluxo de envio e consulta de provas de maneira clara; utilizar termos compreensíveis para o público-alvo; apresentar métricas com explicações suficientes para apoiar sua interpretação. | Entregas 1/3 |
| LGPD | O sistema recebe arquivos PDF e parâmetros necessários para analisar provas. O tratamento dessas informações deve se limitar à finalidade da análise, evitando a coleta e o armazenamento de dados pessoais desnecessários. | Processar somente as informações necessárias para gerar as métricas; não solicitar dados de identificação do professor sem necessidade; informar claramente como os arquivos enviados são utilizados e se são armazenados ou excluídos após o processamento. Adotar medidas de segurança para proteger eventuais dados pessoais presentes nos documentos. | LGPD — Lei nº 13.709/2018: princípios da necessidade, finalidade e transparência: [Lei Geral de Proteção de Dados Pessoais — Lei nº 13.709/2018](https://www.planalto.gov.br/ccivil_03/_ato2015-2018/2018/lei/l13709.htm) |
| Acessibilidade | O envio de arquivos, o preenchimento de parâmetros e a visualização das métricas precisam ser acessíveis a usuários com diferentes capacidades. Isso é relevante para os campos de entrada, mensagens de erro, tabelas, gráficos e resultados textuais. | Permitir navegação por teclado; manter contraste adequado; identificar campos e erros com clareza; não depender exclusivamente de cores para comunicar resultados; apresentar as métricas em formatos legíveis e compreensíveis. | WCAG 2.2: [Web Content Accessibility Guidelines (WCAG) 2.2 — W3C](https://www.w3.org/TR/WCAG22/) |
| Projeto centrado no usuário | A interface deve atender às tarefas e necessidades reais dos professores: enviar uma prova, fornecer os parâmetros necessários e interpretar as métricas retornadas pelo sistema. | Avaliar se os professores conseguem concluir o envio e compreender os resultados; testar a clareza dos campos e das explicações das métricas; revisar a interface com base nos problemas identificados durante avaliações de usabilidade. | ISO 9241-210: [ISO 9241-210:2019 — Ergonomics of human-system interaction](https://www.iso.org/standard/77520.html) |

## 3. Metas de usabilidade

Usabilidade deve ser discutida **no contexto de uso**. Metas quantitativas devem dizer o que será medido, em qual tarefa, com qual população e qual limite será considerado aceitável.

### 3.1 Metas qualitativas

| Meta | Para quem/tarefa | Evidência desejada | Justificativa |
|---|---|---|---|
| Facilitar a identificação dos arquivos aceitos e o envio da prova em PDF. | Docentes | O usuário identifica como enviar o arquivo e consegue realizar o envio sem precisar de orientação externa. | O envio do documento é a primeira etapa de interação com o sistema e precisa ser compreensível. |
| Tornar claros os campos e parâmetros necessários para a análise. | Docentes | O usuário compreende o que cada campo solicita e consegue preencher os parâmetros adequadamente. | Instruções claras ajudam a evitar preenchimentos incorretos e dúvidas durante a configuração da análise. |
| Facilitar a compreensão das métricas apresentadas. | Docentes | O usuário consegue explicar, com suas próprias palavras, o significado das métricas apresentadas, como quantidade de caracteres, grau de formalismo, quantidade de imagens e análise de distratores. | A apresentação dos resultados precisa apoiar a interpretação das informações, mesmo para usuários que não conheçam os detalhes técnicos dos cálculos. |
| Tornar compreensíveis as limitações dos resultados apresentados. | Docentes | O usuário reconhece o que os resultados permitem observar e não interpreta automaticamente uma métrica isolada como uma avaliação definitiva da qualidade da prova. | As métricas oferecem informações para apoiar a análise do professor, mas precisam ser interpretadas considerando seu significado e suas limitações. |
| Facilitar a identificação e a correção de problemas durante o envio ou preenchimento. | Docentes | Quando ocorre um erro, o usuário identifica o problema e compreende como tentar resolvê-lo. | Mensagens de erro claras ajudam o usuário a continuar a tarefa sem depender de suporte externo. |
| Manter a interface compreensível durante todo o fluxo de análise. | Docentes | O usuário consegue identificar em que etapa está e qual ação pode realizar em seguida. | Uma sequência de interação clara reduz a incerteza durante o uso do sistema. |

### 3.2 Metas quantitativas

<!--Meta de EXIGENCIA QUANTITATIVA DE USABILIDADE-->

| ID | Dimensão | Métrica | Tarefa/escopo | Meta | Como medir | Justificativa |
|---|---|---|---|---|---|---|
| MU01 | facilidade de Aprendizado | taxa de sucesso na primeira tentativa (sem auxílio) | T01 | >=90% | teste de usabilidade observado e registro de navegação | Garante que a interface apresente alta usabilidade inicial por meio de um fluxo autoexplicativo, hierarquia visual clara e telas de expicação dos objetivo, o que reduz a curva de aprendizado e permite que novos usuários concluam a tarefa primária sem necessidade de suporte externo ou treinamento prévio. |
| MU02 | facilidade de Memorização | taxa de re-conclusão sem ajuda após intervalo de tempo | T01 | >80% | teste de usabilidade recorrente observado | Adoção de convenções visuais padronizadas, consistência na navegação e affordances claras reduz a carga cognitiva, garantindo que o usuário execute a tarefa com autonomia mesmo após períodos sem utilizar a aplicação. |
| MU03 | eficiência | tempo mediano de execução da tarefa | T01 | <=15min> | cronometragem no teste de usabilidade observado | Avalia o desempenho e a produtividade do usuário já familiarizado com o sistema. Demonstra que a interface minimiza a fricção interativa e o tempo de processamento cognitivo por meio de caminhos de navegação otimizados, atalhos eficientes e layouts funcionais, permitindo a conclusão ágil da tarefa. |
| MU04 | taxa e Gravidade de Erros | número médio de erros cometidos por usuário (e taxa de recuperação) | T01 | <1 erros por usuário | Teste de usabilidade observado registrar cada ação errada (clicks em botão errado, campo não preenchido, upload rejeitado, timeout) e, para cada erro, cronometrar recuperação até próximo passo bem-sucedido | docentes com pouco conhecimento tecnológio tendem a cometer mais erros, seja por falta de experiência, por não terem lido os avisos (por exemplo, limite de tamanho do arquivo no upload) ou por falta de aviso na aplicação |
| MU05 | satisfação | escala pós-tarefa  | T01 | >75% | questionário curto aplicado imediatamente após a tarefa | Mensura a percepção subjetiva e a resposta emocional do usuário em relação à facilidade e ao conforto durante a interação. Garante que o fluxo de telas, o apelo visual e a clareza dos feedbacks gerem uma experiência agradável, minimizando a frustração e promovendo a aceitação contínua do sistema. |

<!--| MU01 | eficácia | taxa de conclusão sem ajuda | T01 | 20% | teste observado | {{...}} |
| MU02 | eficiência | tempo mediano | T01 | 20% | cronômetro/log | {{...}} |
| MU03 | satisfação | escala pós-tarefa | T01 | 20% | questionário | {{...}} | -->

### 3.3 Priorização das metas (se exigida na disciplina)

Se o professor solicitar porcentagens que somem 100%, trate-as como **peso de prioridade**,não como métrica de usabilidade.

| Meta | Peso de prioridade | Justificativa |
|---|---:|---|
| MU01 | 20%% | alta prioridade por ser a porta de entrada. Sem treinamento prévio, uma falha na primeira experiência impede o uso futuro. Recebe peso igual às demais porque o sucesso inicial é pré-requisito crítico para que as outras metas passem a existir. |
| MU02 | 20%% | alta prioridade pelo caráter intermitente de uso. Como o uso ocorre em intervalos espaçados, esquecer o fluxo gera a mesma frustração do primeiro acesso. Prioridade idêntica às outras para garantir retenção do usuário no longo prazo. |
| MU03 | 20%% | alta prioridade devido ao tempo restrito na rotina do usuário. Uma interface lenta ou burocrática faz o usuário abandonar o sistema por falta de tempo. Possui o mesmo peso porque o desempenho operacional viabiliza a adoção no dia a dia. |
| MU04 | 20%% | alta prioridade para evitar o bloqueio e a desistência. Falhas sem mensagem clara ou sem recuperação simples travam a tarefa. Tem peso igual por representar o pilar de resiliência e suporte ao usuário durante a execução. |
| MU05 | 20%% | alta prioridade para a aceitação subjetiva e percepção de valor. Mesmo que a tarefa seja concluída, uma experiência desagradável impede o reuso e a recomendação. O peso de 20% equilibra a performance técnica com a experiência humana. |
| **Total** | **100%** | todas as metricas sao igualmente importante por isso foi divididos igualmente. |

## 4. Como o ciclo será iterado

Explique que artefatos serão revisitados após protótipos e avaliações.

O ciclo de usabilidade seguirá a Engenharia de Usabilidade de Mayhew, com avaliações dos protótipos para verificar o atendimento às metas qualitativas e quantitativas definidas no projeto. Os resultados permitirão identificar problemas de interação e revisar os artefatos afetados, como requisitos, análise de tarefas e protótipos.

No sistema proposto, serão avaliadas tarefas como o envio de PDFs, o preenchimento de parâmetros e a interpretação das métricas. As avaliações poderão considerar a compreensão dos resultados, a ocorrência de erros e o tempo de execução das tarefas. Após os ajustes, novas avaliações verificarão se os problemas foram resolvidos e se as metas de usabilidade estão sendo atendidas.

## Checklist

- [x] Capacidades e restrições têm impacto de IHC explicitado.
- [x] Está claro o limite entre contribuição técnica do TCC e camada interativa da disciplina.
- [ ] Resultados/processamento simulados no protótipo foram explicitados.
- [x] Metas de usabilidade avaliam a interação, não substituem métricas técnicas do TCC.
- [x] Normas/princípios estão contextualizados, não apenas copiados.
- [x] Metas quantitativas são mensuráveis e associadas a tarefas/público.
- [x] Eficácia, eficiência e satisfação são consideradas quando pertinentes.
- [ ] Metas poderão ser verificadas nas Entregas 12–14.

