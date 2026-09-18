# Feedback do Professor > Entrega 01 > Equipe 05

## Avaliação geral

A equipe apresenta uma proposta com boa possibilidade de exploração em IHC e conseguiu estabelecer uma relação compreensível entre a contribuição do TCC, um possível usuário direto e uma situação de uso: o docente que precisa revisar uma avaliação antes de aplicá-la. Também há um esforço relevante de levantamento inicial de alternativas existentes e de explicitação de hipóteses.

Entretanto, a entrega ainda precisa de revisão conceitual antes de servir como base segura para as próximas etapas. O principal ponto de atenção é que, em diversos trechos, a equipe passa rapidamente da atividade humana para a solução tecnológica. Upload de PDF, inserção de parâmetros, dashboard e exibição de métricas são ações ou funcionalidades da solução; não representam, por si só, os objetivos e atividades que o docente realiza no mundo real.

Também existem afirmações classificadas como `[F]` sem evidência correspondente, além de uma definição ainda genérica do usuário prioritário e do contexto de uso. Por fim, há uma inconsistência importante na delimitação do escopo: em alguns pontos a equipe descreve claramente o fluxo que pretende estudar, mas em outros registra que “não terá recorte” ou que o recorte de IHC é “Não”. Isso precisa ser corrigido para que personas, cenários, tarefas e protótipos futuros sejam construídos sobre o mesmo escopo.

A equipe está no caminho correto ao tentar conectar a análise técnica do TCC à tomada de decisão do professor. Agora é necessário deslocar um pouco mais o olhar de “o que nosso sistema faz” para “o que esse professor precisa compreender, decidir e realizar”.

## Pontos positivos

- A contribuição central do TCC foi descrita sem depender de linguagem de implementação, mantendo o foco na análise das características estruturais das avaliações.
- A equipe identificou um usuário direto plausível - docentes/elaboradores de prova - e distinguiu os estudantes como pessoas potencialmente afetadas pelo uso da solução.
- A situação concreta da seção 4.5 é um bom ponto de partida: existe uma pessoa, um objetivo, uma dificuldade e uma consequência, sem necessidade de começar pelo desenho de telas.
- A equipe reconheceu corretamente que a interpretação inadequada dos resultados pode produzir consequências relevantes para a atividade do docente.
- O levantamento inicial de alternativas e produtos existentes está mais desenvolvido do que uma simples lista de concorrentes e já procura comparar o momento da análise e o tipo de informação oferecida.
- A equipe registrou hipóteses prioritárias na matriz de rastreabilidade, o que favorece a continuidade do projeto ao longo das próximas entregas.
- A síntese final consegue explicar, em linhas gerais, a passagem entre problema humano, contribuição computacional e possibilidade de uso.

## Correções prioritárias

### 1. Separar atividade do usuário de funcionalidade do sistema

Na seção 3.2, as atividades principais foram registradas como “upload de prova”, “inserção de dados”, “exibição das métricas em um dashboard” e “análise das métricas”. Há dois problemas aqui.

Primeiro, `A01` e `A02` já pressupõem a solução projetada. Antes da interface, o professor não possui necessariamente a atividade de “fazer upload de um PDF”; sua atividade está relacionada à elaboração, revisão e avaliação da prova. O upload é uma possível forma de interação que poderá apoiar essa atividade.

Segundo, `A03` está atribuída ao **sistema**, apesar de a seção solicitar atividades/objetivos das pessoas. “Exibir métricas” é comportamento da solução, e não atividade humana.

A equipe precisa revisar essa seção perguntando: **o que o docente procura fazer no seu trabalho, independentemente da existência deste sistema?** A partir daí, nas etapas de design, será possível investigar quais ações de interface - upload, parametrização, visualização, detalhamento etc. - apoiam essas atividades.

Essa revisão é importante porque as próximas entregas irão derivar personas, cenários e modelos de tarefas dessas definições. Se a atividade inicial já nascer como uma tela ou funcionalidade, o projeto corre o risco de apenas justificar retrospectivamente uma interface que já estava imaginada.

### 2. Refinar o objetivo prioritário do usuário

