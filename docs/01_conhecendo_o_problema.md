# Entrega 1 — Conhecendo o projeto, o usuário e o problema

**Data:** 19/08/2026
**Status:**  🟨 iniciada  
**Responsabilidade:** 1 solução consolidada por equipe

## Objetivo da atividade

Reinterpretar o tema do TCC sob a perspectiva de Interação Humano-Computador e construir um **entendimento comum entre os integrantes da equipe**.

A disciplina utiliza preferencialmente o tema do TCC para os exercícios de IHC. Isso vale tanto para TCCs que já preveem uma interface quanto para trabalhos cujo resultado principal é algoritmo, modelo, API, biblioteca, análise de dados, infraestrutura, estudo experimental ou outro artefato técnico.

> **Importante:** a interface projetada na disciplina é um artefato de aprendizagem de IHC. Ela **não se torna automaticamente uma obrigação do TCC**. Sua incorporação ao trabalho de conclusão depende de decisão da equipe e do orientador.

Antes de preencher, leia [`../GUIA_ESCOPO_IHC.md`](../GUIA_ESCOPO_IHC.md).

Nesta primeira semana a equipe **não deve começar desenhando telas**. Primeiro deverá compreender:

- o que o TCC realmente produz;
- quem poderia obter valor dessa contribuição;
- quais pessoas interagem, administram, configuram, interpretam ou são afetadas;
- o que essas pessoas precisam alcançar;
- como atividades relacionadas acontecem hoje;
- problemas, limitações e contexto;
- alternativas existentes;
- qual recorte de interação fará sentido para a disciplina.

Ao final desta entrega, a equipe deve diferenciar:

- **tema do TCC** × **escopo formal do TCC** × **escopo de IHC da disciplina**;
- **objetivo do projeto** × **objetivo do usuário**;
- **problema do usuário** × **solução tecnológica**;
- **fato conhecido** × **hipótese** × **lacuna de conhecimento**;
- **capacidade técnica** × **forma de uso dessa capacidade**;
- **funcionalidade** × **atividade/resultado que o usuário precisa alcançar**;
- **usuário direto** × **stakeholders**.

---

## Como classificar as respostas

Sempre que a resposta fizer uma afirmação sobre usuários, problemas, atividades, necessidades, contexto ou mercado, use:

- **[F] Fato conhecido** — existe evidência/fonte.
- **[H] Hipótese** — afirmação plausível que ainda precisa ser investigada.
- **[?] Não sabemos ainda** — lacuna relevante.

Quando usar `[F]`, informe a origem. Hipóteses prioritárias devem receber IDs (`H01`, `H02`...) e também ser registradas em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

> **Exemplo:** `[H] H01 — DBAs considerariam útil comparar automaticamente o plano atual de execução com uma recomendação produzida pelo algoritmo.`

Uma hipótese explicitada é melhor do que uma suposição escondida.

---

# 0. Identificação do TCC e da equipe

## 0.1 Membros

