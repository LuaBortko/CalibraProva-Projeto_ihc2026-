# Matriz de rastreabilidade de IHC

A matriz deve ser atualizada ao longo do semestre. Ela ajuda a demonstrar que a interface não surgiu arbitrariamente e registra **como o conhecimento da equipe evoluiu**.

Para projetos cujo TCC não previa interface, esta matriz é especialmente importante: deve ficar visível a passagem da **contribuição técnica do TCC** para um **cenário de uso plausível**, e desse cenário para as decisões de interação.

## 1. Derivação do escopo de IHC a partir do TCC

| Elemento | Registro da equipe | Evidência/justificativa | Estado |
|---|---|---|---|
| Tema do TCC | Estrutura e formatação das provas o ENEM: Impacto no desempenho geral dos participantes | TCC | definido |
| Resultado técnico esperado | análise e sistema | TCC | definido |
| O TCC previa interface? | sim | MVP | definido |
| Capacidade/contribuição central | analisar se o formato da prova do ENEM impacta no desempenho dos candidatos | TCC | definido |
| Possíveis beneficiários/stakeholders | docentes e alunos | hipótese | H |
| Usuário escolhido para IHC | docente | pois ele é o único usuário que utiliza o sistema | F |
| Objetivo principal do usuário | Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes. | [H] | [H] |
| Contexto de uso adotado | Uma docente, ao elaborar uma prova para seus estudantes, deseja garnatir que está os avaliando com base nos conhecimentos obtidos nas aulas, por isso, utiliza nosso sistema para identificar o impacto do formato de sua prova no desempenho de seus alunos. | [H] | H  |
| Interface/recorte de IHC | Não | Deriva da contribuição central do TCC, do docente como usuário direto e da necessidade de analisar a prova antes de sua aplicação. | revisada |
| Relação com o TCC | parte prevista | [F] | definido |

> Se o escopo de IHC mudar ao longo do semestre, preserve a decisão anterior no histórico e registre **qual evidência motivou a mudança**.

## 2. Registro de hipóteses e lacunas da Entrega 1

Use esta tabela para itens importantes marcados como `[H]` ou `[?]`. Preserve o histórico: não apague uma hipótese refutada.

| ID | Afirmação / dúvida inicial | Tipo | Por que importa | Como/onde investigar | Evidência obtida | Estado atual | Impacto no projeto |
|---|---|---|---|---|---|---|---|
| H01 | O formato da prova impacta do desempenho do aluno | H | Fundamenta a proposta do TCC, pois é necessário verificar se características estruturais da prova apresentam relação com o desempenho dos candidatos. | TCC | [link repositório tcc](https://github.com/beatrizmanaia26/TCC-DesempenhoEnem) | aberta | alto |
| H02 | Poderá fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos | H | Permite verificar se os resultados obtidos pelo TCC possuem aplicabilidade prática e podem efetivamente apoiar a elaboração e revisão de avaliações. | TCC | MVP | aberta | alto |
| H03 | Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes | H | Permite avaliar se a utilização dos resultados pode contribuir para o processo de ensino, indo além da análise das avaliações em si.| Entrega 7 | Não tem | aberta | alto |
| H04 | Um docente do Estado de São Paulo precisa ter um mínimo de conhecimento tecnológico, utilizaria de acordo com a aplicação de alguma avaliação | H | É importante para compreender o perfil e o contexto de uso do público-alvo, orientando o desenvolvimento de uma interface compatível com suas necessidades e conhecimentos tecnológicos. | Entrega 3 | Não tem | aberta | alto |

## 3. Rastreabilidade entre contribuição técnica, necessidades e artefatos

| ID | Capacidade do TCC utilizada | Necessidade/problema | Persona | Cenário problema | Objetivo/tarefa | HTA/GOMS/CTT | Cenário de interação / signos | MoLIC | Tela(s) Figma | Heurística / problema | Tarefa no teste | Decisão/melhoria |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| R01 | {{ex.: recomendação de otimização}} | {{...}} | {{P01}} | {{C01}} | {{T01}} | {{links}} | {{...}} | {{M01}} | {{F01...}} | {{V01 ou —}} | {{UT01}} | {{...}} |
| R02 |  |  |  |  |  |  |  |  |  |  |  |  |

## 4. Rastreabilidade de padrões de interface

Use esta tabela quando o projeto incorporar padrões como dashboard, relatório, histórico, filtros ou administração. O objetivo é **justificar o padrão**, não apenas listar telas.

| ID da tela/fluxo | Padrão de interface | Objetivo/tarefa que justifica | Informação/ação principal | Evidência de necessidade | Artefatos relacionados |
|---|---|---|---|---|---|
| F01 | dashboard | {{T01}} | {{...}} | {{H01/evidência...}} | {{C01/M01}} |
| F02 | histórico com filtros | {{T02}} | {{...}} | {{...}} | {{...}} |
| F03 | administração/CRUD | {{T03}} | {{...}} | {{...}} | {{...}} |

## 5. Registro de mudanças de escopo

| Data | O que mudou | Evidência/feedback que motivou | Artefatos afetados | Responsável |
|---|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |

## Como usar

- Use identificadores estáveis (`H01`, `P01`, `C01`, `T01`, `M01`, `F01`, `UT01`).
- Quando uma necessidade/problema tiver origem em hipótese da Entrega 1, cite o ID correspondente.
- Em TCC sem interface original, pelo menos uma linha deve mostrar claramente **como uma capacidade técnica chega até uma tarefa de usuário e uma tela/fluxo**.
- Uma linha pode se desdobrar quando um objetivo possui múltiplos caminhos.
- Não force relação inexistente: se algo ainda não foi modelado, marque `PENDENTE`.
- Ao remover uma funcionalidade, registre a decisão em vez de apagar silenciosamente o histórico.
- Dashboard, CRUD, filtros e relatórios só devem aparecer quando houver objetivo/tarefa que os justifique.