O objetivo atualmente definido como “aprimorar as aulas a partir de avaliações que representem de forma mais adequada o desempenho dos estudantes” é plausível, mas ainda está distante da situação de interação escolhida.

“Aprimorar as aulas” pode envolver planejamento de conteúdo, estratégias didáticas, acompanhamento individual dos alunos, revisão de material, metodologias de ensino e muitas outras atividades que não estão no recorte proposto.

O restante da entrega aponta para um objetivo mais diretamente relacionado à **elaboração e revisão da avaliação antes de sua aplicação**. A equipe não precisa copiar uma nova frase pronta, mas deve rever o objetivo para que ele descreva o resultado que o docente pretende alcançar naquela situação específica.

Um bom teste é perguntar: **se o sistema desaparecesse, esse objetivo ainda faria sentido como objetivo profissional do docente?** Se sim, provavelmente vocês estão descrevendo o objetivo do usuário e não uma funcionalidade.

### 3. Refinar o usuário prioritário e evitar defini-lo pelas condições da solução

A definição “um docente do Estado de São Paulo com acesso a um computador, conexão à internet e com o mínimo letramento digital” ainda mistura perfil de usuário, condição de uso e restrição tecnológica.

“Docente” também permanece amplo. Ainda não sabemos, por exemplo, em que nível de ensino esse profissional atua, com que frequência elabora avaliações semelhantes ao ENEM, se cria suas próprias questões, se adapta materiais de terceiros, qual responsabilidade possui sobre a prova ou qual familiaridade tem com indicadores quantitativos.

Não é necessário resolver tudo na Entrega 01, pois parte desse refinamento pertence às próximas etapas. Entretanto, a equipe precisa reconhecer essas informações como **lacunas ou hipóteses**, em vez de apresentar um usuário aparentemente fechado.

A justificativa “seria o perfil do nosso usuário final” também é circular: ela repete a escolha, mas não explica por que esse perfil foi priorizado. A equipe deve indicar qual relação esse perfil possui com a tarefa central e por que faz sentido concentrar o projeto de IHC nele.

### 4. Revisar o uso de `[F]`, `[H]` e `[?]`

A classificação de evidências precisa ser revista em várias seções.

Afirmações como “atualmente, os docentes não dispõem de uma ferramenta”, “upload da prova é a atividade mais frequente”, “não existem fatores sociais ou organizacionais”, “não existe necessidade de histórico” e “o público já pode estar familiarizado com determinadas ferramentas” aparecem como fatos, mas a entrega não apresenta evidência suficiente para sustentar essas generalizações.

A marcação `[F]` deve ser usada quando a informação está definida no próprio TCC ou possui fonte/evidência conhecida. Quando a equipe acredita que algo seja plausível, mas ainda precisa verificar com usuários, literatura ou observação, a classificação adequada é `[H]`. Quando nem mesmo há base suficiente para formular uma hipótese segura, use `[?]`.

A equipe fez corretamente esse exercício em alguns pontos, mas ainda está usando `[F]` como sinônimo de “acreditamos que seja assim”. Isso precisa ser corrigido porque a distinção entre conhecimento e suposição é justamente uma das funções centrais desta primeira entrega.

### 5. Fortalecer a descrição do contexto de uso

A seção 5 ainda está muito superficial. “De acordo com a aplicação de alguma avaliação” não descreve adequadamente **quando**, **onde** e **em quais condições** a atividade ocorre.

Além disso, “ser docente do Estado de São Paulo” não é uma condição física de interação. Trata-se de uma delimitação do público ou da validade dos dados utilizados pelo TCC. Já computador e conexão à internet são condições tecnológicas.

Também é precipitado registrar que não existem fatores sociais ou organizacionais. A elaboração de avaliações pode envolver coordenação pedagógica, outros docentes, políticas institucionais, prazos, responsabilidades e regras de aprovação - ou talvez não envolva nada disso no recorte adotado. Neste momento, a equipe ainda precisa investigar.

Para as próximas etapas, o contexto deve ajudar a responder questões como: em que momento do processo de elaboração da prova ocorre a análise, com que pressão de tempo, em qual ambiente, com quais outros artefatos, se o trabalho é individual ou colaborativo e que responsabilidade o docente assume ao decidir alterar ou manter uma questão.