| Nome completo | Matrícula | GitHub |
|---|---:|---|
| Beatriz Manaia Lourenço Berto |22.125.060-8 | [Beatriz manaia Lourenço Berto](https://github.com/beatrizmanaia26)|
| Luana Bortko Rodrigues |24.123.006-9 | [Luana Bortko Rodrigues](https://github.com/LuaBortko) |
| Nuno Martins Guilhermino da Silva |22.126.099-5 |  [Nuno Martins Guilhermino da Silva ](https://github.com/nunomgs136) |

## 0.2 Título atual do TCC

Estrutura e formatação das provas o ENEM: Impacto no desempenho geral dos participantes

## 0.3 Orientador(a)

Charles Henrique Porto Ferreira

## 0.4 Qual é o resultado principal atualmente previsto no TCC?

Marque e descreva:
<!-- DEBATER -->
- [ ] sistema/aplicação interativa;
- [ ] algoritmo;
- [ ] modelo de IA/ML/LLM;
- [ ] biblioteca/API/framework;
- [ ] análise de dataset;
- [X] estudo/benchmark/avaliação experimental;
- [ ] infraestrutura/backend;
- [ ] componente embarcado/IoT;
- [ ] outro: {{...}}.

**Descrição:** Análise das características estruturais das provas do ENEM e de seu possível impacto no desempenho dos estudantes.

## 0.5 O TCC já previa desenvolvimento de interface com usuário?

- [X] Sim, a interface já faz parte do TCC.
- [ ] Parcialmente; existe alguma interação, mas ainda não está bem definida.
- [ ] Não. O TCC é predominantemente técnico e não previa interface.

**Explique o que está formalmente previsto no TCC:** A partir do upload de uma prova de mesmo formato do ENEM, o sistema analisa suas características estruturais e, utilizando as correlações observadas no ENEM, estima seu nível potencial de dificuldade ao oferecer visualização de informações como: uso de elementos visuais, nível de formalidade, construção de distratores, ordem de apresentação das questões e tempo médio de leitura da prova e das questões.

> Esta resposta serve para separar o compromisso do TCC do projeto da disciplina. Mesmo quando a opção for **não**, a equipe irá definir uma interface para exercitar IHC.

---

# 1. Entendendo a contribuição do projeto

## 1.1 Explique o TCC em uma frase, sem citar linguagem de programação, framework ou banco de dados.

Analisa se o formato das provas do ENEM, mensurado por características como a ordem de apresentação das questões, o nível de formalidade, o tempo médio de resolução, a quantidade de palavras por enunciado, a presença de imagens e a construção dos distratores, impacta o desempenho dos candidatos.

## 1.2 Qual situação, atividade ou problema do mundo real motivou o TCC?

[F] Historicamente, estudos sobre a formatação da prova do ENEM são escassos, não recebendo a mesma atenção que outros fatores influentes, como o perfil socioeconômico dos candidatos, revisado por DUTRA. Ademais, as pesquisas relacionadas frequentemente possuem abordagens e motivações diferentes, analisando itens de provas específicas prioritariamente para revelar limitações do ensino básico nas escolas brasileiras (CESTARO, LOPES). Consequentemente, há uma carência de investigações atualizadas que isolem o impacto das características estruturais dos itens no desempenho dos alunos.

- DUTRA, Janderson Ferreira; FIRMINO JUNIOR, João Batista; FERNANDES, Damires Yluska de Souza. Fatores que podem interferir no desempenho de estudantes no ENEM: uma revisão sistemática da literatura. Revista Brasileira de Informática na Educação, 2022. DOI: 10.5753/rbie.2023.3087.

- CESTARO, Débora Cristina; KLEINKE, Maurício Urban; ALLE, Lupe Furtado. Uma análise do desempenho dos participantes e do conteúdo abordado em itens de genética e biologia evolutiva do Exame Nacional do Ensino Médio (ENEM): implicações curriculares. Investigações em Ensino de Ciências, v. 25, n. 3, 2020, p. 503. DOI: 10.22600/1518-8795.ienci2020v25n3p503.

- LOPES, José Christian; RUBINI, Gustavo; MASSUNAGA, Marcelo de Oliveira S.; BARROSO, Marta Feijó. Estudo das questões de Física da prova de Ciências da Natureza do ENEM. Anais da Reunião da Associação Brasileira de Avaliação Educacional (ABAVE), Florianópolis, SC, Brasil, v. 8, 2015.

## 1.3 Qual é a **capacidade/contribuição central** produzida pelo TCC?

Nosso TCC tem como objetivo analisa como características estruturais dos itens do ENEM, como extensão do enunciado, uso de elementos visuais, nível de formalidade, construção de distratores, análise do tempo médio de resolução e ordem de apresentação das questões, influenciam o desempenho dos participantes, a fim de identificar padrões que contribuem para a compreensão do impacto do formato do exame na avaliação das competências dos candidatos e, a partir dos resultados observados, desenvolvemos uma aplicação que analisa o PDF de uma prova enviada e retorna as métricas e suas respectivas influências no desempenho do estudante."

## 1.4 O que se espera que esteja diferente **para pessoas, organizações ou processos** se essa contribuição for bem-sucedida?

[H] Poderá fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos.

## 1.5 O que é mérito técnico/científico do TCC e o que seria uma possível aplicação prática?

| Mérito/contribuição técnica | Possível aplicação/valor em uso |
|---|---|
| Análise de características estruturais das provas do ENEM entre 2020 e 2025, com exceção da edição de 2021. | Aplicação da metodologia de análise a outras provas identificando características estruturais que possam influenciar o desempenho. |
| Identificação de possíveis relações entre as características estruturais analisadas e o desempenho dos candidatos. | |

# 2. Entendendo as pessoas envolvidas

## 2.1 Quem interage diretamente com o produto, se já existe interface prevista?

[F] Docentes/Elaboradores de prova interagem diretamente com o produto.

## 2.2 Quem poderia **usar, configurar, administrar, operar, interpretar ou tomar decisões** a partir da contribuição técnica?

Considere perfis profissionais e stakeholders, não apenas consumidores finais.

| Perfil | Relação com a contribuição | O que faria | Status/evidência |
|---|---|---|---|
| Usuário final | Impacto direto | Upload da prova, inserção de seus parâmetros e analise das métricas obtidas | F |

## 2.3 Existem pessoas afetadas que não usariam a interface diretamente?

| Stakeholder | Como é afetado | Usa interface? | Status/evidência |
|---|---|---|---|
| Alunos | Terão uma avaliação mais condizente | Não | H |

## 2.4 Que características desses perfis podem influenciar a interação? 
<!-- VOLTAR DPS DA ENTREGA 3

<!-- Considere conhecimento do domínio, experiência tecnológica, frequência de uso, necessidades de acessibilidade, responsabilidade profissional, familiaridade com métricas, linguagem técnica, urgência etc.
{{[F/H/?] ...}}
-->
[H] Um docente tem um mínimo de conhecimento tecnológico, utilizaria de acordo com a aplicação de alguma avaliação, 
(complementar depois de outras entregas)

---

# 3. Entendendo objetivos e atividades

## 3.1 O que o usuário está tentando conseguir no mundo real?

<!-- Não responda “usar o algoritmo”, “clicar no sistema” ou “ver o dashboard”. -->
[H] Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes.

## 3.2 Quais são as atividades mais importantes?

| ID | Atividade/objetivo | Quem realiza | Frequência/criticidade inicial | Status/evidência |
|---|---|---|---|---|
| A01 | {{...}} | {{...}} | {{...}} | {{...}} |
| A02 | {{...}} | {{...}} | {{...}} | {{...}} |
| A03 | {{...}} | {{...}} | {{...}} | {{...}} |

## 3.3 Qual atividade parece mais frequente? Por quê?

{{[F/H/?] ...}}

## 3.4 Qual parece mais crítica? Que consequência existe se for mal executada?

{{[F/H/?] ...}}

---

# 4. Entendendo o problema ou processo atual

## 4.1 Como essas atividades são realizadas hoje, antes da interface imaginada na disciplina?

Pode existir software concorrente, linha de comando, planilha, notebook, script, painel técnico, processo manual, consulta a logs, análise visual, troca de mensagens, decisão por especialista etc.

{{[F/H/?] ...}}

## 4.2 O que é difícil, demorado, confuso, repetitivo, arriscado ou pouco transparente?

{{[F/H/?] ...}}

## 4.3 Que informações o profissional precisa interpretar para tomar decisão?

{{[F/H/?] ...}}

## 4.4 O que acontece quando a atividade falha ou quando o resultado é interpretado incorretamente?

{{[F/H/?] ...}}

## 4.5 Conte uma situação concreta.

Escreva uma pequena narrativa com pessoa, objetivo, atividade, contexto, dificuldade e consequência. **Não descreva ainda a futura solução.**

{{[F/H/?] narrativa...}}

## 4.6 Que evidência existe hoje?

| Evidência/fonte | O que sustenta | Limitação |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

---

# 5. Entendendo o contexto de uso

## 5.1 Onde e em quais situações a interação poderia ocorrer?

{{[F/H/?] ...}}

## 5.2 Em quais dispositivos/equipamentos?

{{[F/H/?] ...}}

## 5.3 Existem condições físicas relevantes?

Considere iluminação, ruído, mobilidade, conexão, privacidade, uso compartilhado, interrupções, pressão de tempo etc.

{{[F/H/?] ...}}

## 5.4 Existem fatores sociais ou organizacionais?

Considere papéis, chefias, equipes, permissões, aprovação, responsabilidade profissional, auditoria, turnos e colaboração.

{{[F/H/?] ...}}

## 5.5 Existe necessidade de histórico, rastreabilidade ou auditoria?

{{[F/H/?] ...}}

## 5.6 Um erro pode produzir consequência relevante? Qual?

{{[F/H/?] ...}}

---

# 6. Entendendo mercado e alternativas existentes

> Nesta entrega faça apenas um **levantamento inicial**. A análise aprofundada ocorre na Entrega 2.

## 6.1 Como pessoas resolvem problemas semelhantes hoje?

| Alternativa atual | Quem usa | Para quê | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

## 6.2 Existem produtos que atuam na mesma área, mesmo sem serem equivalentes ao TCC?

{{[F/H/?] ...}}

## 6.3 Quais interfaces profissionais esse público já conhece?

Exemplos possíveis: ferramentas de banco, IDEs, consoles de nuvem, dashboards, plataformas de dados, ferramentas de monitoramento, painéis de IA, sistemas administrativos.

{{[F/H/?] ...}}

## 6.4 O que essas soluções parecem fazer bem?

{{[F/H/?] ...}}

## 6.5 O que parecem fazer mal, dificultar ou não atender?

{{[F/H/?] ...}}

## 6.6 Que padrões de interface ou vocabulário parecem familiares a esse público?

{{[F/H/?] ...}}

---

# 7. Derivando o escopo de IHC da disciplina

## 7.1 Escolha o caminho do projeto

### Caminho A — TCC já possui interface

Explique qual parte da interface será usada como recorte da disciplina e por que esse fluxo é relevante.

{{...}}

### Caminho B — TCC não possui interface prevista

Faça o exercício de transferência de uso:

> **Imagine que o TCC foi concluído com sucesso e uma empresa, laboratório ou organização quer transformar a contribuição em algo utilizável. Quem precisaria interagir com ela e para quê?**

Responda:

1. quem poderia contratar/adotar a solução? {{...}}
2. quem seria o usuário direto? {{...}}
3. quem administraria/configuraria? {{...}}
4. quem interpretaria resultados? {{...}}
5. quem tomaria decisões? {{...}}
6. quais dados/entradas seriam necessários? {{...}}
7. quais resultados deveriam ser compreendidos? {{...}}
8. que erros/rupturas seriam possíveis? {{...}}

## 7.2 Qual perfil será priorizado no projeto de IHC?

{{...}}

**Por que esse perfil foi escolhido?** {{...}}

## 7.3 Qual objetivo desse usuário será priorizado?

{{...}}

## 7.4 Que interface será explorada na disciplina?

Complete:

> **Para fins da disciplina de IHC, será projetada uma interface que permita a `{{perfil}}` utilizar `{{capacidade/resultado do TCC}}` para `{{objetivo}}`, no contexto de `{{situação}}`.**

{{...}}

## 7.5 Qual é a relação dessa interface com o TCC?

- [ ] Já fazia parte do TCC.
- [ ] É um aprofundamento de algo parcialmente previsto.
- [ ] É uma extensão conceitual criada para a disciplina.
- [ ] É um protótipo demonstrativo de aplicação potencial.
- [ ] Outra: {{...}}.

> **Declaração:** a interface desenvolvida nesta disciplina é um artefato de aprendizagem de IHC baseado no tema do TCC. Sua inclusão ou implementação no TCC somente ocorrerá se isso for posteriormente decidido pela equipe e pelo orientador.

---

# 8. Levantando possibilidades de interação — sem desenhar ainda

A equipe pode registrar possibilidades para investigação. **Não significa que todas serão implementadas.**

Marque apenas as que parecem plausíveis e explique o objetivo correspondente.

| Possibilidade | Pode fazer sentido? | Objetivo/tarefa que justificaria | Evidência atual |
|---|---|---|---|
| Dashboard/visão geral | sim/não/talvez | {{...}} | {{...}} |
| Configuração/parametrização | sim/não/talvez | {{...}} | {{...}} |
| Entrada/upload/seleção de dados | sim/não/talvez | {{...}} | {{...}} |
| Acompanhamento de processamento | sim/não/talvez | {{...}} | {{...}} |
| Relatório/resultados | sim/não/talvez | {{...}} | {{...}} |
| Histórico com busca/filtros | sim/não/talvez | {{...}} | {{...}} |
| Comparação de resultados | sim/não/talvez | {{...}} | {{...}} |
| Explicabilidade/detalhamento | sim/não/talvez | {{...}} | {{...}} |
| Administração/configurações globais | sim/não/talvez | {{...}} | {{...}} |
| Usuários/perfis/permissões | sim/não/talvez | {{...}} | {{...}} |
| CRUD de entidade do domínio | sim/não/talvez | {{...}} | {{...}} |
| Auditoria/logs | sim/não/talvez | {{...}} | {{...}} |
| Alertas/ocorrências | sim/não/talvez | {{...}} | {{...}} |
| Ajuda/documentação | sim/não/talvez | {{...}} | {{...}} |

> **Atenção:** “login + dashboard + CRUD” não é uma solução universal. Cada padrão deve surgir de uma tarefa real.

---

# 9. Benefícios e ações iniciais

## 9.1 Qual benefício concreto o projeto de IHC pretende oferecer?

| Benefício esperado | Problema/necessidade | Usuário | Status/evidência |
|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} |

## 9.2 Que ações o usuário deverá conseguir realizar?

| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | {{ação}} | {{objetivo}} | alta/média/baixa |

## 9.3 Tecnologias/restrições já definidas no TCC

A tecnologia aparece **agora**, depois do entendimento do uso.

| Tecnologia/restrição | Por que existe | Possível impacto na interação |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

---

# 10. Hipóteses e dúvidas prioritárias

| ID | Hipótese/dúvida | Por que importa | Como poderá ser investigada |
|---|---|---|---|
| H01 | {{...}} | {{...}} | Entrega 2/3/7/... |
| H02 | {{...}} | {{...}} | {{...}} |
| H03 | {{...}} | {{...}} | {{...}} |

Registre em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

---

# 11. Síntese da equipe

| Pergunta | Síntese atual |
|---|---|
| Qual é a contribuição central do TCC? | {{...}} |
| O TCC já previa interface? | {{...}} |
| Quem é o usuário prioritário de IHC? | {{...}} |
| O que ele precisa alcançar? | {{...}} |
| Qual problema/atividade será estudado? | {{...}} |
| Como isso acontece hoje? | {{...}} |
| Qual é o contexto de uso? | {{...}} |
| Que interface/recorte será explorado? | {{...}} |
| Como a interface se relaciona ao TCC? | {{...}} |
| Quais pontos ainda são hipóteses? | {{H01...}} |

### Delimitação

**Dentro do escopo de IHC:** {{...}}  
**Fora do escopo de IHC:** {{...}}  
**Dentro do escopo formal do TCC:** {{...}}  
**Interface da disciplina será implementada no TCC?** não definido / sim / não — {{justificativa, se houver}}

---

# 12. Como esta entrega alimenta as próximas

- **Entrega 2:** verifica mercado, concorrentes e interfaces profissionais representativas.
- **Entrega 3:** detalha perfis e contexto.
- **Entrega 4:** aprofunda situações problemáticas.
- **Entrega 5:** modela tarefas centrais.
- **Entrega 6:** experimenta alternativas em baixa fidelidade.
- **Entrega 7:** investiga hipóteses com dados.
- **Entrega 8:** define restrições e metas de usabilidade.
- **Entregas 9–11:** transformam o recorte em modelo de interação e protótipo.
- **Entregas 12–14:** avaliam a interface construída na disciplina.

A Entrega 1 é uma **fotografia inicial do conhecimento**. Ela pode e deve ser revisada quando surgirem evidências.

---

# 13. Relação com INOVA e comunicação do projeto

Prepare uma explicação de até três frases:

1. **Problema/atividade humana:** {{...}}
2. **Contribuição técnica do TCC:** {{...}}
3. **Como uma pessoa poderia utilizar essa contribuição:** {{...}}

Essa síntese ajuda a apresentar o projeto para público não especializado sem reduzir seu mérito técnico.

---

# Checklist de qualidade

- [ ] Está clara a diferença entre tema do TCC, escopo formal do TCC e escopo de IHC.
- [ ] A equipe declarou se o TCC já previa interface.
- [ ] Se não previa, foi derivado um usuário plausível e um objetivo de uso.
- [ ] A interface de IHC não foi apresentada como obrigação automática do TCC.
- [ ] A contribuição do TCC foi descrita sem começar por tecnologias de implementação.
- [ ] Usuários diretos e stakeholders foram diferenciados.
- [ ] Foram considerados profissionais que configuram, administram, interpretam ou decidem, quando pertinente.
- [ ] Objetivo do usuário não foi confundido com objetivo do projeto.
- [ ] Processo/problema atual foi descrito antes da solução.
- [ ] Existe situação concreta de uso/problema.
- [ ] Contexto físico, social/organizacional, dispositivos e consequências de erro foram considerados.
- [ ] Mercado/alternativas existentes foram levantados inicialmente.
- [ ] Possibilidades como dashboard, relatório, histórico, filtros e CRUD foram tratadas como hipóteses de solução, não como requisitos automáticos.
- [ ] Cada possibilidade de interface tem um objetivo/tarefa que poderia justificá-la.
- [ ] Afirmações relevantes estão marcadas `[F]`, `[H]` ou `[?]`.
- [ ] Hipóteses prioritárias receberam IDs e foram para a rastreabilidade.
- [ ] O recorte de IHC é viável para modelar, prototipar e avaliar no semestre.
- [ ] A equipe consegue explicar problema humano → contribuição computacional → forma de uso.
