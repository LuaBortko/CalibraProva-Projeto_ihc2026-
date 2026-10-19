# Entrega 7 — Coleta de dados, necessidades e aspectos éticos

**Data:** 15/10/2026
**Status:**  🟨 Em andamento  <br>

## Objetivo da atividade

<!--dica do feedback3

- **Entrega 07 - Coleta de dados:** validar H04 e as características hoje atribuídas às proto-personas, especialmente familiaridade tecnológica, conhecimento de métricas, frequência de elaboração de avaliações, ambiente de uso e necessidade de explicações. (levar em consideracao ao analisar de quem coletar e como coletar dados)

- **Avaliação futura:** verificar se diferentes níveis de experiência tecnológica realmente exigem comportamentos de interface distintos.
-->

Planejar dados necessários para compreender usuários e requisitos de IHC, escolher técnicas adequadas e documentar instrumentos de modo que a aplicação possa ser reproduzida por pessoas diferentes.

## Para escopos de IHC derivados de TCC técnico

Quando o usuário e a interface foram propostos pela disciplina, uma prioridade da coleta é investigar se esse **cenário de uso realmente faz sentido**. Não trate o exercício de comercialização da Entrega 1 como validação de mercado.

Perguntas úteis incluem:

- esse perfil realmente realiza a atividade imaginada? 
- quais ferramentas usa hoje? <!-- pesquisar dados reias, ate agr fizemos hipoteses -->
- quais informações consulta?<!-- pesquisar dados reias, ate agr fizemos hipoteses ex usa enem, enade, anotacoes de aula e provas anteriores p faze prova mas n comprovamos isso com nada -->
- quais decisões toma? 
- que vocabulário utiliza?
- quais parâmetros compreende e quais deveriam ser abstraídos?
- precisa de dashboard, histórico, filtros, relatórios ou comparação? Por quê?
- quais erros são frequentes e quais são críticos?
- existem papéis/permissões diferentes?
- que resultados do algoritmo/modelo seriam úteis ou difíceis de interpretar?

Quando o acesso ao perfil profissional for difícil, discuta com o docente alternativas metodológicas (especialistas próximos, dados secundários, literatura, participantes proxy) e registre as limitações. **Não esconda a limitação da amostra.**

## Hipóteses e lacunas prioritárias herdadas da Entrega 1

