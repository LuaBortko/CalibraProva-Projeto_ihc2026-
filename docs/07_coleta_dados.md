# Entrega 7 — Coleta de dados, necessidades e aspectos éticos

**Data:** 15/10/2026
**Status:**  🟩 Concluída  <br>

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
| H10 | Após identificar resultados abaixo do esperado em uma avaliação, o docente pode querer analisar suas características estruturais para investigar possíveis fatores associados ao desempenho dos alunos. | Nenhuma | A decisão de contemplar o uso do sistema após a aplicação de uma avaliação, para apoiar a análise de seus resultados e a revisão de avaliações futuras, depende da resposta da hipótese H10. | Média |
| H11 | Ao preparar avaliações diferentes para turmas distintas, o docente pode querer comparar suas características estruturais para identificar diferenças que mereçam revisão antes da aplicação. | Nenhuma | A decisão de contemplar a comparação entre versões de uma avaliação como situação de uso do sistema depende da resposta da hipótese H11. | Média |

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
| Motivação para realização do trabalho | H02, H03, H10 e H11 | Avalia qual o principal resultado esperado, se o usuário busca aperfeiçoamento por prazer/propósito ou se apenas cumpre obrigações da carga horária sob pressão de tempo | Define a hierarquia visual do dashboard inicial e o tom das notificações: se o professor busca propósito/aperfeiçoamento (H03), o design deve destacar relatórios de ganho pedagógico e métricas sobre a evolução das provas; se o foco for produtividade/pressão de tempo (H02), a interface deve priorizar a velocidade do fluxo, com relatórios sintéticos em 1 clique e resumos exportáveis para a coordenação. |
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
| Faixa etária dos professores | H04 | Caracterizar o público participante e verificar possíveis diferenças de experiência e familiaridade com tecnologias. | Linguagem, legibilidade e necessidade de orientações, caso os dados indiquem diferenças relevantes. |
| Região de residência e município de atuação profissional | H04 | Compreender a distribuição geográfica dos participantes, considerando o foco do projeto no contexto do ENEM em São Paulo. | Contextualização dos exemplos e adequação do sistema ao público estudado. |
| Área de atuação e disciplinas lecionadas | H03 | Identificar diferenças nas necessidades de professores de diferentes áreas. | Organização das informações e exemplos apresentados pelo sistema. |
| Experiência como professor e frequência com que elabora ou revisa provas | H02, H03 e H05 | Entender a experiência docente e a frequência de contato com a tarefa. | Nível de detalhamento das informações e necessidade de orientações. |
| Ferramentas utilizadas para elaborar, revisar e analisar provas | H06 e H07 | Identificar ferramentas já utilizadas e como elas participam do processo de trabalho. | Compatibilidade com o fluxo atual e formatos de entrada das provas. |
| Etapas realizadas atualmente para revisar uma prova | H05, H08, H10 e H11 | Compreender como o professor realiza a tarefa e quais dificuldades enfrenta. | Organização das etapas e priorização de funcionalidades. |
| Ferramentas digitais utilizadas no cotidiano profissional | H04, H05 e H07 | Identificar a familiaridade com ferramentas digitais e interfaces comuns. | Navegação, organização dos controles e necessidade de instruções. |
| Experiência com sistemas de análise de provas ou desempenho | H02, H03, H07 e H08 | Verificar se o professor já utilizou ferramentas semelhantes e quais recursos conhece. | Necessidade de apresentar conceitos e orientar o uso. |
| Conhecimento sobre métricas e características estruturais de provas | H06 e H08 | Identificar quais conceitos o professor já compreende e quais podem exigir explicação. | Terminologia, explicações das métricas e detalhamento dos resultados. |
| Familiaridade com as tarefas que o sistema pretende apoiar | H04, H05 e H07 | Entender se o professor já analisa características como posição das questões, presença de imagens e distribuição dos itens. | Apresentação das métricas e informações complementares. |
| Dificuldades e necessidades ao interpretar resultados de provas | H02, H03, H08, H10 e H11 | Identificar obstáculos e informações que auxiliariam na análise e na tomada de decisões. | Priorização das métricas, explicações e recursos de consulta. |
| Expectativas em relação ao sistema e benefícios esperados | H02, H03, H08, H10 e H11 | Entender quais problemas os professores esperam resolver com a ferramenta. | Priorização das funcionalidades e informações exibidas. |
| Preferências quanto à apresentação das informações e orientações de uso | H04, H06 e H07 | Investigar quais formatos de explicação e consulta são considerados mais úteis. | Formas de visualização, ajuda contextual e apresentação dos resultados. |
| Disponibilidade e disposição para aprender a utilizar uma nova ferramenta | H04 | Compreender quanto esforço de aprendizagem é aceitável no contexto de trabalho. | Complexidade inicial, necessidade de tutorial e quantidade de orientações. |
| Equipamentos e condições de acesso disponíveis | H04 | Verificar limitações de dispositivo, conexão e ambiente de utilização. | Compatibilidade, legibilidade e comportamento da interface. |

