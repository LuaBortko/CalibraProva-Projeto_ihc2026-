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
| H09 | Aluno poderia ser afetafo pelo sistema indiiretamente | Não consideramos que o aluno tem impacto no sistema de avaliação com base no ENEM pois o seu desenvolvimento é pautado apenas nas análises das provas do ENEM, sem sofrer influências de caraterísticas específicas dos alunos. | Nenhuma | Baixo |

## Parte A — necessidades e requisitos de IHC

> **Responsabilidade:** solução individual por integrante.

### A01 — Beatriz Manaia Lourenço Berto

**Autor(a):** Beatriz Manaia Lourenço Berto - 22.125.060-8

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

### Instrumento I01 — {{nome da técnica}}

**Autor(a):** Beatriz Manaia Lourenço Berto
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

### Instrumento I03 — {{nome da técnica}}

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
