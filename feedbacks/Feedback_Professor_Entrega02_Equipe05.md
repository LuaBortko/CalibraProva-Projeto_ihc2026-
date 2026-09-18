# Feedback do Professor > Entrega 02 > Equipe 05

## Avaliação geral

A Entrega 02 atende ao requisito mínimo de participação individual: a equipe possui três integrantes e apresenta três análises identificadas, uma por aluno - C01 Lucida, C02 Keptune.ai e C03 XCalibre. Portanto, o critério de **pelo menos uma interface corrente/representativa analisada por integrante** foi atendido.

Também existe um conjunto amplo de capturas de tela no diretório entregue em `assets/02_concorrencia/`. Foram encontrados prints das três soluções principais analisadas e também de softwares familiares ao público, como Google Classroom, ChatGPT, Kahoot!, Google Forms e YouTube. As imagens das três análises principais não se limitam a logos ou páginas institucionais: mostram estados de criação/configuração, upload, processamento, tabelas, gráficos e resultados, o que é adequado ao propósito da atividade.

O item 5, que é central nesta entrega, está presente e apresenta cinco recomendações (`RC01` a `RC05`). Em termos gerais, essas recomendações são coerentes com as observações produzidas nas análises. A equipe conseguiu transformar achados dos concorrentes em orientações para o próprio projeto, em vez de simplesmente declarar que pretende “copiar” uma solução existente.

Entretanto, a entrega ainda precisa de correções importantes antes de ser considerada plenamente consolidada. O principal problema está na **rastreabilidade da evidência visual**: embora os arquivos de imagem estejam presentes no ASSETS, vários caminhos registrados no Markdown estão incorretos, incompletos ou não correspondem exatamente aos nomes existentes no diretório. Além disso, as imagens são apenas referenciadas por caminho em tabelas; os pontos positivos, negativos e padrões identificados nem sempre estão associados a uma captura específica de forma suficientemente explícita.

Há ainda uma inconsistência com a matriz de rastreabilidade. O checklist afirma que hipóteses e padrões foram atualizados, mas o arquivo de rastreabilidade entregue continua praticamente no estado da Entrega 01, com placeholders nas tabelas de padrões e artefatos. Isso é especialmente relevante porque a Entrega 02 produziu decisões concretas - dashboard, detalhamento, upload simplificado, exportação e princípios de organização visual - que já deveriam começar a deixar rastros documentados.

## Pontos positivos

- **Cobertura individual atendida:** Nuno analisou a Lucida, Beatriz analisou a Keptune.ai e Luana analisou o XCalibre. A equipe possui três integrantes e apresenta três análises identificadas por autoria.
- As três interfaces selecionadas são coerentes com o domínio do projeto. Mesmo não sendo concorrentes idênticos, oferecem atividades análogas de criação/análise de avaliações, entrada de dados, apresentação de métricas e interpretação de resultados.
- A equipe não ficou restrita aos concorrentes. Também analisou softwares que podem moldar expectativas do público-alvo, como Google Classroom, Google Forms, Kahoot!, ChatGPT e YouTube.
- Os prints das três análises principais apresentam estados de interação relevantes. A Lucida possui telas de criação/configuração e análise; a Keptune apresenta upload, chat, resultados gráficos e tabulares; o XCalibre apresenta entrada, configuração, tabelas e gráficos.
- A síntese comparativa da seção 4 procura comparar critérios comuns entre as soluções e não apenas repetir descrições individuais.
- O item 5 possui recomendações com identificadores estáveis (`RC01` a `RC05`) e origem declarada.
- `RC02`, sobre simplificação do upload, é particularmente bem sustentada: a análise do XCalibre identifica complexidade de entrada e parâmetros, enquanto a Keptune mostra a barreira causada pela exigência de estrutura específica dos arquivos.
- `RC03`, sobre explicação das métricas, está alinhada ao risco de interpretação identificado no projeto e é reforçada pela análise da Keptune e pela dificuldade terminológica observada no XCalibre.
- A equipe conseguiu perceber que padrões de mercado não precisam ser adotados automaticamente: histórico, CRUD, comparação de resultados e administração, por exemplo, foram explicitamente considerados e descartados para o escopo atual.

## Correções prioritárias

### 1. Corrigir a rastreabilidade dos prints e os caminhos dos arquivos

O ASSETS contém um conjunto suficiente de imagens, porém o Markdown possui diversos caminhos inconsistentes com os arquivos efetivamente entregues.

