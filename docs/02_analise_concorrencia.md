# Entrega 2 — Público-alvo e análise de concorrência

*Data:* 26/10/2026 <br>
*Status:* 🟨 em andamento <br>
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
| Criação de prova | Na plataforma, o professor pode fazer uma prova através do upload de material, além da escolha de alguns parâmetros, como nível de dificuldade desejado, número de questões, entre outros | `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova1.png` `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova2.png` `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova3.png` `assets/02_concorrencia/criacao_prova4.png ` | {{...}} | 
| Análise e métricas de provas | Após a aplicação de uma prova, o professor pode inserir na plataforma a folha de respostas dos alunos, assim sendo calculadas a dificuldade e fator discriminatório de cada questão, além de apontar questões fracas e distratores efetivos  | `assets/02_concorrencia/analiselucida1.png`| As informações estão bem organizadas e fáceis de compreender | 

#### Experiência do usuário e opiniões

Use avaliações públicas, relatos, estudos, testes próprios ou outra fonte identificável. Não trate opinião isolada como verdade universal.

No momento não existem avaliações públicas da plataforma fora de poucas avaliações positivas presentes no site da plataforma. A experiência do grupo utilizando a ferramenta ocorreu de forma relativamente tranquila, sem grandes problemas técnicos ou confusões em como utilizar do site, apenas um problema com o upload de folha de respostas na etapa de correção de provas. O site contém um visual limpo e minimalista, com poucos botões e funcionalidades bem explicadas, seja na homepage ou dentro da área do usuário.
#### Padrões e tendências percebidos

A plataforma faz um esforço maior para auxiliar os usuários a compreenderem as estatísticas que estão sendo mostradas para eles, através de gráficos e tabelas, além de possuir indicadores separados por cor para indicar se a prova obteve bons resultados ou não.  