<!-- Coletar dados sobre usuario, dados sobre sua relacao com tecnologi, seu conehcimento do produto, seu conhecimento das tarefas q vai realiza e suas motivacao e valores
proprio usuario(dados demograficos, educação, idiomas fluentes); relação tecnologia(experiencia com computadores, experiencia com ferramentas semelhantes, tecnologia disponivel); conhecimento do dominio do produto(oque e quanto o usuario conhece sobre o assunto em questão); seu conhecimento das tarefas que deverá realizar do cargo; suas motivações e valores(preferencias de produto, usuario assume riscos e explora novas formas de fazer o mesmo trabalho ou evita novas experiencias, preferindo caminhos ja percorridos e testados, usuario prefere um estilo de aprendizado visual, auditivo ou outro, quanto tempo investiria para aprender a utilizar o produto em questão); o usuario utiliza algum tipo de ferramenta para elaborar/revisar suas avaliações?; Ferramentas que o usuario utiliza no dia a dia para auxiliar no trabalho; Conhece algum sistema com função parecida com a do nosso; 
-->

#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| Professores | Docente que elabora/revisa provas | Representa as personas primárias P01 e P03 |
| Aluno | Estudante que realiza avaliações escolares ou simulados no formato ENEM. | Representa a persona secundária P02, que é afetada indiretamente pelo sistema |

<!-- quem utilizara o sistema, quem é afetado
Docente que elabora ou revisa provas e participa da definição de suas características estruturais.
Docente que aplica avaliações e utiliza seus resultados para acompanhar a aprendizagem e orientar o planejamento das aulas.
-->
#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.

- **Voluntariedade e Autonomia:** A participação de todos os professores é estritamente voluntária. Os participantes têm total liberdade para recusar ou interromper a participação a qualquer momento do estudo, sem necessidade de justificativa e sem qualquer penalidade acadêmica ou profissional.

- **Consentimento:** Antes do início da coleta, os professores recebem informações claras sobre os objetivos do projeto, o caráter acadêmico da pesquisa e como suas respostas serão utilizadas. A concordância é formalizada via aceite do Termo de Consentimento Livre e Esclarecido (TCLE)

- **Minimização:** O sistema extrai apenas os parâmetros métricos necessários para os gráficos da interface, sem armazenar dados além do escopo técnico da pesquisa

- **Privacidade:** O ambiente de aplicação do teste e as respostas fornecidas ficam restritos exclusivamente à equipe, garantindo que o estilo de elaboração do docente ou possíveis dificuldades de uso não sejam expostos a terceiros ou a colegas de trabalho.

- **Riscos:** O risco direto ao participante é baixo. Os riscos potenciais estão relacionados a eventual constrangimento em relação ao seu nível de letramento digital ou à avaliação do estilo de elaboração de suas provas. Para mitigar esses riscos, garante-se um ambiente neutro, ressaltando que o foco da investigação é o aprimoramento da interface do sistema e não a avaliação do desempenho pedagógico do professor.