### 6. Corrigir a inconsistência na definição do recorte de IHC

Este é um problema importante de rastreabilidade.

Na seção 7.1, a equipe afirma que utilizará o fluxo completo porque a interface possui escopo reduzido e descreve esse fluxo: envio da prova, análise das características estruturais e apresentação/interpretação das métricas. Na seção 7.4, também existe uma definição razoavelmente clara da interface a ser explorada.

Entretanto, na síntese aparece “não terá recorte”. Na delimitação, “dentro do escopo de IHC” corresponde a todo o MVP, “fora do escopo” aparece como “Nada”, e na matriz de rastreabilidade o campo “Interface/recorte de IHC” está preenchido como “Não”.

Essas respostas não podem coexistir. Mesmo que a equipe decida estudar todo o MVP, isso **já é uma decisão de recorte** e precisa ser descrita explicitamente. O recorte não significa obrigatoriamente excluir metade da aplicação; significa declarar com clareza quais usuários, objetivos, tarefas e fluxos serão efetivamente modelados e avaliados na disciplina.

Antes de avançar, alinhem Entrega 01, síntese e `RASTREABILIDADE.md` para que todos registrem a mesma decisão.

### 7. Melhorar a qualidade das hipóteses prioritárias de IHC

As hipóteses registradas são úteis, mas algumas ainda estão muito próximas das questões científicas do TCC ou estão agregando várias afirmações em uma única hipótese.

`H01`, por exemplo, trata da relação entre formato da prova e desempenho. Essa é uma questão central do próprio TCC e pode permanecer registrada, mas não substitui hipóteses sobre interação e uso.

`H04` combina pelo menos duas ideias: nível de conhecimento tecnológico do docente e frequência/momento de utilização. Essas afirmações podem exigir formas de investigação diferentes e produzir impactos diferentes no design.

Ao longo das próximas entregas, a matriz também deverá incorporar hipóteses especificamente relacionadas ao projeto de IHC: quais informações o docente realmente precisa compreender, como interpreta métricas, quais decisões pretende tomar a partir delas, quais termos são familiares, que nível de explicação necessita e em que momento do processo de elaboração da prova a solução teria valor.

Não é necessário responder essas questões agora; é necessário reconhecê-las e investigá-las de forma planejada.

### 8. Revisar evidências das possibilidades de interface

Na seção 8, expressões como “Tem evidência” são insuficientes para sustentar decisões futuras. A rastreabilidade precisa permitir descobrir **qual** evidência levou à escolha.

Por exemplo, dashboard, exportação, detalhamento e entrada de dados podem fazer sentido, mas cada possibilidade deve estar associada a uma necessidade, hipótese, evidência do TCC, observação de alternativa existente ou futura investigação com usuário.

Também há um ponto conceitual importante: encontrar um padrão em produtos existentes demonstra que aquele padrão **existe no mercado**, mas não demonstra automaticamente que ele é necessário para o usuário de vocês.

Preservem a exploração de alternativas, mas evitem transformar “outros sistemas possuem” em “nosso sistema precisa possuir”.

## Recomendações de melhoria

### 1. Revisar a seção de alternativas sem generalizações indevidas

O levantamento de mercado é útil, porém a afirmação de que “o público já pode estar familiarizado” com determinadas interfaces deve ser tratada como hipótese, a menos que exista evidência sobre o público escolhido.

Também existe duplicação de uma linha na tabela da seção 6.1. É um ajuste simples, mas vale corrigir para manter o documento limpo.

### 2. Tornar a síntese final mais precisa

Algumas respostas da seção 11 ficaram excessivamente resumidas, como “Melhor as aulas”, “De acordo com a elaboração das avaliações” e “Não terá recorte”. A síntese deve ser curta, mas precisa preservar as decisões conceituais construídas ao longo da entrega.

Ela será consultada nas próximas atividades. Portanto, deve funcionar como uma fotografia confiável do estado atual do projeto, e não apenas como uma versão abreviada do texto.

### 3. Revisar a autoverificação do checklist