Também é possível perceber o uso de IAs para auxiliar docentes a facilitarem o seu trabalho, neste caso servindo como formulador de prova, corretor e analista para calcular os dados relevantes sobre os resultados da prova. 

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
|**Ponto positivo — Interface amigável** | A interface é simples de utilizar, com instruções claras sobre o que o usuário deve fazer para poder ter o melhor uso da plataforma, além de não precisar de conhecimentos de programação ou de informática. | Uma plataforma amigável para pessoas com menor letramento digital |
|**Limitação — Customização Limitada** | As avaliações que podem ser avaliadas pela plataforma são feitas apenas em provas criadas pela plataforma e scanea apenas folhas de respostas geradas também pela ferramenta. Enquanto o professor pode editar os resultados dados pela IA, não pode inserir questões criadas anteriormente ou | {{...}} |
|**Ponto Positivo — Variedade de métricas** | A ferramenta disponibiliza várias métricas para auxiliar o professor a se adaptar de acordo com as dificuldades de cada turma, oferencendo dificuldade e fator discriminatório, além de análise de distratores efetivos, questões fracas e comparação entre aluno e a turma completa.  | Oferecer métricas relevantes para melhorar a formulação de provas.|


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
| Upload de arquivos de respostas dos participantes | Precisa fazer o upload de um arquivo em formato CSV ou Excel, seguindo a estrutura especificada pela plataforma para permitir a realização da análise dos itens | `../assets/02_concorrencia/keptune_upload1.jpeg` , `../assets/02_concorrencia/keptune_upload2.jpeg` | Processo bastante intuitivo. |
| Utilização de inteligência artificial para realizar a análise | Na parte de chat, conseguimos conversar com IA para solicitar análise dos itens (calcular métricas como dificuldade e discriminação, identificando itens que podem precisar de revisão, entre outros)| `../assets/02_concorrencia/keptune_analise1` , `../assets/02_concorrencia/keptune_analise2`  | Plataforma com uma ótimo UX, design bem amigável e rápida em responder |
| Visualização de resultados em tabelas, gráficos e outros formatos | Após solicitar uma análise ou fazer uma pergunta à IA, a ferramenta apresenta os resultados no próprio chat, por meio de tabelas, gráficos e outras visualizações, além de disponibilizá-los na seção lateral de tabelas.| `../assets/02_concorrencia/keptune_analise1` , `../assets/02_concorrencia/keptune_analise2`, `../assets/02_concorrencia/keptune_analise3` , `../assets/02_concorrencia/keptune_analise4` | Boa visualização de resultados, gera diferentes gráficos e formatos com diversas cores e categoria as visualizações entre chat e aba lateral, facilitando a organização, além de sugerir recomendações |

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
   
 - A plataforma não só responde com texto, mas também executa código (Python) por trás dos panos e devolve os resultados em forma de tabelas e gráficos. Isso lembra ferramentas tem a vantagem de mostrar o código gerado e permitir edição, dando mais transparência e controle ao usuário.

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
|**Ponto positivo — Interface com informações precisas e diretas** | A interface é visualmente atraente, com organização clara entre chat e aba lateral, apenas com o necessário  informações em tela e organizado de forma que não fique poluído visualmente. | Devemos priorizar um design limpo e funcional, separando bem as áreas de interação para evitar sobrecarga de informações e facilitar a navegação. Isso ajuda a reduzir a curva de aprendizado e melhora a experiência do usuário, especialmente para quem não tem familiaridade com ferramentas de análise de dados. |
|**Ponto positivo — Agilidade nas respostas da IA** | A ferramenta processa comandos e gera análises (tabelas, gráficos, estatísticas) em poucos segundos. | Nenhuma, não integraremos nosso sistema com Inteligência Artifical. |
|**Ponto positivo — Transparência e controle sobre os dados** | O usuário pode ver cada etapa da transformação dos dados e editar o código Python gerado pelas visualizações. | Precisamos garantir a transparência por meio de explicações claras e acessíveis sobre cada métrica apresentada. Isso inclui: descrições do que cada indicador significa, como foi calculado. Podemos usar tooltips, ícones de ajuda, glossário e seções de "como interpretar" no dashboard. Isso fornece ao docente controle interpretativo e reduz o risco de uso incorreto das métricas, já que ele poderá compreender o que está vendo e tomar decisões mais embasadas. |
|**Ponto positivo — Variedade de visualizações e análises** | A plataforma gera resultados personalizados conforme solicitado à I.A., produzindo múltiplos formatos de visualização: tabelas resumo com médias e desvios; gráficos de distribuição dos parâmetros (boxplots); listas detalhadas de itens com problemas (com motivos: discriminação baixa, acaso elevado, dificuldade extrema); gráficos de barras com distribuição de dificuldade por área; contagens e percentuais de itens por motivo de revisão. Os resultados ficam salvos na aba lateral para consulta posterior. | Propomos um dashboard que organize as métricas extraídas em seções claras e objetivas, garantindo fácil compreensão pelos docentes. A ferramenta poderá conter: tabelas; gráficos variados; lista de itens com alertas, contendo motivos destacados e sugestões de ajuste; e gráficos de barras para distribuição de dificuldade por área.Para facilitar a interpretação, incluiremos tooltips explicativos em cada métrica, um glossário de termos técnicos e ícones de ajuda com recomendações práticas. Também disponibilizaremos botões de exportação (CSV/PDF) para que o docente possa salvar ou compartilhar os resultados. As cores serão usadas estrategicamente(vermelho para parâmetros críticos e verde para adequados). |
|**Ponto positivo — Custo benefício** | A plataforma oferece plano gratuito generoso e planos pagos a partir de US$ 5/mês, sendo mais acessível que alguns concorrentes | Nenhuma, nosso sistema será 100% gratuito e disponível para todos|
|**Limitação —Formato específico de arquivo para upload** |O upload exige que os arquivos estejam nos formatos CSV ou Excel e sigam uma estrutura específica, o que pode representar uma barreira para usuários menos experientes. Essa exigência pode dificultar ou até impedir o uso da plataforma por alguns docentes que não possuem seus dados organizados nesse formato.| Idealmente, o sistema deveria possibilitar o upload de diferentes tipos de arquivos e formatos de prova, de modo a atender ao maior número possível de usuários. Entretanto, nesta primeira versão, considerando o escopo e as funcionalidades desenvolvidas com base na estrutura das provas do ENEM, o sistema aceitará apenas arquivos em formato PDF que apresentem uma estrutura semelhante à utilizada pelo exame.|
|**Limitação —Ferramenta em fase de crescimento**  | Plataforma recente (Termos e Condições de junho/2024) e ainda tem pouco tráfego (~2.187 visitas/mês), o que é normal para uma ferramenta nova. Isso indica que o mercado ainda está aberto para soluções focadas em nichos específicos  | Como o Keptune ainda não domina o mercado de análise de itens educacionais, há espaço para uma solução mais especializada e focada, como a nossa, direcionada a docentes do Estado de São Paulo que desejam analisar provas estilo ENEM antes da aplicação. |

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
| Input de arquivo | O usuário insere um arquivo nos formatos .txt ou .dat contendo os dados da avaliação e fornece parâmetros adicionais necessários para que o sistema interprete corretamente a estrutura e o conteúdo do arquivo. | `../assets/02_concorrencia/xcalibraInput1.png` e `../assets/02_concorrencia/xcalibraInput2.png`| A tela para upload e o local para colocar os parâmetros é confuso e tem um layout pouco chamativo |
| Configuração da análise e dos resultados | O usuário define parâmetros relacionados à análise e seleciona as informações e formatos que deseja obter como resultado do processamento. | `../assets/02_concorrencia/xcalibraConf.png` | A interface concentra diversas opções de configuração e utiliza terminologia técnica, exigindo conhecimento prévio do usuário para compreender e selecionar adequadamente os parâmetros. |
| Visualização de estatísticas dos itens | Os resultados da análise são apresentados por meio de tabelas que sintetizam estatísticas dos parâmetros estimados para os itens, como média, desvio-padrão, mínimo e máximo. |  `../assets/02_concorrencia/xcalibraResp.png` | A organização em tabelas facilita a consulta e a comparação dos valores obtidos |
| Visualização gráfica dos resultados | Os resultados também são apresentados por meio de gráficos que representam relações entre os parâmetros obtidos na análise, como dificuldade e discriminação dos itens. |  `../assets/02_concorrencia/xcalibraRespGraf.png` | A representação gráfica complementa os resultados numéricos e facilita a identificação visual de padrões e relações entre os parâmetros analisados. |

