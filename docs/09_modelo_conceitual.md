# Entrega 9 — Modelo conceitual e design centrado na comunicação

**Data:** 25/10/2026 <br>
**Status:** 🟨 em andamento <br>
**Responsabilidade:** soluções individuais, com consolidação da equipe para mapa de objetivos e esquema de signos.

## Objetivo da atividade

Passar do cenário de problema para uma concepção da interação, explicitando objetivos, tópicos de conversa, falas e signos que a interface deverá comunicar/manipular.

## 1. Cenários de interação

Para cada cenário de problema, produza uma versão em que a solução já pode ser descrita. **Destaque claramente o texto alterado** em relação ao cenário original.

### CI01 — Professor percebe um desempenho inesperadamente baixo

**Autor(a):** Luana Bortko Rodrigues **RA:** 24.123.006-9<br>
**Origem:** cenário problema C01 - Professor percebe um desempenho inesperadamente baixo

Maria da Costa Silva é professora de Literatura do ensino médio em uma escola pública do estado de São Paulo. Após corrigir uma avaliação aplicada recentemente a uma de suas turmas, percebe que o desempenho dos estudantes foi consideravelmente inferior ao esperado. Durante as aulas e atividades realizadas ao longo do período, a maioria dos alunos demonstrava compreender os conteúdos trabalhados e conseguia participar das discussões e dos exercícios propostos.

Diante desse resultado, Maria começa a questionar se a dificuldade apresentada pelos estudantes está relacionada à falta de domínio dos conteúdos ou se características da própria avaliação podem ter influenciado a resolução das questões. Ao revisar a prova, observa que algumas questões possuem enunciados extensos, diferentes quantidades de texto, elementos visuais e posições distintas. Ela considera que esses aspectos podem ter dificultado a interpretação ou a resolução de determinadas questões, mas não dispõe de informações suficientes para determinar se existe alguma relação entre essas características e o desempenho da turma.

Para compreender melhor a situação, Maria **decide utilizar um sistema de análise de avaliações para examinar a prova de forma objetiva e obter informações que orientem a revisão de suas próximas avaliações, em vez de depender apenas de impressões e conversas informais com colegas.**

[Q1] Para iniciar essa investigação, Maria, com acesso à versão digital **em pdf de sua avaliação conecta na ferramenta de análise e realiza o envio do arquivo PDF de sua avaliação. O sistema valida as precondições do documento e fornece o feedback de que o arquivo está pronto para o processamento.**

[Q2] Maria precisa compreender quais conhecimentos e informações são necessários para utilizar a ferramenta e interpretar os resultados apresentados. **O sistema exibe orientações contextuais e explicações acessíveis sobre o significado das métricas estruturais e estatísticas, auxiliando Maria a interpretar as informações sem exigir conhecimentos avançados de análise de dados.**

[Q3] Para investigar a situação, Maria **seleciona na interface a análise das características estruturais da prova, como extensão dos enunciados e presença de imagens. O sistema processa esses dados e apresenta visões organizadas que relacionam essas características com o desempenho observado na turma.**

[Q4] Essa investigação ocorre após a correção da avaliação, durante o período em que Maria planeja as próximas atividades e avaliações. Ela **realiza essa interação diretamente no ambiente do sistema durante seu horário de planejamento na escola.**

[Q5] Maria dispõe de um computador ou notebook na escola e de uma cópia digital da avaliação em PDF. **Para acomodar sua rotina atarefada, o sistema oferece uma interação ágil e direta, permitindo que ela conclua a consulta e a interpretação dos dados em pouco tempo.**

[Q6] Para avaliar se a análise foi útil, Maria **examina as analises geradas pelo sistema e julga se os dados oferecem insights relevantes. O sistema comunica o significado dos indicadores de forma clara, destacando pontos de atenção na prova sem sugerir relações precipitadas de causalidade.**

[Q7] Durante a análise, **se o arquivo enviado contiver inconsistências ou formatação incompatível, o sistema interrompe o processamento, exibe uma mensagem de erro explicativa.** Além disso, a proximidade do planejamento das próximas avaliações pode tornar necessário reorganizar suas prioridades e o tempo dedicado à investigação.

[Q8] Ao realizar a análise, Maria **utiliza as opções de navegação oferecidas pela interface para definir seu percurso de investigação.** Ela pretende direcionar seus esforços aos aspectos que considera mais relevantes para compreender as dificuldades observadas durante a correção e, a partir das informações obtidas, decidir quais pontos da avaliação merecem ser revistos.