- **Gravação:** Em entrevistas ou testes de usabilidade presenciais/remotos, o registro em áudio ou tela só é realizado mediante autorização prévia e explícita no TCLE. Caso o participante não autorize a gravação, a atividade é conduzida apenas com anotações manuais

- **Anonimização:** Substituição do nome real do docente e da escola por códigos genéricos e pseudônimos nos documentos públicos e acadêmicos. Trechos de depoimentos que mencionem locais específicos ou nomes de colegas são modificados para manter o sentido sem expor os envolvidos

- **Armazenamento:** Os arquivos e respostas coletadas ficam armazenados em repositório em nuvem de acesso restrito exclusivamente aos integrantes da equipe de pesquisa.

- **Descarte:** Todos os dados brutos identificáveis serão descartados com segurança após o encerramento do semestre letivo e avaliação da disciplina.


> **Responsabilidade:** solução individual por integrante.

### A03 — Nuno Martins Guilhermino da Silva

**Autor(a):** Nuno Martins Guilhermino da Silva - 22.126.099-5

#### Que dados coletar?

| Dado/informação | Hipótese/lacuna relacionada | Por que é necessário | Qual decisão de design pode afetar |
|---|---|---|---|
|  Alfabetismo computacional | H04 | É necessário para verificar quanta facilidade o usuário teria em utilizar a aplicação | A simplificação de elementos visuais da aplicação e como poder acolher corretamente o nível de alfabetização digital dos usuários|
|  Tecnologia disponível | H04 | É necessário para verificar o que seria utilizado pelos usuários | A adaptação da solução para poder se conformar com os programas e hardware utilizados pelos usuários, assim ajudando os usuários a se adaptarem melhor e poderem utilizar a solução com maior facilidade.|
|  Experiência com um produto ou ferramentas semelhantes | H07 | Verificar a experiência dos usuários e encontrar pontos populares e impopulares de UX | A adaptação da solução para algo que agrade o docente a partir de sua experiência, assim deixando a plataforma mais fácil dele compreender as informações retornadas e manusear a solução com mais facilidade.|
|  Educação | H06,H08 | Verificar a alfabetização dos usuários e a facilidade dele com informações como gráficos, tabelas, etc.| Esta informação ajuda a encontrar o melhor meio de mostrar as informações da análise da prova para o usuário, assim facilitando a sua interpretação dos resultados e utiliza-los de uma maneira otimizada.|
|  Idiomas e jargões | H06 | Verificar as capacidades linguísticas dos usuários | A adaptação da explicação das métricas que forem apresentadas aos usuários para que facilite a sua compreensão do que foi feito durante a análise da prova.|
| Conhecimento do domínio | H03,H02,H06,H08 | Verificar a familiaridade dos docentes com conceitos relacionados à elaboração e análise de avaliações, identificando possíveis dificuldades na interpretação das métricas apresentadas. | Definir o nível de detalhamento das métricas e a necessidade de explicações adicionais para que os docentes consigam interpretar os resultados e utilizá-los na revisão de suas avaliações.|
| Tarefas | H02,H03 e H05 | Identificar as atividades realizadas pelos docentes durante a elaboração e revisão de avaliações, verificando em quais momentos e com quais objetivos utilizariam a solução.| Definir quais funcionalidades devem ser priorizadas e como organizar o fluxo de interação para apoiar as tarefas realizadas pelos docentes. |
| Objetivo do usuário | H03 | Identificar o que o docente pretende alcançar ao analisar suas provas e como realiza essa análise atualmente. | Priorizar as informações e funcionalidades que mais contribuem para os objetivos dos docentes. |
| Está disposto a ler texto ao utilizar produtos como o que está sendo projetado?  | H06 | Identificar as preferências dos docentes durante a elaboração e revisão de avaliações, além das dificuldades encontradas com as ferramentas utilizadas e com a organização dessas atividades.| Adaptar o fluxo de interação e a organização das funcionalidades para atender às necessidades identificadas, considerando os métodos de trabalho e as dificuldades relatadas pelos docentes.|
| Preferências e descontentamentos  | H05,H07  | Analisar o raciocínio do docente, quais aspectos ele prioriza quando ele formula as provas, como ferramentas e prazos, além de problemas que ele encontrou ao longo de sua experiência. | Adaptar a aplicação para apresentar informações e processos de uma maneira que se alinhe com as preferências e objetivos dos usuários. |
| Idade | H04 | Verificar experiências com tecnologia a partir de suas vivências | Adaptar ou simplificar a aplicação para poder acolher docentes que tenham menor experiência tecnológica |


