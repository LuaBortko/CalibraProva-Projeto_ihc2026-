# Entrega 2 — Público-alvo e análise de concorrência

*Data:* 26/10/2026 <br>
*Status:* 🟦 revisada após feedback <br>
*Responsabilidade mínima:* cada integrante analisa pelo menos 1 concorrente/interface representativa; a equipe produz síntese comparativa. <br>

## Objetivo da atividade

Compreender soluções do mesmo domínio **e também interfaces familiares ao público-alvo**. O objetivo não é copiar telas, mas identificar convenções, padrões, affordances percebidas, problemas recorrentes, expectativas e oportunidades de design.

> **Concorrente não precisa ser idêntico ao produto.** Pode atuar na mesma área, resolver objetivo semelhante ou disputar a mesma necessidade. Quando não houver concorrente direto, use produtos análogos e softwares que o público já utiliza.

### Para TCCs que não previam interface

Não procure apenas um “concorrente do algoritmo”. Investigue **interfaces profissionais que materializam atividades semelhantes** às que o usuário escolhido precisaria realizar.

Exemplos:

- TCC de banco de dados → consoles de administração, ferramentas para DBA, monitoramento e análise de consultas;
- TCC de LLM/ML → painéis de experimentos, gestão de modelos/datasets, comparação de métricas, revisão de resultados;
- TCC de análise de dados → dashboards, ferramentas de BI, filtros, relatórios e exploração;
- TCC de infraestrutura/API → portais administrativos, observabilidade, logs, gestão de credenciais e uso;
- TCC de cibersegurança → consoles de alertas, triagem, histórico e auditoria.

A pergunta é: **“que convenções esse perfil já conhece para executar tarefas equivalentes?”**

## Entrada obrigatória da Entrega 1

Retome o mapa inicial de alternativas e produtos citado na Entrega 1. Aqui a equipe deixa de trabalhar apenas com impressão inicial e passa a **investigar sistematicamente** cada solução.

| Item citado na Entrega 1 | Tipo | Por que foi citado | Status inicial | Decisão nesta entrega |
|---|---|---|---|---|
| Lucida | análogo | Por ser uma plataforma educacional que oferece recursos de análise do desempenho dos alunos e acompanhamento de seus pontos fortes e dificuldades| F | analisar |
| Keptune | análogo | Estima características dos itens das provas, como dificuldade e discriminação, além de identificar itens psicometricamente fracos. | F | analisar |
| Xcalibre | análogo | A ferramenta estima parâmetros dos itens, como dificuldade, discriminação e métricas estatística, além de disponibilizar relatórios com os resultados obtidos na análise. | F | analisar |
| OpenEduCat | análogo | Disponibiliza uma funcionalidade para analisar itens das prova, como índices de dificuldade e discriminação dos itens e análise dos distratores. | F | A plataforma será descartada da análise, pois, além de ser paga, apresenta diversas funcionalidades que não estão alinhadas ao escopo definido para o projeto. Adicionalmente, não foram encontradas, em fontes de acesso gratuito, capturas de tela das funcionalidades relevantes para a análise proposta. |
| Qstione | análogo | Analisa a qualidade dos itens de uma prova de acordo com a Teoria de Resposta ao Item (TRI) | F | Não foi possível obter acesso à plataforma nem encontrar capturas de tela que permitissem compreender adequadamente seu funcionamento e suas principais interações. |

Se uma hipótese da Entrega 1 for confirmada ou refutada durante esta análise, atualize `H01`, `H02`... em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

## 1. Público-alvo desta análise

O público-alvo desta análise são docentes, perfil priorizado na Entrega 1. A interface em desenvolvimento busca permitir que esses profissionais façam o upload de uma prova, insiram parâmetros quando necessário e visualizem e interpretem métricas relacionadas às características estruturais da avaliação antes de sua aplicação. Essas informações poderão auxiliá-los na análise de possíveis ajustes na prova, buscando reduzir a influência de seu formato no desempenho dos alunos e fazer com que a avaliação mensure, principalmente, os conhecimentos e competências que pretende avaliar.

## 2. Concorrentes diretos/indiretos

### Análise C01 — Lucida

**Autor(a):** Nuno Martins Guilhrmino da Silva — RA:22.126.099-5 <br>
**Tipo:** análogo  <br>
**Link oficial:** [lucida]()<br>
**Data de acesso:** 27/08/2026<br>

#### Contexto e proposta