#### Experiência do usuário e opiniões

Não foram encontradas muitas avaliações sobre o software Xcalibre, sendo identificados principalmente relatos em artigos que utilizaram a ferramenta em contextos científicos. De modo geral, as avaliações encontradas indicam uma experiência de uso positiva. Hurtz (2022) caracteriza o software como relativamente amigável ao usuário e destaca sua interface gráfica para a configuração das análises e apresentação dos resultados. De forma semelhante, Gierl e Ackerman (1996) destacam a facilidade de uso e a organização lógica da interface gráfica. Apesar desses aspectos positivos, a utilização da ferramenta envolve conceitos e parâmetros específicos da TRI, o que pode exigir conhecimento prévio do usuário. Além disso, a análise realizada pela equipe identificou aspectos que podem representar oportunidades de melhoria sob a perspectiva de IHC, especialmente quanto à complexidade da entrada de dados e à organização visual da interface.

#### Padrões e tendências percebidos

A análise evidencia a necessidade de conhecimento prévio sobre os dados de entrada e sobre conceitos básicos de TRI, tornando a configuração inicial mais complexa. Em contrapartida, observa-se uma preocupação em facilitar a interpretação dos resultados por meio de tabelas, gráficos e relatórios que reúnem as métricas previamente selecionadas pelo usuário.

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| **Limitação — Complexidade da entrada de dados** | O Xcalibre exige que o usuário conheça a estrutura do arquivo de entrada e forneça parâmetros adicionais para que os dados sejam interpretados corretamente. | Buscar simplificar a entrada de dados, permitindo que o docente envie a prova com o mínimo possível de configurações adicionais. |
| **Limitação — Necessidade de conhecimento específico** | A configuração e a interpretação das análises envolvem conceitos específicos da TRI e terminologia técnica. | Apresentar as métricas de maneira acessível ao docente, oferecendo explicações sobre seu significado e sua relação com o desempenho dos estudantes. |
| **Ponto positivo — Apresentação visual dos resultados** | Os resultados são apresentados por meio de tabelas e gráficos, facilitando a visualização das métricas obtidas. | Utilizar recursos visuais para facilitar a compreensão das características estruturais identificadas e de suas possíveis relações com o desempenho. |
| **Ponto positivo — Geração de relatórios** | O Xcalibre permite gerar relatórios contendo as métricas e os resultados configurados pelo usuário. | Considerar a apresentação dos resultados de forma organizada e consolidada, facilitando sua consulta pelo docente. |
| **Ponto positivo — Personalização dos resultados** | O usuário pode selecionar previamente quais informações e resultados deseja incluir nos arquivos de saída. | Avaliar a possibilidade de permitir que o docente selecione ou filtre as métricas que considera mais relevantes para sua análise. |