Maria considera que terá alcançado seu objetivo **quando o sistema lhe fornecer uma interpretação clara das características da prova, permitindo identificar pontos que mereçam uma revisão mais cuidadosa e tomar decisões fundamentadas na elaboração de suas futuras avaliações.**

### Diferenças relevantes

| Alteração | Por que foi necessária | Evidência/artefato que justifica |
|---|---|---|
| Substituição de buscas informais pelo uso do sistema | Introduzir a solução de software como meio sistemático para investigar as características da avaliação. | H02, H03, H08 |
| Upload do PDF e validação inicial pelo sistema | Permitir a entrada de dados e fornecer feedback imediato de visibilidade do estado do sistema. | R02, F02, protótipo |
| Apresentação de guias de interpretação pelo sistema | Ajudar a usuária na compreensão das métricas sem exigir conhecimento prévio avançado em estatística. | F03, R03, H06, protótipo |
| Seleção interativa das características estruturais, como extensão de enunciados e imagens| Substituir a observação manual da prova por um fluxo interativo, em que a usuária aciona o recorte desejado (estímulo) e o sistema responde exibindo visualizações organizadas de desempenho (feedback/mudança de estado). | R04, R01, protótipo |
| Execução da análise via sistema no horário de planejamento e ambiente escolar | Adequar o uso da interface ao contexto real de trabalho e à rotina atarefada da professora, oferecendo um fluxo rápido de envio e consulta que respeite sua limitação de tempo. | H05 |
| Exibição das analises | Apoiar a tomada de decisão da usuária fornecendo indicadores claros para avaliar a utilidade da análise, ressaltando que métricas são pontos de reflexão e não prova de causa. | H08, R01, R04, F01, protótipo |
| Emissão de mensagens de erro explicativas | Avisar de forma clara erros que acontecem no input (ex: formato da prova incompativel, tempo de prova ultrapassou o limite)| protótipo |
| Obtenção de diagnósticos claros do sistema para orientar revisões de provas futuras | Conectar o feedback final do sistema ao alcance do objetivo principal da persona | H02, H03, H08, F01, R01, R04, protótipo |

### CI02 — Professor quer verificar uma prova antes de aplicá-la

**Autor(a):** Beatriz Manaia Lourenço Berto **RA:** 22.125.060-8 <br>
**Origem:** cenário problema C02 - Professor quer verificar uma prova antes de aplicá-la.

Maria da Costa Silva é professora de Literatura do ensino médio em uma escola pública do estado de São Paulo e, cerca de duas semanas antes da aplicação das avaliações, começa a elaborar uma prova para uma de suas turmas. Para isso, utiliza como referência os conteúdos trabalhados em aula, questões de provas anteriores, suas próprias anotações, materiais didáticos e as principais dúvidas apresentadas pelos alunos ao longo do período. A partir desses materiais, busca construir questões alinhadas aos conteúdos e objetivos de aprendizagem trabalhados em sala.

[Q2] Para iniciar a elaboração e a revisão da avaliação, Maria precisa ter definido os conteúdos que pretende avaliar, dispor dos materiais de referência necessários e ter acesso aos recursos que utiliza para preparar suas provas. Também precisa conhecer os objetivos de aprendizagem da turma para que possa verificar se as questões estão alinhadas ao que foi trabalhado em aula.[Q2-interação]Além disso, Maria pode utilizar o sistema DesemProv (de avaliação de analise estrutural da prova) para apoiar a revisão da atividade. Para que a avaliação seja processada e suas métricas extraídas com sucesso, estabelece-se como pré-condição que o arquivo enviado esteja em formato PDF, contenha questões de múltipla escolha e atenda aos requisitos estruturais da plataforma. Ademais, é obrigatório o preenchimento de informações essenciais da prova (como o tempo de duração e o número total de questões), enquanto os demais dados permanecem como opcionais, conforme a disponibilidade do docente.

