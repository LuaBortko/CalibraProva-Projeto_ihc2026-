# Entrega 5 — Análise de tarefas: HTA, GOMS e CTT

**Data:** 13/09/2026 
**Status:** 🟨 Em andamento 
**Responsabilidade:** cada integrante modela pelo menos 1 HTA, 1 GOMS e 1 CTT. As três técnicas podem abordar a mesma funcionalidade ou funcionalidades distintas, conforme a orientação da disciplina.

## Objetivo da atividade

Modelar tarefas importantes sob perspectivas complementares: decomposição hierárquica (HTA), estrutura de metas/métodos/operações (GOMS) e relações temporais entre tarefas (CTT). O diagrama deve ser acompanhado de interpretação textual.

## Para projetos cujo TCC não previa interface

Modele **tarefas humanas relacionadas ao uso da contribuição técnica**, e não a implementação interna do algoritmo. Exemplos de boas tarefas para análise:

- investigar uma consulta de baixo desempenho;
- configurar uma análise e selecionar parâmetros;
- submeter um dataset e verificar sua validade;
- acompanhar uma execução demorada;
- comparar dois resultados/modelos;
- interpretar uma recomendação e decidir se a aceita;
- localizar uma execução anterior usando busca/filtros;
- gerar e compartilhar um relatório;
- administrar papéis/permissões quando isso for parte do trabalho real;
- revisar um alerta e registrar uma decisão.

Um CRUD pode gerar tarefas relevantes, mas “cadastrar usuário” só merece modelagem se tiver significado no domínio (papéis, validações, riscos, permissões, dependências).

## Seleção das tarefas

| ID | Tarefa | Persona/cenário de origem | Frequência/criticidade | Autor responsável |
|---|---|---|---|---|
| T01 | Analisar a prova | P1/P2/P3 e C02 | Alta - várias vezes por semestre, sempre que tiver alguma prova a ser aplicada | Beatriz |
| T02 | Analisar histórico de provas | P1/P2/P3 e C01 | Média - No começo ou finais de semestre | Luana |
| T03 | Gerar novas questões baseadas em provas já elaboradas | P1/P2/P3 e C03 | Média - XXXXX | Nuno |

<!--TAREFAS COMPLEXAS A PONTO DE SEREM MODELADAS

quando for definir obj da entrega 5;
-tem q combinar com grupo os objetivos q maparemos a tarefa:tem q ter a tarefa
ex:

1-obj analisa a prova(o padrao) cenario problema bia

