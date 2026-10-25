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
| contribuição técnica do TCC | algorítmo de análise do impacto do formato das avaliaçÕes no desempenho dos candidatos | a aplicação que permite os docentes a submeterem uma avaliação e obter métricas sobre ela.|
| camada de interação da disciplina | interface | análise da compreensão e clareza das métricas, bem como o impacto potencial da estrutura das questões no desempenho da prova. |
| integrações/dados simulados | as integração usadas para a realização das análises são: Bert para analise dos distraotres e XLM-RoBERTa para análise do formalismo | {{limites do protótipo}} ???????|

Em um protótipo de disciplina, é aceitável simular processamento ou resultados quando a implementação técnica não estiver integrada, desde que isso seja declarado e a simulação seja suficiente para avaliar a interação.

## 1. Características da plataforma
<!-- olhar anotacao aula topico 8-->
| Característica | Descrição | Consequência para IHC |
|---|---|---|
| Software | Vue.js 3 (frontend), Node.js (backend), Python (scripts de análise). Navegador web (Chrome, Firefox, Safari, Edge). Requer npm/Node.js instalado localmente. | Design deve ser web-responsivo, suportar diferentes navegadores. Interface adaptável caso falte alguma dependência. |
| Hardware/dispositivos | Servidor cloud hospeda frontend + backend + modelos de IA. Cliente (docente) acessa via navegador em qualquer desktop/notebook com internet e Servidor requer 4+ GB RAM para carregar modelos (XLM-RoBERTa e Sentence-BERT)| Servidor gerencia restrições e interface devr indicar se navegador não é suportado, mostrar mensagem se servidor está sobrecarregado (muitos uploads simultâneos), e permitir retry automático em caso de timeout.|
| Capacidades | (1) Análise em tempo real de 5 métricas (formalismo, similaridade, tempo, distratores, imagens); (2) Processamento 100% local sem envio para servidor externo; (3) Funciona offline após 1ª execução (modelos em cache);(4) Interface intuitiva sem necessidade de conhecimento técnico; (5) Exportação em PDF/EXCEL/CSV. | Interface deve exibir claramente o escopo das 5 análises disponíveis. Permitir seleção individual de cada métrica e disponibilizar botões export destacados após resultados. |
| Restrições | (1) Primeira análise: tempo depende de fila do servidor (pode haver delay em picos de uso); (2) Limite de tamanho de upload (configurável); (3) Processamento pode demorar 10-30 seg dependendo servidor + prova; (4) MVP da aálise em comparação com ENEM, não é análise totalmente com base na prova e suas informações; (5) Depende de uptime do servidor; (6) Internet obrigatória (não funciona offline); (7) sistema só aceita upload de um tipo específico de prova)pdf no mesmo formato do ENEM. | Interface deve: (1) Avisar limite de tamanho ao fazer upload com progresso, (2) Mostrar progresso durante análise com spinner + etapas, (3)Mostrar mensagem se servidor offline, (4) Requer internet (indicar no início) |
| Conectividade/latência | Usuário: deve ter conexão internet estável, velocidade de upload de PDF depende internet do usuário + conexão servidor. Servidor pode ter fila em picos (análises podem aguardar alguns minutos). | {Interface deve: (1) Mostrar que a análise está sendo realizada (spinner) e progresso de velocidade, (2) Timeout para upload: se >5 min sem resposta |
| Segurança/privacidade | Processamento no servidor, transmissão via HTTPS, sem persistência padrão de PDFs (deletados após análise, não necessita de autenticação. LGPD: informar processamento de dados educacionais. | Interface deve: (1) Mostrar cadeado HTTPS e avisar "Conexão segura", (2) Avisar: "PDFs não são salvos, apenas análise realizada", (3) Mostrar política de privacidade/LGPD no rodapé com checkbox "Concordo com termos" |
| Volume de dados/histórico | MVP sem persistência, cada análise é isolada, sem histórico e sem limite de análises. | Interface não precisa busca histórico, paginação de análises antigas. Mas mostraremos filtras os gráficos de resultados da análise como filtrar por mínimo,máximo, medana, maior tempo de leitura... Esses filtros permitem exploração visual dos dados sem precisar de histórico.|
| Tempo de processamento | Upload: 1-5 segundo(depende tamanho + internet usuário). Carregamento servidor: instantâneo (modelos já em memória). Processamento: 10-30 seg (CPU-bound no servidor).  | Interface deve: (1) fornecer opção de remover arquivo do upload (2) Processamento: spinner e progresso na análise (3) Resultado carrega automático quando pronto (com notificação).|
| Papéis/permissões | Acesso irrestrito e sem necessidade de login. Funcionalidades homogêneas para todos os usuários, dependendo apenas do upload de um PDF válido. | Simplifica o fluxo de navegação por não exigir cadastro/login, mas demanda foco na prevenção de erros: torna necessário o uso de orientações claras sobre o formato do PDF, validação prévia no envio e feedback explicativo de falhas. |

## 2. Princípios gerais do projeto

Inclua apenas normas, leis, padrões e princípios realmente relevantes, explicando **como** afetam o projeto. Não transforme esta seção em lista de links.

| Princípio/norma | Aplicabilidade ao contexto | Decisão/requisito decorrente | Fonte |
|---|---|---|---|
| Contexto de uso | {{...}} | {{...}} | Entregas 1/3 |
| LGPD, se aplicável | {{...}} | {{...}} | {{fonte oficial}} |
| Acessibilidade | {{...}} | {{...}} | {{WCAG/norma aplicável}} |
| {{outro}} | {{...}} | {{...}} | {{...}} |

## 3. Metas de usabilidade

Usabilidade deve ser discutida **no contexto de uso**. Metas quantitativas devem dizer o que será medido, em qual tarefa, com qual população e qual limite será considerado aceitável.

### 3.1 Metas qualitativas

| Meta | Para quem/tarefa | Evidência desejada | Justificativa |
|---|---|---|---|
| {{ex.: compreensão clara da diferença entre X e Y}} | {{...}} | {{fala/observação}} | {{...}} |

### 3.2 Metas quantitativas

<!--Meta de EXIGENCIA QUANTITATIVA DE USABILIDADE-->

| ID | Dimensão | Métrica | Tarefa/escopo | Meta | Como medir | Justificativa |
|---|---|---|---|---|---|---|
| MU01 | facilidade de Aprendizado | taxa de sucesso na primeira tentativa (sem auxílio) | T01 | >=90% | teste de usabilidade observado e registro de navegação | Garante que a interface apresente alta usabilidade inicial por meio de um fluxo autoexplicativo, hierarquia visual clara e telas de expicação dos objetivo, o que reduz a curva de aprendizado e permite que novos usuários concluam a tarefa primária sem necessidade de suporte externo ou treinamento prévio. |
| MU02 | facilidade de Memorização | taxa de re-conclusão sem ajuda após intervalo de tempo | T01 | >80% | teste de usabilidade recorrente observado | Adoção de convenções visuais padronizadas, consistência na navegação e affordances claras reduz a carga cognitiva, garantindo que o usuário execute a tarefa com autonomia mesmo após períodos sem utilizar a aplicação. |
| MU03 | eficiência | tempo mediano de execução da tarefa | T01 | <=15min> | cronometragem no teste de usabilidade observado | Avalia o desempenho e a produtividade do usuário já familiarizado com o sistema. Demonstra que a interface minimiza a fricção interativa e o tempo de processamento cognitivo por meio de caminhos de navegação otimizados, atalhos eficientes e layouts funcionais, permitindo a conclusão ágil da tarefa. |
| MU04 | taxa e Gravidade de Erros | número médio de erros cometidos por usuário (e taxa de recuperação) | T01 | <1 erros por usuário | Teste de usabilidade observado registrar cada ação errada (clicks em botão errado, campo não preenchido, upload rejeitado, timeout) e, para cada erro, cronometrar recuperação até próximo passo bem-sucedido | docentes com pouco conhecimento tecnológio tendem a cometer mais erros, seja por falta de experiência, pode não terem lido os avisos (por exemplo, limite de tamanho do arquivo no upload) ou por falta de aviso na aplicação |
| MU05 | satisfação | escala pós-tarefa  | T01 | >75% | questionário curto aplicado imediatamente após a tarefa | Mensura a percepção subjetiva e a resposta emocional do usuário em relação à facilidade e ao conforto durante a interação. Garante que o fluxo de telas, o apelo visual e a clareza dos feedbacks gerem uma experiência agradável, minimizando a frustração e promovendo a aceitação contínua do sistema. |

<!--| MU01 | eficácia | taxa de conclusão sem ajuda | T01 | 20% | teste observado | {{...}} |
| MU02 | eficiência | tempo mediano | T01 | 20% | cronômetro/log | {{...}} |
| MU03 | satisfação | escala pós-tarefa | T01 | 20% | questionário | {{...}} | -->

### 3.3 Priorização das metas (se exigida na disciplina)

Se o professor solicitar porcentagens que somem 100%, trate-as como **peso de prioridade**, não como métrica de usabilidade.

| Meta | Peso de prioridade | Justificativa |
|---|---:|---|
| MU01 | 20%% | alta prioridade por ser a porta de entrada. Sem treinamento prévio, uma falha na primeira experiência impede o uso futuro. Recebe peso igual às demais porque o sucesso inicial é pré-requisito crítico para que as outras metas passem a existir. |
| MU02 | 20%% | alta prioridade pelo caráter intermitente de uso. Como o uso ocorre em intervalos espaçados, esquecer o fluxo gera a mesma frustração do primeiro acesso. Prioridade idêntica às outras para garantir retenção do usuário no longo prazo. |
| MU03 | 20%% | alta prioridade devido ao tempo restrito na rotina do usuário. Uma interface lenta ou burocrática faz o usuário abandonar o sistema por falta de tempo. Possui o mesmo peso porque o desempenho operacional viabiliza a adoção no dia a dia. |
| MU04 | 20%% | alta prioridade para evitar o bloqueio e a desistência. Falhas sem mensagem clara ou sem recuperação simples travam a tarefa. Tem peso igual por representar o pilar de resiliência e suporte ao usuário durante a execução. |
| MU05 | 20%% | alta prioridade para a aceitação subjetiva e percepção de valor. Mesmo que a tarefa seja concluída, uma experiência desagradável impede o reuso e a recomendação. O peso de 20% equilibra a performance técnica com a experiência humana. |
| **Total** | **100%** | todas as metricas sao igualmente importante por isso foi dibidio por 100% |

## 4. Como o ciclo será iterado

Explique que artefatos serão revisitados após protótipos e avaliações.

## Checklist

- [ ] Capacidades e restrições têm impacto de IHC explicitado.
- [ ] Está claro o limite entre contribuição técnica do TCC e camada interativa da disciplina.
- [ ] Resultados/processamento simulados no protótipo foram explicitados.
- [ ] Metas de usabilidade avaliam a interação, não substituem métricas técnicas do TCC.
- [ ] Normas/princípios estão contextualizados, não apenas copiados.
- [ ] Metas quantitativas são mensuráveis e associadas a tarefas/público.
- [ ] Eficácia, eficiência e satisfação são consideradas quando pertinentes.
- [ ] Metas poderão ser verificadas nas Entregas 12–14.
