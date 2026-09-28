# Feedback do Professor > Entrega 03 > Equipe 05

## Avaliação geral

A equipe cumpriu quantitativamente a responsabilidade mínima da Entrega 03. O grupo possui três integrantes e apresentou três personas, cada uma identificada com autoria individual: P01 - Maria da Costa Silva, P02 - João Paulo de Aquino Gonzaga e P03 - Vera Coelho. As três foram classificadas como personas primárias e possuem imagem, nome, papel profissional, características de domínio e tecnologia, objetivos, necessidades, dores, motivadores, restrições, ambiente típico de uso e comportamentos relevantes.

Há também uma evolução importante em relação às entregas anteriores. A equipe procura representar docentes com diferentes níveis de experiência tecnológica, diferentes ambientes de trabalho e diferentes relações com elaboração e análise de avaliações. Além disso, a jornada escolhida para P01 contempla explicitamente um momento anterior ao uso, o uso da plataforma e uma consequência posterior, o que é conceitualmente mais adequado do que transformar a jornada em simples sequência de telas.

Entretanto, esta entrega ainda possui problemas estruturais importantes. O principal é que as três personas são declaradas **primárias**, mas a equipe não justifica por que cada uma delas exige necessidades de interação suficientemente distintas para ser tratada como uma persona primária. Na prática, as decisões de design derivadas das três convergem quase totalmente para a mesma solução: interface simples, upload facilitado, métricas claras e explicações acessíveis. Isso sugere que a equipe criou três personagens diferentes, mas ainda não demonstrou três arquétipos de uso realmente distintos.

Outro ponto crítico está na rastreabilidade. O checklist afirma que os IDs das personas foram adicionados à matriz, porém a `RASTREABILIDADE.md` ainda mantém os campos de persona como placeholders e não registra P01, P02 ou P03 nas relações entre necessidade, cenário, objetivo e demais artefatos. A própria hipótese H04 continua indicada como algo a investigar na Entrega 03, mas permanece sem evidência registrada após a elaboração das personas. Portanto, a documentação atual não corresponde ao estado real do trabalho.

O mapa de empatia apresenta boa riqueza de conteúdo visual, mas o formalismo está incompleto na documentação textual e contém muitos elementos biográficos periféricos que não contribuem diretamente para decisões de interação. O contexto de uso, por sua vez, melhorou em relação à Entrega 01, porém ainda descreve de forma genérica o ambiente social e físico. Finalmente, a jornada possui corretamente “antes, durante e depois”, mas o trecho “durante” comprime praticamente toda a interação em uma única etapa e precisa ser desenvolvido como uma narrativa mais completa do percurso da persona.

## Pontos positivos

- A quantidade mínima foi atendida: há uma persona identificada por integrante.
- As três personas possuem nome, imagem e caracterização relativamente detalhada, evitando fichas compostas apenas por idade e profissão.
- Todas foram explicitamente declaradas como **proto-personas a validar**, o que é adequado neste estágio quando ainda não há investigação empírica suficiente para tratar suas características como fatos.
- A equipe preserva uma distinção útil entre diferentes graus de familiaridade tecnológica: P01 com experiência básica/intermediária, P02 com alta experiência e P03 com familiaridade cotidiana, mas sem especialização em análise de avaliações.
- Os três perfis possuem relação com atividade docente e elaboração ou acompanhamento de avaliações, mantendo conexão geral com o domínio do projeto.
- P01 possui boa relação com o recorte relacionado ao ensino médio e ao contexto do ENEM, razão pela qual foi escolhida para o mapa de empatia e a jornada.
- As personas procuram registrar objetivos pessoais e profissionais que vão além de operar a ferramenta, o que evita reduzir a persona a uma lista de funcionalidades.
- As decisões de design associadas às personas procuram estabelecer consequência para a interface, principalmente quanto à interpretação das métricas, simplicidade e redução de esforço.
- O mapa de empatia foi efetivamente produzido como artefato visual em `assets/03_personas/mapa_empatia.png`.
- A jornada de P01 começa antes da interface, quando Maria já elaborou uma prova e percebe uma incerteza sobre sua estrutura. Também descreve o que ela pretende fazer depois da análise, incluindo eventual revisão da avaliação antes da aplicação.
- O contexto de uso diferencia usuários, tarefas, equipamentos, ambiente físico, ambiente organizacional e volume de dados, sendo uma evolução concreta em relação à descrição muito genérica apresentada anteriormente.