#### De quem coletar?

| Perfil/stakeholder | Critério de inclusão | Relação com persona/público |
|---|---|---|
| Docente | Principal público-alvo | É o principal tipo de pessoa escolhida para o uso da solução, sendo elaborado através de P01 e P03. |
| Alunos | Usuário secundário | É um grupo que seria afetado pelo uso da plataforma, exemplificado por P02.

#### Aspectos éticos

Analise voluntariedade, consentimento, minimização de dados, privacidade, riscos, gravação, anonimização, armazenamento e descarte. Não responda apenas “sim, por causa da LGPD”: explique **quais dados e riscos existem neste projeto**.
### Aspectos éticos

A participação dos docentes e alunos na pesquisa será voluntária, sendo necessário informar previamente os objetivos do estudo e como as informações coletadas serão utilizadas. Os participantes poderão recusar ou interromper sua participação sem sofrer qualquer penalidade.

O consentimento deverá ser obtido antes da realização das entrevistas e testes de usabilidade, incluindo uma autorização específica caso seja necessário realizar gravações de imagem, voz ou tela. Caso o participante não autorize a gravação, suas respostas poderão ser registradas por meio de anotações, mediante seu consentimento.

Serão coletadas apenas as informações necessárias para compreender as características, necessidades e dificuldades dos usuários, como sua experiência com tecnologias, conhecimento sobre elaboração de avaliações e interação com a plataforma. Não será necessário coletar dados pessoais que não contribuam para os objetivos da pesquisa.

Entre os riscos envolvidos estão o possível constrangimento dos docentes ao demonstrarem dificuldades na utilização da plataforma ou na interpretação das métricas apresentadas, além da exposição indevida de informações pessoais ou de avaliações enviadas ao sistema. Para reduzir esses riscos, será esclarecido que o objetivo dos testes é avaliar a interface e não o conhecimento ou desempenho profissional dos participantes.

As informações coletadas serão utilizadas exclusivamente para fins acadêmicos, com acesso restrito aos integrantes da equipe. Na apresentação dos resultados, os participantes serão identificados por códigos, removendo informações que permitam sua identificação direta, como nomes e instituições de ensino.

Os registros e arquivos coletados serão armazenados em ambiente digital com acesso restrito, sendo mantidos apenas pelo período necessário para a realização e documentação da pesquisa. Após esse período, os dados identificáveis que não precisarem ser preservados serão descartados de maneira segura.+

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

- [Link do questionário](https://forms.gle/iWctSMaRJMGyN9K36 ) 



#### Como os dados serão analisados

<!--{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}} -->

<!--ex investigacsao contextual, entrevista, questionario...simular(quesrtionario), fazer o correto pq plinio vai avaliar --> 

As respostas fechadas serão analisadas por meio da distribuição de frequências e proporções, identificando características dos participantes, como familiaridade tecnológica, frequência de elaboração de avaliações, ferramentas utilizadas e conhecimento sobre métricas. Também serão comparadas respostas de docentes com diferentes níveis de experiência, buscando identificar possíveis diferenças nas dificuldades e necessidades de suporte.

As respostas relacionadas às tarefas profissionais e ao uso de ferramentas contribuirão para investigar H05 e H07. Já as respostas sobre conhecimento e interpretação de métricas ajudarão a avaliar H06 e H08, enquanto a relação entre experiência tecnológica e necessidade de orientação contribuirá para investigar H04.