Exemplos observados:

- em C01, alguns arquivos são referenciados com caminho absoluto de workspace, como `/workspaces/.../assets/02_concorrencia/criacao_prova1.png`, enquanto o ASSETS contém apenas `02_concorrencia/criacao_prova1.png`;
- em C02, referências como `keptune_analise1`, `keptune_analise2`, etc. aparecem sem a extensão `.jpeg`;
- na análise de softwares cotidianos, algumas referências do Google Classroom foram quebradas em duas linhas;
- `kahoot-relatorio2.jpeg` não coincide exatamente com o nome entregue no ASSETS, que contém acentuação no nome do arquivo;
- o Markdown cita `forms-exemplo-opcoes.jpeg`, enquanto o arquivo existente é `forms-opcoes.jpeg`;
- o Markdown cita `youtube-enviar-detalhes.jpeg`, enquanto o ASSETS contém `youtube-detalhes.jpeg`.

Isso compromete a verificabilidade da entrega. O professor precisa conseguir abrir o documento e localizar imediatamente a evidência que sustenta cada observação.

A equipe deve padronizar todos os caminhos utilizando exclusivamente o diretório relativo definido para a atividade, por exemplo:

`assets/02_concorrencia/nome_do_arquivo.ext`

Além disso, evitem acentos, espaços ou nomes ambíguos nos arquivos para reduzir problemas de portabilidade.

### 2. Fazer o print funcionar como evidência da análise, não apenas como arquivo anexado

As capturas existem e são relevantes, mas ainda estão pouco integradas à argumentação.

Em várias linhas, a coluna “Evidência/print” lista um ou mais arquivos, enquanto a análise de ponto positivo ou negativo aparece de forma genérica na coluna seguinte. Isso dificulta responder: **qual elemento concreto da tela levou a esta conclusão?**

Por exemplo, dizer que uma interface é “amigável”, “intuitiva” ou “bem organizada” é uma avaliação ampla. A equipe deve apontar o que na captura sustenta essa interpretação: agrupamento de elementos, sequência de passos, hierarquia visual, feedback, rotulagem, quantidade de opções, destaque da ação principal, organização dos resultados etc.

Não é obrigatório transformar todas as imagens em diagramas complexos, mas é importante que cada print relevante esteja acompanhado por uma indicação clara do que deve ser observado. Isso pode ocorrer por legenda, referência textual direta ou anotação visual.

O objetivo da atividade não é provar que a equipe “visitou o site”; é demonstrar que conseguiu **ler criticamente uma interface**.

### 3. Atualizar a matriz de rastreabilidade com os aprendizados da Entrega 02

O checklist da Entrega 02 marca como concluída a atualização de hipóteses e padrões, mas a matriz entregue ainda contém placeholders em “Rastreabilidade entre contribuição técnica, necessidades e artefatos” e “Rastreabilidade de padrões de interface”.

Isso não está coerente com o conhecimento que a equipe produziu nesta entrega.

Agora já existem, pelo menos, decisões ou hipóteses sobre:

- dashboard;
- upload;
- detalhamento/explicabilidade;
- apresentação visual de métricas;
- exportação de resultados;
- simplificação da entrada;
- redução de terminologia técnica;
- organização e hierarquia da informação.

Não é necessário preencher prematuramente artefatos que pertencem a entregas futuras, como MoLIC, Figma ou testes. Esses campos podem continuar como `PENDENTE`. Entretanto, a equipe deve registrar o que **já foi aprendido**, relacionando a recomendação ou padrão à evidência da Entrega 02.

A rastreabilidade deve evoluir junto com o projeto; caso contrário, ela vira apenas um arquivo de template esquecido na pasta.

### 4. Fortalecer a ligação entre cada recomendação do item 5 e as evidências que realmente a sustentam

O conjunto `RC01`–`RC05` é, em geral, consistente, mas a origem ainda pode ser mais precisa.

#### RC01 - recursos visuais

A recomendação é coerente com C01 e C02. Ambas mostram uso de indicadores, gráficos e organização visual dos resultados. C03 também oferece evidência útil, pois apresenta tabelas e gráficos como recursos de interpretação. Portanto, a equipe pode tornar a origem mais completa.

Entretanto, cuidado para não transformar “usar cores” em uma regra genérica. A recomendação importante é **usar representação visual que favoreça interpretação**, e não simplesmente colorir resultados.

#### RC02 - upload simples e claro

