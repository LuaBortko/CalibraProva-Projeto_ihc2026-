# Entrega 2 — Público-alvo e análise de concorrência

*Data:* 26/10/2026 <br>
*Status:* 🟨 em andamento <br>
*Responsabilidade mínima:* cada integrante analisa pelo menos 1 concorrente/interface representativa; a equipe produz síntese comparativa. <br>

## Objetivo da atividade

Compreender soluções do mesmo domínio **e também interfaces familiares ao público-alvo**. O objetivo não é copiar telas, mas identificar convenções, padrões, affordances percebidas, problemas recorrentes, expectativas e oportunidades de design.

> **Concorrente não precisa ser idêntico ao produto.** Pode atuar na mesma área, resolver objetivo semelhante ou disputar a mesma necessidade. Quando não houver concorrente direto, use produtos análogos e softwares que o público já utiliza.

### Para TCCs que não previam interface

Não procure apenas um “concorrente do algoritmo”. Investigue **interfaces profissionais que materializam atividades semelhantes** às que o usuário escolhido precisaria realizar.

Exemplos:

- TCC de banco de dados → consoles de administração, ferramentas para DBA, monitoramento e análise de consultas;
- TCC de LLM/ML → painéis de experimentos, gestão de modelos/datasets, comparação de métricas, revisão de resultados;
- TCC de análise de dados → dashboards, ferramentas de BI, filtros, relatórios e exploração;
- TCC de infraestrutura/API → portais administrativos, observabilidade, logs, gestão de credenciais e uso;
- TCC de cibersegurança → consoles de alertas, triagem, histórico e auditoria.

A pergunta é: **“que convenções esse perfil já conhece para executar tarefas equivalentes?”**

## Entrada obrigatória da Entrega 1

Retome o mapa inicial de alternativas e produtos citado na Entrega 1. Aqui a equipe deixa de trabalhar apenas com impressão inicial e passa a **investigar sistematicamente** cada solução.

| Item citado na Entrega 1 | Tipo | Por que foi citado | Status inicial | Decisão nesta entrega |
|---|---|---|---|---|
| Lucida | análogo | Por ser uma plataforma educacional que oferece recursos de análise do desempenho dos alunos e acompanhamento de seus pontos fortes e dificuldades| F | analisar |
| Keptune | análogo | Estima características dos itens das provas, como dificuldade e discriminação, além de identificar itens psicometricamente fracos. | F | analisar |
| Xcalibre | análogo | A ferramenta estima parâmetros dos itens, como dificuldade, discriminação e métricas estatística, além de disponibilizar relatórios com os resultados obtidos na análise. | F | analisar |
| OpenEduCat | análogo | Disponibiliza uma funcionalidade para analisar itens das prova, como índices de dificuldade e discriminação dos itens e análise dos distratores. | F | A plataforma será descartada da análise, pois, além de ser paga, apresenta diversas funcionalidades que não estão alinhadas ao escopo definido para o projeto. Adicionalmente, não foram encontradas, em fontes de acesso gratuito, capturas de tela das funcionalidades relevantes para a análise proposta. |
| Qstione | análogo | Analisa a qualidade dos itens de uma prova de acordo com a Teoria de Resposta ao Item (TRI) | F | Não foi possível obter acesso à plataforma nem encontrar capturas de tela que permitissem compreender adequadamente seu funcionamento e suas principais interações. |

Se uma hipótese da Entrega 1 for confirmada ou refutada durante esta análise, atualize `H01`, `H02`... em [`../RASTREABILIDADE.md`](../RASTREABILIDADE.md).

## 1. Público-alvo desta análise

O público-alvo desta análise são docentes, perfil priorizado na Entrega 1. A interface em desenvolvimento busca permitir que esses profissionais façam o upload de uma prova, insiram parâmetros quando necessário e visualizem e interpretem métricas relacionadas às características estruturais da avaliação antes de sua aplicação. Essas informações poderão auxiliá-los na análise de possíveis ajustes na prova, buscando reduzir a influência de seu formato no desempenho dos alunos e fazer com que a avaliação mensure, principalmente, os conhecimentos e competências que pretende avaliar.

## 2. Concorrentes diretos/indiretos

### Análise C01 — Lucida

**Autor(a):** Nuno Martins Guilhrmino da Silva — RA:22.126.099-5 
**Tipo:** análogo  
**Link oficial:** {{URL}}  
**Data de acesso:** 27/08/2026

#### Contexto e proposta

