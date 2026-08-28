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

A experiência com o keptune.ai é, no geral, bem positiva. O que mais se destaca é a facilidade de usar, o preço acessível e a rapidez da IA para responder. A plataforma foi feita pra facilitar a análise de dados, permitindo que qualquer pessoa, mesmo sem saber programar, faça coisas como limpar dados, rodar testes estatísticos e gerar gráficos só conversando com o chat.

A interface é bonita e fácil de entender. Os resultados aparecem no chat, mas também ficam guardados numa aba lateral com tabelas e consultas, o que ajuda a organizar o trabalho. A ferramenta é rápida, aceita vários tipos de perguntas e mostra os dados de formas diferentes (tabelas, gráficos etc.), com cores que ajudam na interpretação.

Um ponto forte é o custo: tem um plano grátis bem generoso e os planos pagos começam em US$ 5/mês, o que sai mais barato que alguns concorrentes. Outra coisa legal é que dá pra ver cada passo da transformação dos dados e até editar o código Python gerado pelos gráficos, dando mais controle pra quem usa. Sobre segurança, sites como Scamadviser e Gridinsoft dizem que o keptune.ai é confiável, tem certificado SSL e baixo risco de golpe.

A principal desvantagem é que o arquivo precisa estar num formato específico (CSV ou Excel) e seguir a estrutura que a plataforma exige, o que pode ser um obstáculo pra quem não tá acostumado. Além disso, ainda tem poucos usuários e avaliações públicas: no site keptune.tenereteam.com, a nota é 4,5 de 5, mas só com 5 avaliações. O Scamadviser também mostra que o site tem pouco tráfego, o que é normal pra uma plataforma que ainda tá crescendo. E sobre o Toolradar, ele não é um site de avaliações de usuários, é mais uma base de dados pra IA, então não tem avaliações de pessoas lá.
 
- KEPTUNE. Keptune: data analysis AI for Excel, CSVs & databases. [S. l.]: Keptune, [s. d.]. Disponível em: https://keptune.ai/. Acesso em: 28 ago. 2026.

- TENERETEAM. Keptune: avaliações e recursos. [S. l.]: Tenereteam, [s. d.]. Disponível em: https://keptune.tenereteam.com/. Acesso em: 28 ago. 2026.

- SCAMADVISER. Keptune.ai: análise de confiabilidade do site. [S. l.]: ScamAdviser, [s. d.]. Disponível em: https://www.scamadviser.com/check-website/keptune.ai. Acesso em: 28 ago. 2026.

- GRIDINSOFT. Keptune.ai: análise de segurança e reputação do domínio. [S. l.]: Gridinsoft, [s. d.]. Disponível em: https://pt.gridinsoft.com/domain/keptune.ai. Acesso em: 28 ago. 2026.

- KEPTUNE. Julius AI vs Keptune AI. [S. l.]: Keptune, [s. d.]. Disponível em: https://keptune.ai/articles/julius-ai-alternative. Acesso em: 28 ago. 2026.

#### Padrões e tendências percebidos

1. Interface conversacional como padrão dominante
   
 - A estrutura do keptune.ai segue o modelo de chat-first, ou seja, a interação principal acontece por meio de um chat, assim como ChatGPT, Copilot e Gemini. O usuário faz perguntas em linguagem natural e a IA responde com análises prontas. Isso é uma tendência clara de democratização do acesso à dados.

2. Integração entre linguagem natural e execução de código
   
 - A plataforma não só responde com texto, mas também executa código (Python) por trás dos panos e devolve os resultados em forma de tabelas e gráficos. Isso lembra ferramentas tem a vantagem de mostrar o código gerado e permitir edição, dando mais transparência e controle ao usuário.

3. Organização dos resultados entre chat e painel lateral
   
 - Os resultados aparecem no chat (para interação imediata) e também são salvos em uma aba lateral com tabelas e subconsultas. Isso ajuda a manter o histórico e facilita a consulta depois, algo que melhora a experiência de quem usa a ferramenta para análises mais longas.

4. Tendência de "IA como cientista de dados pessoal"
   
 - A IA pode atuar como um assistente, fazendo análises exploratórias, gerando insights e sugerindo próximos passos.

5. Transparência e controle como diferencial
   
 - O keptune.ai mostra cada etapa da transformação dos dados e permite editar o código Python. Esse padrão de transparência algorítmica está se tornando cada vez mais valorizado por usuários que querem entender o que está sendo feito com seus dados.

6. Custo acessível e plano gratuito
   
 - Oferecer planos gratuitos com funcionalidades básicas e planos pagos acessíveis (a partir de US$ 5/mês) também é um padrão comum entre ferramentas SaaS.