É uma recomendação bem fundamentada. C03 mostra uma entrada complexa e dependente de parâmetros; C02 mostra exigência de formatos estruturados; C01 apresenta um fluxo mais orientado. A síntese produzida é consistente com as três análises.

Preservem essa recomendação.

#### RC03 - explicação de funcionamento e métricas

A recomendação é consistente, mas a origem está subestimada ao citar apenas C02. C03 também sustenta diretamente essa decisão ao mostrar terminologia técnica e necessidade de conhecimento prévio.

Além disso, esta recomendação possui forte relação com a Entrega 01, na qual a própria equipe reconheceu o risco de interpretação incorreta das métricas. Portanto, essa é uma boa oportunidade de demonstrar continuidade entre entregas.

#### RC04 - exportação/download

A recomendação pode ser derivada de C03, mas a equipe precisa esclarecer melhor **qual objetivo do docente exige guardar ou consultar o resultado fora da ferramenta**. A existência de exportação em um concorrente demonstra um padrão, mas ainda não demonstra necessidade do público-alvo.

Neste momento, RC04 deve ser entendida como uma recomendação candidata a ser validada, não como requisito fechado.

#### RC05 - interface simples, organizada e intuitiva

A ideia é pertinente, porém está genérica demais.

“Interface intuitiva” é quase sempre uma intenção desejável e não uma orientação operacional suficientemente precisa. A equipe deve transformar o aprendizado em princípios observáveis: reduzir opções desnecessárias, manter hierarquia visual, apresentar somente informações relevantes em cada etapa, utilizar rótulos compreensíveis ao docente e separar visão geral de detalhamento.

Além disso, C03 não é exemplo positivo de simplicidade; ele é justamente uma evidência de que configurações excessivas e terminologia técnica aumentam a complexidade. Se C03 permanecer como origem de RC05, deixem explícito que a recomendação foi aprendida **por contraste com uma limitação observada**.

### 5. Evitar antecipar decisões de interface que ainda não foram validadas

Em alguns trechos da análise da Keptune, a equipe passa rapidamente do aprendizado para uma especificação praticamente pronta da solução: tooltips, glossário, ícones de ajuda, cores vermelha/verde, gráficos específicos, exportação CSV/PDF e alertas.

Essas são boas alternativas para investigação, mas ainda não são conclusões obrigatórias da análise de concorrência.

A Entrega 02 deve gerar repertório e recomendações. As decisões concretas de design precisam continuar sendo justificadas pelas próximas entregas, considerando objetivos, contexto, tarefas e avaliação com usuários.

Portanto, diferenciem:

- **aprendizado:** o usuário precisa compreender as métricas;
- **recomendação:** oferecer mecanismos de explicação progressiva;
- **alternativas possíveis:** tooltip, glossário, ícone de ajuda, legenda, texto contextual etc.

Esse cuidado evita que o projeto fique preso cedo demais a uma solução específica.

### 6. Melhorar a precisão das observações de IHC

Algumas observações ainda são expressões de gosto ou julgamento amplo, por exemplo:

- “ótimo UX”;
- “design bem amigável”;
- “interface bonita”;
- “layout pouco chamativo”.

Esses comentários precisam ser traduzidos para elementos observáveis da interação.

“Pouco chamativo”, por exemplo, não explica necessariamente um problema de uso. Já “muitos parâmetros apresentados simultaneamente, terminologia técnica e baixa hierarquia entre ações primárias e secundárias” é uma observação que pode orientar uma decisão futura.

A equipe deve fazer esse movimento em toda a entrega: sair de “gostei/não gostei” e chegar a “qual característica da interface produz qual efeito provável para o usuário e sua tarefa”.

### 7. Revisar a relação entre softwares cotidianos e padrões realmente relevantes ao projeto

A seção 3 é útil, mas algumas inferências são amplas.

YouTube, Kahoot!, Google Classroom, Google Forms e ChatGPT têm finalidades muito diferentes. A presença de um padrão nesses sistemas não significa automaticamente que ele seja adequado ao projeto.

Por exemplo, “avaliação pode ser dinâmica e engajadora” derivada do Kahoot! não é necessariamente uma necessidade do sistema proposto, cujo objetivo principal é apoiar a análise de uma prova antes da aplicação.

Mantenham na síntese apenas aprendizados que tenham conexão clara com as tarefas do projeto: upload, organização de resultados, explicações, feedback, hierarquia da informação, navegação e recuperação de dados, quando aplicável.

## Recomendações de melhoria