## Correções prioritárias

### 1. Justificar corretamente a classificação das três personas como primárias

P01, P02 e P03 foram classificadas como personas primárias, mas a entrega não apresenta a justificativa conceitual dessa classificação para cada uma.

Uma persona primária não é simplesmente uma persona importante. Ela representa um perfil cujos objetivos e necessidades de interação não seriam plenamente atendidos por uma interface projetada para outra persona. Por isso, se três personas são primárias, a equipe precisa conseguir demonstrar quais diferenças relevantes de objetivos, conhecimentos, contexto ou comportamento exigem decisões de interação próprias.

No documento atual, ocorre o contrário: as implicações de design das três personas convergem fortemente para a mesma proposta. P01 demanda simplicidade, visualização e poucas etapas; P02 demanda upload simples, dashboard claro, explicações e interface limpa; P03 também demanda métricas claras e contextualizadas. Essa convergência sugere que pode haver um mesmo arquétipo central representado por três histórias biográficas diferentes.

A equipe deve revisar o elenco e responder: **quais diferenças entre P01, P02 e P03 realmente mudam a interface, o fluxo, a linguagem ou os critérios de avaliação?** Se essas diferenças não existirem, algumas personas podem representar variações do mesmo perfil e não deveriam ser classificadas artificialmente como primárias apenas para cumprir quantidade.

É perfeitamente possível manter mais de uma persona primária, inclusive três, mas a justificativa precisa estar relacionada às necessidades de interação - não apenas à diferença de idade, disciplina lecionada ou instituição.

### 2. Preencher a síntese das personas e explicitar as diferenças entre os perfis

A seção “Síntese das personas” não foi respondida. Permaneceu apenas a instrução do template:

> “Explique diferenças entre os perfis e qual persona é prioritária. Evite personas duplicadas que só mudam nome/foto.”

Esse trecho era especialmente importante nesta entrega porque permitiria justamente demonstrar por que existem três personas e qual contribuição cada uma traz ao design.

A equipe deve comparar os perfis em termos de aspectos que realmente afetam a interação: experiência tecnológica, familiaridade com métricas, tipo de avaliação elaborada, pressão de tempo, ambiente de uso, necessidade de explicação, frequência de uso, autonomia e responsabilidade na decisão.

A escolha posterior de P01 como “principal” é razoavelmente justificada pela proximidade com ensino médio e ENEM, mas isso precisa ser conciliado com a classificação das três como primárias. “Principal”, “prioritária” e “primária” não devem ser utilizados como sinônimos sem critério.

### 3. Separar biografia útil de características decorativas

As personas possuem riqueza biográfica, mas parte das informações adicionadas não contribui para compreender a interação com o sistema.

Por exemplo, aparecem elementos como tricotar roupas para as gatas, gostar de séries, referências pessoais a figuras públicas, viagens com a família, interesses sociais amplos e outros detalhes de vida pessoal. Alguns desses elementos podem ajudar a tornar o personagem memorável, mas só são úteis para a persona se contribuírem para objetivos, contexto, comportamento ou decisões de design.

O risco é produzir uma “biografia convincente” sem produzir um **modelo útil de usuário**.

A equipe deve manter características pessoais quando elas ajudam a entender motivações, restrições, valores ou comportamentos relevantes. O restante pode ser reduzido para que a persona fique mais precisa. Uma boa persona não é a que possui mais detalhes; é aquela cujos detalhes ajudam a equipe a decidir melhor.

### 4. Tratar todas as características inventadas das proto-personas como hipóteses

A equipe corretamente informa que P01, P02 e P03 são proto-personas a validar. Entretanto, dentro das fichas, muitas características são descritas com grande precisão, como se já fossem conhecidas: rotina profissional, grau de domínio tecnológico, relação com inteligência artificial, medo relacionado ao emprego, prioridades familiares, práticas de preparação de provas, comportamento de pesquisa e preferências de uso.

Como ainda são proto-personas, essas características não podem ganhar validade apenas porque foram inseridas em uma história fictícia.