#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
|**Ponto positivo — Interface com informações precisas e diretas** | A interface é visualmente atraente, com organização clara entre chat e aba lateral, apenas com o necessário  informações em tela e organizado de forma que não fique poluído visualmente. | Devemos priorizar um design limpo e funcional, separando bem as áreas de interação para evitar sobrecarga de informações e facilitar a navegação. Isso ajuda a reduzir a curva de aprendizado e melhora a experiência do usuário, especialmente para quem não tem familiaridade com ferramentas de análise de dados. |
|**Ponto positivo — Agilidade nas respostas da IA** | A ferramenta processa comandos e gera análises (tabelas, gráficos, estatísticas) em poucos segundos. | Nenhuma, não integraremos nosso sistema com Inteligência Artifical. |
|**Ponto positivo — Transparência e controle sobre os dados** | O usuário pode ver cada etapa da transformação dos dados e editar o código Python gerado pelas visualizações. | Precisamos garantir a transparência por meio de explicações claras e acessíveis sobre cada métrica apresentada. Isso inclui: descrições do que cada indicador significa, como foi calculado. Podemos usar tooltips, ícones de ajuda, glossário e seções de "como interpretar" no dashboard. Isso fornece ao docente controle interpretativo e reduz o risco de uso incorreto das métricas, já que ele poderá compreender o que está vendo e tomar decisões mais embasadas. |
|**Ponto positivo — Variedade de visualizações e análises** | {{...}} | {{...}} |
|**Ponto positivo — Custo benefício** | {{...}} | {{...}} |
|**Limitação —Formato específico de arquivo para upload** | lançada em 2024.... | {{...}} |
|**Limitação —Ferramenta em fase de crescimento**  | {{...}} | {{...}} |
<!--|**Lições —P MIM N FAZ SENTIDO COLOCAR PQ JA TEM PONTO POSITIVO E LIMITACAO AI APRENDO OCM ELAS**  | {{...}} | {{...}} |-->

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

Não encontramos muitas avaliações sobre o software do xcalibre, mas as que encontramos indicam, de modo geral, uma experiência de uso positiva. Hurtz (2022) caracteriza o software como relativamente amigável ao usuário e destaca sua interface gráfica para configuração das análises e apresentação dos resultados . De forma semelhante, uma revisão anterior de Du Toit (1996) destaca a facilidade de uso e a organização lógica da interface gráfica . Apesar desses aspectos positivos, a utilização da ferramenta envolve conceitos e parâmetros específicos da TRI, o que pode exigir conhecimento prévio do usuário. Além disso, foram encontrados poucos relatos públicos e recentes sobre a experiência de uso do Xcalibre.

- HURTZ, Gregory M. Measurement: Interdisciplinary Research and Perspectives, 2022. Disponível em: https://www.tandfonline.com/doi/full/10.1080/15366367.2022.2026736?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

- GIERL, Mark J.; ACKERMAN, Terry. Software Review: XCALIBRE — Marginal Maximum-Likelihood Estimation Program, Windows Version 1.10. Applied Psychological Measurement, v. 20, n. 3, p. 303–307, 1996. Disponível em: https://assess.com/docs/Xcalibre_1996_review.pdf?utm_source=chatgpt.com. Acesso em: 27 ago. 2026.

#### Padrões e tendências percebidos

A análise evidencia a necessidade de conhecimento prévio sobre os dados de entrada e sobre conceitos básicos de TRI, tornando a configuração inicial mais complexa. Em contrapartida, observa-se uma preocupação em facilitar a interpretação dos resultados por meio de tabelas, gráficos e relatórios que reúnem as métricas previamente selecionadas pelo usuário.

#### Pontos positivos, limitações e lições

| Ponto | Evidência | Implicação para nosso projeto |
|---|---|---|
| **Limitação — Complexidade da entrada de dados** | O Xcalibre exige que o usuário conheça a estrutura do arquivo de entrada e forneça parâmetros adicionais para que os dados sejam interpretados corretamente. | Buscar simplificar a entrada de dados, permitindo que o docente envie a prova com o mínimo possível de configurações adicionais. |
| **Limitação — Necessidade de conhecimento específico** | A configuração e a interpretação das análises envolvem conceitos específicos da TRI e terminologia técnica. | Apresentar as métricas de maneira acessível ao docente, oferecendo explicações sobre seu significado e sua relação com o desempenho dos estudantes. |
| **Ponto positivo — Apresentação visual dos resultados** | Os resultados são apresentados por meio de tabelas e gráficos, facilitando a visualização das métricas obtidas. | Utilizar recursos visuais para facilitar a compreensão das características estruturais identificadas e de suas possíveis relações com o desempenho. |
| **Ponto positivo — Geração de relatórios** | O Xcalibre permite gerar relatórios contendo as métricas e os resultados configurados pelo usuário. | Considerar a apresentação dos resultados de forma organizada e consolidada, facilitando sua consulta pelo docente. |
| **Ponto positivo — Personalização dos resultados** | O usuário pode selecionar previamente quais informações e resultados deseja incluir nos arquivos de saída. | Avaliar a possibilidade de permitir que o docente selecione ou filtre as métricas que considera mais relevantes para sua análise. |

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
