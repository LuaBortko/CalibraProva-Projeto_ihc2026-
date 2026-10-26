# Entrega 4 — Cenários de análise/problema

**Data:** 09/09/2026<br> 
**Status:** 🟦 revisada após feedback<br>
**Responsabilidade:** 1 solução completa por integrante

## Objetivo da atividade

Descrever situações atuais em que o usuário tenta alcançar um objetivo e encontra dificuldades. O cenário de análise/problema deve tornar visível **o contexto, os atores, as ações e as rupturas**, sem antecipar a interface que será projetada.

> **Regra central:** cenário de problema é a “história do problema”. Se o texto já diz “o sistema mostra”, “o aplicativo resolve” ou descreve botões/telas futuras, provavelmente está misturando problema com solução.

Sempre que possível, o cenário deve aprofundar uma **situação concreta já registrada na Entrega 1**.

### Quando o TCC não possuía interface

O cenário continua sendo uma história de **problema/atividade humana**, não uma história do futuro sistema. Descreva como o profissional realiza hoje uma atividade semelhante ou como lida atualmente com dados, resultados, configurações, logs, decisões e limitações que o tema do TCC pretende apoiar.

Exemplo: em vez de “o DBA abre o novo dashboard e executa o algoritmo”, descreva “o DBA precisa investigar uma consulta lenta, reúne informações em ferramentas distintas, compara planos manualmente e tem dificuldade para estimar o impacto de uma mudança”.

A interface da disciplina aparecerá somente depois, nos cenários de interação.

Se o integrante escolher um novo problema/situação, explique por que ele passou a ser relevante e indique a evidência que motivou sua inclusão.

## Cenário C01 — Professor percebe um desempenho inesperadamente baixo

**Autor(a):** Luana Bortko Rodrigues **RA:** 24.123.006-9<br>
**Persona(s) relacionada(s):** P01<br>  
**Necessidade relacionada:** Necessita manter seus conhecimentos atualizados, especialmente em relação a novas tecnologias, e contar com recursos que auxiliem no planejamento de aulas interessantes e relevantes. Também valoriza um bom relacionamento com os alunos e busca formas de contribuir para seu desenvolvimento por meio da educação.<br>  
**Situação concreta da Entrega 1 relacionada:** Não contemplada diretamente a entrega 1. O cenário foi acrescentado nesta etapa para ampliar as situações analisadas, considerando a hipótese de que, após observar um desempenho abaixo do esperado, a docente busque analisar características da prova para orientar melhorias em avaliações futuras.<br>  
**Hipóteses ainda presentes:** H01, H02, H03, H04 

### 1. Cenário inicial

Maria da Costa Silva, professora de Literatura do ensino médio de uma escola pública do estado de São Paulo, está corrigindo uma avaliação aplicada recentemente a uma de suas turmas. Durante as aulas e atividades realizadas ao longo do período, Maria percebeu que a maioria dos estudantes demonstrava compreender os conteúdos trabalhados e conseguia participar das discussões e dos exercícios propostos. No entanto, ao corrigir a avaliação, ela percebe que o desempenho da turma foi consideravelmente inferior ao esperado.

O resultado faz com que Maria questione se a dificuldade apresentada pelos estudantes está realmente relacionada à falta de domínio dos conteúdos ou se a forma como a avaliação foi elaborada pode ter influenciado o desempenho. Ao revisar a prova, ela percebe que algumas questões possuem enunciados extensos, diferentes quantidades de texto e elementos visuais, além de estarem distribuídas em posições distintas. Maria considera que essas características podem ter dificultado a interpretação ou a resolução de algumas questões, mas não consegue determinar se elas realmente tiveram relação com o resultado obtido pela turma.

Para tentar compreender melhor a situação, Maria conversa com outros professores da escola e conhecidos da área, buscando saber se já passaram por situações semelhantes e como costumam lidar com resultados inesperados em avaliações. Embora essas conversas possam ajudar a levantar possíveis explicações, Maria percebe que as opiniões são baseadas principalmente em experiências individuais e não permitem verificar de forma objetiva se determinadas características da prova estão relacionadas ao desempenho dos estudantes. Assim, ela busca uma forma de analisar a avaliação aplicada que possa fornecer informações mais concretas e ajudá-la a identificar possíveis melhorias para suas próximas provas.