A equipe deve deixar claro quais elementos derivam de decisões formais do TCC e das entregas anteriores e quais são hipóteses sobre o público que precisarão ser investigadas posteriormente. Não é necessário colocar `[H]` em cada frase da ficha, mas a documentação deve deixar inequívoco que esses detalhes são construções provisórias até existir investigação com usuários ou outra evidência adequada.

Esse cuidado é especialmente importante porque as decisões de design já estão sendo justificadas com base nessas características.

### 5. Completar o formalismo textual do mapa de empatia

O artefato visual possui as dimensões “o que pensa e sente”, “o que vê”, “o que escuta”, “o que fala e faz”, dores e necessidades. Portanto, visualmente há uma estrutura reconhecível de mapa de empatia.

Porém, a documentação textual logo abaixo solicita explicitamente: **o que vê; ouve; diz/faz; pensa/sente; dores; ganhos**. No texto entregue existem “O que vê”, “Ouve”, “Diz/Faz”, “Dores” e “Ganhos”, mas **não existe a seção “Pensa/Sente”**.

Isso significa que o mapa não está formalmente reproduzido de maneira completa no documento.

Além disso, o artefato visual utiliza “necessidades”, enquanto o texto utiliza “ganhos”. A equipe deve padronizar o formalismo adotado e garantir que todas as dimensões apareçam tanto no artefato quanto na documentação.

### 6. Tornar o mapa de empatia mais focado no problema e na experiência relevante para o projeto

O mapa de empatia contém muitos elementos, porém parte deles está distante da atividade que está sendo estudada.

Para esta disciplina, interessa compreender o que a persona vê, ouve, pensa, sente, diz e faz **no contexto que influencia sua forma de elaborar, revisar, aplicar e interpretar avaliações**, além das pressões profissionais e tecnológicas relacionadas.

Quando o mapa passa a acumular gostos pessoais, referências culturais, preocupações gerais ou preferências que não produzem qualquer consequência para a interação, ele perde poder analítico.

A equipe deve revisar cada item com uma pergunta simples: **isso ajuda a explicar uma necessidade, comportamento, dificuldade, expectativa ou decisão de interação?** Se a resposta for não, provavelmente o item é biográfico, mas não é relevante para o mapa de empatia deste projeto.

### 7. Aprofundar o contexto físico de uso

O contexto físico foi descrito basicamente como “em casa” ou “na instituição de ensino”, utilizando computador ou notebook. Isso é um começo, mas ainda não caracteriza suficientemente as condições em que a interação acontece.

P01, P02 e P03 apresentam contextos potencialmente diferentes: escola pública, faculdade e docência on-line em casa. Essas diferenças podem afetar disponibilidade de tempo, interrupções, equipamentos, privacidade, qualidade da conexão, existência de outros sistemas abertos simultaneamente e possibilidade de revisar uma prova com outras pessoas.

Não é necessário inventar essas condições. Quando forem desconhecidas, registrem-nas como hipóteses ou lacunas a investigar. O importante é que o contexto de uso deixe de ser apenas um local geográfico e passe a representar as **condições concretas da atividade**.

### 8. Aprofundar o contexto social e organizacional

A descrição atual do ambiente social/organizacional afirma apenas que o uso ocorre no contexto de trabalho e que os resultados podem apoiar decisões sobre a estrutura da prova.

Isso ainda é insuficiente para caracterizar o contexto social.

A elaboração de uma avaliação pode ser individual ou compartilhada; pode sofrer influência de coordenação, outros docentes, calendário acadêmico, regras institucionais, padronização de avaliações ou prazos. A responsabilidade pela decisão de modificar uma questão também pode variar.

A equipe não precisa pressupor que todos esses fatores existem. Precisa investigar quais realmente são relevantes para as personas escolhidas.

Esse ponto já havia aparecido como lacuna anteriormente e agora deveria começar a ganhar forma nesta entrega.

### 9. Desenvolver melhor a jornada durante o uso da interface

A jornada possui corretamente um **antes**, um **durante** e um **depois**, mas o “durante” está resumido a uma única ação ampla:

> Maria acessa a plataforma, envia o PDF da prova e analisa as métricas e informações apresentadas.