### 1. Incorporar as imagens ao Markdown

Atualmente, a maior parte das imagens é citada como texto em uma coluna. Sugiro que as telas mais importantes sejam efetivamente renderizadas no documento, com legenda curta indicando o achado.

Não é necessário colocar as 35 imagens no corpo principal. Uma seleção representativa por concorrente é suficiente, desde que o restante permaneça no diretório de evidências.

### 2. Escolher uma ou duas telas-chave por conclusão

Quando uma recomendação for importante, apontem quais telas foram decisivas para chegar àquela conclusão.

Exemplo de estrutura de raciocínio:

`captura → elemento observado → consequência para a interação → recomendação`

Esse encadeamento deixará a análise muito mais forte.

### 3. Padronizar o vocabulário de avaliação

Ao invés de alternar entre “amigável”, “bonita”, “intuitiva”, “limpa” e “boa UX”, procurem utilizar termos associados a aspectos observáveis: hierarquia visual, visibilidade, consistência, clareza de rótulos, carga de configuração, feedback, organização, reconhecimento, esforço de entrada e compreensão dos resultados.

### 4. Revisar referências incompletas

Há pelo menos uma referência bibliográfica com marcador de autor incompleto (`[nome completo do coautor]`). Isso deve ser corrigido. Também vale remover parâmetros como `utm_source=chatgpt.com` dos links acadêmicos quando não forem necessários.

### 5. Corrigir pequenos problemas de redação e formatação

Existem erros ortográficos, frases informais e comentários internos que não deveriam permanecer na versão final, como o comentário em caixa alta próximo da seção C02.

Esses problemas não são o foco principal da avaliação, mas a entrega final deve ser limpa o suficiente para funcionar como documentação do projeto ao longo do semestre.

## Pontos que devem alimentar as próximas entregas

- **Perfil do usuário:** verificar se docentes realmente compreendem as métricas propostas e qual nível de explicação necessitam.
- **Tarefas:** confirmar se exportar resultados é uma tarefa real ou apenas um padrão observado em concorrentes.
- **Contexto:** investigar em que momento da elaboração/revisão da prova o docente utilizaria a ferramenta e com que frequência.
- **Design:** preservar como alternativas a explorar a separação entre visão geral e detalhamento, simplificação da entrada e explicação progressiva das métricas.
- **Avaliação:** futuramente testar se gráficos, cores, textos explicativos e mecanismos de detalhamento realmente ajudam na interpretação; não presumir que mais visualizações significam automaticamente melhor compreensão.
- **Rastreabilidade:** registrar `RC01`–`RC05` e suas origens para que seja possível verificar, nas próximas entregas, quais recomendações foram mantidas, alteradas ou descartadas.
- **Continuidade com a Entrega 01:** a preocupação com interpretação incorreta das métricas deve permanecer como eixo importante do projeto. A Entrega 02 trouxe evidências de mercado que reforçam a importância de tornar resultados compreensíveis.

## Síntese das ações recomendadas

1. **Corrigir todos os caminhos dos prints** para corresponder exatamente aos arquivos existentes em `assets/02_concorrencia/`.
2. **Manter a evidência de uma análise por integrante**, que foi atendida corretamente.
3. **Associar cada conclusão relevante a uma captura específica**, deixando claro o elemento positivo, negativo ou padrão observado.
4. **Atualizar a matriz de rastreabilidade** com os aprendizados e recomendações produzidos nesta entrega.
5. **Refinar `RC01`–`RC05`**, preservando o que foi bem sustentado e distinguindo recomendação de requisito já decidido.
6. **Reforçar RC03 com C03 e com o risco de interpretação identificado na Entrega 01.**
7. **Manter RC04 como hipótese/recomendação a validar**, até que a necessidade de exportação seja demonstrada pelo usuário.
8. **Transformar RC05 em orientações mais observáveis e menos genéricas**, explicitando que parte do aprendizado de C03 veio de uma limitação.
9. **Eliminar julgamentos vagos de interface** e substituí-los por observações concretas de IHC.
10. **Revisar referências, comentários internos e formatação** antes de considerar a entrega consolidada.

A equipe fez a parte mais trabalhosa desta atividade: realmente abriu interfaces, percorreu fluxos, capturou estados relevantes e tentou aprender com eles. Agora falta transformar esse material em **evidência rastreável de design**. Print sozinho é fotografia; print ligado a uma observação, a uma consequência de uso e a uma recomendação vira conhecimento de IHC. 🙂