### 2. Questões de refinamento

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---|
| Q1 | [objetivo] Quais as precondições para esse objetivo | Para ajudar no refinamento do cenário inicial  | hipotese |
| Q2 | [Atores] De que informações ou conhecimento os atores precisam para realizar esse objetivo | Para ajudar no refinamento do cenário inicial | hipotese|
| Q3 | [Ações] Quais informações são (ou deveriam ser) criadas, consumidas, manipuladas ou destruídas pelo alcance do objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q4 | [Ambiente ou contexto] Em que situações o cenário ocorre (quando, onde e por quê)? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q5 | [Ambiente ou contexto] Que dispositivos e outros recursos (inclusive tempo) estão disponíveis para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q6 | [Avaliação] Como Maria interpretaria os resultados da análise para decidir se determinadas características da prova merecem ser revisadas? | Identificar os critérios que ela utilizaria para julgar os resultados e decidir se eles são úteis para seu objetivo, sem presumir que as métricas comprovam a causa do baixo desempenho. | hipotese |
| Q7 | [evento] Que acontecimentos externos ou imprevistos durante a preparação da próxima avaliação poderiam alterar, interromper ou exigir mudanças na análise que Maria pretendia realizar? | Identificar acontecimentos que não fazem parte das ações planejadas por Maria, mas que podem modificar as condições ou o andamento da atividade. | hipotese |
| Q8 | [planejamento] Como Maria decidiria por onde começar a análise, quais características priorizar e quais resultados consultar em seguida para orientar possíveis revisões na prova? | Compreender o raciocínio usado para estabelecer uma estratégia, definir prioridades e decidir os próximos passos, e não apenas enumerar ações. | hipotese |

### 3. Cenário refinado

Maria da Costa Silva é professora de Literatura do ensino médio em uma escola pública do estado de São Paulo. Após corrigir uma avaliação aplicada recentemente a uma de suas turmas, percebe que o desempenho dos estudantes foi consideravelmente inferior ao esperado. Durante as aulas e atividades realizadas ao longo do período, a maioria dos alunos demonstrava compreender os conteúdos trabalhados e conseguia participar das discussões e dos exercícios propostos.

Diante desse resultado, Maria começa a questionar se a dificuldade apresentada pelos estudantes está relacionada à falta de domínio dos conteúdos ou se características da própria avaliação podem ter influenciado a resolução das questões. Ao revisar a prova, observa que algumas questões possuem enunciados extensos, diferentes quantidades de texto, elementos visuais e posições distintas. Ela considera que esses aspectos podem ter dificultado a interpretação ou a resolução de determinadas questões, mas não dispõe de informações suficientes para determinar se existe alguma relação entre essas características e o desempenho da turma.

Para compreender melhor a situação, Maria conversa com outros professores da escola e conhecidos da área, buscando conhecer suas experiências com resultados inesperados em avaliações. Embora essas conversas ajudem a levantar possíveis explicações, ela percebe que as opiniões se baseiam principalmente em experiências individuais e não permitem analisar de maneira sistemática as características da prova. Por isso, decide procurar uma forma mais objetiva de examinar a avaliação e obter informações que possam orientar a revisão de suas próximas provas.

[Q1] Para iniciar essa investigação, Maria precisa ter acesso à versão digital da avaliação e às informações necessárias para realizar a análise. Ela também precisa compreender quais condições devem ser atendidas para que consiga utilizar uma ferramenta de análise e obter resultados referentes à prova.

[Q2] Maria precisa compreender quais conhecimentos e informações são necessários para utilizar a ferramenta e interpretar os resultados apresentados. Embora tenha experiência na elaboração e correção de avaliações, ela pode precisar de explicações sobre o significado das métricas e sobre o que é possível concluir a partir delas.

[Q3] Para investigar a situação, Maria pretende examinar características estruturais da avaliação, como a extensão dos enunciados, a presença de elementos visuais e a organização das questões. Ela também precisa obter informações que a ajudem a relacionar essas características às observações que fez durante a correção, sem presumir que elas sejam necessariamente responsáveis pelo desempenho dos estudantes.

[Q4] Essa investigação ocorre após a correção da avaliação, durante o período em que Maria planeja as próximas atividades e avaliações. Ela pretende realizar a análise em seu ambiente de trabalho, considerando as condições em que costuma preparar materiais e organizar suas tarefas docentes.

[Q5] Maria dispõe de um computador ou notebook na escola e de uma cópia digital da avaliação em PDF. Entretanto, sua rotina de trabalho limita o tempo disponível para atividades adicionais, pois ela também precisa preparar aulas, corrigir outras atividades e planejar novas avaliações.

[Q6] Para avaliar se a análise foi útil, Maria precisa interpretar os resultados apresentados e julgar se eles oferecem informações relevantes para revisar a prova. Ela deverá considerar o significado e as limitações das métricas, verificando se os resultados ajudam a identificar características que mereçam uma investigação mais cuidadosa, sem tratar possíveis relações como comprovação de causalidade.

