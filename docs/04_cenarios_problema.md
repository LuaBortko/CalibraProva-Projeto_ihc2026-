# Entrega 4 — Cenários de análise/problema

**Data:** 09/09/2026<br> 
**Status:** 🟩 concluída <br>
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
**Situação concreta da Entrega 1 relacionada:** 4.1, 4.2 e 4.5<br>  
**Hipóteses ainda presentes:** H01, H02, H03, H04 

### 1. Cenário inicial

Maria da Costa Silva, professora de Literatura do ensino médio de uma escola pública do estado de São Paulo, está corrigindo uma avaliação aplicada recentemente a uma de suas turmas. Durante as aulas e atividades realizadas ao longo do período, Maria percebeu que a maioria dos estudantes demonstrava compreender os conteúdos trabalhados e conseguia participar das discussões e dos exercícios propostos. No entanto, ao corrigir a avaliação, ela percebe que o desempenho da turma foi consideravelmente inferior ao esperado.

O resultado faz com que Maria questione se a dificuldade apresentada pelos estudantes está realmente relacionada à falta de domínio dos conteúdos ou se a forma como a avaliação foi elaborada pode ter influenciado o desempenho. Ao revisar a prova, ela percebe que algumas questões possuem enunciados extensos, diferentes quantidades de texto e elementos visuais, além de estarem distribuídas em posições distintas. Maria considera que essas características podem ter dificultado a interpretação ou a resolução de algumas questões, mas não consegue determinar se elas realmente tiveram relação com o resultado obtido pela turma.

Para tentar compreender melhor a situação, Maria conversa com outros professores da escola e conhecidos da área, buscando saber se já passaram por situações semelhantes e como costumam lidar com resultados inesperados em avaliações. Embora essas conversas possam ajudar a levantar possíveis explicações, Maria percebe que as opiniões são baseadas principalmente em experiências individuais e não permitem verificar de forma objetiva se determinadas características da prova estão relacionadas ao desempenho dos estudantes. Assim, ela busca uma forma de analisar a avaliação aplicada que possa fornecer informações mais concretas e ajudá-la a identificar possíveis melhorias para suas próximas provas.

### 2. Questões de refinamento

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---|
| Q1 | por que os atores querem ou precisam alcançar esse objetivo | Para ajudar no refinamento do cenário inicial | hipotese  |
| Q2 | quais as precondições para esse objetivo | Para ajudar no refinamento do cenário inicial  | hipotese |
| Q3 | de que informações ou conhecimento os atores precisam para realizar esse objetivo | Para ajudar no refinamento do cenário inicial | hipotese|
| Q4 | quais informações são (ou deveriam ser) criadas, consumidas, manipuladas ou destruídas pelo alcance do objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q5 | em que situações o cenário ocorre (quando, onde e por quê)? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q6 | que dispositivos e outros recursos (inclusive tempo) estão disponíveis para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q7 | como os atores alcançam o objetivo atualmente? como gostariam de fazê-lo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q8 | quais problemas ou dificuldades podem surgir ao realizá-la? como podem ser resolvidos ou contornados? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q9 | [do objetivo] como os atores conseguem saber se o objetivo foi concluído e alcançado com sucesso? | Para ajudar no refinamento do cenário inicial | hipotese |

### 3. Cenário refinado

Maria da Costa Silva, professora de Literatura do ensino médio de uma escola pública do estado de São Paulo, está corrigindo uma avaliação aplicada recentemente a uma de suas turmas. Durante as aulas e atividades realizadas ao longo do período, Maria percebeu que a maioria dos estudantes demonstrava compreender os conteúdos trabalhados e conseguia participar das discussões e dos exercícios propostos. No entanto, ao corrigir a avaliação, ela percebe que o desempenho da turma foi consideravelmente inferior ao esperado.