As respostas abertas serão analisadas por codificação temática, agrupando relatos semelhantes. Por fim, os resultados orientarão decisões de design e permitirão sustentar, refutar ou reformular as hipóteses, considerando que as respostas declaradas, isoladamente, não comprovam o comportamento real dos usuários nem a usabilidade do sistema.

> Cada integrante deve preparar uma técnica/instrumento completo. As técnicas devem ser diferentes entre si e **questionário deve estar entre as técnicas escolhidas**, conforme o enunciado da disciplina.

### Instrumento I02 — Entrevista Semiestruturada

**Autor(a):** Luana Bortko Rodrigues
**Técnica:** entrevista semiestruturada
**Objetivo:** Investigar o processo de trabalho de docentes na elaboração e revisão de avaliações por meio de perguntas fechadas (estruturadas) para caracterizar de forma objetiva o perfil do professor, seu tempo de carreira, nível de ensino e grau de familiaridade com tecnologias; e perguntas abertas (não estruturadas) de caráter exploratório para investigar profundamente suas dores, hábitos reais, estratégias de revisão e modelos mentais ao interpretar métricas estruturais de exames (como contagem de palavras e presença de imagens). O intuito é reunir dados de perfil e insights qualitativos detalhados para fundamentar as decisões de design da interface.
**Público:** Docentes que elaboram ou revisam avaliações e simulados.

<!-- etica: pq ela foi selecionada, motivo da entrevista, oq eu to desenvolvendo, oque ela ajuda ao participar dessa entrevista 
Roteiro da entrevista: conjunto de perguntas
estruturadas(perguntas fechadas): perguntas que não tem pra onde escapar
não estruturada(perguntas abertas): A gente não tem controle da resposta
Totalmente estruturada se torna um questionario falado
-->

#### Procedimento padronizado de aplicação

1. **Preparação:** Elaboração, estruturação e alinhamento prévio do roteiro de perguntas (balanceando os blocos de perguntas fechadas e abertas), agendamento prévio da sessão (presencial ou remota), teste funcional dos equipamentos de captação de áudio/gravação de tela e revisão do material de apoio.

2. **Apresentação/Consentimento:** Introdução do participante ao estudo, apresentando o que está sendo desenvolvido e o motivo da entrevista. Explica-se por que o docente foi selecionado (por sua experiência prática na elaboração e revisão de avaliações) e como sua participação contribui para o projeto (ajudando a alinhar a interface do sistema às necessidades reais dos professores). Em seguida, realiza-se a leitura e aceite do Termo de Consentimento Livre e Esclarecido (TCLE), reforçando o caráter voluntário, a garantia de anonimato, a autorização prévia para gravação de áudio e assegurando que o objeto sob avaliação é a interface do software.

3. **Aplicação:** Condução da entrevista alternando os blocos estruturados e não estruturados conforme o roteiro elaborado, mantendo uma postura neutra, sem induzir respostas e permitindo que o participante discorra livremente sobre suas experiências.

4. **Encerramento:** Agradecimento pela colaboração, abertura do espaço para considerações finais e encerramento da gravação.

5. **Armazenamento/Anonimização:** As gravações de áudio e as respectivas transcrições são salvas em um repositório em nuvem com controle de acesso restrito exclusivamente à equipe de pesquisa. Todos os identificadores diretos e indiretos (como nomes de participantes, instituições de ensino, turmas e terceiros) são removidos ou substituídos por códigos genéricos nas transcrições e relatórios, garantindo a sigilosidade e o anonimato de todas as informações coletadas.

#### Instrumento (Roteiro)

<!-- Cole aqui o questionário/roteiro completo ou forneça link **mais uma cópia textual no repositório**. -->
##### Bloco 1: Perfil e Contexto (perguntas fechadas e abertas)

1. Há quanto tempo você atua na docência?

2. Em qual(is) nível(is) de ensino você leciona atualmente? (Ensino Fundamental/Ensino Médio /Ensino Superior/Pós-graduação)