2-obj analsia historico de provas (ja analisadas, dashboard de td prova ja analisda, tem comeco meio e fim, é objetivo cenario problema lu

3-tem conj de prova, uso p faze analise estatisitica e historica de periodo, dado perido faze analise estatisitcia e peço p ia produzir mais x questoes objetivo cenario problema nuno

outra opcao:
-comparar analises de provas (analisa dashboard de td rova q ele analisou,
-relatorios personalizados (?) 
-avaliar escrita???

-usa tabela do 1, parte de filtro e tal  p ajuda se quiser


tarefa n eh upload analise e analisa resultado eh PASSO de 1 tarefa, ta errado, como sei se eh passo ou tarefa?

obj tarefa msm pega do d cenario problema
identifica obj é consdierar ex usuario acoreda, obj faze upload ve se faz sentdio a pessoa acorda vou usa e faze yploiad

ver se obj final de us sistema eh faze upload, as tarefas sao os objetivos 
tcc todo, o sistema q previmos eh o obj de 1 pessoa so


NA MODELAGEM DE HTA GOMS E CTT TEM Q USA TODOS OS RECURSOS DA TECNICA


<!-- TAREFAS:ANALISAR PROVA

esses passos sao de 1 objetivo: analisar prova

1-upload de arquivo contendo prova
  -maneiras de fazer upload?
  -formatos aceitos?
  -padrões que prova precisa ter para ser analisada?
  -...

2-inserção de dados da prova de maneira manual
  -tem difernetes maneiras de ser inserida?
  -...

3-análise do dashboard com métricas da prova
  -maneiras de analisar dashboard?

4-download do dashboard
  -em que formatos?
  -quantas maneiras de fazer download?
-->

> Priorize tarefas necessárias para que o usuário alcance objetivos centrais. Não desperdice a modelagem em ações triviais isoladas, como “clicar em login”, se o objetivo relevante é maior. Da mesma forma, não modele o funcionamento interno do algoritmo como se fosse uma tarefa humana.

---

<!--
tarefas tem q ter complexidade:

DECIDIR 3 OBJETIVOS MAIS IMPORTANTES DO PROJETO
-isso tem haver com duvida q tirmos ontem cm plinio?
-ja q tem 4 tarefas a gnt escolhe 1 objetivo p duplica ent?

ex goms 2 metodos
tem q expandir msm q n seja oq faremoas d vdd , usa emtodo em sua completudw

goms
go
g1 
op
op
op

g2
metodo 1 
regra selecao 
 op 
 op

  g3
  metodo sleecao 2
  op
  op

metodo de selecao sao 2 maneiras de faze msm coisa 
 se no projeto n precisa
 pode traze cois nova q nnc apareceu no texto p treina o metodo
-->

## HTA — T01 Analisar a prova

**Autor(a):** Beatriz Manaia Lourenço Berto — 22.125.060-8
contexto mais comum eh o da bia no passado la 

### Descrição da tarefa

<!--{{objetivo, ponto de início, conclusão esperada, contexto}}-->

- Objetivo: Permitir que o docente envie uma prova em um dos formatos aceitos pelo sistema para que suas características estruturais sejam extraídas e analisadas, possibilitando a visualização de métricas que apoiem a tomada de decisão sobre possíveis ajustes na avaliação.

- Ponto de início: O docente possui uma prova pronta para análise, salva no dispositivo que será utilizado para acessar o sistema, em um dos formatos suportados.

- Conclusão esperada: A prova foi carregada com sucesso no sistema e as métricas referentes às suas características estruturais estão disponíveis para consulta.

- Contexto: uploCerca de duas semanas antes da aplicação das avaliações, durante o período de preparação e revisão das provas, em ambiente adequado de trabalho, como a instituição de ensino, escritório ou casa, com acesso a computador, recursos digitais e à internet.

### Diagrama

![HTA T01](../assets/05_tarefas/hta_t01.svg)

### Decomposição e planos

| ID | Objetivo/operação | Plano/ordem | Problema ou decisão de design observada |
|---|---|---|---|
| 0 | (objetivo) Analisar prova | 1 > 2 > 3 > 4  | {{...}} |
| 1 | (sub objetivo) Fazer upload de prova | 1.1 > 1.2  | {{...}} |
| 1.1 | (operação) Selecionar arquivo em formato válido (PDF) | 1.1 pode ser feita antes ou depois da 1.2 | {{...}} |
| 1.2 | (operação) Enviar arquivo em formato válido(PDF) | 1.2 pode ser feita antes ou depois da 1.1 | {{...}} |
| 2 | (sub objetivo) Inserir de dados da prova | 2.1 / 2.2  | {{...}} |
| 2.1 | (operação) | (decisão) Docente deve escolher entre 2.1 e 2.2 | {{...}} |
| 2.2 | (operação) | (decisão) Docente deve escolher entre 2.1 e 2.2  | {{...}} |
| 3 | (sub objetivo) Analisar dados do Dashboard | 3.1 + 3.2 | {{...}} |
| 3.1 | (operação) Visualizar  Tabelas e gráficos das métricas  |  | {{...}} |
| 3.2 | (operação) Ler  detalhamento das métrica |  | {{...}} |
| 4 | (sub objetivo) Exportar Dashboard | 4.1 + 4.2 + 4.3  | {{...}} |
| 4.1 | (operação) Exportar em PDF| Pode fazer 4.1 ou 4.2 ou 4.3 em paralelo | {{...}} |
| 4.2 | (operação) Exportar em Excel | Pode fazer 4.1 ou 4.2 ou 4.3 em paralelo | {{...}} |
| 4.3 | (operação) Exportar em CSV| Pode fazer 4.1 ou 4.2 ou 4.3 em paralelo | {{...}} |

<!--ACHAM Q COLOCA 2.1 TB? ELE FLO P COLOCA OPERACAO MAS AI N SEI OQ COLOCA EM ORDEM 
>
**Verificação do HTA:**

- O objetivo 0 representa uma meta do usuário?
- As subtarefas são necessárias e suficientes?
- Os **planos** indicam ordem, alternativa, repetição ou condição?
- A decomposição parou em nível útil para projeto de interação?

---

## GOMS — T02 Analisar a prova

**Autor(a):** {{nome — matrícula}}

### Goal

`G0: {{meta do usuário}}`

### Métodos, operadores e regras de seleção

- **Method M1:** {{...}}
  - Operators: {{perceber, apontar, clicar, digitar, decidir... conforme o nível adotado}}
- **Method M2:** {{...}}
  - Operators: {{...}}
- **Selection Rule SR1:** usar M1 quando {{condição}}; usar M2 quando {{condição}}.

> Não chame qualquer passo de “método”. Em GOMS, métodos são sequências alternativas capazes de atingir uma meta; regras de seleção explicam quando escolher entre eles.

---

## CTT — T03  Analisar a prova

**Autor(a):** {{nome — matrícula}}

### Descrição

{{...}}

### Diagrama

![CTT T03](../assets/05_tarefas/ctt_t03.svg)

### Legenda e relações temporais usadas

| Operador/relação | Significado no diagrama | Exemplo no modelo |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

Identifique, quando aplicável, tarefas de usuário, sistema, interação e tarefas abstratas. Verifique se concorrência, escolha, habilitação, desabilitação e repetição estão representadas corretamente segundo a notação adotada em aula.


## HTA — T01 Analisar histórico de provas

**Autor(a):** {{nome — matrícula}}


### Descrição da tarefa

{{objetivo, ponto de início, conclusão esperada, contexto}}

### Diagrama

![HTA T01](../assets/05_tarefas/hta_t01.svg)

### Decomposição e planos

| ID | Objetivo/operação | Plano/ordem | Problema ou decisão de design observada |
|---|---|---|---|
| 0 | {{objetivo principal}} | {{1 }} 2 > 3 / 1 ou 2 etc.> | {{...}} |

**Verificação do HTA:**

- O objetivo 0 representa uma meta do usuário?
- As subtarefas são necessárias e suficientes?
- Os **planos** indicam ordem, alternativa, repetição ou condição?
- A decomposição parou em nível útil para projeto de interação?

---

## GOMS — T02 Analisar histórico de provas

**Autor(a):** {{nome — matrícula}}

### Goal

`G0: {{meta do usuário}}`

### Métodos, operadores e regras de seleção

- **Method M1:** {{...}}
  - Operators: {{perceber, apontar, clicar, digitar, decidir... conforme o nível adotado}}
- **Method M2:** {{...}}
  - Operators: {{...}}
- **Selection Rule SR1:** usar M1 quando {{condição}}; usar M2 quando {{condição}}.

> Não chame qualquer passo de “método”. Em GOMS, métodos são sequências alternativas capazes de atingir uma meta; regras de seleção explicam quando escolher entre eles.

---

## CTT — T03 Analisar histórico de provas

**Autor(a):** {{nome — matrícula}}

### Descrição

{{...}}

### Diagrama

![CTT T03](../assets/05_tarefas/ctt_t03.svg)

### Legenda e relações temporais usadas

| Operador/relação | Significado no diagrama | Exemplo no modelo |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

Identifique, quando aplicável, tarefas de usuário, sistema, interação e tarefas abstratas. Verifique se concorrência, escolha, habilitação, desabilitação e repetição estão representadas corretamente segundo a notação adotada em aula.


## HTA — T01 Gerar novas questões baseadas em provas já elaboradas

**Autor(a):** {{nome — matrícula}}


### Descrição da tarefa

{{objetivo, ponto de início, conclusão esperada, contexto}}

### Diagrama

![HTA T01](../assets/05_tarefas/hta_t01.svg)

### Decomposição e planos

| ID | Objetivo/operação | Plano/ordem | Problema ou decisão de design observada |
|---|---|---|---|
| 0 | {{objetivo principal}} | {{1 }} 2 > 3 / 1 ou 2 etc.> | {{...}} |

**Verificação do HTA:**

- O objetivo 0 representa uma meta do usuário?
- As subtarefas são necessárias e suficientes?
- Os **planos** indicam ordem, alternativa, repetição ou condição?
- A decomposição parou em nível útil para projeto de interação?

---

## GOMS — T02 Gerar novas questões baseadas em provas já elaboradas

**Autor(a):** {{nome — matrícula}}

### Goal

`G0: {{meta do usuário}}`

### Métodos, operadores e regras de seleção

- **Method M1:** {{...}}
  - Operators: {{perceber, apontar, clicar, digitar, decidir... conforme o nível adotado}}
- **Method M2:** {{...}}
  - Operators: {{...}}
- **Selection Rule SR1:** usar M1 quando {{condição}}; usar M2 quando {{condição}}.

> Não chame qualquer passo de “método”. Em GOMS, métodos são sequências alternativas capazes de atingir uma meta; regras de seleção explicam quando escolher entre eles.

---

## CTT — T03 Gerar novas questões baseadas em provas já elaboradas

**Autor(a):** {{nome — matrícula}}

### Descrição

{{...}}

### Diagrama

![CTT T03](../assets/05_tarefas/ctt_t03.svg)

### Legenda e relações temporais usadas

| Operador/relação | Significado no diagrama | Exemplo no modelo |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

Identifique, quando aplicável, tarefas de usuário, sistema, interação e tarefas abstratas. Verifique se concorrência, escolha, habilitação, desabilitação e repetição estão representadas corretamente segundo a notação adotada em aula.




**Autor(a):** {{nome — matrícula}}

### Descrição

{{...}}

### Diagrama

![CTT T03](../assets/05_tarefas/ctt_t03.svg)

### Legenda e relações temporais usadas

| Operador/relação | Significado no diagrama | Exemplo no modelo |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

Identifique, quando aplicável, tarefas de usuário, sistema, interação e tarefas abstratas. Verifique se concorrência, escolha, habilitação, desabilitação e repetição estão representadas corretamente segundo a notação adotada em aula.

---

## Síntese da equipe

Quais problemas de interação, oportunidades e requisitos apareceram a partir das modelagens? Quais tarefas irão para o protótipo e para o teste de usabilidade?

## Checklist

- [ ] Cada integrante produziu ao menos 1 HTA, 1 GOMS e 1 CTT.
- [ ] Cada artefato identifica autor e tarefa.
- [ ] Diagramas são legíveis e possuem fonte editável quando possível.
- [ ] HTA contém planos, não apenas árvore de tópicos.
- [ ] GOMS distingue Goals, Operators, Methods e Selection Rules.
- [ ] CTT usa operadores temporais e tipos de tarefa coerentes.
- [ ] Há texto explicando cada diagrama.
- [ ] Tarefas estão ligadas a cenários/personas na rastreabilidade.
- [ ] Em TCC técnico, as tarefas descrevem o que a pessoa faz com a contribuição/resultados, não passos internos do código.
- [ ] CRUDs, relatórios, filtros e atividades administrativas foram escolhidos por relevância ao objetivo do usuário.