O resultado faz com que Maria questione se a dificuldade apresentada pelos estudantes está realmente relacionada à falta de domínio dos conteúdos ou se a forma como a avaliação foi elaborada pode ter influenciado o desempenho. Ao revisar a prova, ela percebe que algumas questões possuem enunciados extensos, diferentes quantidades de texto e elementos visuais, além de estarem distribuídas em posições distintas. Maria considera que essas características podem ter dificultado a interpretação ou a resolução de algumas questões, mas não consegue determinar se elas realmente tiveram relação com o resultado obtido pela turma. [Q1] Ela busca compreender melhor o que pode ter contribuído para o desempenho abaixo do esperado, pois acredita que isso pode ajudá-la a elaborar avaliações que representem de maneira mais adequada o conhecimento de seus estudantes.

Para tentar compreender melhor a situação, Maria conversa com outros professores da escola e conhecidos da área, buscando saber se já passaram por situações semelhantes e como costumam lidar com resultados inesperados em avaliações. Embora essas conversas possam ajudar a levantar possíveis explicações, Maria percebe que as opiniões são baseadas principalmente em experiências individuais e não permitem verificar de forma objetiva se determinadas características da prova estão relacionadas ao desempenho dos estudantes. [Q7] Por isso, ela busca uma forma mais objetiva de realizar essa análise, sem depender exclusivamente da experiência de outros professores.

[Q2] Para investigar a situação, Maria precisa partir da avaliação, considerando o contexto em que a prova foi elaborada e aplicada. [Q3] Ela precisa compreender quais aspectos da maneira como uma avaliação é elaborada podem estar relacionados ao desempenho dos estudantes e como esses aspectos podem afetar a forma como eles interpretam e resolvem as questões. [Q4] Ao realizar essa investigação, Maria considera tanto as características presentes na avaliação, como a extensão dos enunciados, a presença de elementos visuais e a organização das questões, quanto aquilo que observou no desempenho de seus alunos. [Q5] Essa situação ocorre após a correção da avaliação, durante seu período de planejamento na própria escola, quando Maria analisa os resultados da turma e começa a pensar em como pode melhorar suas próximas avaliações. [Q6] Ela dispõe de um computador ou notebook no ambiente escolar, mas possui pouco tempo disponível para realizar atividades adicionais devido à sua rotina de trabalho.

[Q8] Para que essa investigação seja útil, Maria precisa conseguir compreender as informações obtidas e utilizá-las para refletir sobre suas escolhas ao elaborar avaliações, sem precisar dominar métodos complexos ou depender de interpretações que não consiga compreender. [Q9] Ela considera que terá alcançado seu objetivo quando conseguir compreender melhor o que pode estar contribuindo para os resultados de seus alunos e tiver elementos que a ajudem a tomar decisões mais conscientes sobre a forma como avalia seus conhecimentos. 

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

## Cenário C02 — ⁠Professor quer verificar uma prova antes de aplicá-la

**Autor(a):** Beatriz Manaia Lourenço Berto **RA:** 22.125.060-8<br>
**Persona(s) relacionada(s):** P02<br>
**Necessidade relacionada:** Necessita manter-se constantemente atualizado sobre os avanços tecnológicos, tanto para acompanhar novas áreas quanto para aprimorar conhecimentos já adquiridos. Também busca receber feedbacks frequentes de alunos e outros docentes, utilizando essas percepções para aperfeiçoar continuamente suas aulas e práticas de ensino. Além disso, busca formas mais eficientes e precisas de avaliar e mensurar o nível de conhecimento e o desenvolvimento dos alunos, identificando suas dificuldades e oportunidades de melhoria. 

<br> <!--persona e qqr necessidade q user orecisa em r outra entrega tb-->

**Situação concreta da Entrega 1 relacionada:** 4.1 e 4.5 <br> 
**Hipóteses ainda presentes:** H01, H02, H03, H04 

### 1. Cenário inicial

João Paulo é professor universitário do curso de Ciência da Computação e, cerca de duas semanas antes da aplicação das avaliações, começa a elaborar as provas de suas turmas. Para isso, pode utilizar como base os conteúdos trabalhados em aula, questões de provas anteriores, questões do ENADE ou da Pós-Comp, suas próprias anotações, materiais didáticos e as principais dúvidas apresentadas pelos alunos ao longo do semestre. A partir desses materiais, busca construir questões alinhadas aos conteúdos e objetivos de aprendizagem trabalhados em sala.