## 3. Softwares que o público-alvo usa no cotidiano

Analise interfaces que moldam a expectativa do público, mesmo que não sejam concorrentes.

Google Forms

O Google Forms é amplamente utilizado para criação e aplicação de questionários e avaliações. A pesquisa do IFAL (2025) o cita entre os recursos digitais utilizados para elaboração de avaliações, listas de exercícios e provas, incluindo recursos de correção automática. Estudos também relatam sua utilização por professores de diferentes disciplinas para aplicação de avaliações e coleta de dados.

Influência sobre as expectativas: o Forms estabeleceu um padrão de facilidade e rapidez na criação de avaliações. Os professores passaram a esperar recursos como criação simplificada de formulários, correção automática, organização das respostas e possibilidade de análise dos resultados. Dessa forma, funcionalidades que antes poderiam ser consideradas diferenciais passam a ser percebidas como requisitos básicos de usabilidade.

YouTube

O YouTube é uma plataforma de compartilhamento de vídeos que se tornou um recurso complementar essencial no ensino. Professores utilizam a ferramenta para disponibilizar videoaulas, conteúdos explicativos, documentários, animações e outros materiais audiovisuais que auxiliam na compreensão de conceitos abordados em sala de aula. Além disso, a plataforma permite a criação de playlists organizadas por tema, o compartilhamento de links com os alunos e a utilização de vídeos como ponto de partida para debates, pesquisas e atividades práticas, enriquecendo o repertório didático com diferentes linguagens.

Influência sobre as expectativas: o YouTube contribuiu para estabelecer a expectativa de que conteúdos educacionais podem ser visuais, acessíveis e consumidos de forma rápida e intuitiva. Isso aumenta a valorização de recursos multimídia, como vídeos, imagens e conteúdos interativos, além da possibilidade de complementar materiais tradicionais com diferentes formatos de aprendizagem.


| Software | Por que o público usa | Padrões relevantes | Prints | O que aprender |
|---|---|---|---|---|
| Google Sala de Aula (Classroom) | Centraliza aulas, materiais, atividades e comunicação. Cria turmas, compartilha arquivos, define prazos, aplica trabalhos e dá feedback. Integra-se ao Drive, Docs, Planilhas e Meet. | Centralização, simplicidade, navegação intuitiva, integração com ecossistema. |`assets/02_concorrencia/googleClassroom-inicio.jpeg`, | integrações facilitam usabilidade, plataforma apenas com informaões necessárias nas respectivas etapas(Interface limpa) |
googleClassroom-inicio <!--VER TUTORIAL PASSO A PASSO E PEGAR PRINTS DE LA>