3. Com qual frequência você elabora ou revisa provas formais? (Semanalmente/Mensalmente/Bimestralmente/Semestralmente/Raramente)

4. Você utiliza algum software no computador para criar ou formatar suas avaliações? (Sim (Quais? Ex.: Word, Google Docs, Canva, geradores de questões)/Não (Elaboro de outra forma / manuscrito))

5. Já utilizou alguma ferramenta que mostre métricas ou estatísticas automáticas sobre o conteúdo das suas provas?(Sim/Não)

6. Quais equipamentos você costuma utilizar para elaborar e revisar suas avaliações? (ex.: computador pessoal/notebook, computador da escola, tablet) E qual é o tipo de tela e ambiente em que você costuma trabalhar?

7. Você encontra limitações de conexão ou de equipamentos na sua rotina de trabalho?"

##### Bloco 2: Processo de Trabalho e Dificuldades (perguntas abertas)

1. Pode me descrever, passo a passo, como você costuma elaborar ou revisar uma prova, desde o momento em que decide criar as questões até ela estar pronta para aplicação?

2. Quais são os maiores desafios ou a parte mais trabalhosa durante esse processo de elaboração/revisão?

3. Ao elaborar uma avaliação, você costuma atentar para características como o tamanho do texto de apoio, quantidade de imagens ou distribuição das alternativas? Como você avalia esses elementos hoje?

##### Bloco 3: Interpretação de Métricas e Relevância do Sistema (perguntas abertas)

1. Ao colocar uma prova no sistema e receber um diagnóstico indicando o número total de palavras, a quantidade de imagens e o tamanho médio do texto por questão, de que forma essas informações ajudariam você na revisão da prova?

2. Se o sistema destacar que uma questão específica possui um texto muito mais longo do que as demais ou que a prova tem poucas imagens de apoio, isso levaria você a alterar a questão ou o formato da prova? Por quê?

3. Ao visualizar essas estatísticas na tela, você prefere ver apenas os números brutos (ex.: '1.200 palavras') ou gostaria de explicações visuais e dicas contextuais mostrando como a extensão do texto pode impactar o tempo de resolução dos alunos?

4. Em qual momento da sua rotina faria mais sentido acessar um painel como esse: enquanto está digitando as questões, logo após finalizar a prova ou após ver os resultados dos alunos?

##### Bloco 4: Usabilidade e Fechamento (perguntas fechadas e abertas)

1. Em uma escala de 1 a 5, quão confortável você se sente ao aprender a utilizar novos softwares ou ferramentas digitais no seu trabalho? (1 = Muito desconfortável; 5 = Muito confortável)

2. Quando precisa analisar informações sobre o seu trabalho, você prefere visualizar dados na forma de gráficos, relatórios em texto descritivo ou alertas visuais simples?

3. Há algum recurso ou informação que você considera fundamental para decidir usar um sistema de análise de provas na sua rotina?

#### Como os dados serão analisados
<!--{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}}-->

Os dados brutos coletados nas sessões de entrevista semiestruturada serão transcritos e analisados por meio de uma abordagem integrada em três etapas complementares:

- **Distribuição de respostas (Análise Descritiva dos Dados Estruturados):** As respostas do Bloco 1 (perfil) e do Bloco 4 (usabilidade/preferencias) serão tabuladas para mapear a distribuição percentual e o perfil dos participantes. Essa distribuição servirá para caracterizar quantitativamente a amostra e identificar se diferentes faixas de experiência docente ou familiaridade tecnológica exigem padrões distintos de interface.

- **Codificação Temática (Análise Qualitativa de Conteúdo):** As transcrições das respostas abertas dos Blocos 2 e 3 serão submetidas à análise de conteúdo e agrupadas em códigos e categorias temáticas recorrentes, tais como: Fluxo e Gargalos de Elaboração(como o professor constrói a prova e onde gasta mais tempo); Modelo Mental de Métricas(como o docente interpreta dados como contagem de palavras, quantidade de imagens e extensão por questão); Demanda por Explicações (preferência por valores numéricos diretos versus orientações contextuais e dicas pedagógicas); Momento do Uso(em qual etapa do trabalho o professor prefere acionar a ferramenta).