Em um ambiente tranquilo e com acesso à internet, João prepara uma primeira versão da avaliação em seu computador. Após finalizar as questões, inicia um processo de revisão cuidadoso. Relê os enunciados, verifica se estão claros e objetivos, se apresentam ambiguidades, se as alternativas são coerentes e se as questões realmente avaliam os conteúdos que deseja verificar. Também observa características como a extensão dos textos, a quantidade de informações apresentadas e o nível de interpretação exigido, buscando evitar que aspectos relacionados à estrutura das questões interfiram indevidamente no desempenho dos alunos.

Depois de realizar algumas alterações, João pede auxílio a outros professores para que revisem a prova e compartilhem suas opiniões sobre as questões. Esse processo permite obter diferentes perspectivas e identificar possíveis problemas que não haviam sido percebidos durante sua própria revisão.

Entretanto, mesmo após essas etapas, a análise da avaliação continua baseada principalmente na experiência e na percepção dos professores. João não possui uma forma objetiva e baseada em dados de verificar se determinadas características estruturais das questões, como extensão do enunciado, quantidade de informações ou nível de interpretação exigido, podem estar associadas ao desempenho dos estudantes. Dessa forma, embora consiga avaliar a qualidade das questões sob diferentes perspectivas, permanece sem evidências que permitam identificar possíveis características da estrutura da prova que possam impactar o desempenho dos alunos.

### 2. Questões de refinamento 

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---| 
| Q1 | Quais as condições para realização da atividade? | Para ajudar no refinamento do cenário inicial | hipotese | 
| Q2 | Quais os detalhes sobre a sequência de ações que compõe uma atividade? | Para ajudar no refinamento do cenário inicial | hipotese |     
| Q3 | Porque os atores querem ou precisam alcancar esse objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q4 | Quais as precondicoes para esse objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q5 | De que informações ou conhecimentos os atores precisam para realizar esse objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q6 | Em que situações o cenário ocorre (quando,onde e porque)? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q7 | Quais são as técnologias utilizadas no ambiente de trabalho? Como os usuários as utilizam? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q8 | Quais características do(s) ator(es) lhes auxiliam ou atrapalham em alcançar o objetivo? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q9 | De que informações ou conhecimento os atores precisam para realizar essa ação? | Para ajudar no refinamento do cenário inicial | hipotese |
| Q10 | [do objetivo]Como os atores conseguem saber se o objetivo foi concluído e alcançado com sucesso? | Para ajudar no refinamento do cenário inicial | hipotese |

### 3. Cenário refinado

<!--Reescreva o cenário incorporando as respostas. Marque o conteúdo novo de forma consistente (por exemplo, `**[NOVO: ...]**`).-->

João Paulo é professor universitário do curso de Ciência da Computação e, cerca de duas semanas antes da aplicação das avaliações, começa a elaborar as provas de suas turmas. **[Q6] [Esse processo ocorre durante o período destinado pelo professor à preparação das avaliações, podendo ser realizado na instituição de ensino, em seu escritório ou em casa, de acordo com sua disponibilidade e rotina de trabalho.]** Para isso, pode utilizar como base os conteúdos trabalhados em aula, questões de provas anteriores, questões do ENADE ou da Pós-Comp, suas próprias anotações, materiais didáticos e as principais dúvidas apresentadas pelos alunos ao longo do semestre. A partir desses materiais, busca construir questões alinhadas aos conteúdos e objetivos de aprendizagem trabalhados em sala.

**[Q1] [Para realizar essa atividade, João precisa dispor de um ambiente adequado, com recursos como computador, notebook ou tablet, mesa, cadeira, iluminação adequada, papel e caneta, quando necessário, além de acesso à internet. Também pode consultar livros, materiais didáticos, provas anteriores e outras fontes de apoio durante a elaboração.]**