A plataforma foi desenvolvida para auxiliar no diagnóstico de dificuldades em sala de aula. Por meio da criação de provas, do escaneamento de folhas de resposta e da disponibilização de métricas detalhadas, como dificuldade e discriminação dos itens, além da identificação de questões com baixo desempenho e distratores efetivos, a Lucida oferece aos docentes informações que auxiliam na identificação dos conteúdos que necessitam de maior atenção e reforço em sala de aula.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Criação de prova | Na plataforma, o professor pode fazer uma prova através do upload de material, além da escolha de alguns parâmetros, como nível de dificuldade desejado, número de questões, entre outros | `assets/02_concorrencia/criacao_prova1.png` `assets/02_concorrencia/criacao_prova2.png` `assets/02_concorrencia/criacao_prova3.png` `assets/02_concorrencia/criacao_prova4.png ` | A interface apresenta boa organização visual e divide a criação da prova em etapas bem definidas. Os campos possuem rótulos e feedbacks claros, como a indicação de arquivos adicionados e das configurações selecionadas. Entretanto, a tela de personalização concentra muitas opções, aumentando a quantidade de informações apresentadas simultaneamente. Além disso, algumas escolhas, como os estilos ENEM e ENADE, podem exigir conhecimento prévio do usuário. | 
| Análise e métricas de provas | Após a aplicação de uma prova, o professor pode inserir na plataforma a folha de respostas dos alunos, assim sendo calculadas a dificuldade e fator discriminatório de cada questão, além de apontar questões fracas e distratores efetivos  | `assets/02_concorrencia/analiselucida1.png`| A interface utiliza cores para diferenciar e sinalizar resultados, como verde para boa discriminação, amarelo para valores baixos e vermelho para valores muito baixos. As três métricas principais ficam em destaque no topo, seguidas por gráficos de acertos por dificuldade e, posteriormente, pela análise individual das questões. A hierarquia visual facilita a leitura dos dados, enquanto os alertas destacam situações que exigem atenção, como questões com discriminação negativa. | 

#### Experiência do usuário e opiniões

Use avaliações públicas, relatos, estudos, testes próprios ou outra fonte identificável. Não trate opinião isolada como verdade universal.

No momento não existem avaliações públicas da plataforma fora de poucas avaliações positivas presentes no site da plataforma. A experiência do grupo utilizando a ferramenta ocorreu de forma relativamente tranquila, sem grandes problemas técnicos ou confusões em como utilizar do site, apenas um problema com o upload de folha de respostas na etapa de correção de provas. O site contém um visual limpo e minimalista, com poucos botões e funcionalidades bem explicadas, seja na homepage ou dentro da área do usuário.

#### Padrões e tendências percebidos

A plataforma utiliza diferentes formas de apresentação, como gráficos e tabelas, para exibir as estatísticas da análise. Também utiliza cores associadas aos indicadores para diferenciar os resultados e destacar informações que podem exigir atenção do usuário.

Observa-se o uso de ferramentas de IA para automatizar diferentes etapas relacionadas à avaliação, como formulação de provas, correção e análise dos resultados. Esse padrão evidencia a possibilidade de reduzir tarefas manuais e concentrar diferentes etapas do processo em uma mesma ferramenta, embora sua aplicação não seja necessariamente adequada ao escopo do projeto.

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
|**Ponto positivo — Orientação ao usuário** | A interface apresenta instruções que orientam o usuário sobre as etapas necessárias para utilizar a plataforma, sem exigir conhecimentos de programação para realizar as principais tarefas. | Priorizar orientações claras para a realização das tarefas, reduzindo a necessidade de conhecimento técnico prévio. |
|**Limitação — Customização Limitada** | A plataforma restringe a análise às avaliações criadas na própria ferramenta e às folhas de respostas geradas por ela, não permitindo analisar diretamente uma prova criada previamente pelo docente. | Permitir que o docente utilize uma avaliação já elaborada como entrada para a análise, sem exigir sua criação dentro da própria plataforma. |
|**Ponto Positivo — Variedade de métricas** | A ferramenta disponibiliza várias métricas para auxiliar o professor a se adaptar de acordo com as dificuldades de cada turma, oferencendo dificuldade e fator discriminatório, além de análise de distratores efetivos, questões fracas e comparação entre aluno e a turma completa. | Apresentar métricas relacionadas às características dos itens e ao desempenho observado, priorizando aquelas que tenham relação direta com os objetivos da análise da prova. |

### Análise C02 — Keptune.ai