Isso comprime toda a experiência de interação em uma única etapa. Para uma jornada de usuário, é importante representar os principais momentos pelos quais a pessoa passa, especialmente aqueles em que objetivo, emoção, dúvida ou decisão mudam.

Neste projeto, a jornada durante o uso poderia distinguir, conceitualmente, momentos como entrada na solução, entendimento do que será analisado, fornecimento da avaliação, espera/processamento, primeiro contato com os resultados, exploração de pontos de atenção, busca de explicação e decisão sobre o que fazer com a informação. Não se trata de transformar a jornada em wireflow ou antecipar telas, mas de descrever **a experiência da pessoa ao longo da atividade**.

No estado atual, a etapa “durante” ainda está mais próxima de uma descrição resumida de fluxo funcional do que de uma jornada.

### 10. Preservar a qualidade da etapa posterior da jornada, mas manter suas conclusões como hipóteses

A parte posterior ao uso é um dos melhores elementos da jornada. A equipe não encerra a experiência no momento em que Maria fecha o sistema: ela utiliza os resultados para revisar a prova, aplica a avaliação e posteriormente interpreta o desempenho dos estudantes.

Isso está alinhado à ideia de que a experiência do usuário possui consequências depois da interação.

Entretanto, há um salto importante entre “analisar características estruturais da prova” e “compreender quais conteúdos precisam ser reforçados em aula”. O sistema proposto não necessariamente demonstra que determinado conteúdo foi ou não aprendido; ele fornece informação sobre possíveis relações entre características estruturais e desempenho.

Portanto, essa consequência pedagógica deve permanecer como hipótese a validar e não como benefício garantido da ferramenta.

### 11. Corrigir a matriz de rastreabilidade antes de avançar

Este é um problema de conformidade e continuidade importante.

O checklist da Entrega 03 afirma:

> “IDs das personas foram adicionados à rastreabilidade.”

Porém, a `RASTREABILIDADE.md` entregue ainda apresenta `{{P01}}` como exemplo dentro da linha R01 e não possui registros concretos de P01, P02 ou P03.

Além disso:

- H04 continua com “Entrega 3” como local de investigação e “Não tem” em evidência obtida;
- a seção de relação entre capacidade, necessidade, persona e cenário continua vazia;
- o recorte de IHC continua registrado como “Não”, inconsistência já apontada anteriormente;
- os padrões de interface continuam com placeholders.

A equipe precisa atualizar a rastreabilidade para refletir o que já foi produzido. Não é necessário antecipar cenários, tarefas ou modelos ainda não realizados: nesses campos, usem `PENDENTE`. O que não pode ocorrer é a matriz continuar dizendo que nada existe quando três personas e uma jornada já foram construídas.

### 12. Revisar o checklist com mais rigor

O checklist marca como concluídos itens que a própria documentação contradiz.

O exemplo mais evidente é a afirmação de que os IDs das personas foram adicionados à rastreabilidade. Também é discutível marcar que as personas “não são apenas diferenças demográficas superficiais” sem antes realizar a síntese que demonstra exatamente quais diferenças de objetivos e necessidades justificam a existência de três personas.

O checklist deve funcionar como verificação crítica da equipe. Marcar tudo como concluído sem conferir o artefato enfraquece a própria função do documento.

## Recomendações de melhoria

### 1. Refinar objetivos das personas

Os objetivos de P01 e P02 estão bastante amplos e incluem várias metas pessoais e profissionais. Isso é aceitável em uma persona, mas a equipe deve destacar quais objetivos são especialmente importantes para o projeto.

O foco deve permanecer em objetivos humanos, não em operar o software. Por exemplo, a persona pode querer ter confiança de que sua avaliação representa melhor aquilo que pretende avaliar; “fazer upload de PDF” é apenas uma tarefa possível para atingir esse objetivo.

### 2. Explorar melhor a diferença de conhecimento estatístico

As três personas apontam, de formas diferentes, familiaridade limitada com métricas psicométricas ou estatísticas. Isso parece ser um elemento muito importante do projeto.

A equipe deve investigar posteriormente se essa característica realmente distingue os perfis ou se é uma necessidade compartilhada pelo público. Essa resposta terá impacto direto sobre linguagem, explicações, visualizações, ajuda e critérios de avaliação da interface.