**[Q7] [Entre as tecnologias utilizadas em seu ambiente de trabalho estão ferramentas como o Google Classroom, utilizado para organizar e disponibilizar materiais, atividades e avaliações aos alunos; o Google Forms, utilizado para criar e aplicar questionários e avaliações; e ferramentas de Inteligência Artificial, como o ChatGPT, que podem auxiliar na elaboração, adaptação e revisão de questões. Essas tecnologias apoiam diferentes etapas do processo de ensino e avaliação.]**

É nesse ambiente que João prepara uma primeira versão da avaliação. **[Q2] [Durante esse processo, inicialmente define o modelo da prova, como múltipla escolha ou dissertativa, estabelece a quantidade de questões e seleciona os conteúdos e objetivos que pretende avaliar. Em seguida, consulta materiais de apoio, elabora ou adapta as questões e organiza a avaliação.]**

Após finalizar as questões, inicia um processo de revisão cuidadoso. Relê os enunciados, verifica se estão claros e objetivos, se apresentam ambiguidades, se as alternativas são coerentes e se as questões realmente avaliam os conteúdos que deseja verificar. Também observa características como a extensão dos textos, a quantidade de informações apresentadas e o nível de interpretação exigido, buscando evitar que aspectos relacionados à estrutura das questões interfiram indevidamente no desempenho dos alunos. **[Q9] [Para realizar essa atividade, João precisa ter conhecimento sobre os conteúdos e conceitos fundamentais da disciplina, os objetivos de aprendizagem trabalhados em aula e aspectos relacionados à elaboração de questões, como clareza, correção textual, identificação de ambiguidades e adequação entre a questão e aquilo que se pretende avaliar. Também precisa reconhecer características estruturais das questões que possam influenciar o desempenho dos estudantes.]**

Depois de realizar algumas alterações, ele pede auxílio a outros professores para que revisem a prova e compartilhem suas opiniões sobre as questões. Esse processo permite obter diferentes perspectivas e identificar possíveis problemas que não haviam sido percebidos durante sua própria revisão.

**[Q8] [A experiência do professor na elaboração de avaliações, seu conhecimento sobre os conteúdos da disciplina e sua familiaridade com ferramentas tecnológicas podem facilitar esse processo. Por outro lado, a limitação de tempo e a dificuldade em analisar objetivamente os fatores que podem influenciar o desempenho dos estudantes podem dificultar a identificação precisa de possíveis problemas na avaliação.]**

**[Q3] [João busca elaborar avaliações adequadas porque deseja obter informações confiáveis sobre o nível de conhecimento dos alunos e utilizar essas informações para aprimorar suas aulas. Para isso, precisa que os resultados das avaliações representem adequadamente o conhecimento dos alunos, sem que características estruturais da prova interfiram indevidamente nesse desempenho.]**

**[Q4] [Para alcançar esse objetivo, é necessário que a avaliação contenha questões alinhadas aos conteúdos e objetivos de aprendizagem, apresentadas de maneira clara e coerente, e que suas características estruturais não introduzam dificuldades que não estejam relacionadas ao conhecimento que se pretende avaliar.]**

**[Q5] [Para utilizar os resultados das avaliações na melhoria das aulas, João precisa obter informações que permitam compreender como os alunos estão aprendendo e quais aspectos do ensino podem ser aprimorados. Para isso, precisa conhecer os principais pontos fortes e dificuldades dos alunos, identificar os conteúdos em que apresentam maior dificuldade, compreender suas percepções e feedbacks sobre as aulas e observar quais estratégias e formas de explicação favorecem melhor a compreensão dos conteúdos. Também precisa de resultados de avaliações que representem adequadamente o conhecimento dos estudantes, para identificar quais conteúdos precisam ser retomados ou aprofundados.]**

**[Q10] [João consegue avaliar se está alcançando o objetivo de melhorar suas aulas por meio dos resultados das avaliações, das dúvidas apresentadas pelos alunos, dos feedbacks recebidos e da comparação do desempenho entre diferentes avaliações ou turmas após mudanças em suas estratégias de ensino. Entretanto, essas informações podem ser comprometidas caso o desempenho observado nas avaliações seja influenciado por características estruturais das questões, dificultando a identificação do que representa efetivamente uma dificuldade de aprendizagem.]**

