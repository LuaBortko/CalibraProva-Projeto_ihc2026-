# Entrega 3 — Personas, mapa de empatia, contexto de uso e jornada

**Data:** {{03/09/2026}}  
**Status:** 🟨  em andamento
**Responsabilidade:** 1 persona por integrante; 1 mapa de empatia, 1 contexto de uso consolidado e 1 jornada por equipe (salvo orientação diferente do docente).

## Objetivo da atividade

Representar grupos de usuários de forma útil para decisões de design. Persona não é personagem decorativo: suas características devem alterar requisitos, prioridades, linguagem, fluxos ou critérios de avaliação.

## Atenção a projetos técnicos

Em TCCs sem interface original, a persona pode representar um **profissional que se apropria da contribuição técnica**: DBA, analista, cientista de dados, administrador, pesquisador, técnico, operador, gestor ou especialista de domínio.

Não escolha um perfil apenas porque “parece combinar” com a tecnologia. Explique **qual objetivo esse perfil teria e qual parte da contribuição do TCC produziria valor para ele**. Se ainda for hipótese, mantenha como hipótese/proto-persona a validar.

Também considere papéis diferentes quando houver tarefas distintas, por exemplo:

- operador que executa análises;
- administrador que configura e gerencia permissões;
- especialista que interpreta resultados;
- gestor que consulta relatórios e decide;
- auditor que revisa histórico.

## Entradas da Entrega 1

Antes de criar personas, retome os tipos de usuários, características relevantes, objetivos e hipóteses registradas na Entrega 1. A persona **não deve transformar uma hipótese inicial em fato por meio de uma história fictícia**.

| Item da Entrega 1 | Status inicial | Evidência disponível agora | Como será tratado nesta entrega |
|---|---|---|---|
| Docentes/elaboradores de provas como usuários diretos | F | A Entrega 1 identifica docentes/elaboradores de provas como os usuários que interagem diretamente com o produto. | Incorporar |
| Docente do Estado de São Paulo como perfil priorizado | F | O recorte do TCC utiliza dados do ENEM referentes ao Estado de São Paulo, e a Entrega 1 definiu esse perfil como prioritário para a interface. | Incorporar |
| Necessidade de conhecimento tecnológico para utilizar a ferramenta | H04 | A Entrega 1 registra essa característica como hipótese, sem evidência suficiente para afirmar o nível de conhecimento tecnológico do público. | Manter como hipótese e investigar |
| Uso da ferramenta durante a elaboração de avaliações | H04 | A Entrega 1 relaciona o uso à aplicação/elaboração de avaliações, mas não apresenta evidência sobre a frequência ou o momento exato de uso. | Manter como hipótese e investigar |
| Aprimorar as avaliações para que representem melhor o desempenho dos estudantes | H03 | Registrado como objetivo esperado na Entrega 1, mas ainda como hipótese quanto ao benefício efetivamente percebido pelo usuário. | Manter como hipótese e investigar |
| Docente precisa interpretar métricas sobre características estruturais das provas | F | A Entrega 1 identifica as métricas e características estruturais que precisam ser interpretadas para apoiar decisões sobre a avaliação. | Incorporar |
| Docente possui dificuldade para identificar possíveis efeitos das características estruturais da prova | F | Atualmente essa análise depende principalmente do conhecimento, experiência e repertório do próprio docente. | Incorporar |
| Alunos são afetados pelos resultados da ferramenta | H | A Entrega 1 identifica os alunos como stakeholders afetados, mas não como usuários diretos da interface. | Manter como hipótese e não representar como usuário da persona |
| Resultados da análise podem fornecer subsídios para docentes/elaboradores avaliarem características estruturais das provas e ajustarem sua dificuldade | H02 | A Entrega 1 apresenta essa possibilidade como uma contribuição do projeto, mas ainda não há evidência de que os usuários realmente utilizariam essas informações dessa forma. | Manter como hipótese e investigar |

## 1. Personas

### Persona P01 — Antenor da Costa Silva
<!-- Presencial e Escola -->
**Autor(a):** Luana Bortko Rodrigues -- RA: 24.123.006-9<br>  
**Tipo:** primário  <br>
**Base de evidências:** Proto-persona a validar<br>
**Hipóteses da Entrega 1 relacionadas:** H02, H03 e H04<br>

![Persona P01](../assets/03_personas/persona_p01.svg)

| Campo | Descrição |
|---|---|
| Faixa etária / contexto relevante | {{somente o que impacta o uso}} |
| Ocupação/papel | {{...}} |
| Conhecimento do domínio | {{...}} |
| Experiência tecnológica | {{...}} |
| Objetivos | {{...}} |
| Necessidades | {{...}} |
| Dores/frustrações | {{...}} |
| Motivadores | {{...}} |
| Restrições/acessibilidade | {{...}} |
| Ambiente típico de uso | {{...}} |
| Comportamentos relevantes | {{...}} |

