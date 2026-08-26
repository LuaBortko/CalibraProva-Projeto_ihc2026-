# Entrega 1 — Conhecendo o projeto, o usuário e o problema

**Data:** 19/08/2026

**Status:** 🟩 Concluida

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

## 1.3 Qual é a **capacidade/contribuição central** produzida pelo TCC?

Nosso TCC tem como objetivo analisa como características estruturais dos itens do ENEM, como extensão do enunciado, uso de elementos visuais, nível de formalidade, construção de distratores, análise do tempo médio de resolução e ordem de apresentação das questões, influenciam o desempenho dos participantes, a fim de identificar padrões que contribuem para a compreensão do impacto do formato do exame na avaliação das competências dos candidatos e, a partir dos resultados observados, desenvolvemos uma aplicação que analisa o PDF de uma prova enviada e retorna as métricas e suas respectivas influências no desempenho do estudante."

## 1.4 O que se espera que esteja diferente **para pessoas, organizações ou processos** se essa contribuição for bem-sucedida?

[H] Poderá fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos.

## 1.5 O que é mérito técnico/científico do TCC e o que seria uma possível aplicação prática?

| Mérito/contribuição técnica | Possível aplicação/valor em uso |
|---|---|
| Análise de características estruturais das provas do ENEM entre 2020 e 2025, com exceção da edição de 2021. | Aplicação da metodologia de análise a outras provas identificando características estruturais que possam influenciar o desempenho. |
| Identificação de possíveis relações entre as características estruturais analisadas e o desempenho dos candidatos. | |

---

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
[H] Um docente do Estado de São Paulo precisa ter um mínimo de conhecimento tecnológico, utilizaria de acordo com a aplicação de alguma avaliação, 
(complementar depois de outras entregas)

---

# 3. Entendendo objetivos e atividades

## 3.1 O que o usuário está tentando conseguir no mundo real?

<!-- Não responda “usar o algoritmo”, “clicar no sistema” ou “ver o dashboard”. -->
[H] Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes.

## 3.2 Quais são as atividades mais importantes?

| ID | Atividade/objetivo | Quem realiza | Frequência/criticidade inicial | Status/evidência |
|---|---|---|---|---|
| A01 | Upload de prova estilo ENEM em pdf | Usuário final | De acordo com a aplicação de alguma avaliação | F |
| A02 | Inserção de dados da prova para análise | Usuário final | De acordo com a aplicação de alguma avaliação | F |
| A03 | Exibição das métricas da prova em um dashboard | Sistema | De acordo com o upload de uma prova | F |
| A04 | Análise das métricas extraídas a partir da prova | Usuário final | De acordo com a aplicação de alguma avaliação | F |

## 3.3 Qual atividade parece mais frequente? Por quê?

[F] Upload da prova 

## 3.4 Qual parece mais crítica? Que consequência existe se for mal executada?

[F] A A04 é a mais crítica, pois, caso as métricas apresentadas sejam imprecisas podem levar o docente a uma análise incorreta e, consequentemente, à elaboração de uma avaliação que não mensure adequadamente o conhecimento dos estudantes.

---

# 4. Entendendo o problema ou processo atual

## 4.1 Como essas atividades são realizadas hoje, antes da interface imaginada na disciplina?

[F] Atualmente, os docentes não dispõem de uma ferramenta que os auxilie, antes da aplicação da avaliação, a identificar características relacionadas à estrutura e à elaboração das questões que podem influenciar o desempenho dos alunos. Dessa forma, a análise prévia dessas características depende, principalmente, do conhecimento, da experiência e do repertório do próprio docente.

## 4.2 O que é difícil, demorado, confuso, repetitivo, arriscado ou pouco transparente?

[F] Identificar se a avaliação mede apenas o conhecimento teórico dos alunos, ou seja, se o desempenho da prova não é impactado pelo formato da avaliação.

## 4.3 Que informações o profissional precisa interpretar para tomar decisão?

[F] O docente precisa interpretar as métricas e características estruturais identificadas na prova, como tempo médio, quantidade de palavras, presença de imagens, nível de formalidade, características dos distratores e ordem das questões, além da relação dessas características com o desempenho observada no ENEM. A partir dessas informações, poderá identificar quais características apresentam maior influência sobre o desempenho e decidir quais aspectos da avaliação devem ser ajustados, buscando reduzir a interferência do formato da prova para que o resultado reflita principalmente os conhecimentos e competências avaliados.