[Q7] Durante a análise, acontecimentos imprevistos, como a identificação de um problema no arquivo ou a ausência de informações necessárias para continuar o processamento, podem interromper o procedimento ou exigir mudanças no que Maria havia planejado. Além disso, a proximidade do planejamento das próximas avaliações pode tornar necessário reorganizar suas prioridades e o tempo dedicado à investigação.

[Q8] Ao realizar a análise, Maria precisa decidir por onde começar, quais características da prova priorizar e quais resultados consultar em seguida. Ela pretende direcionar seus esforços aos aspectos que considera mais relevantes para compreender as dificuldades observadas durante a correção e, a partir das informações obtidas, decidir quais pontos da avaliação merecem ser revistos.

Maria considera que terá alcançado seu objetivo quando conseguir compreender os resultados da análise, identificar características da prova que mereçam uma revisão mais cuidadosa e utilizar essas informações para tomar decisões mais fundamentadas na elaboração de avaliações futuras. Dessa forma, espera aprimorar suas práticas avaliativas e refletir sobre como representar de maneira mais adequada o conhecimento dos estudantes.

### 4. Elementos extraídos

| Elemento | Evidência no cenário |
|---|---|
| Ator(es) | Maria da Costa Silva, professora de Literatura do ensino médio de uma escola pública do estado de São Paulo. |
| Objetivo(s) | Maria busca compreender o que pode estar contribuindo para o desempenho abaixo do esperado dos estudantes, de modo a realizar avaliações que representem melhor seus conhecimentos. A partir dessa compreensão, pretende aperfeiçoar suas próximas avaliações e utilizar seus resultados para orientar melhor suas aulas. |
| Contexto | Após corrigir uma avaliação, Maria percebe que o desempenho da turma foi inferior ao esperado, apesar de os estudantes demonstrarem compreensão dos conteúdos durante as aulas e atividades. A situação ocorre durante seu período de planejamento na escola, enquanto analisa os resultados e pensa em como melhorar suas próximas avaliações. |
| Recursos/informações | A avaliação aplicada, os resultados observados nos estudantes, as características presentes nas questões da prova, a experiência e opinião de outros professores, computador ou notebook disponível no ambiente escolar e o tempo limitado de Maria devido à sua rotina de trabalho. |
| Ações | Corrigir a avaliação; revisar as questões e suas características; questionar possíveis motivos para o baixo desempenho; conversar com outros professores e conhecidos da área; buscar formas de compreender melhor os resultados; refletir sobre a elaboração de próximas avaliações. |
| Problemas/rupturas | O desempenho dos estudantes foi inferior ao esperado; Maria não consegue determinar se o resultado está relacionado ao domínio dos conteúdos ou à forma como a avaliação foi elaborada |
| Consequências | Maria permanece com dúvidas sobre o que contribuiu para o desempenho da turma e sobre a adequação da avaliação utilizada. Isso dificulta a identificação de possíveis melhorias nas avaliações e pode limitar sua capacidade de utilizar os resultados das provas para orientar melhor suas próximas aulas. |

### 5. Implicações para as próximas entregas

Investigar se características do formato das avaliações apresentam relação com o desempenho dos estudantes, verificando se características como posição das questões, extensão dos enunciados, presença de elementos visuais, disposição dos distratores, formalismo impactam no desempenho do aluno.

## Cenário C02 — Professor quer verificar uma prova antes de aplicá-la

**Autor(a):** Beatriz Manaia Lourenço Berto **RA:** 22.125.060-8<br>
**Persona(s) relacionada(s):** P02<br>
**Necessidade relacionada:** Necessita manter-se constantemente atualizado sobre os avanços tecnológicos, tanto para acompanhar novas áreas quanto para aprimorar conhecimentos já adquiridos. Também busca receber feedbacks frequentes de alunos e outros docentes, utilizando essas percepções para aperfeiçoar continuamente suas aulas e práticas de ensino. Além disso, busca formas mais eficientes e precisas de avaliar e mensurar o nível de conhecimento e o desenvolvimento dos alunos, identificando suas dificuldades e oportunidades de melhoria. 

<br> <!--persona e qqr necessidade q user orecisa em r outra entrega tb-->

**Situação concreta da Entrega 1 relacionada:** 4.1 e 4.5 <br> 
**Hipóteses ainda presentes:** H01, H02, H03, H04 

### 1. Cenário inicial