| Ferramentas de IA — ChatGPT | IA generativa para planejamento, criação de conteúdo e automação. Gera planos, atividades, exercícios, roteiros, textos, questões, adapta materiais, simula diálogos, sugere exemplos e auxilia na correção. | Automação, assistência inteligente, redução de tarefas repetitivas. |`assets/02_concorrencia/chatGPT.upload.jpeg`, `assets/02_concorrencia/chatGPT.conversa.jpeg`| valorização ferramentas que economizam tempo e personalizam conteúdos |
| Kahoot! | Gamificação para revisão e avaliação interativa. Cria quizzes, enquetes, jogos em tempo real. Feedback imediato, rankings, imagens, vídeos e música. Para revisão, avaliação formativa e engajamento.| Feedback imediato, pontuação, competição saudável, elementos lúdicos. | `assets/02_concorrencia/kahoot-criar.jpeg`,`assets/02_concorrencia/kahoot-inicio.jpeg`,`assets/02_concorrencia/kahoot-relatorio.jpeg`,`assets/02_concorrencia/kahoot-relatorio2.jpeg`, `assets/02_concorrencia/kahoot-criacao.jpeg`, `assets/02_concorrencia/kahoot-criacao2.jpeg`,| Avaliação pode ser dinâmica e engajadora; não apenas funcional, dashboard com reusltados facilita compreensão geral|
| Google Forms| Criação e aplicação de questionários e avaliações. Elabora provas, listas de exercícios, com correção automática, organização de respostas e análise de resultados. | Simplicidade, correção automática, organização de dados, integração com Planilhas. | `assets/02_concorrencia/forms-relatorio.jpeg`,`assets/02_concorrencia/forms-inicio.jpeg`,`assets/02_concorrencia/forms-exemplo-importacao.jpeg`,`assets/02_concorrencia/forms-exemplo-opcoes.jpeg`| Correção automática e organização de respostas. |
| YouTube | Plataforma de vídeos para complementar o ensino. Disponibiliza videoaulas, conteúdos explicativos, documentários, animações. Cria playlists, compartilha links, enriquece o repertório didático com linguagem audiovisual. | Acessibilidade, conteúdo visual, linguagem próxima do aluno. | `assets/02_concorrencia/youtube-criacao.jpeg`,`assets/02_concorrencia/youtube-enviar-video.jpeg`, `assets/02_concorrencia/youtube-enviar-detalhes.jpeg`| Conteúdo educacional deve ser visual, rápido e de fácil acesso e com possível restrição de visualizadores |


## 3.1 Padrões de interface relevantes ao escopo de IHC

Registre somente padrões encontrados nas soluções analisadas e que possam ter relação com objetivos reais da equipe.

| Padrão observado | Produto(s) | Para qual tarefa serve | Vantagem percebida | Risco/limitação | Aplicável ao nosso escopo? |
|---|---|---|---|---|---|
| Dashboard | Ferramentas de IA; Google Forms; Kahoot; Google Classroom | Apresentar uma visão geral das principais informações e resultados | Centraliza informações e facilita a visualização inicial dos resultados por meio de elementos visuais | Pode concentrar muitas informações e dificultar a compreensão se não houver boa organização, hierarquia visual e descrição adequada | Sim |
| Relatório | Ferramentas de IA; Google Classroom; Kahoot!; Google Forms | Organizar e apresentar os resultados da análise de forma estruturada, permitindo consultar informações com diferentes níveis de detalhamento | Facilita a interpretação dos resultados e o acesso às informações de forma organizada, reunindo e estruturando os dados obtidos | O excesso de informações pode dificultar a localização dos dados mais relevantes | Não |
| Histórico + filtros | Ferramentas de IA; YouTube | Consultar informações ou interações anteriores e localizar conteúdos específicos | Facilita a recuperação de informações e a localização de conteúdos relevantes | Aumenta a complexidade da interface e pode não ser necessário para o escopo atual | Não |
| Administração/CRUD | Google Classroom; Google Forms; Ferramentas de IA; Kahoot | Gerenciar usuários, turmas, atividades e conteúdos | Permite organizar e administrar diferentes elementos do sistema | Adiciona funcionalidades que não são essenciais para a análise proposta | Não |
| Comparação de resultados | Ferramentas de IA | Comparar informações ou resultados obtidos em diferentes análises | Facilita a identificação de diferenças e padrões entre os resultados | Pode gerar uma interface mais complexa quando há muitos resultados ou elementos para comparar | Não |
| Detalhamento pós-processamento | Ferramentas de IA | Permitir que o usuário consulte detalhes e explicações após a obtenção dos resultados | Permite aprofundar a análise sem sobrecarregar a visualização inicial | O excesso de informações pode dificultar a navegação e a compreensão dos resultados | Sim |
| Upload | Google Forms; Ferramentas de IA; YouTube; Kahoot; Google Classroom | Enviar arquivos, textos ou outras informações para serem processados pelo sistema | Torna a entrada de dados simples e direta para o usuário | É necessário validar o formato, o tamanho e o conteúdo dos dados enviados | Sim |