[Q4] Maria prepara e revisa suas avaliações utilizando os recursos disponíveis em sua rotina de trabalho. Também pode utilizar plataformas educacionais, para organizar e disponibilizar materiais aos alunos, ferramentas para elaborar questionários e avaliações e ferramentas de inteligência artificial, para auxiliar na elaboração, adaptação ou revisão de questões. A escolha desses recursos depende das necessidades da atividade e de sua familiaridade com as ferramentas disponíveis.[Q4-interação]Os docentes podem utilizar o DesemProv, um sistema web para análise estrutural de provas, antes ou após a aplicação das avaliações. Antes da aplicação, a ferramenta é utilizada para compreender características estruturais da prova (como quantidade de caracteres, presença de imagens, formalismo, distribuidores/distratores e tempo estimado de leitura) e compará-las com os impactos observados em questões do ENEM. Isso facilita a compreensão global da avaliação e apoia o refinamento prévio dos itens.

[Q1] Durante a preparação da prova, Maria organiza suas atividades em etapas. Inicialmente, define o formato da avaliação, a quantidade de questões e os conteúdos que pretende avaliar. Em seguida, consulta os materiais de referência, elabora ou adapta as questões e organiza uma primeira versão da prova. Depois, revisa os enunciados, verifica a clareza das questões e a coerência das alternativas e realiza alterações quando identifica possíveis problemas. Por fim, pode solicitar que outros professores revisem a avaliação e compartilhem suas opiniões antes da aplicação.[Q1-interação]Buscando uma análise mais aprofundada e objetiva do que a mera opinião de um colega, o docente realiza o upload da avaliação em formato PDF no sistema DesemProv. Após o envio, a aplicação processa o arquivo e retorna gráficos e métricas que permitem compreender a distribuição estrutural da prova, bem como avaliar o impacto potencial dessas características com base nos dados de referência do ENEM. Desse modo, Maria consegue examinar criticamente as propriedades de sua avaliação e decidir fundamentadamente sobre a necessidade de correções.

Após preparar uma primeira versão da avaliação, Maria inicia um processo de revisão cuidadoso. Relê os enunciados, verifica se estão claros e objetivos, se apresentam ambiguidades, se as alternativas são coerentes e se as questões realmente avaliam os conteúdos que deseja verificar. Também observa características como a extensão dos textos, a quantidade de informações apresentadas e o nível de interpretação exigido, buscando evitar que aspectos relacionados à estrutura das questões interfiram indevidamente no desempenho dos alunos.

[Q6] Para realizar essa revisão, Maria precisa conhecer os conteúdos da disciplina, os objetivos de aprendizagem trabalhados em aula e os princípios de elaboração de questões, como clareza, correção textual, identificação de ambiguidades e adequação entre a questão e o conteúdo que se pretende avaliar. Caso utilize uma ferramenta de análise estrutural, também precisará compreender quais informações deve fornecer e como interpretar as métricas apresentadas.

[Q3] Maria busca elaborar avaliações adequadas porque deseja obter informações confiáveis sobre o conhecimento dos alunos e utilizar essas informações para aprimorar suas aulas. Para isso, precisa compreender os conteúdos que pretende avaliar, conhecer as dificuldades que observa durante as aulas e saber quais características da elaboração de questões podem merecer atenção. Seu conhecimento da disciplina e de sua turma contribui para que tome decisões coerentes com os objetivos de aprendizagem.[Q3-interação]Para utilizar o sistema e analisar a prova, o docente precisa conhecer detalhadamente as informações da avaliação que elaborou para preencher corretamente os inputs. Ademais, após o sistema retornar as métricas em formatos visuais e gráficos, é necessário que o professor possua capacidade analítica para interpretar os resultados ou, ao menos, compreender as informações de suporte textuais fornecidas pela plataforma.

[Q5] Sua experiência como professora e seu conhecimento dos conteúdos podem facilitar a elaboração e a revisão da avaliação. Por outro lado, o tempo limitado para preparar as provas e a dificuldade de identificar objetivamente quais características estruturais podem estar associadas ao desempenho dos estudantes podem dificultar a identificação de aspectos que mereçam uma análise mais aprofundada.[Q5/Q6-interação] Para interagir com a ferramenta, o docente precisa ser organizado na reunião prévia dos dados exigidos pela plataforma (como tempo de duração, gabarito e nível de dificuldade das questões) e apresentar uma habilidade básica de interpretação. Para auxiliar nesse processo, o sistema não apenas retorna as representações gráficas, mas também fornece descrições detalhadas e explicações textuais sobre os dados apresentados, servindo como um guia para apoiar o professor na leitura e compreensão dos resultados.