Maria da Costa Silva é professora de Literatura do ensino médio em uma escola pública do estado de São Paulo. Cerca de duas semanas antes da aplicação das avaliações, começa a elaborar uma prova para uma de suas turmas. Para isso, utiliza como referência os conteúdos trabalhados em aula, questões de provas anteriores, materiais didáticos, suas próprias anotações e as principais dúvidas apresentadas pelos alunos ao longo do período. A partir desses materiais, busca construir questões alinhadas aos conteúdos e objetivos de aprendizagem trabalhados em sala.

Em um ambiente tranquilo e com acesso à internet, Maria prepara uma primeira versão da avaliação em seu computador. Após finalizar as questões, inicia um processo de revisão cuidadoso. Relê os enunciados, verifica se estão claros e objetivos, se apresentam ambiguidades, se as alternativas são coerentes e se as questões realmente avaliam os conteúdos que deseja verificar. Também observa características como a extensão dos textos, a quantidade de informações apresentadas e o nível de interpretação exigido, buscando evitar que aspectos relacionados à estrutura das questões interfiram indevidamente no desempenho dos alunos.

Depois de realizar algumas alterações, Maria pede auxílio a outros professores para que revisem a prova e compartilhem suas opiniões sobre as questões. Esse processo permite obter diferentes perspectivas e identificar possíveis problemas que não haviam sido percebidos durante sua própria revisão.

Entretanto, mesmo após essas etapas, a análise da avaliação continua baseada principalmente na experiência e na percepção dos professores. Maria não possui uma forma objetiva e baseada em dados de verificar se determinadas características estruturais das questões, como a extensão dos enunciados, a quantidade de informações ou o nível de interpretação exigido, podem estar associadas ao desempenho dos estudantes. Dessa forma, embora consiga avaliar as questões sob diferentes perspectivas, permanece sem evidências que a ajudem a identificar quais características estruturais da prova merecem atenção antes de sua aplicação.

### 2. Questões de refinamento 

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---| 
| Q1 | [Planejamento] Quais os detalhes sobre a sequência de ações que compõe uma atividade? | Para ajudar no refinamento do cenário inicial | hipotese |     
| Q2 | [Objetivos] Quais as precondicoes para esse objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q3 | [Atores] De que informações ou conhecimentos os atores precisam para realizar esse objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q4 | [Ambiente ou contexto] Quais são as técnologias utilizadas no ambiente de trabalho? Como os usuários as utilizam? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q5 | [Atores] Quais características do(s) ator(es) lhes auxiliam ou atrapalham em alcançar o objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q6 | [Ações] De que informações ou conhecimento os atores precisam para realizar essa ação? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q7 | [Avaliação] Como os atores conseguem saber se o objetivo foi concluído e alcançado com sucesso? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q8 | [Evento] Que acontecimentos inesperados durante a preparação da avaliação poderiam levar Maria a alterar as questões ou modificar o planejamento da revisão? | Identificar acontecimentos que possam modificar o andamento da atividade ou exigir mudanças no que havia sido planejado. | hipotese |

### 3. Cenário refinado

<!-- tirei q1 q3 e q6 -->
<!--Reescreva o cenário incorporando as respostas. Marque o conteúdo novo de forma consistente (por exemplo, `**[NOVO: ...]**`).-->

Maria da Costa Silva é professora de Literatura do ensino médio em uma escola pública do estado de São Paulo e, cerca de duas semanas antes da aplicação das avaliações, começa a elaborar uma prova para uma de suas turmas. Para isso, utiliza como referência os conteúdos trabalhados em aula, questões de provas anteriores, suas próprias anotações, materiais didáticos e as principais dúvidas apresentadas pelos alunos ao longo do período. A partir desses materiais, busca construir questões alinhadas aos conteúdos e objetivos de aprendizagem trabalhados em sala.

[Q2] Para iniciar a elaboração e a revisão da avaliação, Maria precisa ter definido os conteúdos que pretende avaliar, dispor dos materiais de referência necessários e ter acesso aos recursos que utiliza para preparar suas provas. Também precisa conhecer os objetivos de aprendizagem da turma para que possa verificar se as questões estão alinhadas ao que foi trabalhado em aula.

[Q4] Maria prepara e revisa suas avaliações utilizando os recursos disponíveis em sua rotina de trabalho. Também pode utilizar plataformas educacionais, para organizar e disponibilizar materiais aos alunos, ferramentas para elaborar questionários e avaliações e ferramentas de inteligência artificial, para auxiliar na elaboração, adaptação ou revisão de questões. A escolha desses recursos depende das necessidades da atividade e de sua familiaridade com as ferramentas disponíveis.