Antes de decidir “que dados coletar”, retome os itens `[H]` e `[?]` da Entrega 1 e o registro de hipóteses em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md). A coleta deve responder perguntas reais do projeto, e não apenas produzir um formulário porque a técnica foi solicitada.
<!-- NAO COLOCA HIPOTESES DA PERSOA EM RASTREABILIDADE -->
| ID | Hipótese/lacuna | Evidência atual | Decisão que depende da resposta | Prioridade |
|---|---|---|---|---|
| H01 | O formato da prova impacta do desempenho do aluno | [link repositório tcc](https://github.com/beatrizmanaia26/TCC-DesempenhoEnem) | A decisão de alterar o formato da prova depende da resposta da hipótese H01 | média |
| H02 | Poderá fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos | MVP | A decisão de "elaborar e revisar avaliações que meçam adequadamente os conhecimentos dos estudantes, buscando reduzir a influência das características estruturais da prova sobre seu desempenho e utilizando destes dados para aprimorar aulas" depende da resposta da hipótese H02 | Alta |
| H03 | Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes | Não tem | A decisão de escolher quais aspectos da aula devem ser modificados mais rigorosamente com base nos resultados da avaliação depende da resposta da hipótese H03 | Alta |
| H04 | Um docente do Estado de São Paulo precisa ter um mínimo de conhecimento tecnológico | Estamos desenvolvendo um sistema que apresenta funcionalidades básicas por parte do usuário, como fazer upload e conectar o dispositivo à intenret, com base nisso, difernetes tipos de personas, como as exploradas na entrega3 conseguem utilizar o sistema, desde que tenham o mínimo de conhecimento tecnológico. | A decisão de utilizar ou não o sistema depende de o usuário ter um conhecimento tecnológico mínimo, ou seja, depende da resposta da hipótese H04 | Alta |
| H05 | Os docentes utilizariam a interface durante a elaboração ou revisão das avaliações, antes de sua aplicação. | Não tem | Nenhuma | Baixa |
| H06 | O detalhamento de como cada métrica foi calculada pode auxiliar os docentes na interpretação dos resultados. | Entrega 2 e [link repositório tcc](https://github.com/beatrizmanaia26/TCC-DesempenhoEnem) | A decisão de ajustar a prova com base na análise das métricas oferecidas pelo sistema depende da resposta da hipótese H06 | Alta |
| H07 | Os docentes possuem conhecimento prévio de ferramentas voltadas à criação, gerenciamento ou análise de avaliações. | Entrega2 | Decisão de padrões de interface  depende da resposta da hipótese H07 pois, caso seja afirmativo, é bom reutilizar os padrões para manter os sistemas similares. | Alta |
| H08 | A apresentação das métricas pode auxiliar os docentes a decidir quais características estruturais da avaliação devem ser mantidas ou ajustadas. | Não tem | A decisão de ajustar a prova com base na análise das métricas oferecidas pelo sistema depende da resposta da hipótese H08 | Alta |
| H09 | Aluno poderia ser afetado pelo sistema indiretamente | Não consideramos que o aluno tem impacto no sistema de avaliação com base no ENEM pois o seu desenvolvimento é pautado apenas nas análises das provas do ENEM, sem sofrer influências de caraterísticas específicas dos alunos. | Nenhuma | Baixo |

## Parte A — necessidades e requisitos de IHC

> **Responsabilidade:** solução individual por integrante.

### A01 — Beatriz Manaia Lourenço Berto

**Autor(a):** Beatriz Manaia Lourenço Berto - 22.125.060-8

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
| Idiomas e jargões | Lacuna de idioma | Identifica o vocabulário, termos e jargões próprios da prática docente para garantir tanto que a linguagem do sistema seja natural e alinhada ao contexto do usuário, quanto perceber possíveis padrões em suas avaliações.| Design do sistema: Permitir que os docentes enviem termos e jargões utilizados em sua prática profissional para análise da prova e possível adaptacao da linguagem do sistema, buscando utilizar um vocabulário mais familiar, natural e acessível aos usuários, de acordo com seu contexto de atuação. |
| Experiência com computadores | H04 | Identifica o grau de proficiência tecnológica dos usuários e auxilia na verificação da correlação entre o conhecimento prévio dos participantes e a percepção de usabilidade. | Define a complexidade da interface, estabelecendo se o sistema exigirá guias assistidos, tutoriais contextuais ou uma navegação mais direta e minimalista. |
| Tecnologia disponível| Lacuna de informaçÕes específicas de recursos computacionais | Mapeia os recursos computacionais aos quais o usuário tem acesso, como hardware (tamanho e resolução do monitor, velocidade de processamento), softwares e ferramentas do cotidiano, identificando limitações do ambiente físico de trabalho | Pode afetar a responsabilidade do sistema e a usabilidade da ferramenta principal (análise da prova) |
| Conhecimentos das tarefas que deverá realizar no cargo| H05,H07 | Identifica quais tarefas o usuário precisa realizar no cotidiano, se são primárias ou secundárias, frequentes ou infrequentes, e qual a sua experiência prévia em tarefas semelhantes | O design pode ser ajustado para fornecer subsídios para facilitar ainda mais a execução das atividades |
| Experiência no cargo que ocupa | Lacuna referente a experiência em hipóteses | Informa o cargo atual do usuário, tempo de experiência na função, responsabilidades e trabalhos anteriores para entender sua maturidade profissional no planejamento de avaliações. | Define o grau de explicabilidade e a profundidade dos diagnósticos pedagógicos |
| Motivação para realização do trabalho | H02, H03 | Avalia qual o principal resultado esperado, se o usuário busca aperfeiçoamento por prazer/propósito ou se apenas cumpre obrigações da carga horária sob pressão de tempo | Define a hierarquia visual do dashboard inicial e o tom das notificações: se o professor busca propósito/aperfeiçoamento (H03), o design deve destacar relatórios de ganho pedagógico e métricas sobre a evolução das provas; se o foco for produtividade/pressão de tempo (H02), a interface deve priorizar a velocidade do fluxo, com relatórios sintéticos em 1 clique e resumos exportáveis para a coordenação. |
| Tarefas que precisa de suporte/auxilio (melhorar texto) | H01,H07 | Mapeia as principais dificuldades enfrentadas no cotidiano, identificando quais etapas exigem suporte (por exemplo:computacional) para alcançar seus objetivos | Determina a hierarquia das ferramentas de apoio e alertas do sistema: define quais automações e relatórios de correção de ruído estrutural devem receber destaque prioritário na navegação. |
| Ferramentas mais utilizadas no cotidiano | H07 | Mapeia os hábitos de uso, preferências, aversões e experiências prévias com softwares do domínio ou concorrentes (ex: Word, Google Docs, ChatGPT)| Deve tentar seguir os padrões de design dos sistemas cnhecidos e utilizados. |
| Quais suas atitudes em relação a um novo produto | H04, H07 | Identifica se o usuário costuma assumir riscos e explorar novas formas de trabalho ou se evita novas tecnologias, preferindo rotinas conhecidas ou guias passo a passo, considera também maneiras como o docente realiza suas avaliacoes  | Direciona a didática da interface e o nível de orientação ao usuário: define se a aplicação necessitará de tutoriais guiados, linguagem consultiva e elementos gráficos didáticos que facilitem o aprendizado e incentivem o uso por pessoas menos inclinadas a testar novos softwares.|
| Gravidade dos erros de uma avaliação | H01, H08, H09 | Avalia a frequência em que identifica problemas, as possíveis consequências dos erros cometidos pelo usuário ao elaborar uma prova. | Pode trazer uma hierarquia visual das métricas em decorrência das características qe mais afetam o desempenho em cada prova |
| Estilo de aprendizado e preferência por treinamento | Lacuna sobre treinamento | Identifica o quanto o usuário valoriza treinamentos, quanto tempo pode dedicar para aprender o produto e se prefere um estilo de aprendizado visual, prático ou guiado. | Determina o nível de suporte e a curva de aprendizado da aplicação: orienta o desenvolvimento de ajudas visuais na própria tela (como pequenos guias explicativos ao lado de gráficos complexos) para permitir que o usuário aprenda a usar a ferramenta enquanto executa suas tarefas. |
| Conhecimento do domínio do produto | H02, H06, H08 | Informa o quanto o usuário domina as características estruturais de exames organizados e a análise estatística de itens. | Define o nível de complexidade das visualizações de dados e a necessidade de tradução estatística: determina a escolha de gráficos simplificados (ex: barras e marcadores diretos) em detrimento de gráficos de dispersão complexos, além de direcionar o uso de tooltips explicativos e diagnósticos em linguagem natural que traduzam termos como "p-valor" ou "distratores". |

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| Docentes | Atuar na elaboração, revisão ou aplicação de avaliações de múltipla escolha (especialmente no Ensino Médio ou cursos preparatórios para vestibulares/ENEM). Representam os usuários primários da aplicação, diretamente responsáveis por interagir com a interface, subir arquivos e interpretar os diagnósticos. | P1,P3 |
| Alunos | Estudantes do Ensino Médio ou pré-vestibular que fazem provas de múltipla escolha com frequência. Eles são os afetados indiretamente pelo sistema (persona secundária) e não usam a interface, mas suas percepções sobre cansaço, ansiedade e tamanho dos enunciados ajudam a definir requisitos indiretos e a validar o impacto real do projeto. | P2 |

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.

A coleta de dados respeitará os princípios de não maleficência, justiça, autonomia e beneficência, avaliando os riscos e benefícios para docentes e alunos:

1- **Voluntariedade e consentimento:** antes da aplicação serão informados sobre os objetivos da pesquisa, as informações que serão coletadas, a finalidade de seu uso e o tempo estimado de participação, a participação será voluntária, mediante consentimento livre e esclarecido (TCLE) e com liberdade de desistência a qualquer momento sem prejuízos. Participações de menores seguirão as exigências éticas específicas.

2-**Minimização e privacidade dos dados:** serão coletadas apenas as informações necessárias para compreender o perfil, a fluência digital e as necessidades dos usuários, sem solicitar provas com identificação nominal de estudantes.

3-**Confidencialidade, anonimização e armazenamento:** as informações serão utilizadas exclusivamente para as finalidades informadas aos participantes. Os resultados serão apresentados de forma anonimizada, sem identificação dos indivíduos ou das instituições envolvidas. Os dados brutos serão armazenados em local seguro, com acesso restrito à equipe responsável, e mantidos apenas pelo período necessário, sendo posteriormente descartados de maneira adequada.

4-**Prevenção de riscos e beneficência:** a pesquisa deverá evitar constrangimentos, exposição de informações profissionais e situações que possam ser interpretadas como avaliação do desempenho dos docentes. As perguntas serão direcionadas às experiências, dificuldades e necessidades relacionadas às tarefas, sem julgamentos sobre a competência dos participantes. O tempo dedicado à pesquisa será limitado ao necessário.

5-**Justiça e equidade:** a seleção dos participantes buscará contemplar diferentes níveis de experiência profissional e familiaridade tecnológica, evitando que a pesquisa considere apenas docentes com maior domínio de ferramentas digitais. A participação de alunos, quando pertinente, deverá ocorrer de forma voluntária e sem prejuízos acadêmicos.


> **Responsabilidade:** solução individual por integrante.

### A02 — Luana Bortko Rodrigues

**Autor(a):** Luana Bortko Rodrigues - 24.123.006-9

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
| {{...}} | {{H01/H02/...}} | {{...}} | {{...}} |

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
| {{...}} | {{H01/H02/...}} | {{...}} | {{...}} |

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.


> **Responsabilidade:** solução individual por integrante.

### A03 — Nuno Martins Guilhermino da Silva

**Autor(a):** Nuno Martins Guilhermino da Silva - 22.126.099-5

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
| {{...}} | {{H01/H02/...}} | {{...}} | {{...}} |

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
| {{...}} | {{H01/H02/...}} | {{...}} | {{...}} |

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.

> Repita A02, A03... <!-- SE A VISAO FOR A MESMA TDBM, cada um faz cm-->

## Parte B — ferramentas de coleta
<!--ex investigacsao contextual, entrevista, questionario...simular(quesrtionario), fazer o correto pq plinio vai avaliar --> 
> Cada integrante deve preparar uma técnica/instrumento completo. As técnicas devem ser diferentes entre si e **questionário deve estar entre as técnicas escolhidas**, conforme o enunciado da disciplina.

### Instrumento I01 — Questionário 

**Autor(a):** Beatriz Manaia Lourenço Berto
**Técnica:** questionário 
**Objetivo:** Obter, de maneira rápida e estruturada, um conjunto de informações de diversos representantes do público-alvo, permitindo caracterizar o perfil dos docentes, sua familiaridade com tecnologias, seu conhecimento sobre avaliação da aprendizagem e suas necessidades no contexto de atuação profissional, a fim de identificar características do público e subsidiar a definição de requisitos de interação e interface do sistema.
**Público:** Docentes (com diferentes níveis de experiência profissional e familiaridade tecnológica) 

#### Procedimento padronizado de aplicação
<!--descrever passo a passo como questionário será aplicado de forma que outra pessoa consiga aplica-lo seguindo essas orientações-->
1. preparação:  <br>
- Elaborar o questionário com perguntas objetivas e, quando necessário, abertas, organizadas por temas relacionados ao perfil profissional dos docentes, à experiência com tecnologias, à elaboração de avaliações, ao conhecimento de métricas e às necessidades de apoio na interpretação dos resultados. Revisar as perguntas para evitar ambiguidades, indução de respostas e coleta de informações desnecessárias. Disponibilizar o instrumento em um formulário digital e definir os critérios de participação.<br>
2. apresentação/consentimento:<br>
- Apresentar aos participantes os objetivos da pesquisa, a finalidade da coleta, o tempo estimado de preenchimento, os dados solicitados e como as respostas serão utilizadas e protegidas. Informar que a participação é voluntária e que o participante pode desistir, conforme as condições apresentadas no consentimento, sem prejuízos. Solicitar o consentimento antes de iniciar o questionário.<br>
3. aplicação: <br>
- Disponibilizar o link do formulário aos docentes que atendam aos critérios de participação. Permitir que respondam individualmente, no momento e local de sua preferência, sem interferência nas respostas. Manter as mesmas perguntas e opções de resposta para todos os participantes, garantindo a padronização da coleta.<br>
4. encerramento: <br>
- Ao final do formulário, agradecer a participação e, se pertinente, disponibilizar um canal de contato para dúvidas sobre a pesquisa. Verificar se as respostas foram registradas corretamente, sem solicitar informações adicionais que permitam identificar os participantes desnecessariamente.<br>
5. armazenamento/anonimização <br>
-  Armazenar as respostas em ambiente digital protegido, com acesso restrito à equipe responsável pela pesquisa. Evitar a coleta de nomes, e-mails ou outros identificadores quando não forem necessários. Antes da análise e divulgação, remover ou generalizar eventuais informações identificáveis e apresentar os resultados de forma agrupada, mantendo os dados apenas pelo período necessário e realizando seu descarte adequado.

#### Instrumento

<!--Cole aqui o questionário/roteiro completo ou forneça link **mais uma cópia textual no repositório**.-->

- ![Link do questionário](https://forms.gle/iWctSMaRJMGyN9K36 ) 


#### Como os dados serão analisados

<!--{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}} -->

<!--ex investigacsao contextual, entrevista, questionario...simular(quesrtionario), fazer o correto pq plinio vai avaliar --> 

As respostas fechadas serão analisadas por meio da distribuição de frequências e proporções, identificando características dos participantes, como familiaridade tecnológica, frequência de elaboração de avaliações, ferramentas utilizadas e conhecimento sobre métricas. Também serão comparadas respostas de docentes com diferentes níveis de experiência, buscando identificar possíveis diferenças nas dificuldades e necessidades de suporte.

As respostas relacionadas às tarefas profissionais e ao uso de ferramentas contribuirão para investigar H05 e H07. Já as respostas sobre conhecimento e interpretação de métricas ajudarão a avaliar H06 e H08, enquanto a relação entre experiência tecnológica e necessidade de orientação contribuirá para investigar H04.

As respostas abertas serão analisadas por codificação temática, agrupando relatos semelhantes. Por fim, os resultados orientarão decisões de design e permitirão sustentar, refutar ou reformular as hipóteses, considerando que as respostas declaradas, isoladamente, não comprovam o comportamento real dos usuários nem a usabilidade do sistema.

> Cada integrante deve preparar uma técnica/instrumento completo. As técnicas devem ser diferentes entre si e **questionário deve estar entre as técnicas escolhidas**, conforme o enunciado da disciplina.

### Instrumento I02 — {{nome da técnica}}

**Autor(a):** Luana Bortko Rodrigues
**Técnica:** questionário / entrevista semiestruturada / observação / grupo focal / outra autorizada  
**Objetivo:** {{...}}  
**Público:** {{...}}

#### Procedimento padronizado de aplicação

1. {{preparação}}
2. {{apresentação/consentimento}}
3. {{aplicação}}
4. {{encerramento}}
5. {{armazenamento/anonimização}}

#### Instrumento

Cole aqui o questionário/roteiro completo ou forneça link **mais uma cópia textual no repositório**.

#### Como os dados serão analisados

{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}}


<!--ex investigacsao contextual, entrevista, questionario...simular(quesrtionario), fazer o correto pq plinio vai avaliar --> 
> Cada integrante deve preparar uma técnica/instrumento completo. As técnicas devem ser diferentes entre si e **questionário deve estar entre as técnicas escolhidas**, conforme o enunciado da disciplina.

### Instrumento I03 — INVESTIGACAO CONTEXTUAL??????

**Autor(a):** Nuno Martins Guilhermino da Silva
**Técnica:** questionário / entrevista semiestruturada / observação / grupo focal / outra autorizada  
**Objetivo:** {{...}}  
**Público:** {{...}}

#### Procedimento padronizado de aplicação

1. {{preparação}}
2. {{apresentação/consentimento}}
3. {{aplicação}}
4. {{encerramento}}
5. {{armazenamento/anonimização}}

#### Instrumento

Cole aqui o questionário/roteiro completo ou forneça link **mais uma cópia textual no repositório**.

#### Como os dados serão analisados

{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}}