A plataforma foi desenvolvida para auxiliar no diagnóstico de dificuldades em sala de aula. Por meio da criação de provas, do escaneamento de folhas de resposta e da disponibilização de métricas detalhadas, como dificuldade e discriminação dos itens, além da identificação de questões com baixo desempenho e distratores efetivos, a Lucida oferece aos docentes informações que auxiliam na identificação dos conteúdos que necessitam de maior atenção e reforço em sala de aula.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Criação de prova | Na plataforma, o professor pode fazer uma prova através do upload de material, além da escolha de alguns parâmetros, como nível de dificuldade desejado, número de questões, entre outros | `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova1.png` `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova2.png` `/workspaces/CalibraProva-Projeto_ihc2026-/assets/02_concorrencia/criacao_prova3.png` `assets/02_concorrencia/criacao_prova4.png ` | {{...}} | 
| Análise e métricas de provas | Após a aplicação de uma prova, o professor pode inserir na plataforma a folha de respostas dos alunos, assim sendo calculadas a dificuldade e fator discriminatório de cada questão, além de apontar questões fracas e distratores efetivos  | `assets/02_concorrencia/analiselucida1.png`| As informações estão bem organizadas e fáceis de compreender | 

#### Experiência do usuário e opiniões

Use avaliações públicas, relatos, estudos, testes próprios ou outra fonte identificável. Não trate opinião isolada como verdade universal.

No momento não existem avaliações públicas da plataforma fora de poucas avaliações positivas presentes no site da plataforma. A experiência do grupo utilizando a ferramenta ocorreu de forma relativamente tranquila, sem grandes problemas técnicos ou confusões em como utilizar do site, apenas um problema com o upload de folha de respostas na etapa de correção de provas. O site contém um visual limpo e minimalista, com poucos botões e funcionalidades bem explicadas, seja na homepage ou dentro da área do usuário.
#### Padrões e tendências percebidos

{{...}}

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| {{...}} | {{...}} | {{...}} |


### Análise C02 — Keptune.ai