## 4.4 O que acontece quando a atividade falha ou quando o resultado é interpretado incorretamente?

[F] Caso o resultado seja incorreto ou seja interpretado de forma equivocada, o professor poderá realizar ajustes na prova com base em parâmetros inadequados. Isso pode resultar em uma avaliação na qual as características do formato tenham ainda mais influência sobre o desempenho dos alunos, fazendo com que a nota seja menos representativa dos conhecimentos e competências que a avaliação deveria mensurar.

## 4.5 Conte uma situação concreta.

Escreva uma pequena narrativa com pessoa, objetivo, atividade, contexto, dificuldade e consequência. **Não descreva ainda a futura solução.**

[H] Uma docente está elaborando uma prova para avaliar os conhecimentos adquiridos pelos estudantes ao longo das aulas. Antes da aplicação, ela deseja garantir que o desempenho dos alunos seja influenciado principalmente pelos conhecimentos e competências que pretende avaliar, e não por características relacionadas ao formato da prova. No entanto, ela tem dificuldade para identificar se aspectos como a extensão dos enunciados, a presença de imagens, a formalidade da linguagem, os distratores e a ordem das questões podem interferir no desempenho dos estudantes. Como consequência, pode aplicar uma avaliação na qual o resultado dos alunos seja influenciado não apenas pelo conhecimento adquirido, mas também pelas características estruturais da própria prova. 

## 4.6 Que evidência existe hoje?

| Evidência/fonte | O que sustenta | Limitação |
|---|---|---|
|DUTRA, J. F.; FIRMINO JUNIOR, J. B.; FERNANDES, D. Y. S. (2022). Fatores que podem interferir no desempenho de estudantes no ENEM: uma revisão sistemática da literatura.| Sustenta que o desempenho dos participantes no ENEM pode estar relacionado a diferentes fatores e apresenta um panorama dos fatores investigados pela literatura. Também permite identificar quais aspectos do desempenho no ENEM já foram estudados. | A revisão não tem como foco específico o impacto das características estruturais ou de formatação das questões sobre o desempenho. |
| CESTARO, D. C.; KLEINKE, M. U.; ALLE, L. F. (2020). Uma análise do desempenho dos participantes e do conteúdo abordado em itens de genética e biologia evolutiva do ENEM: implicações curriculares. | Demonstra que características e conteúdos específicos dos itens do ENEM podem ser analisados em relação ao desempenho dos participantes, evidenciando a possibilidade de investigar o comportamento dos itens da avaliação. | O estudo possui um recorte específico em questões de genética e biologia evolutiva e tem foco nas implicações curriculares, não na influência das características estruturais ou de formatação dos itens. |
| LOPES, J. C.; RUBINI, G.; MASSUNAGA, M. O. S.; BARROSO, M. F. (2015). Estudo das questões de Física da prova de Ciências da Natureza do ENEM. | Demonstra a existência de pesquisas que analisam as questões do ENEM considerando suas características e o desempenho dos participantes, contribuindo para a compreensão de como os itens podem ser investigados. | O estudo é direcionado às questões de Física da área de Ciências da Natureza e não investiga especificamente o conjunto de características estruturais analisadas pelo TCC. |

---

# 5. Entendendo o contexto de uso

## 5.1 Onde e em quais situações a interação poderia ocorrer?

[F] De acordo com a aplicação de alguma avaliação.

## 5.2 Em quais dispositivos/equipamentos?

[F] Computadores.

## 5.3 Existem condições físas relevantes?

<!-- Considere iluminação, ruído, mobilidade, conexão, privacidade, uso compartilhado, interrupções, pressão de tempo etc.
-->
[F] Será necessário um computador e conexão com a internet e o docente ser do Estado de São Paulo, pois os dados do ENEM que utilizaremos como base para analisar as provas por meio do sistema consideram o recorte geográfico desse Estado.

## 5.4 Existem fatores sociais ou organizacionais?
<!--
Considere papéis, chefias, equipes, permissões, aprovação, responsabilidade profissional, auditoria, turnos e colaboração.
-->

[F] Não.

## 5.5 Existe necessidade de histórico, rastreabilidade ou auditoria?

[F] Não.

## 5.6 Um erro pode produzir consequência relevante? Qual?