Entretanto, mesmo após essas etapas, a análise da avaliação continua baseada principalmente na experiência e na percepção dos professores. João não possui uma forma objetiva e baseada em dados de verificar se determinadas características estruturais das questões, como a extensão do enunciado, a quantidade de informações apresentadas ou o nível de interpretação exigido, podem estar associadas ao desempenho dos estudantes. Dessa forma, embora consiga avaliar a qualidade das questões sob diferentes perspectivas, permanece sem evidências que permitam identificar se a própria estrutura da avaliação pode constituir um fator capaz de impactar o desempenho dos alunos, mesmo quando o conteúdo e o nível de dificuldade da questão estejam adequados aos objetivos de aprendizagem.

### 4. Elementos extraídos

| Elemento | Evidência no cenário |
|---|---|
| Ator(es) | João Paulo de Aquino Gonzaga. |
| Objetivo(s) | Elaborar avaliações adequadas aos conteúdos e objetivos de aprendizagem, obtendo resultados que representem de forma confiável o conhecimento dos alunos e permitam aprimorar suas aulas. |
| Contexto | Cerca de duas semanas antes da aplicação das avaliações, durante o período de preparação das provas, em ambiente adequado de trabalho, como a instituição de ensino, escritório ou casa, com acesso a recursos físicos, digitais e à internet. |
| Recursos/informações | Conteúdos trabalhados em aula, questões de provas anteriores, questões do ENADE ou da Pós-Comp, anotações do professor, materiais didáticos, dúvidas dos alunos, livros, avaliações e outras fontes de apoio; computador, notebook ou tablet; Google Classroom, Google Forms e ferramentas de Inteligência Artificial. |
| Ações | Definir o modelo e a quantidade de questões; selecionar conteúdos e objetivos de aprendizagem; consultar materiais de apoio; elaborar ou adaptar questões; organizar e revisar a avaliação; verificar clareza, ambiguidades, coerência e adequação das questões; analisar características estruturais, como extensão, quantidade de informações e nível de interpretação; realizar alterações; solicitar a revisão de outros professores; analisar os resultados e utilizá-los para aprimorar as aulas. |
| Problemas/rupturas | Mesmo após a revisão individual e por outros professores, João não possui uma forma objetiva e baseada em dados para verificar se características estruturais das questões estão associadas ao desempenho dos estudantes. A análise permanece baseada principalmente na experiência e percepção dos professores. |
| Consequências | João permanece sem evidências suficientes para identificar se a estrutura da avaliação pode impactar o desempenho dos alunos, mesmo quando o conteúdo e o nível de dificuldade estão adequados aos objetivos de aprendizagem. Como consequência, pode interpretar de forma incorreta as dificuldades apresentadas pelos estudantes, comprometendo a identificação dos conteúdos que precisam ser retomados ou aprofundados e, consequentemente, dificultando o aprimoramento de suas aulas. |

### 5. Implicações para as próximas entregas

<!--Quais tarefas merecem análise? Quais informações precisam ser coletadas? **Não desenhe a solução ainda.** -->

A principal informação que precisa ser coletada e analisada é a relação entre as características estruturais das questões de uma prova e o desempenho dos estudantes. O TCC deverá investigar se aspectos como a quantidade de palavras do enunciado, a presença de imagens, o tempo disponível para resolução, o nível de formalismo da linguagem e as características dos distratores podem influenciar o desempenho dos alunos, considerando especificamente questões do ENEM.

## Cenário C03 — Professor quer comparar duas versões de uma avaliação

**Autor(a):** Nuno Martins Guilhermino da Silva **RA:** 22.126.099-5<br>   
**Persona(s) relacionada(s):** P03<br>
**Necessidade relacionada:** Com o seu trabalho, ela precisa acompanhar o progresso de seus alunos ao longo do andamento de sua tutela, e para isso ela precisa ter certeza que suas provas são apropriadas para o nível de cada turma/pessoa, e com sua rotina corrida, precisa de rápida certificação de que suas avaliações são formuladas com qualidade.<br>  
**Situação concreta da Entrega 1 relacionada:** Seção 4.4 <br>  
**Hipóteses ainda presentes:** H01, H02,H03 ou H04 