**Autor(a):** Beatriz Manaia Lourenço Berto — RA:22.125.060-8  
**Tipo:** análogo  
**Link oficial:** [keptune](https://keptune.ai/)
**Data de acesso:** 27/08/2026

#### Contexto e proposta

A Keptune.ai é uma plataforma de análise de dados que disponibiliza, entre suas ferramentas, recursos para análise de itens de avaliações e exames. A partir do upload de arquivos CSV ou Excel contendo as respostas dos participantes, a ferramenta permite calcular métricas relacionadas aos itens, como dificuldade, discriminação e outros indicadores de desempenho, além de identificar questões potencialmente problemáticas ou com desempenho inadequado que possam necessitar de revisão. Para realizar a análise, o usuário pode fornecer informações sobre os itens e definir os critérios desejados, enquanto a inteligência artificial auxilia no processamento e na geração dos resultados.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Upload de arquivos de respostas dos participantes | Precisa fazer o upload de um arquivo em formato CSV ou Excel, seguindo a estrutura especificada pela plataforma para permitir a realização da análise dos itens | `assets/02_concorrencia/keptune_upload1.jpeg` , `assets/02_concorrencia/keptune_upload2.jpeg` | A interface organiza as opções de entrada de dados em uma barra lateral, separando fontes como arquivos, bases de dados e datasets públicos. Os arquivos adicionados permanecem visíveis nessa mesma área, facilitando sua identificação. A barra também é dividida em abas para dados e conversas com a IA, reduzindo a quantidade de informações exibidas simultaneamente. A área principal permanece limpa e apresenta um ícone de upload, indicando de forma clara que o primeiro passo da interação é adicionar os dados. |
| Utilização de inteligência artificial para realizar a análise | Na parte de chat, conseguimos conversar com IA para solicitar análise dos itens (calcular métricas como dificuldade e discriminação, identificando itens que podem precisar de revisão, entre outros)| `assets/02_concorrencia/keptune_analise1.jpeg` , `assets/02_concorrencia/keptune_analise2.jpeg`  | A interface mantém a barra lateral com abas para dados e conversas, facilitando a criação de novos chats e o acesso aos dados. Na área principal, quando não há conversa iniciada, uma mensagem orienta e incentiva o usuário a iniciar a análise. Durante a interação, o chat ocupa a maior parte da tela, priorizando a conversa com a IA. Destaca-se também a organização das tabelas geradas pela IA na barra lateral, permitindo acessá-las posteriormente de forma rápida. |
| Visualização de resultados em tabelas, gráficos e outros formatos | Após solicitar uma análise ou fazer uma pergunta à IA, a ferramenta apresenta os resultados no próprio chat, por meio de tabelas, gráficos e outras visualizações, além de disponibilizá-los na seção lateral de tabelas.| `assets/02_concorrencia/keptune_analise1.jpeg` , `assets/02_concorrencia/keptune_analise2.jpeg`, `assets/02_concorrencia/keptune_analise3.jpeg` , `assets/02_concorrencia/keptune_analise4.jpeg` | Os resultados são apresentados em diferentes formatos, como tabelas e gráficos, utilizando cores e categorias para facilitar a diferenciação das informações. As visualizações geradas ficam organizadas entre o chat e a barra lateral, permitindo acessar posteriormente os resultados produzidos. A possibilidade de a IA sugerir recomendações a partir dos resultados também amplia a utilidade da visualização para a análise dos dados. |

#### Experiência do usuário e opiniões

Use avaliações públicas, relatos, estudos, testes próprios ou outra fonte identificável. Não trate opinião isolada como verdade universal.

A experiência com o keptune.ai é, no geral, bem positiva. O que mais se destaca é a facilidade de usar, o preço acessível e a rapidez da IA para responder. A plataforma foi feita pra facilitar a análise de dados, permitindo que qualquer pessoa, mesmo sem saber programar, faça coisas como limpar dados, rodar testes estatísticos e gerar gráficos só conversando com o chat.

A interface é bonita e fácil de entender. Os resultados aparecem no chat, mas também ficam guardados numa aba lateral com tabelas e consultas, o que ajuda a organizar o trabalho. A ferramenta é rápida, aceita vários tipos de perguntas e mostra os dados de formas diferentes (tabelas, gráficos etc.), com cores que ajudam na interpretação.

Um ponto forte é o custo: tem um plano grátis bem generoso e os planos pagos começam em US$ 5/mês, o que sai mais barato que alguns concorrentes. Outra coisa legal é que dá pra ver cada passo da transformação dos dados e até editar o código Python gerado pelos gráficos, dando mais controle pra quem usa. Sobre segurança, sites como Scamadviser e Gridinsoft dizem que o keptune.ai é confiável, tem certificado SSL e baixo risco de golpe.

A principal desvantagem é que o arquivo precisa estar num formato específico (CSV ou Excel) e seguir a estrutura que a plataforma exige, o que pode ser um obstáculo pra quem não tá acostumado. Além disso, ainda tem poucos usuários e avaliações públicas: no site keptune.tenereteam.com, a nota é 4,5 de 5, mas só com 5 avaliações. O Scamadviser também mostra que o site tem pouco tráfego, o que é normal pra uma plataforma que ainda tá crescendo. E sobre o Toolradar, ele não é um site de avaliações de usuários, é mais uma base de dados pra IA, então não tem avaliações de pessoas lá.
 
#### Padrões e tendências percebidos

1. Interface conversacional como padrão dominante
   
 - A estrutura do keptune.ai segue o modelo de chat-first, ou seja, a interação principal acontece por meio de um chat, assim como ChatGPT, Copilot e Gemini. O usuário faz perguntas em linguagem natural e a IA responde com análises prontas. Isso é uma tendência clara de democratização do acesso à dados.

2. Integração entre linguagem natural e execução de código
   
 - A plataforma apresenta o código utilizado para gerar algumas visualizações e permite que o usuário o edite, possibilitando consultar como o resultado foi produzido e modificar o processamento quando necessário.

3. Organização dos resultados entre chat e painel lateral
   
 - Os resultados aparecem no chat (para interação imediata) e também são salvos em uma aba lateral com tabelas e subconsultas. Isso ajuda a manter o histórico e facilita a consulta depois, algo que melhora a experiência de quem usa a ferramenta para análises mais longas.

4. Tendência de "IA como cientista de dados pessoal"
   
 - A IA pode atuar como um assistente, fazendo análises exploratórias, gerando insights e sugerindo próximos passos.

5. Transparência e controle como diferencial
   
 - O keptune.ai mostra cada etapa da transformação dos dados e permite editar o código Python. Esse padrão de transparência algorítmica está se tornando cada vez mais valorizado por usuários que querem entender o que está sendo feito com seus dados.

6. Custo acessível e plano gratuito
   
 - Oferecer planos gratuitos com funcionalidades básicas e planos pagos acessíveis (a partir de US$ 5/mês) também é um padrão comum entre ferramentas SaaS.


#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
|**Ponto positivo — Interface com informações precisas e diretas** | A interface é visualmente atraente, com organização clara entre chat e aba lateral, apenas com o necessário  informações em tela e organizado de forma que não fique poluído visualmente. | Organizar as informações de forma hierárquica, priorizando o conteúdo relevante para cada etapa da interação e evitando a apresentação simultânea de informações desnecessárias. |
|**Ponto positivo — Agilidade nas respostas da IA** | A ferramenta processa comandos e gera análises (tabelas, gráficos, estatísticas) em poucos segundos. | Nenhuma, não integraremos nosso sistema com Inteligência Artifical. |
|**Ponto positivo — Transparência e controle sobre os dados** | O usuário pode ver cada etapa da transformação dos dados e editar o código Python gerado pelas visualizações. | Valorizar a transparência dos resultados, apresentando informações que permitam ao docente compreender o significado das métricas e como elas são obtidas. |
|**Ponto positivo — Variedade de visualizações e análises** | A plataforma gera resultados personalizados conforme solicitado à I.A., produzindo múltiplos formatos de visualização: tabelas resumo com médias e desvios; gráficos de distribuição dos parâmetros (boxplots); listas detalhadas de itens com problemas (com motivos: discriminação baixa, acaso elevado, dificuldade extrema); gráficos de barras com distribuição de dificuldade por área; contagens e percentuais de itens por motivo de revisão. Os resultados ficam salvos na aba lateral para consulta posterior. | Oferecer diferentes formas de apresentação dos resultados, selecionadas de acordo com o tipo de informação e com as necessidades de interpretação do docente. As informações devem ser organizadas de forma a facilitar a consulta e a identificação dos principais resultados. |
|**Ponto positivo — Custo benefício** | A plataforma oferece plano gratuito generoso e planos pagos a partir de US$ 5/mês, sendo mais acessível que alguns concorrentes | Nenhuma, nosso sistema será 100% gratuito e disponível para todos|
|**Limitação — Formato específico de arquivo para upload** | O upload exige que os arquivos estejam nos formatos CSV ou Excel e sigam uma estrutura específica, o que pode representar uma barreira para usuários menos experientes. Essa exigência pode dificultar ou até impedir o uso da plataforma por alguns docentes que não possuem seus dados organizados nesse formato.|Considerar as características e o contexto dos usuários ao definir o formato de entrada dos dados, buscando reduzir barreiras durante o processo de upload. |
|**Limitação — Ferramenta em fase de crescimento** | Plataforma recente (Termos e Condições de junho/2024) e ainda tem pouco tráfego (~2.187 visitas/mês), o que é normal para uma ferramenta nova. Isso indica que o mercado ainda está aberto para soluções focadas em nichos específicos  | Como o Keptune ainda não domina o mercado de análise de itens educacionais, há espaço para uma solução mais especializada e focada, como a nossa, direcionada a docentes do Estado de São Paulo que desejam analisar provas estilo ENEM antes da aplicação. |

<!--|**Lições —P MIM N FAZ SENTIDO COLOCAR PQ JA TEM PONTO POSITIVO E LIMITACAO AI APRENDO OCM ELAS**  | {{...}} | {{...}} |-->

### Análise C03 — XCalibre

**Autor(a):** Luana Bortko Rodrigues — RA:24.123.006-9  
**Tipo:** análogo  
**Link oficial:** [xcalibre](https://assess.com/xcalibre/)  
**Data de acesso:** 27/08/2026

#### Contexto e proposta

O Xcalibre é uma ferramenta voltada à análise psicométrica de avaliações, com ênfase na Teoria de Resposta ao Item (TRI). A partir dos dados de respostas de uma avaliação, a ferramenta permite estimar parâmetros relacionados aos itens, como dificuldade e discriminação, além de disponibilizar estatísticas complementares, visualizações e relatórios técnicos que auxiliam na avaliação do desempenho dos itens e da prova como um todo.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Input de arquivo | O usuário insere um arquivo nos formatos .txt ou .dat contendo os dados da avaliação e fornece parâmetros adicionais necessários para que o sistema interprete corretamente a estrutura e o conteúdo do arquivo. | `assets/02_concorrencia/xcalibraInput1.png` e `assets/02_concorrencia/xcalibraInput2.png`| A interface apresenta diversas opções de configuração e personalização, mas exige conhecimento prévio sobre a estrutura dos dados e dos parâmetros necessários para a análise. A presença de seis abas e de diferentes campos para configurar o arquivo, identificar sua estrutura e definir o local dos resultados aumenta a quantidade de informações apresentadas ao usuário. Isso pode dificultar a compreensão inicial da interface, especialmente para usuários que ainda não conhecem o funcionamento da ferramenta. |
| Configuração da análise e dos resultados | O usuário define parâmetros relacionados à análise e seleciona as informações e formatos que deseja obter como resultado do processamento. | `assets/02_concorrencia/xcalibraConf.png` | A interface concentra diversas opções de configuração da análise e dos resultados em uma mesma tela, utilizando termos técnicos e opções específicas do processamento. Isso oferece maior possibilidade de personalização, mas exige conhecimento prévio sobre a análise para que o usuário saiba quais parâmetros selecionar e quais formatos de resultado utilizar. |
| Visualização de estatísticas dos itens | Os resultados da análise são apresentados por meio de tabelas que sintetizam estatísticas dos parâmetros estimados para os itens, como média, desvio-padrão, mínimo e máximo. |  `assets/02_concorrencia/xcalibraResp.png` | A interface apresenta um breve texto explicativo seguido por tabelas de resumo das estatísticas dos itens. As tabelas organizam os dados em colunas, como parâmetro, quantidade de itens, média, desvio-padrão, mínimo e máximo, permitindo consultar e comparar os valores de forma estruturada. |
| Visualização gráfica dos resultados | Os resultados também são apresentados por meio de gráficos que representam relações entre os parâmetros obtidos na análise, como dificuldade e discriminação dos itens. |  `assets/02_concorrencia/xcalibraRespGraf.png` | A interface utiliza gráficos para complementar a apresentação dos resultados, com diferentes tipos de visualização para representar os parâmetros analisados. Cada gráfico é acompanhado por uma breve descrição que explica o que está sendo apresentado, auxiliando o usuário na interpretação das informações. |

#### Experiência do usuário e opiniões

Não foram encontradas muitas avaliações sobre o software Xcalibre, sendo identificados principalmente relatos em artigos que utilizaram a ferramenta em contextos científicos. De modo geral, as avaliações encontradas indicam uma experiência de uso positiva. Hurtz (2022) caracteriza o software como relativamente amigável ao usuário e destaca sua interface gráfica para a configuração das análises e apresentação dos resultados. De forma semelhante, Gierl e Ackerman (1996) destacam a facilidade de uso e a organização lógica da interface gráfica. Apesar desses aspectos positivos, a utilização da ferramenta envolve conceitos e parâmetros específicos da TRI, o que pode exigir conhecimento prévio do usuário. Além disso, a análise realizada pela equipe identificou aspectos que podem representar oportunidades de melhoria sob a perspectiva de IHC, especialmente quanto à complexidade da entrada de dados e à organização visual da interface.

#### Padrões e tendências percebidos

A análise evidencia que a configuração inicial exige conhecimento prévio sobre a estrutura dos dados de entrada e sobre conceitos básicos de TRI, além de envolver diferentes parâmetros de configuração. Em contrapartida, os resultados são apresentados por meio de tabelas, gráficos e relatórios que organizam as métricas selecionadas pelo usuário, facilitando a consulta e a interpretação das informações obtidas.

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| **Limitação — Complexidade da entrada de dados** | O Xcalibre exige que o usuário conheça a estrutura do arquivo de entrada e forneça parâmetros adicionais para que os dados sejam interpretados corretamente. | Buscar simplificar a entrada de dados, permitindo que o docente envie a prova com o mínimo possível de configurações adicionais. |
| **Limitação — Necessidade de conhecimento específico** | A configuração e a interpretação das análises envolvem conceitos específicos da TRI e terminologia técnica. | Apresentar as métricas de maneira acessível ao docente, oferecendo explicações sobre seu significado e sua relação com o desempenho dos estudantes. |
| **Ponto positivo — Apresentação visual dos resultados** | Os resultados são apresentados por meio de tabelas e gráficos, facilitando a visualização das métricas obtidas. | Utilizar recursos visuais para facilitar a compreensão das características estruturais identificadas e de suas possíveis relações com o desempenho. |
| **Ponto positivo — Geração de relatórios** | O Xcalibre permite gerar relatórios contendo as métricas e os resultados configurados pelo usuário. | Considerar a apresentação dos resultados de forma organizada e consolidada, facilitando sua consulta pelo docente. |
| **Ponto positivo — Personalização dos resultados** | O usuário pode selecionar previamente quais informações e resultados deseja incluir nos arquivos de saída. | Avaliar a possibilidade de permitir que o docente selecione ou filtre as métricas que deseja consultar para sua análise. |

## 3. Softwares que o público-alvo usa no cotidiano

Analise interfaces que moldam a expectativa do público, mesmo que não sejam concorrentes.

| Software | Por que o público usa | Padrões relevantes | Prints | O que aprender |
|---|---|---|---|---|
| Google Sala de Aula (Classroom) | Centraliza aulas, materiais, atividades e comunicação. Cria turmas, compartilha arquivos, define prazos, aplica trabalhos e dá feedback. Integra-se ao Drive, Docs, Planilhas e Meet. | Centralização, simplicidade, navegação intuitiva, integração com ecossistema. |`assets/02_concorrencia/googleClassroom-inicio.jpeg`, `assets/02_concorrencia/googleClassroom-muralAvisos.jpeg`,`assets/02_concorrencia/googleClassroom-criarAtividade.jpeg`| Organização das informações por etapas e centralização dos recursos utilizados pelo docente. |
| Ferramentas de IA — ChatGPT | IA generativa para planejamento, criação de conteúdo e automação. Gera planos, atividades, exercícios, roteiros, textos, questões, adapta materiais, simula diálogos, sugere exemplos e auxilia na correção. | Automação, assistência inteligente, redução de tarefas repetitivas. |`assets/02_concorrencia/chatGPT.upload.jpeg`, `assets/02_concorrencia/chatGPT.conversa.jpeg`| Interfaces que reduzem etapas desnecessárias podem facilitar tarefas recorrentes do usuário. |
| Kahoot! | Gamificação para revisão e avaliação interativa. Cria quizzes, enquetes, jogos em tempo real. Feedback imediato, rankings, imagens, vídeos e música. Para revisão, avaliação formativa e engajamento.| Feedback imediato, pontuação, competição saudável, elementos lúdicos. | `assets/02_concorrencia/kahoot-criar.jpeg`,`assets/02_concorrencia/kahoot-inicio.jpeg`,`assets/02_concorrencia/kahoot-relatorio.jpeg`,`assets/02_concorrencia/kahoot-relatório2.jpeg`, `assets/02_concorrencia/kahoot-criacao.jpeg`, `assets/02_concorrencia/kahoot-criacao2.jpeg`,| Dashboards podem facilitar a compreensão inicial dos resultados ao reunir as principais informações em uma visão geral. |
| Google Forms| Criação e aplicação de questionários e avaliações. Elabora provas, listas de exercícios, com correção automática, organização de respostas e análise de resultados. | Simplicidade, correção automática, organização de dados, integração com Planilhas. | `assets/02_concorrencia/forms-relatorio.jpeg`,`assets/02_concorrencia/forms-inicio.jpeg`,`assets/02_concorrencia/forms-exemplo-importacao.jpeg`,`assets/02_concorrencia/forms-opcoes.jpeg`| Organização dos dados e apresentação dos resultados de forma estruturada podem facilitar a consulta e a análise. |
| YouTube | Plataforma de vídeos para complementar o ensino. Disponibiliza videoaulas, conteúdos explicativos, documentários, animações. Cria playlists, compartilha links, enriquece o repertório didático com linguagem audiovisual. | Acessibilidade, conteúdo visual, linguagem próxima do aluno. | `assets/02_concorrencia/youtube-criacao.jpeg`,`assets/02_concorrencia/youtube-enviar-video.jpeg`, `assets/02_concorrencia/youtube-detalhes.jpeg`| A organização e o acesso direto ao conteúdo facilitam sua localização e consulta. |


## 3.1 Padrões de interface relevantes ao escopo de IHC

Registre somente padrões encontrados nas soluções analisadas e que possam ter relação com objetivos reais da equipe.

| Padrão observado | Produto(s) | Para qual tarefa serve | Vantagem percebida | Risco/limitação | Aplicável ao nosso escopo? |
|---|---|---|---|---|---|
| Dashboard | Ferramentas de IA; Google Forms; Kahoot; Google Classroom | Apresentar uma visão geral das principais informações e resultados | Centraliza informações mais relevantes e facilita a compreensão inicial dos resultados | Pode concentrar muitas informações e dificultar a compreensão se não houver boa organização, hierarquia visual e descrição adequada | Sim |
| Relatório | Ferramentas de IA; Google Classroom; Kahoot!; Google Forms | Organizar e apresentar os resultados da análise de forma estruturada, permitindo consultar informações com diferentes níveis de detalhamento | Facilita a interpretação dos resultados | O excesso de informações pode dificultar a localização dos dados mais relevantes | Sim |
| Histórico + filtros | Ferramentas de IA; YouTube | Consultar informações ou interações anteriores e localizar conteúdos específicos | Facilita a recuperação de informações e a localização de conteúdos relevantes | Aumenta a complexidade da interface e pode não ser necessário para o escopo atual | Não, considerando o escopo atual. |
| Administração/CRUD | Google Classroom; Google Forms; Ferramentas de IA; Kahoot | Gerenciar usuários, turmas, atividades e conteúdos | Permite organizar e administrar diferentes elementos do sistema | Adiciona funcionalidades que não são essenciais para a análise proposta | Não |
| Comparação de resultados | Ferramentas de IA | Comparar informações ou resultados obtidos em diferentes análises | Facilita a identificação de diferenças e padrões entre os resultados | Pode gerar uma interface mais complexa quando há muitos resultados ou elementos para comparar | Não, pois a comparação entre diferentes análises não constitui uma tarefa central do escopo atual. |
| Detalhamento pós-processamento | Ferramentas de IA | Permitir que o usuário consulte detalhes e explicações após a obtenção dos resultados | Permite aprofundar a análise sem sobrecarregar a visualização inicial | O excesso de informações pode dificultar a navegação e a compreensão dos resultados | Sim |
| Upload | Google Forms; Ferramentas de IA; YouTube; Kahoot; Google Classroom | Enviar um pdf para processamento e análise. | Torna a entrada de dados simples e direta para o usuário |É necessário orientar o usuário sobre formatos e requisitos do arquivo enviado. | Sim |

## 4. Síntese comparativa da equipe

| Critério | C01 | C02 | C03 | Oportunidade para o projeto |
|---|---|---|---|---|
| Dashboard | X | X | - | Julgamos adequado adotá-lo no projeto, utilizando diferentes recursos de visualização, como gráficos, cores, indicadores e legendas, para facilitar a identificação de padrões e diferenças entre as métricas. Deve-se, entretanto, manter uma hierarquia visual adequada para evitar excesso de informações. |
| Descrição de como funciona | - | X | - | Achamos relevante adotar o padrão visto em C02, principalmente porque as métricas utilizadas no projeto podem exigir conhecimento prévio para serem interpretadas. As explicações devem ser apresentadas de forma objetiva, sem sobrecarregar a interface principal. |
| Upload de arquivos | X | X | X | Consideramos adequado seguir o padrão dos produtos analisados, adaptando-o ao contexto do projeto para tornar o envio da prova simples e reduzir a necessidade de configurações técnicas por parte do docente. |
| Exportação / download dos resultados | - | - | X | Embora não pretendamos reproduzir necessariamente o formato de relatório (como é apresentado no C03), consideramos relevante oferecer uma forma de exportar as métricas apresentadas no dashboard, permitindo seu uso e consulta fora da ferramenta. |

## 5. Recomendações derivadas

Liste recomendações com origem explícita.

- **RC01 - Recursos Visuais:** Utilizar diferentes recursos visuais, como gráficos, indicadores, cores e legendas, para apresentar as métricas e facilitar a identificação e interpretação dos resultados — derivada de **C01, C02 e C03**.

- **RC02 - Upload Simples e Claro:** Desenvolver uma etapa de upload simples e clara, com orientações sobre o arquivo esperado e as informações necessárias para a análise — derivada de **C01, C02 e C03**.

- **RC03:** Disponibilizar explicações sobre o funcionamento da análise, o significado das métricas e a forma como os resultados foram obtidos, permitindo que o usuário compreenda melhor as informações apresentadas — derivada de **C02 e C03**.

<!--  
- **RC04:** Permitir a exportação ou o download das métricas e resultados apresentados no dashboard, possibilitando que o usuário armazene e consulte os resultados posteriormente — derivada de **C03**. 
-->

- **RC04:** Organizar a interface com hierarquia visual clara, priorizando as informações relevantes em cada etapa, reduzindo opções desnecessárias e separando a visão geral dos resultados de seus detalhamentos. Utilizar rótulos compreensíveis ao docente e diferentes formas de apresentação, como tabelas e gráficos, conforme a necessidade de consulta.

## 6. Histórico de revisões

- Mudança nos caminhos das imagens, todos estão agora no modelo 'assets/02_concorrencia/criacao_prova1.png'

- Na seção 2, na coluna "Observação de IHC", está explicando de acordo com as prints

- Em rastreabilidade.md foram adicionadas as informações dessa entrega

- Ajustes nas recomendações da seção 5

- Correção na análise do Keptune, na tabela dos pontos positivos, negativos e lições. Agora não está especificando uma solução concreta

- Na seção 3, houve um ajuste para que as informações tivessem uma conexão mais clara com as tarefas do nosso projeto

- Ajuste nas seções 2 e 3 de partes em que o texto estava muito genérico/amplo. 

## Referências
<!--{{fontes dos produtos, avaliações e literatura}} -->
- KEPTUNE. Keptune: data analysis AI for Excel, CSVs & databases. [S. l.]: Keptune, [s. d.]. Disponível em: https://keptune.ai/. Acesso em: 28 ago. 2026.

- TENERETEAM. Keptune: avaliações e recursos. [S. l.]: Tenereteam, [s. d.]. Disponível em: https://keptune.tenereteam.com/. Acesso em: 28 ago. 2026.

- SCAMADVISER. Keptune.ai: análise de confiabilidade do site. [S. l.]: ScamAdviser, [s. d.]. Disponível em: https://www.scamadviser.com/check-website/keptune.ai. Acesso em: 28 ago. 2026.

- GRIDINSOFT. Keptune.ai: análise de segurança e reputação do domínio. [S. l.]: Gridinsoft, [s. d.]. Disponível em: https://pt.gridinsoft.com/domain/keptune.ai. Acesso em: 28 ago. 2026.

- KEPTUNE. Julius AI vs Keptune AI. [S. l.]: Keptune, [s. d.]. Disponível em: https://keptune.ai/articles/julius-ai-alternative. Acesso em: 28 ago. 2026.

- HURTZ, Gregory M. Measurement: Interdisciplinary Research and Perspectives, 2022. Disponível em: https://www.tandfonline.com/doi/full/10.1080/15366367.2022.2026736?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

- GIERL, Mark J.; ACKERMAN, Terry. Software Review: XCALIBRE — Marginal Maximum-Likelihood Estimation Program, Windows Version 1.10. Applied Psychological Measurement, v. 20, n. 3, p. 303–307, 1996. Disponível em: https://assess.com/docs/Xcalibre_1996_review.pdf?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

- SANTOS, Amanda da Silva; SANTOS, [nome completo do coautor]. Percepções docentes sobre o uso de recursos digitais: um estudo com professores dos cursos de licenciatura do IFAL-Campus Maceió. Maceió: Instituto Federal de Alagoas, 2025. Trabalho de Conclusão de Curso (Licenciatura em Ciências Biológicas) – Instituto Federal de Alagoas, Campus Maceió. Disponível em: https://repositorio.ifal.edu.br/server/api/core/bitstreams/e7bb7a93-9870-48db-825c-fb43f0838228/content. Acesso em: 2 set. 2026.

- OLIVEIRA, Arthur Marques de; TUSSI, Graziela Bergonsi. Docência e inteligência artificial (IA): caminhos na era da educação 5.0. Revista de Produtos Educacionais e Pesquisas em Ensino, Cornélio Procópio, v. 9, n. 2, p. 106–122, 2025. Disponível em: https://periodicos.uenp.edu.br/index.php/reppe/article/view/2048. Acesso em: 2 set. 2026.

- LIMA, A. P. et al. This diversity of perspectives, previous experiences, and the rate of non-use of DTRs in face-to-face education. Revista Brasileira de Informática na Educação (RBIE), Porto Alegre, v. 32, p. 533–567, 2024. DOI: https://doi.org/10.5753/rbie.2024.3894. Disponível em: https://journals-sol.sbc.org.br/index.php/rbie/article/download/3894/2971/22967. Acesso em: 2 set. 2026.

- Lucida — Crie atividades com IA em segundos. Disponível em: <https://lucidaexam.com/>. Acesso em: 6 set.. 2026.

- GRUETZMACHER, Felipe. UX Writing acessível: como guiar pessoas sem barreiras. Disponível em: <https://www.pertodigital.com.br/blog/ux-writing-acessivel-como-guiar-pessoas-sem-barreiras>. Acesso em: 6 set.. 2026.

- GORDON, Kelley. Visual Hierarchy in UX: Definition. Disponível em: <https://www.nngroup.com/articles/visual-hierarchy-ux-definition/?lm=why-does-a-design-look-good-part2&pt=article>. Acesso em: 6 set.. 2026.

- GORDON, Kelley. 5 Principles of Visual Design in UX. Disponível em: <https://www.nngroup.com/articles/principles-visual-design/?lm=screen-resolution-and-page-layout&pt=article>. Acesso em: 6 set.. 2026.




## Checklist

- [X] O mapa inicial de alternativas da Entrega 1 foi revisitado e aprofundado.
- [X] Hipóteses relevantes sobre mercado/padrões foram atualizadas na rastreabilidade quando surgiram evidências.
- [X] Há pelo menos uma análise completa por integrante.
- [X] Cada análise contém prints legíveis da interface.
- [X] Prints mostram telas/estados relevantes, não apenas logos/homepage.
- [X] Foram analisados concorrentes e/ou interfaces representativas ao público.
- [ ] Em TCC sem interface original, foram investigadas ferramentas profissionais análogas às atividades do usuário escolhido.
- [X] Padrões como dashboard, relatório, filtros e CRUD foram analisados como soluções para tarefas, não como requisitos automáticos.
- [X] Opiniões de UX têm fonte.
- [X] A síntese compara critérios comuns e produz recomendações.
- [X] Não há “copiar porque o concorrente faz”; há justificativa de adequação ao público/contexto.