[F] Sim, pois caso as métricas apresentadas pelo nosso sistema sejam imprecisas, podem levar o docente a uma análise incorreta e, consequentemente, à elaboração de uma avaliação que não mensure adequadamente o conhecimento dos estudantes.

---

# 6. Entendendo mercado e alternativas existentes

> Nesta entrega faça apenas um **levantamento inicial**. A análise aprofundada ocorre na Entrega 2.

## 6.1 Como pessoas resolvem problemas semelhantes hoje?

| Alternativa atual | Quem usa | Para quê | Status/evidência |
|---|---|---|---|
| da experiência e do repertório do próprio docente | docente | identificar, antes da aplicação da avaliação, características relacionadas à estrutura e à elaboração das questões que podem influenciar o desempenho dos alunos | [F] |
| utilizar ferramentas após a aplicação da prova que avaliem o desempenho dos alunos | docentes | identificar características relacionadas à estrutura e à elaboração das questões que podem influenciam o desempenho dos alunos | [F] |

## 6.2 Existem produtos que atuam na mesma área, mesmo sem serem equivalentes ao TCC?

[F] Sim. Foram identificados produtos que atuam na área de avaliação educacional e análise de questões, embora não sejam equivalentes ao nosso TCC. Entre eles estão Lucida, Xcalibre, Keptune Item Analysis e OpenEduCat Quiz. Essas ferramentas oferecem funcionalidades relacionadas à criação, aplicação, correção, gerenciamento e/ou análise de avaliações.

A principal diferença em relação ao nosso MVP está no momento e objetivo da análise: enquanto essas soluções possuem forte foco na criação, aplicação ou análise dos resultados das avaliações, nosso MVP busca realizar uma análise preventiva, antes da aplicação da prova, a partir de um PDF, utilizando características estruturais dos itens e as relações observadas na análise do ENEM para auxiliar o docente na decisão sobre possíveis ajustes na avaliação.

## 6.3 Quais interfaces profissionais esse público já conhece?

[F] O público já pode estar familiarizado com:

- Lucida → plataforma educacional / dashboard de avaliação e desempenho
  
- Xcalibre → interface de análise psicométrica e TRI
  
- Keptune Item Analysis → interface de análise de itens e métricas de avaliação
  
- OpenEduCat Quiz → plataforma educacional para criação e gerenciamento de avaliações

- Qstione → plataforma educional para correção automática e análise de métricas de avaliação
  
  
<!--Exemplos possíveis: ferramentas de banco, IDEs, consoles de nuvem, dashboards, plataformas de dados, ferramentas de monitoramento, painéis de IA, sistemas administrativos.-->


## 6.4 O que essas soluções parecem fazer bem?

[F] 

A Lucida parece fazer bem a integração de diferentes etapas do processo de avaliação em uma única plataforma. A ferramenta oferece recursos para criação de provas e simulados, correção das avaliações, análise do desempenho dos alunos e acompanhamento de seus pontos fortes e dificuldades. Destaca-se também pela apresentação de métricas por questão e por aluno, permitindo identificar questões potencialmente problemáticas, níveis de dificuldade e conteúdos que precisam ser reforçados. Dessa forma, a plataforma centraliza informações da avaliação e do desempenho dos estudantes, auxiliando o docente na interpretação dos resultados e na tomada de decisões pedagógicas.

A Keptune.ai é uma plataforma voltada à análise psicométrica de avaliações. A partir do upload de um arquivo CSV contendo as respostas dos participantes, a plataforma realiza, com auxílio de inteligência artificial, os cálculos necessários para estimar características dos itens, como dificuldade e discriminação, além de identificar itens psicometricamente fracos.

O XCalibre é uma plataforma destinada à análise de avaliações com base na Teoria de Resposta ao Item (TRI). A partir dos resultados de uma prova, a ferramenta estima parâmetros dos itens, como dificuldade, discriminação e p-value, além de disponibilizar relatórios com os resultados obtidos na análise.

Qstione é uma plataforma que disponibiliza ferramentas para a análise da qualidade de avaliações. Após a aplicação de uma prova elaborada na própria plataforma, seus resultados podem ser analisados segundo critérios baseados na Teoria de Resposta ao Item (TRI), permitindo avaliar a qualidade dos itens e obter uma medida geral do desempenho dos alunos.