### 3. Evitar transformar decisões preliminares em requisitos definitivos

Na Entrega 03 já aparecem como soluções praticamente decididas dashboard, gráficos, indicadores, tooltips e pop-ups.

Essas alternativas foram aprendidas na análise de concorrência e fazem sentido como possibilidades, mas ainda devem ser confrontadas com personas, cenários, tarefas e posteriormente avaliação.

A persona deve ajudar a justificar ou questionar uma decisão - não apenas confirmar o desenho que a equipe já queria construir.

### 4. Melhorar a redação da jornada

A jornada contém alguns problemas de redação e um caractere `}` residual no campo de pensamento/emoção. Há também frases excessivamente longas e objetivos que misturam “avaliar de forma justa”, “melhorar aulas” e “medir apenas conhecimentos teóricos”.

Vale revisar a escrita depois de corrigir a estrutura conceitual.

## Pontos que devem alimentar as próximas entregas

- **Entrega 04 - Cenários de problema:** utilizar as personas revisadas para representar situações anteriores à solução, principalmente os momentos em que o docente elabora e revisa uma avaliação e ainda não possui apoio da plataforma.
- **Entrega 04:** não transformar os cenários em histórias de uso do sistema. As dificuldades atuais das personas devem aparecer antes da intervenção tecnológica.
- **Entrega 05 - Análise de tarefas:** derivar tarefas dos objetivos das personas e dos cenários, evitando iniciar diretamente por “upload de PDF” apenas porque essa funcionalidade já está prevista.
- **Entrega 07 - Coleta de dados:** validar H04 e as características hoje atribuídas às proto-personas, especialmente familiaridade tecnológica, conhecimento de métricas, frequência de elaboração de avaliações, ambiente de uso e necessidade de explicações.
- **Avaliação futura:** verificar se diferentes níveis de experiência tecnológica realmente exigem comportamentos de interface distintos.
- **Rastreabilidade:** registrar P01, P02 e P03 imediatamente e preservar suas relações com H02, H03 e H04.
- **Jornada:** usar o percurso de P01 como fonte para identificar pontos de decisão, incerteza, expectativa e interpretação que deverão aparecer posteriormente nos cenários e nas tarefas.
- **Contexto:** investigar quais fatores físicos, sociais e organizacionais realmente interferem na revisão de avaliações em casa, na escola, na faculdade ou em trabalho remoto.

## Síntese das ações recomendadas

1. **Revisar a classificação de P01, P02 e P03 como personas primárias e justificar cada classificação pelas diferenças que realmente afetam a interação.**
2. **Preencher a seção “Síntese das personas”, que permaneceu como instrução do template.**
3. **Reduzir detalhes biográficos sem consequência para o design e fortalecer características que afetam objetivos, comportamento e contexto de uso.**
4. **Manter explicitamente as três personas como proto-personas e não transformar detalhes fictícios em evidências sobre usuários reais.**
5. **Completar o mapa de empatia textual com “Pensa/Sente” e padronizar “ganhos”/“necessidades” de acordo com o formalismo adotado.**
6. **Revisar o mapa de empatia para concentrá-lo em aspectos relevantes à atividade de elaborar, revisar e interpretar avaliações.**
7. **Aprofundar os contextos físico, social e organizacional sem inventar fatos; o que ainda não for conhecido deve ser tratado como hipótese ou lacuna.**
8. **Expandir a etapa “durante” da jornada para representar os principais momentos da experiência, e não apenas resumir o fluxo inteiro em uma linha.**
9. **Preservar o “depois” da jornada, mas tratar benefícios pedagógicos ainda não comprovados como hipóteses.**
10. **Atualizar imediatamente a `RASTREABILIDADE.md` com P01, P02 e P03 e corrigir o checklist que afirma que essa atualização já foi realizada.**

A equipe avançou na representação das pessoas e já possui material suficiente para construir bons cenários. O próximo passo é fazer com que essas três personas deixem de ser apenas três professores com histórias diferentes e passem a funcionar como **instrumentos de decisão de design**. Se trocar o nome e a foto de uma persona não mudar nenhuma decisão da interface, é sinal de que ainda falta descobrir o que realmente distingue aquele perfil.