**Autor(a):** Beatriz Manaia Lourenço Berto — RA:22.125.060-8  
**Tipo:** análogo  
**Link oficial:** [keptune](https://keptune.ai/)
**Data de acesso:** 27/08/2026

#### Contexto e proposta

A Keptune.ai é uma plataforma de análise de dados que disponibiliza, entre suas ferramentas, recursos para análise de itens de avaliações e exames. A partir do upload de arquivos CSV ou Excel contendo as respostas dos participantes, a ferramenta permite calcular métricas relacionadas aos itens, como dificuldade, discriminação e outros indicadores de desempenho, além de identificar questões potencialmente problemáticas ou com desempenho inadequado que possam necessitar de revisão. Para realizar a análise, o usuário pode fornecer informações sobre os itens e definir os critérios desejados, enquanto a inteligência artificial auxilia no processamento e na geração dos resultados.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Upload de arquivos de respostas dos participantes | Precisa fazer o upload de um arquivo em formato CSV ou Excel, seguindo a estrutura especificada pela plataforma para permitir a realização da análise dos itens | `../assets/02_concorrencia/keptune_upload1.jpeg` , `../assets/02_concorrencia/keptune_upload2.jpeg` | Processo bastante intuitivo. |

| Utilização de inteligência artificial para realizar a análise | Na parte de chat, conseguimos conversar com IA para solicitar análise dos itens (calcular métricas como dificuldade e discriminação, identificando itens que podem precisar de revisão, entre outros)| `../assets/02_concorrencia/keptune_analise1` , `../assets/02_concorrencia/keptune_analise2`  | Plataforma com uma ótimo UX, design bem amigável e rápida em responder |

| Visualização de resultados em tabelas, gráficos e outros formatos | Após solicitar uma análise ou fazer uma pergunta à IA, a ferramenta apresenta os resultados no próprio chat, por meio de tabelas, gráficos e outras visualizações, além de disponibilizá-los na seção lateral de tabelas.| `../assets/02_concorrencia/keptune_analise1` , `../assets/02_concorrencia/keptune_analise2`, `../assets/02_concorrencia/keptune_analise3` , `../assets/02_concorrencia/keptune_analise4` | Boa visualização de resultados, gera diferentes gráficos e formatos com diversas cores e categoria as visualizações entre chat e aba lateral, facilitando a organização, além de sugerir recomendações |

#### Experiência do usuário e opiniões

Use avaliações públicas, relatos, estudos, testes próprios ou outra fonte identificável. Não trate opinião isolada como verdade universal.

<!-- mercado, a experiência dos usuários com o keptune.ai é predominantemente positiva, destacando-se pela facilidade de uso, custo-benefício acessível e agilidade nas respostas da inteligência artificial. A plataforma é projetada para democratizar a análise de dados, permitindo que pessoas sem conhecimento em programação realizem tarefas complexas — como limpeza automatizada de dados, testes estatísticos e geração de gráficos — utilizando apenas comandos em linguagem natural em um chat interativo. A interface é descrita como intuitiva, amigável e visualmente atraente, com uma organização que separa os resultados entre a área de conversação e uma aba lateral de tabelas e subconsultas, facilitando o fluxo de trabalho e a consulta posterior. Um dos grandes diferenciais apontados é o custo: a ferramenta oferece um plano gratuito generoso e planos pagos a partir de US$ 5/mês, sendo considerada mais acessível que concorrentes como o Julius AI, em parte devido à sua eficiente execução de código diretamente no navegador, o que reduz custos computacionais e aumenta a privacidade dos dados. Além disso, a transparência é valorizada, pois o usuário pode ver cada etapa da transformação dos dados e editar o código Python gerado pelas visualizações, o que confere maior controle sobre as análises. Em termos de confiabilidade e segurança, análises de sites como o Scamadviser e Gridinsoft atestam que o keptune.ai é legítimo e confiável, com certificado SSL válido e baixo risco de golpe. No entanto, há alguns pontos de atenção: a principal limitação relatada é a exigência de um formato específico de arquivo (CSV ou Excel) para o upload, o que pode exigir um preparo prévio dos dados e representar uma barreira inicial para usuários menos experientes. Outro aspecto relevante é que a base de usuários e o número de avaliações públicas ainda são reduzidos — em uma plataforma de avaliações, a nota é de 4,5 de 5, mas com apenas 5 avaliações; ferramentas de comparação como o Toolradar indicam que ainda não há avaliações de usuários, e o Scamadviser aponta um baixo volume de visitantes, o que é esperado para um site em fase de crescimento. Além disso, é importante não confundir o keptune.ai com a plataforma Neptune.ai, que é focada em rastreamento de experimentos de machine learning e foi recentemente adquirida pela OpenAI, o que não tem relação com o keptune.ai e pode gerar equívocos. Em comparação direta com o Julius AI, o keptune.ai é apresentado como uma alternativa mais barata e com maior flexibilidade, especialmente por executar o código no navegador do usuário, garantindo mais privacidade e controle. Em resumo, a experiência do usuário com o keptune.ai é amplamente positiva, marcada por uma interface intuitiva, respostas rápidas da IA, recursos abrangentes e custo acessível, sendo uma opção atraente para quem busca análise de dados sem programação. A principal ressalva é a necessidade de adaptar os arquivos ao formato exigido e o fato de a plataforma ainda estar em consolidação, com um número limitado de avaliações públicas disponíveis.

Links de referência:

Site oficial e descrição da ferramenta: https://keptune.ai/

Página de avaliações e recursos: https://keptune.tenereteam.com/

Análise de confiabilidade (Scamadviser): https://www.scamadviser.com/check-website/keptune.ai

Análise de segurança (Gridinsoft): https://pt.gridinsoft.com/domain/keptune.ai

Comparação com Julius AI: https://keptune.ai/articles/julius-ai-alternative -->

#### Padrões e tendências percebidos

{{...}}

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| {{...}} | {{...}} | {{...}} |


### Análise C03 — XCalibre

**Autor(a):** Luana Bortko Rodrigues — RA:24.123.006-9  
**Tipo:** análogo  
**Link oficial:** [xcalibre](https://assess.com/xcalibre/)  
**Data de acesso:** 27/08/2026

#### Contexto e proposta

O Xcalibre é uma ferramenta voltada à análise psicométrica de avaliações, com ênfase na Teoria de Resposta ao Item (TRI). A partir dos dados de respostas de uma avaliação, a ferramenta permite estimar parâmetros relacionados aos itens, como dificuldade e discriminação, além de disponibilizar estatísticas complementares, visualizações e relatórios técnicos que auxiliam na avaliação do desempenho dos itens e da prova como um todo.

#### Funcionalidades relevantes

| Funcionalidade | Como é realizada | Evidência/print | Observação de IHC |
|---|---|---|---|
| Input de arquivo | O usuário insere um arquivo nos formatos .txt ou .dat contendo os dados da avaliação e fornece parâmetros adicionais necessários para que o sistema interprete corretamente a estrutura e o conteúdo do arquivo. | `../assets/02_concorrencia/xcalibraInput1.png` e `../assets/02_concorrencia/xcalibraInput2.png`| A tela para upload e o local para colocar os parâmetros é confuso e tem um layout pouco chamativo |
| Configuração da análise e dos resultados | O usuário define parâmetros relacionados à análise e seleciona as informações e formatos que deseja obter como resultado do processamento. | `../assets/02_concorrencia/xcalibraConf.png` | A interface concentra diversas opções de configuração e utiliza terminologia técnica, exigindo conhecimento prévio do usuário para compreender e selecionar adequadamente os parâmetros. |
| Visualização de estatísticas dos itens | Os resultados da análise são apresentados por meio de tabelas que sintetizam estatísticas dos parâmetros estimados para os itens, como média, desvio-padrão, mínimo e máximo. |  `../assets/02_concorrencia/xcalibraResp.png` | A organização em tabelas facilita a consulta e a comparação dos valores obtidos |
| Visualização gráfica dos resultados | Os resultados também são apresentados por meio de gráficos que representam relações entre os parâmetros obtidos na análise, como dificuldade e discriminação dos itens. |  `../assets/02_concorrencia/xcalibraRespGraf.png` | A representação gráfica complementa os resultados numéricos e facilita a identificação visual de padrões e relações entre os parâmetros analisados. |

#### Experiência do usuário e opiniões

As avaliações encontradas sobre o Xcalibre indicam, de modo geral, uma experiência de uso positiva. Hurtz (2022) caracteriza o software como relativamente amigável ao usuário e destaca sua interface gráfica para configuração das análises e apresentação dos resultados . De forma semelhante, uma revisão anterior de Du Toit (1996) destaca a facilidade de uso e a organização lógica da interface gráfica . Apesar desses aspectos positivos, a utilização da ferramenta envolve conceitos e parâmetros específicos da TRI, o que pode exigir conhecimento prévio do usuário. Além disso, foram encontrados poucos relatos públicos e recentes sobre a experiência de uso do Xcalibre.

- HURTZ, Gregory M. Measurement: Interdisciplinary Research and Perspectives, 2022. Disponível em: https://www.tandfonline.com/doi/full/10.1080/15366367.2022.2026736?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

- GIERL, Mark J.; ACKERMAN, Terry. Software Review: XCALIBRE — Marginal Maximum-Likelihood Estimation Program, Windows Version 1.10. Applied Psychological Measurement, v. 20, n. 3, p. 303–307, 1996. Disponível em: https://assess.com/docs/Xcalibre_1996_review.pdf?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

#### Padrões e tendências percebidos

{{...}}

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| {{...}} | {{...}} | {{...}} |

> Repita a subseção para C02, C03... até atender à quantidade da equipe.

## 3. Softwares que o público-alvo usa no cotidiano

<!--Citar 5 softwares  + genéricos focados em São Paulo -->
Analise interfaces que moldam a expectativa do público, mesmo que não sejam concorrentes.

| Software | Por que o público usa | Padrões relevantes | Prints | O que aprender |
|---|---|---|---|---|
| {{...}} | {{...}} | {{...}} | {{link local}} | {{...}} |

## 3.1 Padrões de interface relevantes ao escopo de IHC

Registre somente padrões encontrados nas soluções analisadas e que possam ter relação com objetivos reais da equipe.

| Padrão observado | Produto(s) | Para qual tarefa serve | Vantagem percebida | Risco/limitação | Aplicável ao nosso escopo? |
|---|---|---|---|---|---|
| dashboard | {{...}} | {{...}} | {{...}} | {{...}} | sim/não/talvez |
| relatório | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |
| histórico + filtros | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |
| administração/CRUD | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |
| comparação de resultados | {{...}} | {{...}} | {{...}} | {{...}} | {{...}} |

## 4. Síntese comparativa da equipe

| Critério | C01 | C02 | C03 | Oportunidade para o projeto |
|---|---|---|---|---|
| Navegação |  |  |  |  |
| Feedback/estado |  |  |  |  |
| Prevenção/recuperação de erro |  |  |  |  |
| Terminologia |  |  |  |  |
| Acessibilidade |  |  |  |  |
| Eficiência |  |  |  |  |

## 5. Recomendações derivadas

Liste recomendações com origem explícita.

- **RC01:** {{recomendação}} — derivada de {{C01/C02/evidência}}.
- **RC02:** {{...}}

## Referências

{{fontes dos produtos, avaliações e literatura}}

## Checklist

- [ ] O mapa inicial de alternativas da Entrega 1 foi revisitado e aprofundado.
- [ ] Hipóteses relevantes sobre mercado/padrões foram atualizadas na rastreabilidade quando surgiram evidências.
- [ ] Há pelo menos uma análise completa por integrante.
- [ ] Cada análise contém prints legíveis da interface.
- [ ] Prints mostram telas/estados relevantes, não apenas logos/homepage.
- [ ] Foram analisados concorrentes e/ou interfaces representativas ao público.
- [ ] Em TCC sem interface original, foram investigadas ferramentas profissionais análogas às atividades do usuário escolhido.
- [ ] Padrões como dashboard, relatório, filtros e CRUD foram analisados como soluções para tarefas, não como requisitos automáticos.
- [ ] Opiniões de UX têm fonte.
- [ ] A síntese compara critérios comuns e produz recomendações.
- [ ] Não há “copiar porque o concorrente faz”; há justificativa de adequação ao público/contexto.