[Q1] Durante a preparação da prova, Maria organiza suas atividades em etapas. Inicialmente, define o formato da avaliação, a quantidade de questões e os conteúdos que pretende avaliar. Em seguida, consulta os materiais de referência, elabora ou adapta as questões e organiza uma primeira versão da prova. Depois, revisa os enunciados, verifica a clareza das questões e a coerência das alternativas e realiza alterações quando identifica possíveis problemas. Por fim, pode solicitar que outros professores revisem a avaliação e compartilhem suas opiniões antes da aplicação.

Após preparar uma primeira versão da avaliação, Maria inicia um processo de revisão cuidadoso. Relê os enunciados, verifica se estão claros e objetivos, se apresentam ambiguidades, se as alternativas são coerentes e se as questões realmente avaliam os conteúdos que deseja verificar. Também observa características como a extensão dos textos, a quantidade de informações apresentadas e o nível de interpretação exigido, buscando evitar que aspectos relacionados à estrutura das questões interfiram indevidamente no desempenho dos alunos.

[Q6] Para realizar essa revisão, Maria precisa conhecer os conteúdos da disciplina, os objetivos de aprendizagem trabalhados em aula e os princípios de elaboração de questões, como clareza, correção textual, identificação de ambiguidades e adequação entre a questão e o conteúdo que se pretende avaliar. Caso utilize uma ferramenta de análise estrutural, também precisará compreender quais informações deve fornecer e como interpretar as métricas apresentadas.

[Q3] Maria busca elaborar avaliações adequadas porque deseja obter informações confiáveis sobre o conhecimento dos alunos e utilizar essas informações para aprimorar suas aulas. Para isso, precisa compreender os conteúdos que pretende avaliar, conhecer as dificuldades que observa durante as aulas e saber quais características da elaboração de questões podem merecer atenção. Seu conhecimento da disciplina e de sua turma contribui para que tome decisões coerentes com os objetivos de aprendizagem.

[Q5] Sua experiência como professora e seu conhecimento dos conteúdos podem facilitar a elaboração e a revisão da avaliação. Por outro lado, o tempo limitado para preparar as provas e a dificuldade de identificar objetivamente quais características estruturais podem estar associadas ao desempenho dos estudantes podem dificultar a identificação de aspectos que mereçam uma análise mais aprofundada.

[Q8] Durante a preparação da avaliação, acontecimentos inesperados, como uma alteração no prazo de entrega da prova estabelecido pela escola ou uma mudança nos conteúdos que precisam ser contemplados, podem exigir que Maria reorganize suas prioridades, altere algumas questões ou modifique o planejamento da revisão. Essas situações podem reduzir o tempo disponível para a atividade e exigir adaptações na forma como ela conduz a preparação da avaliação.

[Q7] Maria pode avaliar se a prova está pronta para ser aplicada verificando se as questões estão alinhadas aos conteúdos e objetivos de aprendizagem, se os enunciados são claros e se as alternativas são coerentes. As opiniões dos professores que colaboram na revisão também podem ajudá-la a identificar problemas que não havia percebido. Caso utilize uma ferramenta de análise estrutural, precisará interpretar os resultados e julgar se eles fornecem informações relevantes para revisar a avaliação. Após a aplicação, o desempenho dos alunos e as dúvidas apresentadas poderão contribuir para avaliar suas escolhas, embora esses dados, isoladamente, não comprovem que determinadas características estruturais causaram dificuldades.

Entretanto, mesmo após essas etapas, a análise da avaliação continua baseada principalmente na experiência e na percepção dos professores. Maria não possui uma forma objetiva e baseada em dados de verificar se determinadas características estruturais das questões, como a extensão dos enunciados, a quantidade de informações apresentadas ou o nível de interpretação exigido, podem estar associadas ao desempenho dos estudantes. Dessa forma, embora consiga avaliar as questões sob diferentes perspectivas, permanece sem evidências suficientes para identificar quais características da estrutura da prova merecem atenção antes de sua aplicação.

### 4. Elementos extraídos