### 1. Cenário inicial
Vera é uma professora de inglês que preparou duas versões de uma avaliação para aplicar em turmas diferentes, buscando evitar o compartilhamento de respostas entre os alunos. Entretanto, ela deseja garantir que as diferenças entre as avaliações não façam com que uma das turmas seja favorecida ou prejudicada.

Como não possui uma ferramenta específica para comparar a estrutura das duas avaliações, Vera realiza essa análise manualmente. Ela revisa ambas as provas, observando características como o tamanho dos enunciados e das alternativas, a presença de elementos visuais e a organização das questões, buscando identificar diferenças que possam afetar o desempenho dos alunos, além de procurar opiniões externas de outros funcionários e professores da escola onde trabalha quando consegue.

Quando encontra diferenças que considera relevantes, Vera modifica uma das avaliações e realiza novamente a comparação. Esse processo é repetido até que, com base em sua própria análise, considere que as duas versões apresentam estruturas suficientemente semelhantes.


### 2. Questões de refinamento

Use os tipos de questões/taxonomia definidos na aula. As perguntas devem revelar informações **ainda ausentes** do cenário, não repetir o que já foi respondido.

| # | Questão | Por que precisa ser respondida | Fonte/forma de obter resposta |
|---|---|---|---|
| Q1 | Quais as precondições para esse objetivo? | Para ajudar no refinamento do cenário inicial | Hipótese |
| Q2 | De que informações ou conhecimento os atores precisam para realizar esse objetivo? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q3 | Em que situações o cenário ocorre (quando, onde e por quê)? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q4 | Que dispositivos e outros recursos (inclusive tempo) estão disponíveis para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial | Hipótese |
| Q5 | Quem depende do resultado do objetivo? Quem consome quais informações geradas pelo alcance do objetivo? Quem precisa ser notificado da conclusão (bem-sucedida ou malsucedida) do objetivo? | Para ajudar no refinamento do cenário inicial | Hipótese |
| Q6 | Quais pressões existem para o alcance do objetivo? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q7 | De quem depende o alcance do objetivo? Quem fornece as informações necessárias? | Para ajudar no refinamento do cenário inicial| Hipótese |
| Q8 | Que decisões os atores precisam tomar? Como o ambiente atual auxilia ou dificulta essas decisões? Quais as consequências de uma decisão errada? |Para ajudar no refinamento do cenário inicial | Hipótese |
| Q9 | Como os atores alcançam o objetivo atualmente? Como gostariam de fazê-lo? | Para ajudar no refinamento do cenário inicial | Hipótese |

### 3. Cenário refinado

Vera é uma professora de inglês que está preparando duas versões de uma avaliação para aplicar em duas de suas turmas, buscando evitar o compartilhamento de respostas entre os alunos. **[Q1] Antes de iniciar a comparação, Vera já elaborou as duas versões da avaliação e definiu os conteúdos e objetivos de aprendizagem que pretende avaliar.** Ela deseja garantir que, apesar de diferentes, as avaliações possuam estruturas semelhantes e que essas diferenças não favoreçam ou prejudiquem nenhuma das turmas.

**[Q2] Para realizar essa análise, Vera considera seu conhecimento sobre o conteúdo avaliado, o nível esperado de conhecimento de cada turma e sua experiência na elaboração de avaliações, buscando identificar características das questões que possam alterar sua dificuldade ou influenciar o desempenho dos alunos.**

**[Q3] Esse processo ocorre durante a elaboração e revisão das avaliações, antes de sua aplicação. Vera costuma realizar essa atividade em sua casa, seu principal ambiente de preparação das aulas, embora possa realizá-la em outros locais que ofereçam os recursos necessários.** **[Q4] Para elaborar, modificar e comparar as avaliações, ela utiliza um computador com acesso a editores de texto e precisa reservar parte de seu tempo de preparação para revisar as duas versões.**