O checklist está praticamente todo marcado como concluído, mas a própria análise da entrega mostra pontos ainda abertos: contexto pouco caracterizado, fatos sem evidência suficiente, usuário ainda genérico e recorte inconsistente.

O checklist deve servir como instrumento de autocrítica, não como etapa burocrática de encerramento. Se uma condição ainda não estiver suficientemente atendida, deixá-la desmarcada é mais útil para a equipe do que registrar um “OK” prematuro.

### 4. Melhorar a consistência terminológica

Ao longo da entrega aparecem “docente”, “elaborador de prova”, “usuário final” e “professor”. Esses termos podem representar a mesma pessoa, mas também podem representar papéis distintos.

A equipe deve escolher a terminologia com cuidado e, quando houver diferentes papéis, explicitar a diferença. Isso será importante quando forem criadas personas e cenários.

### 5. Tratar consequências de erro também sob a perspectiva da interação

A equipe já identificou que resultados imprecisos ou interpretações incorretas podem influenciar a revisão da avaliação. Nas próximas etapas, vale separar dois tipos de risco: erro do processamento técnico e erro/ruptura de interpretação durante a interação.

Essa distinção ajudará a disciplina a manter o foco em IHC: como apresentar resultados, incertezas e explicações de forma que o usuário compreenda o que pode ou não concluir a partir da análise.

## Pontos que devem alimentar as próximas entregas

- **Entrega 2:** aprofundar as alternativas existentes e diferenciar “padrão encontrado em concorrentes” de “necessidade comprovada do usuário”.
- **Entrega 3:** investigar o perfil real do docente priorizado: experiência na elaboração de avaliações, familiaridade tecnológica, conhecimento sobre métricas, frequência de elaboração de provas e contexto profissional.
- **Entrega 4:** aprofundar o cenário atual sem o sistema, descrevendo situações reais de elaboração/revisão de avaliações, dificuldades e consequências.
- **Entrega 5:** derivar tarefas a partir dos objetivos do docente, evitando começar por upload, dashboard ou outros elementos da interface.
- **Entrega 7:** investigar principalmente `H02`, `H03` e as partes de `H04`, além de novas hipóteses de IHC que surgirem sobre interpretação das métricas e utilidade da análise.
- **Rastreabilidade:** corrigir imediatamente o campo “Interface/recorte de IHC”, manter os IDs de hipóteses estáveis e ligar posteriormente necessidades, cenários, tarefas e decisões de interface às evidências que as justificaram.
- **Projeto futuro da interface:** dar atenção especial à interpretação e explicabilidade das métricas. A equipe já identificou que uma interpretação inadequada pode afetar decisões do docente; portanto, esse ponto provavelmente terá relevância para o design e para a avaliação de IHC.

## Síntese das ações recomendadas

1. **Reescrever a seção 3 a partir das atividades e objetivos reais do docente**, separando-os de funcionalidades como upload, dashboard e exibição de métricas.
2. **Refinar o objetivo prioritário do usuário**, aproximando-o da situação de elaboração/revisão da avaliação escolhida como recorte.
3. **Revisar todas as marcações `[F]`, `[H]` e `[?]`**, principalmente nas seções de usuário, frequência, processo atual, contexto e alternativas.
4. **Definir de forma consistente o recorte de IHC** e atualizar a Entrega 01, a síntese e a matriz de rastreabilidade com a mesma decisão.
5. **Tratar características ainda desconhecidas do docente e do contexto como hipóteses/lacunas**, deixando sua investigação para as entregas apropriadas.
6. **Substituir “Tem evidência” por referências rastreáveis à evidência concreta** que sustenta cada possibilidade de interação.
7. **Revisar o checklist final após as correções**, marcando como concluído apenas o que estiver efetivamente demonstrado na entrega.

A proposta tem um bom ponto de partida para IHC, principalmente porque existe uma decisão humana relevante no centro do problema: interpretar informações sobre uma avaliação e decidir se algo deve ser revisto antes de sua aplicação. O próximo avanço da equipe é garantir que o projeto seja guiado por essa atividade e pelas necessidades do docente - e não pelo dashboard que já começou a aparecer cedo demais na conversa. 🙂