OpenEduCat é uma plataforma que oferece diversas ferramentas para a administração de instituições de ensino. Além de funcionalidades relacionadas a aspectos logísticos, como transporte e gerenciamento de funcionários, a plataforma permite o gerenciamento de informações acadêmicas, como notas e dados dos estudantes. Também é disponibilizada uma funcionalidade para análise de itens de prova. Por meio da digitalização das avaliações utilizando OMR, após a aplicação da prova, a plataforma apresenta índices de dificuldade e discriminação dos itens, além de uma análise dos distratores, indicando quais alternativas incorretas foram mais selecionadas pelos alunos.

## 6.5 O que parecem fazer mal, dificultar ou não atender?

[F] Em relação ao problema específico do nosso MVP, a principal limitação dessas soluções é que não têm como foco a análise preventiva das características estruturais de uma avaliação antes de sua aplicação, utilizando como referência relações observadas no desempenho dos candidatos no ENEM. As ferramentas analisadas concentram-se principalmente na criação, aplicação, correção ou análise psicométrica das avaliações a partir dos resultados obtidos pelos participantes. Dessa forma, não identificamos, entre as soluções analisadas, uma ferramenta que tenha como objetivo específico avaliar previamente características como extensão dos enunciados, presença de imagens, nível de formalidade, características dos distratores e ordem das questões, relacionando-as ao possível impacto no desempenho dos estudantes.

ASSESSMENT SYSTEMS CORPORATION. Xcalibre: Item Response Theory Analysis Software, Designed to Make IRT Easier. [S. l.], 2026. Disponível em: https://assess.com/xcalibre/. Acesso em: 23 ago. 2026.

KEPTUNE.AI. Item Analysis Calculator for Tests and Exams. [S. l.], 2026. Disponível em: https://keptune.ai/tools/item-analysis. Acesso em: 23 ago. 2026.

OPENEDUCAT. Quiz & Assessment Software. [S. l.], [s. d.]. Disponível em: https://openeducat.org/feature-quiz/. Acesso em: 23 ago. 2026.

LUCIDA. Lucida: crie atividades com IA em segundos. [S. l.], [s. d.]. Disponível em: https://lucidaexam.com/. Acesso em: 23 ago. 2026.

## 6.6 Que padrões de interface ou vocabulário parecem familiares a esse público?

[F] Os padrões identificados foram:
1-A maioria das ferramentas utilizam o mesmo ícone para simbolizar o upload de uma prova/material, já o texto após esse ícone varia, por exemplo: "Upload CSV or Excel files", "Arraste e solte seu material. Faça upload de múltiplos arquivos PDF, DOC, DOCX ou TXT. Limite até aproximadamente 350.000 palavras no total.", entre outros.

2-Possibilidade de exportar os resultados para diferentes tipos de arquivo como excel e word.

3-Mostrar os resultados das analises com diferentes métricas (gráficos de pizza, coluna, porcentagem, entre outros) e com cores distintas.

---

# 7. Derivando o escopo de IHC da disciplina

## 7.1 Escolha o caminho do projeto

### Caminho A — TCC já possui interface

Explique qual parte da interface será usada como recorte da disciplina e por que esse fluxo é relevante.

Como a interface proposta possui um escopo reduzido, o fluxo completo será considerado como recorte da disciplina. Contemplando o envio de uma prova com estrutura semelhante à do ENEM, a análise de suas características estruturais e a apresentação de métricas associadas às relações observadas entre essas características e o desempenho dos candidatos no ENEM. Como a análise realizada no TCC possui um recorte geográfico específico para o estado de São Paulo, os resultados obtidos são inicialmente aplicáveis a esse contexto. Dessa forma, o público priorizado para a utilização da interface será composto por docentes que atuam no estado de São Paulo. A partir dos resultados, o docente poderá identificar características do formato da prova que podem estar relacionadas ao desempenho dos estudantes, auxiliando na decisão sobre possíveis ajustes na avaliação.

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

Um docente do Estado de São Paulo com acesso a um computador, conexão a internet e com o minimo letramento digital.

**Por que esse perfil foi escolhido?** 

Seria o perfil do nosso usuário final.

## 7.3 Qual objetivo desse usuário será priorizado?

Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes.