- **Agrupamento de Problemas:** As dificuldades, receios e necessidades relatados pelos professores serão organizados e sintetizados em um quadro de problemas de usabilidade e oportunidades de melhoria. Esses achados qualitativos serão convertidos diretamente em requisitos de interface, servindo para definir as prioridades de layout, a organização da navegação e o nível de ajuda contextual do sistema.

### Instrumento I03 — Investigação Contextual

**Autor(a):** Nuno Martins Guilhermino da Silva
**Técnica:** Investigação Contextual 
**Objetivo:** Compreender como os docentes realizam, na prática, o processo de elaboração e revisão de avaliações, identificando as etapas realizadas, ferramentas utilizadas e dificuldades encontradas, para orientar o desenvolvimento da solução. 
**Público:** Docentes que elaboram ou revisam avaliações escolares.

#### Procedimento padronizado de aplicação

1. **preparação**
Elaboração do roteiro de observação e das perguntas que serão realizadas aos docentes, definição das atividades que serão acompanhadas, preparação do ambiente para a demonstração do processo e confirmação da participação dos docentes.
2. **apresentação/consentimento**
Apresentação dos objetivos da investigação e explicação de como será realizada cada etapa do processo. Será solicitado o consentimento dos participantes para a realização da investigação e utilização das informações coletadas, explicando como os dados serão registrados, utilizados e armazenados. Também será informado que a participação é voluntária e que o docente poderá interrompê-la a qualquer momento, além de ser solicitada uma autorização específica caso sejam necessárias gravações de áudio, imagem ou tela.
3. **aplicação**
Para a aplicação, será utilizado o modelo mestre-aprendiz, no qual o docente demonstrará como realiza o processo de elaboração e revisão de suas avaliações, enquanto o pesquisador observa e faz perguntas sobre as atividades realizadas, as ferramentas utilizadas e os critérios considerados durante o processo.
4. **encerramento**
Após a demonstração, serão realizadas perguntas complementares para esclarecer possíveis dúvidas e confirmar com o docente se as interpretações feitas pelo pesquisador representam corretamente o processo observado. Em seguida, o participante terá a oportunidade de acrescentar informações que considere relevantes. Por fim, será agradecida sua participação e a investigação será encerrada.
5. **armazenamento/anonimização**
As respostas, anotações e eventuais gravações realizadas durante a investigação serão armazenadas em ambiente digital com acesso restrito aos integrantes da equipe. Informações que permitam identificar os participantes, como nomes e instituições de ensino, serão substituídas por códigos ou removidas dos registros utilizados na análise. Também serão verificadas possíveis informações pessoais presentes nas avaliações demonstradas pelos docentes, evitando sua exposição. Os dados identificáveis serão mantidos apenas pelo período necessário para a realização e documentação da pesquisa, sendo posteriormente descartados de maneira segura.
#### Instrumento

Cole aqui o questionário/roteiro completo ou forneça link **mais uma cópia textual no repositório**.
Bloco 1 — Contextualização do docente

Objetivo: compreender a experiência e o contexto de trabalho do participante.

Perguntas possíveis:
- Há quanto tempo atua como docente?
- Quais disciplinas leciona?
- Com que frequência elabora ou revisa avaliações?

Bloco 2 — Demonstração do processo

Objetivo: observar como o docente elabora ou revisa uma avaliação e compreender suas decisões.

Solicitação inicial:
Poderia demonstrar como você normalmente realiza a elaboração ou revisão de uma avaliação, utilizando as ferramentas que costuma empregar?

Aspectos a observar:
- Sequência das atividades realizadas.
- Ferramentas e materiais consultados.
- Critérios utilizados para revisar questões.
- Dificuldades, interrupções e retrabalho.