## Síntese

Explique quais lacunas de conhecimento sobre usuários o conjunto de técnicas pretende reduzir. Indique explicitamente quais hipóteses da Entrega 1 deverão ficar **sustentadas, refutadas ou refinadas** após a análise dos dados. Quando os dados forem coletados/analisados, atualize o histórico em `RASTREABILIDADE.md`.

<!-- CORRIGIR EVIDENCIA DA RASTREABILIDADE DE HIPOTESES, AS Q TEM ESTAO ERRADAS -->
## Checklist

- [ ] Hipóteses/lacunas prioritárias da Entrega 1 foram revisitadas.
- [ ] Se o escopo de IHC foi derivado de TCC técnico, a coleta investiga a plausibilidade do usuário, tarefa e contexto adotados.
- [ ] Perguntas não pressupõem que dashboard, CRUD, filtros ou relatórios sejam necessários; investigam a necessidade.
- [ ] Cada dado a coletar responde uma dúvida concreta do projeto ou justifica outra necessidade de informação.
- [ ] Parte A identifica dados e perfis de coleta de forma específica.
- [ ] Aspectos éticos são contextualizados para o projeto.
- [ ] Há uma técnica completa por integrante e técnicas distintas.
- [ ] Questionário está incluído entre as técnicas.
- [ ] Cada instrumento possui objetivo, público, procedimento e conteúdo integral.
- [ ] Perguntas evitam indução e coletam apenas dados necessários.
- [ ] Está claro como os dados serão analisados e usados no design.