| Elemento | Evidência no cenário |
|---|---|
| Ator(es) | Maria da Costa Silva, professora de Literatura do ensino médio em uma escola pública do estado de São Paulo. |
| Objetivo(s) | Elaborar avaliações adequadas aos conteúdos e objetivos de aprendizagem, obtendo resultados que representem de forma confiável o conhecimento dos alunos e permitam aprimorar suas aulas. |
| Contexto | Cerca de duas semanas antes da aplicação das avaliações, durante o período de preparação das provas, em ambiente adequado de trabalho, ([H]como a instituição de ensino, escritório ou casa), com acesso a recursos físicos, digitais e à internet. |
| Recursos/informações | Conteúdos trabalhados em aula, questões de provas anteriores, anotações, materiais didáticos, dúvidas dos alunos, livros e outras fontes de apoio; computador ou notebook e acesso à internet. Também podem ser utilizadas plataformas educacionais e ferramentas de inteligência artificial. |
| Ações | Definir o modelo e a quantidade de questões; selecionar conteúdos e objetivos de aprendizagem; consultar materiais de apoio; elaborar ou adaptar questões; organizar e revisar a avaliação; verificar clareza, ambiguidades, coerência e adequação das questões; analisar características estruturais, como extensão, quantidade de informações e nível de interpretação; realizar alterações; solicitar a revisão de outros professores; analisar os resultados e utilizá-los para aprimorar as aulas. |
| Problemas/rupturas | Maria precisa julgar se as características estruturais das questões podem influenciar o desempenho dos alunos, mas pode ter dificuldade para distinguir problemas relacionados à estrutura da prova daqueles relacionados ao domínio dos conteúdos. A avaliação dessas características depende dos critérios que utiliza, das evidências disponíveis e de sua capacidade de interpretar essas informações. |
| Consequências | Sem evidências suficientes para fundamentar suas decisões, Maria pode deixar de identificar características das questões que mereçam revisão ou atribuir dificuldades dos alunos aos conteúdos quando outros fatores podem estar envolvidos. Isso pode limitar a interpretação dos resultados da avaliação e a identificação dos conteúdos que precisam ser retomados ou aprofundados nas aulas. |

### 5. Implicações para as próximas entregas

<!--Quais tarefas merecem análise? Quais informações precisam ser coletadas? **Não desenhe a solução ainda.** -->

A principal informação que precisa ser coletada e analisada é a relação entre as características estruturais das questões de uma prova e o desempenho dos estudantes. O TCC deverá investigar se aspectos como a quantidade de palavras do enunciado, a presença de imagens, o tempo disponível para resolução, o nível de formalismo da linguagem e as características dos distratores podem influenciar o desempenho dos alunos, considerando especificamente questões do ENEM.

## Cenário C03 — Professor quer comparar duas versões de uma avaliação

**Autor(a):** Nuno Martins Guilhermino da Silva **RA:** 22.126.099-5<br>   
**Persona(s) relacionada(s):** P03<br>
**Necessidade relacionada:** Com o seu trabalho, ela precisa acompanhar o progresso de seus alunos ao longo do andamento de sua tutela, e para isso ela precisa ter certeza que suas provas são apropriadas para o nível de cada turma/pessoa, e com sua rotina corrida, precisa de rápida certificação de que suas avaliações são formuladas com qualidade.<br>  
**Situação concreta da Entrega 1 relacionada:** Não contemplada diretamente na Entrega 1. O cenário foi acrescentado nesta etapa para ampliar as situações analisadas pelo projeto, considerando a hipótese de que um professor precise comparar duas versões de uma mesma avaliação para identificar diferenças estruturais que possam favorecer ou prejudicar uma das turmas.<br>
**Hipóteses ainda presentes:** H01, H02,H03 ou H04 

### 1. Cenário inicial

Vera é uma professora de inglês que preparou duas versões de uma avaliação para aplicar em turmas diferentes, buscando evitar o compartilhamento de respostas entre os alunos. Entretanto, ela deseja garantir que as diferenças entre as avaliações não façam com que uma das turmas seja favorecida ou prejudicada.

Como não possui uma ferramenta específica para comparar a estrutura das duas avaliações, Vera realiza essa análise manualmente. Ela revisa ambas as provas, observando características como o tamanho dos enunciados e das alternativas, a presença de elementos visuais e a organização das questões, buscando identificar diferenças que possam afetar o desempenho dos alunos, além de procurar opiniões externas de outros funcionários e professores da escola onde trabalha quando consegue.

Quando encontra diferenças que considera relevantes, Vera modifica uma das avaliações e realiza novamente a comparação. Esse processo é repetido até que, com base em sua própria análise, considere que as duas versões apresentam estruturas suficientemente semelhantes.