**Decisões de design influenciadas por P01:**

- {{...}}

### Persona P02 — João Paulo de Aquino Gonzaga

**Autor(a):** Beatriz Manaia Lourenço Berto <br> 
**Tipo:** primária <br>
**Base de evidências:** proto-persona a validar <br> 
**Hipóteses da Entrega 1 relacionadas:** H02, H03 e H04 <br>

![Persona P02](../assets/03_personas/persona_p02.webp)

| Campo | Descrição |
|---|---|
| Faixa etária / contexto relevante |João é um homem de 35 anos que teve amplo acesso a oportunidades educacionais ao longo de sua formação, incluindo ensino em escolas particulares e participação em diversos cursos de capacitação. Esse contexto contribuiu para sua formação acadêmica e para o desenvolvimento de uma relação próxima com os estudos e a tecnologia. |
| Ocupação/papel | Atua como professor de Ciência da Computação, lecionando para turmas do 5º, 6º e 7º semestres, nos períodos vespertino e noturno, em uma faculdade privada de São Paulo |
| Conhecimento do domínio | Possui alto conhecimento sobre educação e elaboração de avaliações, com experiência na criação, aplicação e acompanhamento do desempenho dos alunos em provas. Tem familiaridade com a análise de resultados e busca compreender as dificuldades apresentadas pelos estudantes, mas não necessariamente possui conhecimento aprofundado sobre métricas psicométricas específicas utilizadas na análise de avaliações. |
| Experiência tecnológica | **Alta.** Possui contato com tecnologia desde a adolescência, quando explorava computadores e equipamentos como rádios, televisõs e dispositivos de acesso à internet, buscando compreender seu funcionamento e solucionar problemas em casa. Atualmente, mantém-se atualizado em relação às novas tecnologias e demonstra grande facilidade para aprender e se adaptar a novas ferramentas e recursos tecnológicos.|
| Objetivos | Deseja transformar conteúdos complexos em aulas de fácil compreensão, atendendo tanto alunos com maior dificuldade quanto aqueles que apresentam maior facilidade de aprendizado. Busca ajudá-los a desenvolver confiança em seus conhecimentos e prepará-los para ingressar no mercado de trabalho. Valoriza a combinação entre conteúdos teóricos e atividades práticas em suas aulas. |
| Necessidades | Necessita manter-se constantemente atualizado sobre os avanços tecnológicos, tanto para acompanhar novas áreas quanto para aprimorar conhecimentos já adquiridos. Também busca receber feedbacks frequentes de alunos e outros docentes, utilizando essas percepções para aperfeiçoar continuamente suas aulas e práticas de ensino. Além disso, busca formas mais eficientes e precisas de avaliar e mensurar o nível de conhecimento e o desenvolvimento dos alunos, identificando suas dificuldades e oportunidades de melhoria.  |
| Dores/frustrações | Possui uma forte cobrança em relação ao próprio trabalho e enfrenta dificuldades para conciliar as demandas profissionais com momentos de descanso e lazer. Também se preocupa com a possibilidade de os alunos perderem o interesse pelo aprendizado e se tornarem excessivamente dependentes do uso de IA. Além disso, sente dificuldade em avaliar de maneira precisa e confiável o nível de conhecimento dos alunos, especialmente diante dessas mudanças na forma de aprendizagem. |
| Motivadores | Sua principal motivação é contribuir para a democratização do acesso à educação e utilizar a tecnologia como uma aliada do desenvolvimento humano e da construção de uma sociedade mais justa. Além de lecionar em uma faculdade privada, produz conteúdos didáticos gratuitos em suas redes sociais, buscando compartilhar conhecimento para além da sala de aula. Também se envolve com pesquisas relacionadas a cidades inteligentes, movido pelo interesse em explorar como a tecnologia pode ser aplicada para solucionar problemas da sociedade e melhorar a qualidade de vida das pessoas. |
| Restrições/acessibilidade | Não apresenta limitações, dificuldades ou condições que possam afetar sua utilização do sistema. Possui acesso a uma boa conexão de internet, alta familiaridade com tecnologias e facilidade para aprender e se adaptar a novas ferramentas e recursos digitais. |
| Ambiente típico de uso | Utiliza o sistema principalmente em casa, durante a preparação de atividades e avaliações, e na faculdade, especialmente em horários vagos. Acessa a plataforma principalmente por meio de seu notebook pessoal, sobretudo nas semanas que antecedem a aplicação das avaliações, para planejar e analisar as atividades. |
| Comportamentos relevantes | Costuma preparar suas avaliações com antecedência e revisar os conteúdos antes de aplicá-las. Após as avaliações, demonstra interesse em analisar o desempenho dos alunos e identificar suas principais dificuldades. Busca utilizar ferramentas tecnológicas que facilitem seu trabalho e explora novas soluções digitais para aprimorar suas práticas de ensino. Além disso, procura constantemente estratégias para tornar suas aulas mais dinâmicas e engajantes, buscando manter a atenção dos alunos e estimular seu interesse e disposição para aprender. |