Como não possui uma ferramenta específica para comparar a estrutura das avaliações, Vera realiza essa análise manualmente. Ela observa características como o tamanho dos enunciados e das alternativas, a presença de elementos visuais e a organização das questões. **[Q7] O processo depende principalmente de sua própria análise e experiência, embora, quando possível, ela também procure outros professores e funcionários da escola para obter opiniões externas sobre as avaliações. A decisão final sobre as alterações, entretanto, permanece com Vera.**

**[Q8] Durante a comparação, Vera precisa decidir quais diferenças entre as avaliações são relevantes, se elas podem influenciar o desempenho dos alunos, quais questões precisam ser modificadas e quando as duas versões estão suficientemente equivalentes. A ausência de uma ferramenta específica dificulta essas decisões, fazendo com que dependam principalmente de sua percepção e experiência. Uma decisão inadequada pode resultar em diferenças que favoreçam ou prejudiquem uma das turmas.**

**[Q6] Além disso, Vera precisa realizar todo esse processo dentro do prazo disponível antes da aplicação das provas e possui a responsabilidade de produzir avaliações adequadas ao conteúdo e ao nível de suas turmas. Quando encontra diferenças que considera relevantes, ela modifica uma das avaliações e realiza novamente a comparação.**

**[Q5]O resultado desse processo afeta tanto Vera quanto seus alunos, pois estes receberão as versões finais das avaliações e seu desempenho poderá ser influenciado por diferenças entre elas. Vera, como responsável pela elaboração e revisão, precisa saber se foram identificadas diferenças relevantes e quando a comparação pode ser considerada concluída.**

**[Q9] Atualmente, Vera repete manualmente esse processo de comparação e alteração até considerar que as duas avaliações possuem estruturas suficientemente semelhantes. Ela gostaria de realizar essa comparação de maneira mais rápida e objetiva, recebendo informações claras sobre as diferenças entre as provas e os aspectos que podem exigir sua atenção, reduzindo o tempo dedicado à revisão e aumentando sua confiança de que diferenças estruturais não afetarão de maneira desigual suas turmas.**

### 4. Elementos extraídos

| Elemento | Evidência no cenário |
|---|---|
| Ator(es) | Vera Coelho |
| Objetivo(s) | Comparar duas versões de uma avaliação destinadas a turmas diferentes, buscando garantir que diferenças em suas estruturas não favoreçam ou prejudiquem o desempenho de uma das turmas. |
| Contexto | Antes da aplicação das provas, Vera possui duas versões da avaliação já elaboradas e precisa revisá-las e compará-las antes de aplicá-las em turmas diferentes.|
| Recursos/informações | Ela tem o seu computador pessoal com acesso a um editor de texto, uma conexão com a internet, conhecimento prévio de suas turmas e o conteúdo sendo ensinado. |
| Ações | Vera elabora as duas versões da avaliação, compara manualmente suas características estruturais e identifica possíveis diferenças relevantes. Quando possível, consulta outros professores e funcionários para obter opiniões externas. Caso identifique diferenças que considere relevantes, realiza alterações e repete a comparação. |
| Problemas/rupturas | Vera não possui uma ferramenta específica que forneça evidências concretas sobre as diferenças estruturais entre as avaliações. Dessa forma, a comparação depende principalmente de sua própria percepção e experiência e das opiniões de outros professores, dificultando determinar com segurança quando as duas versões estão suficientemente equivalentes.|
| Consequências | Diferenças estruturais não identificadas durante a revisão podem influenciar o desempenho dos alunos, fazendo com que os resultados das turmas sejam afetados não apenas pelo conhecimento ou preparação dos estudantes, mas também pelas características das versões das avaliações que receberam.|

### 5. Implicações para as próximas entregas

A principal tarefa a ser analisada é verificar se as diferenças na estrutura das provas podem afetar o desempenho dos alunos. Para isso, devem ser coletadas informações sobre as características das duas avaliações, como a quantidade de palavras dos enunciados e das alternativas, a presença de imagens, o tempo de resolução da prova, o nível de formalidade da escrita e as características dos distratores.

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