### 2. Questões de refinamento

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---|
| Q1 | [Atores] De que informações ou conhecimento os atores precisam para realizar esse objetivo? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q2 | [Ambiente ou contexto] Em que situações o cenário ocorre (quando, onde e por quê)? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q3 | [Ambiente ou contexto] Que dispositivos e outros recursos (inclusive tempo) estão disponíveis para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial | Hipótese |
| Q4 | [Atores] Quem depende do resultado do objetivo? Quem consome quais informações geradas pelo alcance do objetivo? Quem precisa ser notificado da conclusão (bem-sucedida ou malsucedida) do objetivo? | Para ajudar no refinamento do cenário inicial | Hipótese |
| Q5 | [Ambiente ou contexto] Quais pressões existem para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q6 | [Atores] De quem depende o alcance do objetivo? Quem fornece as informações necessárias? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q7 | [Objetivos] Que decisões os atores precisam tomar? Como o ambiente atual auxilia ou dificulta essas decisões? Quais as consequências de uma decisão errada? |Para ajudar no refinamento do cenário inicial | Hipótese |
| Q8 | [Ação] Como Vera verifica se uma diferença identificada entre as versões é relevante e precisa ser corrigida? | Investigar como ela realiza essa análise e quais critérios utiliza para decidir se deve alterar uma questão. | Hipótese |
| Q9 | [Avaliação] Que critérios ou evidências Vera utiliza para determinar que a comparação foi suficiente e que as versões estão prontas para serem aplicadas? | Compreender como ela avalia a conclusão da atividade, além de sua própria percepção de semelhança entre as provas. | Hipótese |
| Q10 | [Eventos] Que acontecimentos inesperados poderiam interromper a comparação ou exigir mudanças nas versões das avaliações ou no planejamento da atividade? | Identificar situações que podem alterar o andamento da comparação e exigir adaptações. | Hipótese |
| Q11 | [Planejamento] Como Vera organiza e prioriza as etapas da comparação entre as duas versões da avaliação? | Compreender como ela planeja a atividade e quais critérios utiliza para definir a sequência das etapas. | Hipótese |

### 3. Cenário refinado
<!-- Deletados q1 e q9 -->

Vera é professora de inglês e preparou duas versões de uma avaliação para aplicar em turmas diferentes, buscando evitar o compartilhamento de respostas entre os alunos. Ela deseja verificar se as diferenças entre as versões podem fazer com que uma das turmas seja favorecida ou prejudicada.

Como não possui uma ferramenta específica para comparar a estrutura das duas avaliações, Vera precisa encontrar uma maneira de identificar diferenças relevantes entre elas. Essa comparação pode envolver características como a extensão dos enunciados e das alternativas, a presença de elementos visuais e a organização das questões.

[Q1] Para realizar a comparação, Vera pode precisar considerar os conteúdos avaliados, os objetivos de aprendizagem e as características das turmas, além de reconhecer quais aspectos da estrutura das questões merecem atenção. Os conhecimentos e critérios que ela efetivamente utiliza ainda precisam ser investigados.

[Q2] [Q3] [Q5] A comparação ocorre no contexto de preparação das avaliações, antes de sua aplicação. O local em que Vera realiza essa atividade, os recursos tecnológicos e materiais disponíveis e as pressões que influenciam seu trabalho — como eventuais restrições de prazo — ainda precisam ser identificados.

[Q11] Para conduzir a comparação, Vera precisa definir por onde começar, quais aspectos examinar primeiro e como organizar as etapas da revisão. A estratégia que utiliza para priorizar essas etapas e decidir o que analisar em seguida ainda precisa ser investigada.

[Q8] Ao identificar diferenças entre as versões, Vera precisa avaliar se elas são relevantes, se podem afetar a dificuldade das questões e se justificam alterações. Os critérios que utiliza para tomar essas decisões e a forma como lida com dúvidas durante a comparação ainda precisam ser compreendidos.

[Q4] [Q6] Os resultados da comparação podem ser úteis para Vera na revisão das avaliações e, indiretamente, para os alunos que realizarão as provas. Também é necessário investigar se outras pessoas participam do processo, utilizam seus resultados ou fornecem informações que auxiliam a análise.

[Q10] Durante a preparação, acontecimentos não previstos podem exigir mudanças no planejamento ou nas avaliações. Quais ocorrências são relevantes nesse contexto e como Vera reagiria a elas ainda precisam ser investigados.

[Q9] Ao final da comparação, Vera precisa avaliar se as diferenças identificadas foram tratadas adequadamente e se dispõe de informações suficientes para decidir que as avaliações estão prontas para aplicação. Os critérios e as evidências que utiliza para chegar a essa conclusão ainda precisam ser investigados.

Sem uma ferramenta específica de apoio, a comparação pode depender de análises manuais e dos critérios adotados pela própria professora. Uma ferramenta que apresente diferenças estruturais de maneira organizada e compreensível poderia ajudá-la a identificar aspectos que merecem atenção, apoiando sua revisão sem substituir sua avaliação pedagógica.