Perguntas possíveis:
- Por que você escolheu realizar essa etapa dessa maneira?
- Como identifica se uma questão precisa ser modificada?
- Quais características considera importantes ao revisar uma questão?
- Existe alguma etapa que considera particularmente trabalhosa?

Bloco 4 — Encerramento e validação

Objetivo: esclarecer dúvidas e confirmar as observações.

Perguntas possíveis:
- Existe alguma parte do processo que não conseguimos acompanhar?
- Entendemos corretamente que você utiliza determinada ferramenta para determinada finalidade?
- Há alguma dificuldade importante que não apareceu durante a demonstração?
#### Como os dados serão analisados

{{ex.: distribuição de respostas, codificação temática, agrupamento de problemas}}
Os dados serão analisados através do agrupamento de problemas e métodos identificados durante a investigação, verificando semelhanças e diferenças nos processos utilizados pelos docentes para elaborar e revisar suas avaliações. Também serão identificadas as ferramentas mais utilizadas, as dificuldades recorrentes e os critérios mais frequentemente considerados durante a realização das atividades, buscando encontrar necessidades em comum que possam orientar o desenvolvimento da solução.
## Síntese

Explique quais lacunas de conhecimento sobre usuários o conjunto de técnicas pretende reduzir. Indique explicitamente quais hipóteses da Entrega 1 deverão ficar **sustentadas, refutadas ou refinadas** após a análise dos dados. Quando os dados forem coletados/analisados, atualize o histórico em `RASTREABILIDADE.md`.

O conjunto de técnicas de coleta de dados pretende reduzir as lacunas de conhecimento sobre o perfil dos docentes, sua familiaridade com tecnologias, a linguagem utilizada, conhecimento do domínio e os métodos utilizados na elaboração e revisão de avaliações e suas necessidades em relação à interpretação das métricas apresentadas pela solução.

As hipóteses H02, H05, H06, H07 e H08 poderão ser sustentadas, refutadas ou refinadas a partir dos dados coletados pelos instrumentos, permitindo verificar as necessidades dos docentes, suas experiências com ferramentas semelhantes e a utilidade das informações apresentadas pela solução.

A hipótese H03 poderá ser refinada através das respostas dos docentes, permitindo observar como as avaliações e seus resultados influenciam o planejamento e a elaboração das aulas. A hipótese H04 também poderá ser refinada através da identificação dos conhecimentos tecnológicos dos docentes e das dificuldades encontradas na utilização de ferramentas digitais, permitindo compreender melhor o nível de familiaridade tecnológica necessário para utilizar a solução.

A hipótese H09 poderá ser refinada a partir da identificação dos possíveis impactos indiretos da utilização da solução sobre os alunos. Já a H01 depende principalmente das análises realizadas no TCC, não podendo ser diretamente sustentada ou refutada pelos instrumentos de coleta de dados desta entrega.
<!-- CORRIGIR EVIDENCIA DA RASTREABILIDADE DE HIPOTESES, AS Q TEM ESTAO ERRADAS -->
## Checklist

- [X] Hipóteses/lacunas prioritárias da Entrega 1 foram revisitadas.
- [ ] Se o escopo de IHC foi derivado de TCC técnico, a coleta investiga a plausibilidade do usuário, tarefa e contexto adotados.
- [X] Perguntas não pressupõem que dashboard, CRUD, filtros ou relatórios sejam necessários; investigam a necessidade.
- [X] Cada dado a coletar responde uma dúvida concreta do projeto ou justifica outra necessidade de informação.
- [X] Parte A identifica dados e perfis de coleta de forma específica.
- [X] Aspectos éticos são contextualizados para o projeto.
- [X] Há uma técnica completa por integrante e técnicas distintas.
- [X] Questionário está incluído entre as técnicas.
- [X] Cada instrumento possui objetivo, público, procedimento e conteúdo integral.
- [X] Perguntas evitam indução e coletam apenas dados necessários.
- [X] Está claro como os dados serão analisados e usados no design.