**Decisões de design influenciadas por P02:**

- *Upload simplificado e orientado:* João prepara avaliações com antecedência e busca ferramentas que facilitem seu trabalho. Ele tem alta familiaridade tecnológica, mas valoriza eficiência e não quer perder tempo com configurações complexas.
- *Dashboard visual com métricas interpretáveis:* João sente dificuldade em avaliar precisamente o nível de conhecimento dos alunos e deseja identificar características da prova que possam impactar o desempenho. Ele precisa de informações claras e rápidas para tomar decisões.
- *Explicações integradas e acessíveis*: João valoriza o entendimento profundo e busca melhorar continuamente suas práticas. Ele precisa compreender o que cada métrica significa e como se relaciona com o desempenho, para ajustar suas provas de forma fundamentada.
- *Interface limpa:* João tem alta experiência tecnológica, mas enfrenta forte cobrança e dificuldade em conciliar demandas. Ele não quer perder tempo navegando em interfaces confusas. Além disso, ele valoriza a clareza para focar no que é essencial.

### Persona P03 — {{nome fictício}}

**Autor(a):** {{nome — matrícula}}  <br>
**Tipo:** primária / secundária  <br>
**Base de evidências:** entrevista / questionário / literatura / observação / proto-persona a validar / combinação <br> 
**Hipóteses da Entrega 1 relacionadas:** {{H01, H02 ou —}}<br>

![Persona P03](../assets/03_personas/persona_p01.svg)

| Campo | Descrição |
|---|---|
| Faixa etária / contexto relevante | {{somente o que impacta o uso}} |
| Ocupação/papel | {{...}} |
| Conhecimento do domínio | {{...}} |
| Experiência tecnológica | {{...}} |
| Objetivos | {{...}} |
| Necessidades | {{...}} |
| Dores/frustrações | {{...}} |
| Motivadores | {{...}} |
| Restrições/acessibilidade | {{...}} |
| Ambiente típico de uso | {{...}} |
| Comportamentos relevantes | {{...}} |

**Decisões de design influenciadas por P03:**

- {{...}}

### Síntese das personas

Explique diferenças entre os perfis e qual persona é prioritária. Evite personas duplicadas que só mudam nome/foto.

## 2. Mapa de empatia — equipe
<!-- Mulher branca entre 46/47 anos  de são paulo, casada escola publica --> 
**Persona escolhida:** {{P01}}  
**Justificativa:** {{por que esse perfil é relevante}}

![Mapa de empatia](../assets/03_personas/mapa_empatia.svg)

Documente também em texto: o que vê; ouve; diz/faz; pensa/sente; dores; ganhos. Diferencie **evidência** de **hipótese**.

## 3. Contexto de uso — consolidação

| Dimensão | Descrição | Implicação de design |
|---|---|---|
| Usuários | {{...}} | {{...}} |
| Tarefas | {{...}} | {{...}} |
| Equipamentos | {{...}} | {{...}} |
| Ambiente físico | {{...}} | {{...}} |
| Ambiente social/organizacional | {{...}} | {{...}} |
| Papéis/permissões/governança | {{...}} | {{...}} |
| Volume de dados/histórico | {{...}} | {{...}} |

## 4. Jornada do usuário — equipe

**Persona:** {{P01}}  
**Objetivo da jornada:** {{...}}  
**Início e fim da jornada:** {{...}}

| Etapa | Situação/ação | Objetivo | Pensamento/emoção | Dor | Oportunidade de design | Evidência |
|---|---|---|---|---|---|---|
| 1 | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |

> A jornada pode incluir etapas **antes, durante e depois** do uso do produto. Não transforme a jornada em lista de telas.

## Síntese

Quais necessidades e objetivos devem obrigatoriamente aparecer nos cenários e nas tarefas seguintes?

## Checklist

- [ ] Existe pelo menos uma persona por integrante.
- [ ] As personas não são apenas diferenças demográficas superficiais.
- [ ] Está claro o que é dado real e o que é hipótese/proto-persona.
- [ ] A persona não “validou por ficção” uma hipótese da Entrega 1; afirmações continuam marcadas como hipótese quando não há evidência.
- [ ] Objetivos e dores têm consequência para o design.
- [ ] Contexto de uso está coerente com a Entrega 1.
- [ ] Em TCC sem interface original, a persona possui relação explícita com a contribuição técnica.
- [ ] Papéis administrativos, técnicos e decisórios só foram criados quando possuem objetivos/tarefas diferentes.
- [ ] Jornada possui etapas, dores e oportunidades e não é apenas wireflow.
- [ ] IDs das personas foram adicionados à rastreabilidade.