### 4. Elementos extraídos

| Elemento | Evidência no cenário |
|---|---|
| Ator(es) | Vera Coelho, professora de inglês |
| Objetivo(s) | Comparar duas versões de uma avaliação destinadas a turmas diferentes, buscando evitar que diferenças em suas estruturas não favoreçam ou prejudiquem o desempenho de uma das turmas. |
| Contexto | Antes da aplicação das provas, Vera precisa revisar duas versões da mesma avaliação, preparadas para turmas diferentes. |
| Recursos/informações | [H] Ela tem o seu computador pessoal com acesso a um editor de texto, uma conexão com a internet, conhecimento prévio de suas turmas e o conteúdo sendo ensinado. |
| Ações | Vera elabora as duas versões da avaliação, compara manualmente suas características estruturais e identifica possíveis diferenças relevantes. Quando possível, consulta outros professores e funcionários para obter opiniões externas. Caso identifique diferenças que considere relevantes, realiza alterações e repete a comparação. |
| Problemas/rupturas | Vera precisa decidir quais diferenças entre as avaliações são relevantes e se as duas versões são suficientemente equivalentes para serem aplicadas em turmas diferentes. Essa decisão pode ser difícil porque nem toda diferença visual ou textual implica uma diferença de dificuldade, enquanto diferenças aparentemente pequenas podem exigir análise mais cuidadosa. Ela precisa interpretar as características das questões, julgar a necessidade de alterações e decidir quando há evidências suficientes para concluir a revisão. |
| Consequências | Se Vera não identificar uma diferença relevante ou avaliar incorretamente sua importância, as versões podem apresentar exigências distintas aos alunos. Nesse caso, diferenças nos resultados das turmas podem refletir não apenas o conhecimento dos estudantes, mas também características das avaliações que receberam. Por outro lado, alterações desnecessárias podem aumentar o trabalho de revisão sem melhorar a equivalência entre as versões. |

### 5. Implicações para as próximas entregas

A principal tarefa a ser analisada é verificar se as diferenças na estrutura das provas podem afetar o desempenho dos alunos. Para isso, devem ser coletadas informações sobre as características das duas avaliações, como a quantidade de palavras dos enunciados e das alternativas, a presença de imagens, o tempo de resolução da prova, o nível de formalidade da escrita e as características dos distratores.

## Histórico de revisões

- No cenário C01:
    - Agora as questões cobrem todas as questões mais explicitamentes;
    - Retirada de perguntas que ja estavam no cenario inicial;
    - Melhora na parte do evento, planejamento e avaliação;
    - Agora é explicito que o cenário vem de uma situação que não estava pensada na entrega 1;
- No cenário C02:
    - Troca de persona (Pois a persona anterior foi excluida do projeto); 
    - Agora as questões cobrem todas as questões mais explicitamentes;
    - Retirada de perguntas que ja estavam no cenario inicial;
    - Melhora na parte do evento;
    - Melhora no refinamento tentando não deixar tao extenso e diminuindo informações hipoteticas/ deixando claro que são hipoteses (principalmente na parte de ferramentas especificas e locais/ equipamentos);
    - Não deixar mais a ausência de ferramenta/ não possuir uma forma especifica como o problema principal;
- No cenário C03:
    - Agora as questões cobrem todas as questões mais explicitamentes;
    - Retirada de perguntas que ja estavam no cenario inicial;
    - Melhora na parte do evento, planejamento e avaliação;
    - Agora é explicito que o cenário vem de uma situação que não estava pensada na entrega 1;
    - Redução de suposições no refinamento;
    - Não deixar mais a ausência de ferramenta/ não possuir uma forma especifica como o problema principal;
- Adição das informaçoes necessarias no Rastreamento

## Checklist

- [X] Há um cenário completo por integrante.
- [X] Cada cenário tem título, ator, objetivo, contexto e problema.
- [X] O cenário possui origem rastreável na Entrega 1 ou justifica claramente a inclusão de uma nova situação.
- [X] O texto descreve a situação atual, sem antecipar a solução.
- [] Para TCC sem interface original, o cenário descreve uma prática humana plausível relacionada à contribuição técnica, e não “a falta de uma tela”.
- [X] Questões de refinamento acrescentam informação nova.
- [X] O refinamento mostra claramente o que foi adicionado/alterado.
- [X] Cenários são diferentes o suficiente para cobrir objetivos/problemas relevantes.
- [X] Cada cenário está ligado a persona/necessidade na matriz de rastreabilidade.