## 7.4 Que interface será explorada na disciplina?
<!--
Complete:
> **Para fins da disciplina de IHC, será projetada uma interface que permita a `{{perfil}}` utilizar `{{capacidade/resultado do TCC}}` para `{{objetivo}}`, no contexto de `{{situação}}`.**
-->
Para fins da disciplina de IHC, será projetada uma interface que permita ao docente utilizar métricas relacionadas ao possível impacto das características estruturais das provas no desempenho dos estudantes para apoiar a elaboração de avaliações que representem de forma mais adequada seus conhecimentos, no contexto do processo de ensino e avaliação.

## 7.5 Qual é a relação dessa interface com o TCC?

- [X] Já fazia parte do TCC.
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
| Dashboard/visão geral | sim | Apresentar uma visão geral das métricas extraídas da prova e de suas possíveis relações com o desempenho dos estudantes, utilizando diferentes formatos de apresentação de dados, tanto quantitativos quanto visuais, incluindo diversos tipos de gráficos.  | Tem evidência. |
| Configuração/parametrização | não | | Tem evidência.  |
| Entrada/upload/seleção de dados | sim |Permitir ao docente inserir uma prova para que suas características estruturais sejam automaticamente extraídas e analisadas pelo sistema, além de possibilitar a inserção manual de dados específicos como parâmetros para análise. | Tem evidência.  |
| Acompanhamento de processamento | não |  | Tem evidência.  |
| Relatório/resultados | não |  | Tem evidência.  |
| Histórico com busca/filtros | não |  | Tem evidência.  |
| Comparação de resultados | não |  | Tem evidência.  |
| Explicabilidade/detalhamento | sim | Permitir ao docente compreender cada métrica apresentada, sua interpretação e sua possível relação com o desempenho dos estudantes por meio de um dashboard organizado e didático. | Não tem evidência no momento.  |
| Administração/configurações globais | não |  | Tem evidência.  |
| Usuários/perfis/permissões | não |  | Tem evidência.  |
| CRUD de entidade do domínio | não |  | Tem evidência.  |
| Auditoria/logs | não |  | Tem evidência.  |
| Alertas/ocorrências | não |  | Tem evidência.  |
| Ajuda/documentação | não |  | Tem evidência.  |

> **Atenção:** “login + dashboard + CRUD” não é uma solução universal. Cada padrão deve surgir de uma tarefa real.

---

# 9. Benefícios e ações iniciais

## 9.1 Qual benefício concreto o projeto de IHC pretende oferecer?

| Benefício esperado | Problema/necessidade | Usuário | Status/evidência |
|---|---|---|---|
| Avaliar se características estruturais específicas da prova poderiam impactar o desempenho dos alunos | A possibilidade de o formato da prova impactar no desempenho dos estudantes | Docentes | F |

## 9.2 Que ações o usuário deverá conseguir realizar?

| ID | O usuário precisa conseguir... | Para alcançar... | Prioridade inicial |
|---|---|---|---|
| F01 | Fazer upload de prova múltipla escolha em pdf | Ter um material para a análise | alta |
| F02 | Fazer a inserção de dados da prova para análise | Sistema conhecer os parâmetros da prova | alta |
| F03 | Analisar as métricas extraídas a partir da prova(visualização gráfica, indicadores quantitativos, análise de correlação entre variáveis estruturais e desempenho) | Avaliação do possível impacto do formato da prova no desempenho dos alunos | alta |

<!--| F01 | {{ação}} | {{objetivo}} | alta/média/baixa | -->

## 9.3 Tecnologias/restrições já definidas no TCC

A tecnologia aparece **agora**, depois do entendimento do uso.

| Tecnologia/restrição | Por que existe | Possível impacto na interação |
|---|---|---|
| Python | Análise de dados | latência |
| Vue | Desenvolvimento da aplicação web | - |
| PyMuPDF | Extração dos textos dos enunciados e da existência de imagens| latência |
| S-BERT | Analise dos distratores | latência |
| XLM-roBERTa | Analise da formalidade | latência |

---

# 10. Hipóteses e dúvidas prioritárias