[Q8] Durante a preparação da avaliação, acontecimentos inesperados, como uma alteração no prazo de entrega da prova estabelecido pela escola ou uma mudança nos conteúdos que precisam ser contemplados, podem exigir que Maria reorganize suas prioridades, altere algumas questões ou modifique o planejamento da revisão. Essas situações podem reduzir o tempo disponível para a atividade e exigir adaptações na forma como ela conduz a preparação da avaliação.[Q8-interação] Ao utilizar o DesemProv para analisar sua avaliação, Maria pode identificar, por meio das métricas retornadas, que certas características estruturais (como textos excessivamente longos ou de alto formalismo) estão muito presentes. Com base nesses insights objetivos sobre o impacto potencial dos itens, ela pode decidir modificar questões específicas antes da aplicação da prova.

[Q7] Maria pode avaliar se a prova está pronta para ser aplicada verificando se as questões estão alinhadas aos conteúdos e objetivos de aprendizagem, se os enunciados são claros e se as alternativas são coerentes. As opiniões dos professores que colaboram na revisão também podem ajudá-la a identificar problemas que não havia percebido. Caso utilize uma ferramenta de análise estrutural, precisará interpretar os resultados e julgar se eles fornecem informações relevantes para revisar a avaliação. Após a aplicação, o desempenho dos alunos e as dúvidas apresentadas poderão contribuir para avaliar suas escolhas, embora esses dados, isoladamente, não comprovem que determinadas características estruturais causaram dificuldades.[Q7-interação] O objetivo é considerado concluído quando o sistema fornece as métricas detalhadas, as informações gerais e as descrições dos gráficos. A partir disso, cabe ao professor utilizar os resultados gerados pela ferramenta para analisar criticamente a sua prova, refletindo sobre a necessidade de implementar modificações estruturais antes de aplicá-la aos alunos.

Entretanto, mesmo após essas etapas, a análise da avaliação continua baseada principalmente na experiência e na percepção dos professores. Maria não possui uma forma objetiva e baseada em dados de verificar se determinadas características estruturais das questões, como a extensão dos enunciados, a quantidade de informações apresentadas ou o nível de interpretação exigido, podem estar associadas ao desempenho dos estudantes. Dessa forma, embora consiga avaliar as questões sob diferentes perspectivas, permanece sem evidências suficientes para identificar quais características da estrutura da prova merecem atenção antes de sua aplicação.


<!--le ate achar onde entra o sistema e add a info na interface, responde essas perguntas com base na interface

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
-------

-->

### Diferenças relevantes
<!-- identifica onde cenario problema vira interacao, de q parte passa a vira iteracao-->
| Alteração | Por que foi necessária | Evidência/artefato que justifica |
|---|---|---|
| Q1-interação | Porque o sistema DesemProv fornece uma forma mais estruturada, precisa e baseada em dados para o docente analisar as características formais da avaliação, indo além da dependência exclusiva da opinião de colegas. | Goms, CTT, Protótipo |
| Q2-interação | Pois detalha quais são as pré-condições técnicas e de dados necessárias para o uso do sistema de análise estrutural de provas (DesemProv). | R02, protótipo |
| Q3-interação | Ao compreender o que o usuário precisa para alcançar o objetivo dentro do sistema, conseguimos fornecer essas informações de suporte na aplicação para otimizar e agilizar as funções do usuário, ou apenas informá-lo de sua necessidade, tornando o sistema cada vez mais intuitivo e eficiente. | H04, H06, H07, R03 |
| Q4-interação | Ao fornecer o DesemProv para os docentes analisarem as características estruturais de suas provas, bem como o possível impacto dessas características, cria-se um método baseado em dados e estudos, sendo muito mais comprovado do que apenas pedir a opinião e contar com a disponibilidade de colegas. | F01, F02, H08, H11 |
| Q5/Q6-interação | Para identificar as características dos atores (como a necessidade de organização e habilidade básica de interpretação) e as informações de suporte que o sistema deve fornecer (como descrições detalhadas dos gráficos) para ajudá-los a alcançar o objetivo com sucesso. | H06, H08, R01, R03 |
| Q7-interação | Para definir o critério de conclusão do objetivo com o auxílio do sistema (fornecimento de métricas e descrições gráficas), permitindo que o docente saiba o momento exato em que a análise estrutural foi entregue para apoiar sua tomada de decisão crítica. | HTA, GOMS, CTT, H01, H02, H03, H08 |
| Q8-interação | Para prever como o próprio feedback do sistema (as métricas e o impacto potencial de características como formalismo e extensão de texto) pode atuar como um evento inesperado que motiva o docente a modificar e refinar questões específicas antes da aplicação da prova e ajuda a prepararmos o sistema com base no que motiva o usuário a usá-lo | GOMS, CTT, Concorrência, H10, H11 |