## 4. Síntese comparativa da equipe

| Critério | C01 | C02 | C03 | Oportunidade para o projeto |
|---|---|---|---|---|
| Dashboard | X | X | - | Julgamos adequado adotá-lo no projeto, utilizando diferentes recursos de visualização, como gráficos, cores, indicadores e legendas, para facilitar a identificação de padrões e diferenças entre as métricas. Deve-se, entretanto, manter uma hierarquia visual adequada para evitar excesso de informações. |
| Descrição de como funciona | - | X | - | Achamos relevante adotar o padrão visto em C02, principalmente porque as métricas utilizadas no projeto podem exigir conhecimento prévio para serem interpretadas. As explicações devem ser apresentadas de forma objetiva, sem sobrecarregar a interface principal. |
| Upload de arquivos | X | X | X | Consideramos adequado seguir o padrão dos produtos analisados, adaptando-o ao contexto do projeto para tornar o envio da prova simples e reduzir a necessidade de configurações técnicas por parte do docente. |
| Exportação / download dos resultados | - | - | X | Embora não pretendamos reproduzir necessariamente o formato de relatório (como é apresentado no C03), consideramos relevante oferecer uma forma de exportar as métricas apresentadas no dashboard, permitindo seu uso e consulta fora da ferramenta. |

## 5. Recomendações derivadas

Liste recomendações com origem explícita.

- **RC01:** Utilizar diferentes recursos visuais, como gráficos, indicadores, cores e legendas, para apresentar as métricas e facilitar a identificação e interpretação dos resultados — derivada de **C01 e C02**.

- **RC02:** Desenvolver uma etapa de upload simples e clara, com orientações sobre o arquivo esperado e as informações necessárias para a análise — derivada de **C01, C02 e C03**.

- **RC03:** Disponibilizar explicações sobre o funcionamento da análise, o significado das métricas e a forma como os resultados foram obtidos, permitindo que o usuário compreenda melhor as informações apresentadas — derivada de **C02**.

- **RC04:** Permitir a exportação ou o download das métricas e resultados apresentados no dashboard, possibilitando que o usuário armazene e consulte os resultados posteriormente — derivada de **C03**.

- **RC05:** Desenvolver uma interface simples, organizada e intuitiva, priorizando a visibilidade das informações relevantes e evitando o excesso de elementos na apresentação dos resultados — derivada das **observações da equipe durante a análise das soluções C01, C02 e C03**.

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


## Checklist

- [ ] O mapa inicial de alternativas da Entrega 1 foi revisitado e aprofundado.
- [ ] Hipóteses relevantes sobre mercado/padrões foram atualizadas na rastreabilidade quando surgiram evidências.
- [ ] Há pelo menos uma análise completa por integrante.
- [ ] Cada análise contém prints legíveis da interface.
- [ ] Prints mostram telas/estados relevantes, não apenas logos/homepage.
- [ ] Foram analisados concorrentes e/ou interfaces representativas ao público.
- [ ] Em TCC sem interface original, foram investigadas ferramentas profissionais análogas às atividades do usuário escolhido.
- [ ] Padrões como dashboard, relatório, filtros e CRUD foram analisados como soluções para tarefas, não como requisitos automáticos.
- [ ] Opiniões de UX têm fonte.
- [ ] A síntese compara critérios comuns e produz recomendações.
- [ ] Não há “copiar porque o concorrente faz”; há justificativa de adequação ao público/contexto.