| ID | Hipótese/dúvida | Por que importa | Como poderá ser investigada |
|---|---|---|---|
| H01 | O formato da prova impacta do desempenho do aluno | Fundamenta a proposta do TCC, pois é necessário verificar se características estruturais da prova apresentam relação com o desempenho dos candidatos. | TCC |
| H02 | Poderá fornecer subsídios para que professores e elaboradores de provas avaliem características estruturais de suas avaliações, contribuindo para ajustes que tornem o nível de dificuldade mais adequado aos objetivos propostos | Permite verificar se os resultados obtidos pelo TCC possuem aplicabilidade prática e podem efetivamente apoiar a elaboração e revisão de avaliações. | TCC |
| H03 | Aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes | Permite avaliar se a utilização dos resultados pode contribuir para o processo de ensino, indo além da análise das avaliações em si. | Entrega 7 |
| H04 | Um docente do Estado de São Paulo precisa ter um mínimo de conhecimento tecnológico, utilizaria de acordo com a aplicação de alguma avaliação | É importante para compreender o perfil e o contexto de uso do público-alvo, orientando o desenvolvimento de uma interface compatível com suas necessidades e conhecimentos tecnológicos. | Entrega 3 |


Registre em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

---

# 11. Síntese da equipe

| Pergunta | Síntese atual |
|---|---|
| Qual é a contribuição central do TCC? | Analisar se o formato da prova do ENEM impacta no desempenho dos candidatos |
| O TCC já previa interface? | Sim |
| Quem é o usuário prioritário de IHC? | Docentes |
| O que ele precisa alcançar? | Melhor as aulas |
| Qual problema/atividade será estudado? | Melhoria da elaboração de provas |
| Como isso acontece hoje? | não achamos ferramentas que identifiquem previamente características da prova que podem influenciar o desempenho dos alunos, dependendo principalmente do conhecimento e experiência de cada docente | 
| Qual é o contexto de uso? | De acordo com a elaboração das avaliações |
| Que interface/recorte será explorado? | Não terá recorte |
| Como a interface se relaciona ao TCC? | Representa o MVP do TCC |
| Quais pontos ainda são hipóteses? | H01, H02, H03, H04 |

### Delimitação

**Dentro do escopo de IHC:** o MVP do TCC, englobando o desenvolvimento e avaliação da interface que permite ao docente fazer upload de uma prova, inserir parâmetros quando necessário e visualizar e interpretar as métricas relacionadas às características estruturais da avaliação.
**Fora do escopo de IHC:** Nada
**Dentro do escopo formal do TCC:** Tudo
**Interface da disciplina será implementada no TCC?** Sim

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

1. **Problema/atividade humana:** Elaborar avaliações que representem adequadamente o conhecimento dos estudantes.
2. **Contribuição técnica do TCC:** Identificar possíveis relações entre características do formato das provas do ENEM e o desempenho dos candidatos.
3. **Como uma pessoa poderia utilizar essa contribuição:** Utilizar essas relações como apoio para revisar e aprimorar a estrutura de futuras avaliações.

Essa síntese ajuda a apresentar o projeto para público não especializado sem reduzir seu mérito técnico.

---

# Checklist de qualidade 
<!-- REVISAR DPS -->

- [x] Está clara a diferença entre tema do TCC, escopo formal do TCC e escopo de IHC.
- [x] A equipe declarou se o TCC já previa interface.
- [ ] Se não previa, foi derivado um usuário plausível e um objetivo de uso.
- [x] A interface de IHC não foi apresentada como obrigação automática do TCC.
- [x] A contribuição do TCC foi descrita sem começar por tecnologias de implementação.
- [x] Usuários diretos e stakeholders foram diferenciados.
- [x] Foram considerados profissionais que configuram, administram, interpretam ou decidem, quando pertinente.
- [x] Objetivo do usuário não foi confundido com objetivo do projeto.
- [x] Processo/problema atual foi descrito antes da solução.
- [x] Existe situação concreta de uso/problema.
- [x] Contexto físico, social/organizacional, dispositivos e consequências de erro foram considerados.
- [x] Mercado/alternativas existentes foram levantados inicialmente.
- [x] Possibilidades como dashboard, relatório, histórico, filtros e CRUD foram tratadas como hipóteses de solução, não como requisitos automáticos.
- [x] Cada possibilidade de interface tem um objetivo/tarefa que poderia justificá-la.
- [x] Afirmações relevantes estão marcadas `[F]`, `[H]` ou `[?]`.
- [x] Hipóteses prioritárias receberam IDs e foram para a rastreabilidade.
- [x] O recorte de IHC é viável para modelar, prototipar e avaliar no semestre.
- [x] A equipe consegue explicar problema humano → contribuição computacional → forma de uso.