### CI03 — {{título}}

**Autor(a):** Nuno Martins Guilhermino da Silva **RA:** 22.126.099-5<br>
**Origem:** cenário problema C03 - Professor quer comparar duas versões de uma avaliação

{{cenário de interação com alterações marcadas}}

### Diferenças relevantes

| Alteração | Por que foi necessária | Evidência/artefato que justifica |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

## 2. Design centrado na comunicação

**Nome do cenário:** CI01

| Tópico > subtópico | Falas e signos envolvidos | Intenção/efeito esperado |
|---|---|---|
| {{objetivo}} | `U: ...` / `D: ...` | {{...}} |
| > {{subtópico}} | {{...}} | {{...}} |

**Nome do cenário:** CI02

| Tópico > subtópico | Falas e signos envolvidos | Intenção/efeito esperado |
|---|---|---|
| {{objetivo}} | `U: ...` / `D: ...` | {{...}} |
| > {{subtópico}} | {{...}} | {{...}} |

**Nome do cenário:** CI03

| Tópico > subtópico | Falas e signos envolvidos | Intenção/efeito esperado |
|---|---|---|
| {{objetivo}} | `U: ...` / `D: ...` | {{...}} |
| > {{subtópico}} | {{...}} | {{...}} |

**Convenção:** `U` = usuário; `D` = preposto do designer/sistema, conforme a abordagem de Engenharia Semiótica adotada na disciplina.


<!-- mapa eh 1 p equipe toda-->


## 3. Mapa de objetivos

Cada integrante apresenta seu mapa e a equipe cria um **mapa consolidado**, eliminando duplicidades e resolvendo conflitos de nomenclatura.

### Mapa de CI01

![Mapa ci01](../assets/09_modelo_conceitual/mapa_objetivos.svg)

### Mapa de CI02

![Mapa ci02](../assets/09_modelo_conceitual/mapa_objetivos.svg)

### Mapa de CI03

![Mapa ci03](../assets/09_modelo_conceitual/mapa_objetivos.svg)

### Mapa Consolidado

![Mapa consolidado](../assets/09_modelo_conceitual/mapa_objetivos.svg)

### Dicionário de objetivos do mapa consolidado <!-- mapa eh 1 p equipe toda-->

| ID | Objetivo | Persona(s) | Cenário(s) | Prioridade |
|---|---|---|---|---|
| O01 | {{...}} | {{P01}} | {{CI01}} | {{...}} |

## 4. Esquema conceitual de signos
<!--unico e alinhamento ebatido entre todos escolher , ipload,td input e output sao signos, se tem sinalizacao do sistem a eh sigo baseado so na parte de analise da tela é sobre obj ex analise de prova vai ter mtoo signos, dado exibidos e tem grupos de signos (grupo da prova, da área...  -->


Conforme alinhado em sala existem duas telas enem e sobre que nao fazem parte da analise cocneitual por xxxxx motivo (agrega mais valor ao proj faze o da analise)
Consolide as informações em **uma tabela única**.

| Grupo | Signo | Origem | Observações/semântica | Tipo de conteúdo | Restrição | Valor padrão | Prevenção | Recuperação |
|---|---|---|---|---|---|---|---|---|
| Credenciais | usuário | domínio | {{...}} | texto | não nulo | — | {{...}} | {{...}} |

### Regras para os signos

- Use o vocabulário do domínio do usuário.
- Evite duplicar o mesmo conceito com nomes diferentes.
- Diferencie informação fornecida pelo usuário, produzida pelo sistema e derivada do domínio.
- Registre prevenção e recuperação apenas quando fizer sentido; explique as siglas usadas.

## Síntese

Quais objetivos/tópicos/signos deverão necessariamente aparecer nos diagramas MoLIC?

## Checklist

- [ ] Cenários de interação mostram alterações em relação aos cenários de problema.
- [ ] Cada solução individual identifica autor e cenário de origem.
- [ ] Tópicos/falas/signos são coerentes com objetivos do usuário.
- [ ] Mapas individuais foram consolidados.
- [ ] O esquema de signos está em uma tabela única e sem duplicações conceituais.
- [ ] Nomes de objetivos/signos serão reutilizados na Entrega 10.
