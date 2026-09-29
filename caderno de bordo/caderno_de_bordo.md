# Caderno de bordo — Ecos de uma Civilização

Projeto desenvolvido para a disciplina **Criatividade Computacional — CIn/UFPE — 2026.2**.

**Integrantes:** Aline Marianna · Amanda Arruda · Ellian Rodrigues · Fabriely Santos · Monyque Lima · Nícolas Veiga

Este arquivo consolida o processo de criação da coleção em um único caderno de bordo. Ele reúne a definição do eixo, o uso das skills de ideação, o que foi decidido manualmente pelo grupo, o registro cronológico das gerações, os prompts integrais preservados no repositório, ferramentas, modelos, sementes, parâmetros, referências, iterações, descartes e lacunas de documentação.

---

## 1. Eixo do projeto

Criar uma coleção de imagens que revele progressivamente uma civilização fictícia desaparecida. Cada imagem representa uma nova descoberta — objeto, documento, estrutura ou possível cena do passado — e deve partir do conhecimento construído pelas anteriores. O que varia é o tipo de descoberta e o que ela revela; o que se repete é a necessidade de acrescentar informação relevante. Para pertencer à coleção, uma geração precisa complementar, aprofundar ou contradizer de forma coerente o que já havia sido estabelecido.

A ordem é parte do projeto: uma descoberta aceita modifica o contexto disponível para a próxima. A civilização, portanto, não foi escrita inteira antes das imagens; ela foi construída durante o processo de geração, avaliação, aceitação, iteração e descarte.

---

## 2. O que foi feito na mão pelo grupo

A intervenção humana documentada foi principalmente **conceitual, autoral e curatorial**. O grupo definiu a ideia inicial, o eixo, as regras de continuidade, os pontos de partida de cada descoberta, os elementos que deveriam se repetir ou variar, as restrições dos prompts e as referências utilizadas. Depois de cada geração, o grupo avaliou o que a imagem efetivamente mostrava, decidiu se o resultado seria aceito, iterado ou descartado e atualizou o conhecimento acumulado. O descarte da primeira tentativa da descoberta 10 foi uma decisão humana: a imagem era plausível, mas afirmava alimentação, cozinha e relação funcional antes de haver evidência suficiente. Não há registro de edição manual ou pós-produção das imagens finais; o trabalho manual documentado está na concepção, escrita/ajuste dos prompts, seleção de referências, avaliação, interpretação, descrição, organização da sequência e curadoria da coleção.

### 2.1 Responsabilidade do grupo e da IA

| Etapa | Responsável principal | Registro |
|---|---|---|
| Ideia inicial e eixo | Grupo | discussão e uso das skills de ideação |
| Escolha da próxima direção | Grupo | ponto de partida de cada descoberta |
| Construção e ajuste dos prompts | Grupo, com apoio das ferramentas conversacionais | arquivos em `prompts/` |
| Geração das imagens | IA | ChatGPT nas descobertas 01–08; Codex + gerador integrado nas 09–10; 11–12 sem ferramenta registrada no repositório |
| Avaliação da imagem | Grupo | aceitar, iterar ou descartar |
| Atualização do conhecimento | Grupo | descrições e caderno de gerações |
| Descarte da cozinha | Grupo | rejeição por salto narrativo |
| Organização da coleção e documentação | Grupo | repositório, descrições e apresentação |

---

## 3. Skills de ideação — quatro linhas

- **`abrir-o-leque`:** transformou a ideia de um museu de objetos independentes em uma sequência de descobertas arqueológicas conectadas.
- **`afiar-o-eixo`:** definiu a continuidade, o que se repete, o que varia e o critério para uma geração pertencer à coleção.
- **`derrubar-a-ideia`:** testou fragilidades da proposta e levou o grupo a explicitar ordem, acúmulo, descarte e participação humana antes e depois da geração.
- **`escutar-a-reuniao`:** ficou registrada, mas não foi utilizada no desenvolvimento documentado desta coleção.

---

## 4. Sementes, modelos e parâmetros — visão geral

| # | Descoberta | Data | Ferramenta | Modelo | Parâmetros registrados | Referência principal |
|---:|---|---|---|---|---|---|---|
| 01 | Estela das Três Correntes | 22/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | nenhuma |
| 02 | O Limiar Apagado | 22/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | descoberta 01 |
| 03 | A Câmara do Terceiro Vazio | 23/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | descobertas 01–02 |
| 04 | O Disco Oculto | 23/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | descobertas anteriores / descrições 01 e 03; imagem 02 |
| 05 | A Mesa das Três Ofertas | 23/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | descobertas 01–04 |
| 06 | O Fragmento das Três Rotas | 23/09/2026 | ChatGPT | não informado pela interface | 4:5, vertical | imagens 01, 04 e 05 |
| 07 | A Confluência Vazia | 24/09/2026 | ChatGPT | 5.6-Sol-medium | 4:5, vertical ou próxima disso | imagens 06 e 01, nessa ordem |
| 08 | O Tecido das Três Tramas | 24/09/2026 | ChatGPT | 5.6-Sol-medium | 4:5, vertical | imagem 07 |
| 09 | O Cesto de Travessia | 24/09/2026 | Codex + gerador de imagens integrado | não informado | 4:5; arquivo final 1122 × 1402 px | imagem e descrição 08 |
| 10 | Os Recipientes do Cesto | 24/09/2026 | Codex + gerador de imagens integrado | não informado | 4:5; arquivos 1122 × 1402 px | imagem e descrição 09; imagem 01 na tentativa descartada |
| 11 | A Grade dos Quatro Espaços | 28/09/2026 | não registrado | não registrado | não registrados | não registrada | continuação material do Cesto de Travessia, conforme descrição final |
| 12 | A Placa das Quatro Partes | 28/09/2026 | não registrado | não registrado | não registrados | não registrada | continuação da descoberta 11, conforme descrição final |

---

## 5. Definição e teste do eixo — 09/09/2026

## Ponto de partida

Antes da utilização das skills, o grupo já havia discutido uma ideia inicial:
criar um museu virtual de uma civilização fictícia que desapareceu.

A proposta era permitir que o visitante conhecesse essa civilização através
de documentos históricos, objetos e outros elementos encontrados no museu.
Cada objeto teria sua própria história e revelaria uma parte da civilização,
permitindo compreender aos poucos sua cultura, cotidiano e acontecimentos
importantes.

Apesar de gostarmos da ideia, ela ainda estava bastante aberta. Não estava
claro o que conectaria os diferentes artefatos além de todos pertencerem à
mesma civilização.

---

# 1. Abrir o leque

**Skill utilizada:** `abrir-o-leque`

Mesmo já tendo uma ideia inicial, utilizamos a skill para explorar outras
possibilidades antes de assumir que o formato do museu seria o eixo definitivo
do projeto.

A modalidade escolhida pelo grupo foi **imagem**, enquanto o assunto que já
estava sendo considerado era o museu de uma civilização fictícia desaparecida.

A skill gerou diferentes possibilidades de coleções dentro desse tema. Entre
as possibilidades discutidas, uma chamou especialmente nossa atenção:

> Organizar a coleção como uma escavação arqueológica, em que cada nova
> imagem corresponde a uma descoberta progressivamente mais antiga e pode
> alterar aquilo que se acreditava sobre a civilização.

O grupo decidiu explorar essa direção porque ela adicionava algo que faltava
na proposta inicial: uma relação entre as imagens.

Em vez de simplesmente termos vários objetos pertencentes ao mesmo museu,
passamos a considerar que os artefatos poderiam representar etapas de uma
investigação, na qual cada descoberta acrescenta conhecimento sobre a
civilização.

A partir disso, mantivemos a ideia do museu virtual, mas incorporamos a
estrutura de uma descoberta arqueológica progressiva.

---

# 2. Afiar o eixo

**Skill utilizada:** `afiar-o-eixo`

Depois de escolher essa direção, utilizamos a skill para tentar transformar a
ideia em um eixo mais específico.

## 2.1 Restrição

Uma primeira possibilidade discutida foi estabelecer que a civilização nunca
poderia aparecer diretamente.

Nesse formato, só poderiam aparecer ruínas, documentos, objetos e outros
vestígios deixados por ela.

O grupo decidiu **não adotar essa restrição**.

Apesar de ela criar uma regra visual forte, percebemos que gostaríamos de
manter a possibilidade de representar cenas do passado caso uma descoberta
permitisse reconstruí-las.

A discussão então passou a ser:

> Como manter essa liberdade narrativa sem transformar a coleção em um
> conjunto de imagens independentes?

Decidimos que **toda imagem deverá estar vinculada a alguma descoberta da
escavação**.

Assim, uma imagem pode mostrar um objeto, documento, estrutura ou até uma
cena do passado, mas ela precisa surgir a partir do processo de descoberta e
do conhecimento disponível naquele momento.

---

## 2.2 O que se repete e o que varia

O grupo definiu que o elemento constante da coleção será o processo de
descoberta.

Toda imagem deverá acrescentar alguma informação sobre a civilização.

O que varia será principalmente:

- o tipo de vestígio encontrado;
- a informação revelada;
- a parte da civilização que está sendo investigada.

Isso permite que a coleção tenha objetos, documentos, estruturas, inscrições,
reconstruções de cenas e outros elementos sem que cada imagem seja um
recomeço independente.

Também discutimos se cada nova descoberta deveria obrigatoriamente contradizer
alguma descoberta anterior.

Achamos que isso poderia tornar a progressão artificial.

Decidimos então que cada descoberta precisa **acrescentar informação nova**,
mas não necessariamente contradizer algo.

Algumas descobertas podem complementar ou aprofundar informações anteriores,
enquanto outras podem revelar contradições e mudar a interpretação do que já
havia sido encontrado.

---

## 2.3 Critério de pertencimento

Inicialmente, relacionar uma imagem à escavação parecia suficiente.

Durante a discussão percebemos que essa regra ainda permitiria incluir
praticamente qualquer imagem: bastaria afirmar que aquele objeto havia sido
encontrado.

Por isso adicionamos um segundo critério.

Para entrar na coleção, a descoberta precisa:

1. estar relacionada ao processo de descoberta da civilização;
2. acrescentar informação relevante sobre a civilização, seus habitantes ou
   sua história.

Portanto, uma imagem não deverá entrar na coleção apenas porque o resultado
visual ficou interessante.

---

# 3. Derrubar a ideia

**Skill utilizada:** `derrubar-a-ideia`

Depois de definir o eixo, utilizamos a skill como um teste. A proposta foi
tentar encontrar situações nas quais nosso eixo deixaria de funcionar.

---

## Ataque 1 — Isso é uma coleção ou apenas um lote?

O primeiro questionamento foi sobre o que realmente conectaria os diferentes
vestígios.

Consideramos, por exemplo, uma coleção contendo:

- uma estrutura semelhante a uma casa abandonada;
- uma grande escultura cuja função ainda não é conhecida;
- um objeto metálico de formato estranho;
- inscrições ou documentos encontrados durante a exploração.

Inicialmente pensamos que a descrição de cada imagem poderia estabelecer essa
relação.

Por exemplo, uma inscrição poderia vir acompanhada de uma interpretação dos
pesquisadores indicando que determinado símbolo parecia estar relacionado a
comida ou alimentação.

Percebemos, porém, que **apenas adicionar uma descrição não seria suficiente**.

Ainda seria possível produzir vários objetos independentes e simplesmente
inventar uma legenda para cada um.

A partir desse questionamento, o grupo definiu uma característica mais forte:

> As descobertas devem construir conhecimento de maneira cumulativa.

Cada novo vestígio deve partir do conhecimento que já existe e acrescentar,
complementar ou contradizer alguma interpretação anterior.

Dessa maneira, os artefatos não representam apenas curiosidades independentes
de um museu. Eles participam da reconstrução progressiva da civilização.

---

## Ataque 2 — A restrição realmente restringe alguma coisa?

O segundo questionamento foi se a regra de que "toda imagem precisa estar
ligada a uma descoberta" realmente restringia a coleção.

Em teoria, seria possível imaginar qualquer coisa e depois inventar uma
descoberta para justificá-la.

Por exemplo:

> Queremos colocar uma nave espacial na coleção?
> Basta dizer que encontramos uma nave espacial.

Isso mostrou que apenas relacionar a imagem a uma descoberta ainda era uma
regra fraca.

O grupo percebeu que existe outra restrição importante: **continuidade**.

Cada nova descoberta deve fazer sentido considerando o estágio atual da
investigação.

Por exemplo, se até determinado momento foram encontradas apenas estruturas,
placas e objetos simples, revelar imediatamente uma enorme nave espacial pode
ser um salto muito grande.

Além de quebrar a progressão, uma descoberta desse tamanho pode revelar
informações demais e diminuir as possibilidades das próximas descobertas.

Portanto, uma ideia pode até aparecer durante o processo, mas sua introdução
precisa fazer sentido diante das evidências disponíveis naquele momento.

---

## Ataque 3 — Se retirarmos quatro artefatos, alguém percebe?

O terceiro teste foi imaginar algumas descobertas sendo removidas da coleção.

Concluímos que isso poderia causar problemas porque as descobertas possuem
dependência entre si.

Uma descoberta posterior pode acrescentar ou modificar uma interpretação
apresentada anteriormente.

Se a descoberta anterior for removida, a posterior pode perder parte do
sentido.

Também podem surgir saltos estranhos na evolução do conhecimento.

Por exemplo:

> vestígios de casas → placas → ??? → ??? → tecnologia espacial

Se as descobertas intermediárias forem removidas, a tecnologia apresentada
posteriormente pode parecer surgir sem nenhuma sustentação.

Da mesma forma, se a descoberta 5 contradiz uma interpretação criada na
descoberta 3, remover a descoberta 3 faz com que a contradição deixe de fazer
sentido.

A partir desse teste, percebemos que **a ordem dos artefatos também faz parte
do eixo da coleção**.

---

## Ataque 4 — Outros grupos poderiam fazer a mesma coisa?

Outro questionamento foi o que diferenciaria nosso projeto de qualquer outro
grupo que decidisse criar imagens de uma civilização fictícia.

Inicialmente pensamos que as próprias imagens e descrições já seriam
suficientemente diferentes.

Porém, percebemos que outro grupo poderia utilizar exatamente o mesmo processo
e apenas começar com outra civilização.

Essa discussão ajudou a esclarecer uma decisão importante que ainda não estava
explícita:

> Não queremos escrever toda a história da civilização primeiro e depois usar
> IA apenas para ilustrá-la.

O grupo estabelecerá uma descoberta e um contexto inicial, mas a civilização
será construída progressivamente durante a própria produção.

Cada geração receberá como contexto aquilo que já foi descoberto.

O grupo também fornecerá um novo ponto de partida para orientar a próxima
descoberta.

O resultado poderá acrescentar, aprofundar ou contradizer informações
anteriores, desde que seja considerado coerente com o estágio atual da
investigação.

Portanto, **não sabemos previamente exatamente como será a civilização no
final da coleção**.

---

## Ataque 5 — Cadê o descarte?

Para testar nosso critério de descarte, imaginamos a seguinte situação:

As primeiras descobertas apresentam casas, inscrições e objetos relativamente
simples.

Em seguida, uma geração produz uma enorme nave espacial e uma descrição
falando sobre a exploração de um "planeta verde".

A nave não seria descartada simplesmente por parecer avançada.

O principal critério seria verificar a relação entre:

- a imagem;
- sua descrição;
- o conhecimento acumulado até aquele momento.

Se descobertas anteriores já sustentassem a existência de tecnologia espacial,
a nave poderia fazer sentido.

Por outro lado, se nada anteriormente mencionasse exploração espacial,
outros planetas ou elementos relacionados, a descoberta estaria introduzindo
informações sem sustentação.

Nesse caso, ela seria descartada.

Assim, definimos que o descarte também funcionará como um **controle da
continuidade da civilização**.

---

## Ataque 6 — A ferramenta está escolhendo por vocês?

Outro risco identificado foi deixar que a IA determinasse toda a evolução da
civilização.

Se simplesmente fornecêssemos o contexto anterior e perguntássemos "qual é a
próxima descoberta?", o grupo teria pouca participação nas decisões.

Decidimos então trabalhar com o seguinte fluxo:

1. analisar o conhecimento acumulado;
2. o grupo escolhe um ponto de partida para a próxima descoberta;
3. o contexto anterior e esse ponto de partida são fornecidos à IA;
4. a IA gera o novo material;
5. o grupo analisa novamente a imagem e sua descrição;
6. o resultado é aceito, ajustado ou descartado;
7. somente os resultados aceitos passam a integrar o contexto das próximas
   descobertas.

Assim, a IA participa da expansão da civilização, mas não decide sozinha qual
direção será seguida.

O grupo interfere **antes e depois da geração**.

---

## Ataque 7 — O que pode dar errado na apresentação?

Tentamos imaginar perguntas ou críticas que poderiam aparecer durante a
apresentação.

Duas surgiram imediatamente:

> "O que vocês criaram e o que a IA criou sozinha?"

e

> "A história da civilização ficou muito fraca."

A primeira pergunta reforçou a importância de registrar as decisões do grupo.

Precisaremos conseguir mostrar quais pontos de partida foram escolhidos por
nós, quais resultados foram propostos pela IA, o que descartamos e quais
decisões alteraram a direção da coleção.

A segunda pergunta revelou um risco mais interessante.

Como não queremos definir toda a história previamente, existe a possibilidade
de termos uma sequência coerente de descobertas, mas que seja superficial ou
pouco interessante.

Por exemplo, poderíamos acabar apenas seguindo uma sequência previsível de
casas, placas, objetos e tecnologias.

Decidimos que, se isso acontecer, o grupo poderá alterar os prompts e,
principalmente, os pontos de partida das próximas descobertas.

Podemos direcionar a investigação para aspectos ainda pouco explorados, como:

- conjunturas políticas;
- guerras e conflitos;
- interesses de diferentes grupos;
- grupos ou raças;
- animais e outras formas de vida;
- organização social;
- cultura e outros aspectos da civilização.

Essas intervenções não devem apagar aquilo que já foi descoberto.

Os novos elementos ainda precisam respeitar o conhecimento acumulado ou
contradizê-lo de maneira justificável.

Assim, podemos influenciar a riqueza da narrativa sem escrever previamente
toda a história.

---

# 4. O que mudou depois dos testes

A ideia inicial era relativamente simples:

> Um museu virtual contendo objetos e documentos de uma civilização fictícia
> desaparecida.

Depois das discussões e dos testes, algumas características passaram a fazer
parte do projeto.

A coleção será **sequencial e cumulativa**.

Uma descoberta não existe isoladamente: ela passa a integrar o conhecimento
disponível para as próximas.

A civilização também **não será totalmente definida previamente**.

O grupo escolherá pontos de partida, enquanto a interação com a IA ajudará a
expandir elementos ainda desconhecidos.

A **continuidade** funcionará como uma das principais restrições.

Nem tudo que a IA produzir será incorporado. Uma geração precisa fazer sentido
considerando aquilo que já foi descoberto.

Por fim, percebemos que **a ordem da coleção importa**. Remover ou reorganizar
determinadas descobertas pode eliminar o contexto necessário para compreender
as posteriores.

---

# 5. Eixo atual

**Título:** Vestígios

**Modalidade:** Imagem

**Tema / Área de exploração:** Arqueologia fictícia e construção generativa
de uma civilização desaparecida por meio de IA.

A ideia do grupo é criar um museu virtual de uma civilização fictícia
desaparecida, que será construída progressivamente ao longo das descobertas.
Partiremos de uma imagem e de um contexto inicial, e cada nova imagem deverá
estar ligada a uma descoberta que faça sentido a partir do conhecimento
acumulado até aquele momento. As imagens podem representar objetos,
documentos, vestígios ou até cenas do passado. O que varia é o tipo de
descoberta e aquilo que ela revela; o que se repete é que toda descoberta
precisa acrescentar alguma informação relevante sobre a civilização. Para
fazer parte da coleção, não basta a imagem ser visualmente interessante: ela
precisa complementar, aprofundar ou contradizer de forma coerente algo que já
tenha sido estabelecido anteriormente.

---

# 6. Próximos passos

Com o eixo definido, os próximos passos serão testar as ferramentas de geração
de imagem e iniciar as primeiras descobertas.

Desde as primeiras gerações serão registrados:

- prompts completos;
- ferramenta e modelo utilizados;
- parâmetros relevantes e seed, quando disponíveis;
- contexto fornecido à IA;
- ponto de partida definido pelo grupo;
- resultados aceitos;
- resultados descartados e seus motivos;
- alterações manuais;
- decisões que modificarem a direção da coleção.

Esse material será utilizado posteriormente no caderno de bordo do projeto.

---

## 6. Registro cronológico das gerações

O texto abaixo preserva o registro cronológico existente no repositório. Ele documenta as decisões do grupo antes e depois das gerações 01–10.

## 22/09/2026 — Preparação da descoberta 01

### Ponto de partida escolhido

O grupo decidiu iniciar a coleção com uma estela de pedra escura encontrada
na entrada de uma estrutura subterrânea ainda não explorada. A peça recebeu o
nome provisório de **Estela das Três Correntes**.

Foram definidos como seus principais elementos três sulcos convergindo para
uma cavidade circular vazia, resíduos de cobre oxidado, inscrições desconhecidas
e um reparo antigo com grampos metálicos.

### Motivo da escolha

A estela permite introduzir uma identidade visual e algumas evidências sobre
a civilização sem determinar antecipadamente toda a sua história. O artefato
sugere a existência de escrita ou notação, trabalho em pedra, uso de metal e
preocupação com a preservação de determinados objetos.

Ao mesmo tempo, o significado das três linhas e da cavidade central permanece
indefinido. Esses elementos poderão ser aprofundados ou reinterpretados por
descobertas posteriores.

### Decisões para a imagem

- apresentar a peça como um achado arqueológico real, e não como um objeto de
  fantasia;
- manter a cavidade central vazia;
- não utilizar símbolos pertencentes a idiomas reais;
- não mostrar habitantes nem reconstruir a civilização nesta primeira etapa;
- incluir sinais de desgaste e um reparo realizado antes do soterramento;
- evitar revelar a função exata do objeto ou a causa do desaparecimento.

### Estado atual

O prompt foi utilizado no ChatGPT e o resultado foi considerado adequado para
a coleção. A imagem apresenta os principais elementos definidos pelo grupo:
os três sulcos convergentes, a cavidade circular vazia, os resíduos de cobre,
as inscrições, os grampos metálicos e o contexto arqueológico.

A imagem foi armazenada em `colecao/01-descoberta/imagem.png`, acompanhada de
sua descrição. O modelo específico, a seed e os demais parâmetros não foram
disponibilizados pela interface utilizada. A quantidade de tentativas não foi
registrada.

### Decisão

Resultado aceito como a primeira descoberta de **Ecos de uma Civilização**.
Seus elementos passam a integrar o conhecimento acumulado e deverão ser
considerados na preparação da descoberta 02.

---

## 22/09/2026 — Preparação da descoberta 02

### Conhecimento considerado

A preparação partiu dos elementos estabelecidos pela Estela das Três
Correntes: a pedra escura, os três sulcos convergentes, as incrustações de
cobre, as inscrições desconhecidas, o reparo antigo e a entrada da estrutura
subterrânea.

### Ponto de partida escolhido

A exploração avançará até o primeiro compartimento da estrutura, onde será
encontrado um portal interno denominado provisoriamente **O Limiar Apagado**.
O portal repetirá o motivo das três correntes, mas uma delas terá sido
deliberadamente destruída enquanto as outras duas permaneceram preservadas.

### Motivo da escolha

Como a coleção terá doze artefatos, o grupo decidiu que a segunda descoberta
deveria produzir um avanço narrativo maior do que apenas encontrar uma peça
complementar à estela. Ao mesmo tempo, ela não deveria revelar a organização
da civilização, o significado definitivo do símbolo ou a causa de seu
desaparecimento.

O apagamento seletivo confirma a recorrência das três correntes e introduz a
primeira evidência de transformação ou conflito. A descoberta questiona a
possível ideia de equilíbrio sugerida pela estela, mas mantém em aberto quem
realizou o apagamento e o que a terceira corrente representava.

### Decisões para a imagem

- utilizar a primeira imagem como referência de materiais e linguagem visual;
- apresentar um portal interno, evitando repetir a composição da estela;
- manter exatamente três faixas identificáveis;
- preservar duas faixas e mostrar destruição intencional somente na terceira;
- distinguir marcas de cinzel de erosão ou quebra natural;
- não introduzir habitantes, corpos, armas ou tecnologia avançada;
- não determinar visualmente o significado das correntes;
- manter a aparência de fotografia arqueológica documental.

### Estado atual

O prompt foi utilizado no ChatGPT com a primeira descoberta como referência
visual. A imagem resultante preserva a pedra escura, o cobre oxidado, o sistema
de inscrições e a aparência documental estabelecidos anteriormente.

O portal apresenta duas correntes preservadas e uma região central destruída,
com marcas que se diferenciam do desgaste natural. O espaço além da entrada
permanece escuro e não antecipa novas descobertas. A imagem foi armazenada em
`colecao/02-descoberta/imagem.png`, acompanhada de sua descrição.

O modelo específico, a seed e os demais parâmetros não foram disponibilizados
pela interface utilizada. A quantidade de tentativas não foi registrada.

### Decisão

Resultado aceito como a segunda descoberta de **Ecos de uma Civilização**.
A recorrência das três correntes e o apagamento intencional de uma delas passam
a integrar o conhecimento acumulado para a preparação da descoberta 03. O
significado das correntes e a autoria ou motivação da destruição permanecem
como questões abertas.

---

## 23/09/2026 — Preparação da descoberta 03

### Conhecimento considerado

A preparação partiu do apagamento intencional registrado no Limiar Apagado: uma
das três faixas do portal teve seu cobre removido, os símbolos raspados e a
pedra marcada por golpes de cinzel, enquanto as outras duas permaneceram
preservadas.

### Ponto de partida escolhido

A exploração avança para além do portal danificado, até uma pequena câmara sem
outras saídas visíveis, batizada provisoriamente de **A Câmara do Terceiro
Vazio**. Ao fundo há um nicho com três receptáculos circulares: dois guardam
discos de cobre oxidado, e o terceiro está vazio, mas com superfície lisa e
polida, sem sinais de violência.

### Motivo da escolha

O grupo decidiu que a terceira descoberta deveria reabrir a interpretação
estabelecida pela descoberta 02, em vez de apenas confirmá-la. Em vez de
reforçar a ideia de destruição, o nicho sugere que o objeto associado à
terceira corrente foi retirado com cuidado — uma remoção, não um ataque. Isso
introduz uma contradição relevante: o mesmo símbolo recebeu tratamentos muito
diferentes em locais distintos da estrutura.

### Decisões para a imagem

- utilizar as duas primeiras imagens como referência de material, pedra e
  oxidação do cobre;
- manter exatamente três receptáculos no nicho;
- preservar dois receptáculos com discos de cobre e resíduo orgânico
  mineralizado;
- apresentar o terceiro receptáculo vazio, mas liso e sem marcas de violência,
  em contraste direto com o dano do portal;
- não revelar o destino do objeto ausente nem quem o retirou;
- manter a aparência de fotografia arqueológica documental.

### Estado atual

O prompt foi utilizado no ChatGPT com as duas primeiras imagens como
referência. O resultado trouxe uma variação em relação ao previsto: em vez de
um receptáculo vazio e polido, o terceiro receptáculo aparece coberto por uma
protuberância lisa e abaulada esculpida na própria pedra, sem nenhum traço de
cobre. O grupo avaliou que essa variação era ainda mais interessante do que a
ideia original, pois sugere um selamento deliberado em vez de uma simples
ausência, reforçando o contraste com o apagamento violento do portal.

A descrição em `colecao/03-descoberta/descricao.md` foi ajustada para refletir
esse resultado. A imagem foi armazenada em `colecao/03-descoberta/imagem.png`.
O modelo específico, a seed e os demais parâmetros não foram disponibilizados
pela interface utilizada.

### Decisão

Resultado aceito como a terceira descoberta de **Ecos de uma Civilização**. O
selamento do terceiro receptáculo passa a integrar o conhecimento acumulado
para a preparação da descoberta seguinte. Permanece em aberto se algo ainda
está oculto sob a protuberância e qual sua relação com o disco de cobre
encontrado na descoberta 04.

---

## 23/09/2026 — Preparação da descoberta 04

### Conhecimento considerado

A preparação partiu da remoção cuidadosa registrada na Câmara do Terceiro
Vazio: um objeto associado à terceira corrente foi retirado de um receptáculo
sem sinais de dano, ao contrário do apagamento violento observado no portal.

### Ponto de partida escolhido

Fora do caminho principal da escavação, a equipe encontra um recuo estreito na
rocha, selado com argamassa, contendo um pequeno disco de cobre oxidado
embrulhado em tecido mineralizado — batizado provisoriamente de **O Disco
Oculto**. O disco repete o motivo das três correntes, mas com uma variação:
as três linhas convergem para uma pequena saliência central, e não para um
vazio.

### Motivo da escolha

Como as descobertas 01 e 03 deixaram cavidades e receptáculos vazios sem
explicação, o grupo decidiu que a quarta descoberta deveria apresentar, pela
primeira vez, um objeto portátil isolado que possa (mas não deva ser
confirmado que) estar relacionado a esses vazios. A variação do símbolo — uma
saliência em vez de um vazio — foi escolhida para aprofundar o motivo das três
correntes sem resolver seu significado, e o cuidado no esconderijo reforça a
leitura de remoção deliberada, e não destruição, iniciada na descoberta 03.

### Decisões para a imagem

- utilizar as descobertas anteriores como referência de material e oxidação;
- fotografar o disco isoladamente, em plano fechado, com escala de referência;
- manter as três linhas sinuosas, agora convergindo para uma saliência central;
- incluir vestígios do tecido mineralizado e do esconderijo selado, sem revelar
  novas salas ao fundo;
- não confirmar se o disco pertence à estela, ao nicho, a nenhum ou a ambos;
- manter a aparência de fotografia arqueológica documental.

### Estado atual

O prompt foi utilizado no ChatGPT com as descobertas anteriores como
referência. A imagem resultante mostra o disco de cobre oxidado em plano
fechado, com as três linhas convergindo para uma saliência central, tecido
mineralizado ao redor da borda, escala métrica e um fragmento de argamassa
visível junto à abertura do esconderijo ao fundo — correspondendo bem ao que
havia sido planejado. A imagem foi armazenada em
`colecao/04-descoberta/imagem.png`, acompanhada de sua descrição.

O modelo específico, a seed e os demais parâmetros não foram disponibilizados
pela interface utilizada.

### Decisão

Resultado aceito como a quarta descoberta de **Ecos de uma Civilização**. A
existência de um objeto deliberadamente escondido, e não destruído, passa a
integrar o conhecimento acumulado. Permanece em aberto se o disco pertence à
cavidade da estela, ao receptáculo selado do nicho, a nenhum dos dois, e quem
o escondeu.

---

## 23/09/2026 — Preparação da descoberta 05

### Conhecimento considerado

A preparação partiu da consolidação de um padrão recorrente em torno de três
partes: a estela apresentou três correntes convergindo para um centro vazio,
o portal revelou o apagamento deliberado de uma delas, o nicho mostrou três
receptáculos com tratamento desigual e o disco oculto indicou que o elemento
associado à terceira corrente havia sido preservado em segredo, e não apenas
destruído.

### Ponto de partida escolhido

A exploração avança para uma pequena câmara lateral, onde a equipe encontra um
bloco baixo de pedra escura, com três cavidades rasas alinhadas na superfície
superior. Duas cavidades preservam resíduos orgânicos mineralizados e vestígios
de cobre oxidado; a terceira, embora intacta, parece ter sido deliberadamente
esvaziada ou limpa. A peça recebeu o nome provisório de **A Mesa das Três
Ofertas**.

### Motivo da escolha

O grupo decidiu que a quinta descoberta deveria ampliar a civilização para além
da arquitetura simbólica e dos objetos isolados, revelando um indício de
prática material concreta. A nova peça sugere que o padrão triplo não era
apenas decorativo, mas organizava ações repetidas — possivelmente oferendas,
partilhas, preparos ou outra forma de procedimento estruturado.

Ao mesmo tempo, a descoberta preserva a ambiguidade necessária ao projeto: não
define se a estrutura é ritual, doméstica, política, funerária ou
administrativa, nem explica de forma definitiva o significado das três partes.
A terceira cavidade, novamente tratada de modo diferente, reforça a continuidade
do mistério sem apenas repetir o apagamento do portal ou o selamento do nicho.

### Decisões para a imagem

- utilizar as descobertas anteriores como referência de pedra, cobre oxidado,
  inscrições e linguagem documental;
- apresentar a peça como um bloco baixo de pedra fixo ao solo, em uma pequena
  câmara lateral;
- manter exatamente três cavidades rasas alinhadas;
- preservar resíduos materiais e vestígios de cobre nas duas primeiras;
- representar a terceira cavidade intacta, porém esvaziada ou raspada, sem
  destruição violenta e sem selamento;
- evitar qualquer confirmação visual definitiva da função da peça;
- manter a aparência de fotografia arqueológica documental.

### Estado atual

O prompt foi utilizado no ChatGPT com as descobertas anteriores como
referência visual. A imagem resultante mostrou com clareza o bloco baixo de
pedra escura em uma pequena câmara lateral, com três cavidades rasas
alinhadas, inscrições discretas e vestígios de cobre oxidado preservados nas
duas primeiras cavidades. A terceira cavidade apareceu intacta, porém mais
limpa e esvaziada, sem marcas de destruição violenta nem selamento,
correspondendo bem ao que havia sido planejado.

A imagem foi armazenada em `colecao/05-descoberta/imagem.png`, acompanhada de
sua descrição. O modelo específico, a seed e os demais parâmetros não foram
disponibilizados pela interface utilizada.

### Decisão

Resultado aceito como a quinta descoberta de **Ecos de uma Civilização**. A
peça passa a integrar a coleção como evidência de que o padrão triplo da
civilização também organizava práticas materiais concretas. A diferença de
tratamento da terceira cavidade permanece como uma nova questão aberta para as
descobertas seguintes.



---

## 23/09/2026 — Preparação da descoberta 06

### Conhecimento considerado

A preparação partiu das cinco primeiras descobertas, nas quais o motivo das
três correntes apareceu em monumentos, arquitetura, receptáculos, objetos e em
uma prática material concreta. Em todas elas, a terceira parte do conjunto
recebeu algum tipo de tratamento diferente ou permaneceu associada a uma lacuna
interpretativa.

### Ponto de partida escolhido

A exploração avança para uma área próxima à Mesa das Três Ofertas, onde a
equipe encontra uma placa larga de pedra escura quebrada em uma das
extremidades. Em sua superfície há relevo baixo, três linhas sinuosas e
agrupamentos de sinais distribuídos em regiões diferentes da peça. A terceira
linha se perde justamente na área fraturada. A peça recebeu o nome provisório
de **O Fragmento das Três Rotas**.

### Motivo da escolha

O grupo decidiu que a sexta descoberta deveria ampliar o universo da
civilização para além dos objetos e das práticas localizadas, introduzindo a
possibilidade de uma organização espacial mais ampla.

A nova peça sugere que o motivo das três correntes pode estar relacionado a
caminhos, regiões, territórios, cursos ou outra forma de estruturar o espaço,
sem definir qual dessas interpretações é a correta.

Também foi considerado importante evitar que toda ausência de informação sobre
a terceira parte fosse explicada por destruição intencional. Neste caso, a
perda da informação parece decorrer da quebra material da peça.

### Decisões para a imagem

- apresentar uma placa larga de pedra escura, caída e parcialmente quebrada;
- utilizar visão quase superior para privilegiar a leitura da superfície;
- manter três linhas sinuosas distribuídas pela peça;
- incluir agrupamentos abstratos de sinais em duas regiões preservadas;
- fazer a terceira linha desaparecer na área fraturada;
- inserir um pequeno motivo circular que dialogue indiretamente com o Disco
  Oculto;
- preservar a estética de fotografia arqueológica documental;
- evitar qualquer confirmação visual definitiva de que a peça representa um
  mapa, rios ou estradas.

### Estado atual

O prompt foi utilizado no ChatGPT com as descobertas anteriores como
referência visual. A imagem resultante apresenta uma placa larga de pedra
escura caída no solo da escavação, vista quase de cima, com três linhas
sinuosas distribuídas pela superfície, agrupamentos de sinais abstratos e
vestígios azul-esverdeados de cobre oxidado.

A terceira linha desaparece na área quebrada da peça, cuja fratura possui
aspecto irregular e antigo, sem indicar apagamento deliberado. Um pequeno motivo
circular preservado em outra região estabelece uma ligação visual indireta com
o Disco Oculto. A imagem foi armazenada em
`colecao/06-descoberta/imagem.png`, acompanhada de sua descrição.

O modelo específico, a seed e os demais parâmetros não foram disponibilizados
pela interface utilizada.

### Decisão

Resultado aceito como a sexta descoberta de **Ecos de uma Civilização**. A
peça passa a integrar a coleção como primeira evidência de que o motivo das
três correntes pode estar ligado à maneira como a civilização representava ou
organizava o espaço, sem determinar ainda se essas linhas correspondem a
caminhos, cursos d’água, territórios ou outra estrutura.

---

## 24/09/2026 — Preparação da descoberta 07

### Conhecimento considerado

A preparação considerou o Fragmento das Três Rotas (06), com suas linhas
distribuídas por uma superfície ampla, e a Estela das Três Correntes (01), em
que três sulcos convergem para uma cavidade central vazia. Também permaneceu
em aberto a possível relação entre essa cavidade e o Disco Oculto (04).

### Ponto de partida escolhido

Foi escolhida uma nova placa de pedra escura, próxima ao Fragmento das Três
Rotas, com três sulcos que se aproximam de uma cavidade circular central. A
peça recebeu o nome **A Confluência Vazia**.

### Motivo da escolha

A sétima descoberta aproxima visualmente duas formas do motivo triplo já
observadas: linhas distribuídas numa placa e linhas que convergem para um
centro. A intenção foi começar a sugerir que esses padrões poderiam fazer
parte de uma organização relacionada, sem determinar se representam caminhos,
territórios, grupos ou outra coisa.

### Decisões para a imagem

- utilizar as imagens 06 e 01 como referências, nessa ordem;
- manter três canais sinuosos convergindo para uma cavidade central vazia;
- preservar pedra escura, resíduos azul-esverdeados de cobre e sinais
  geométricos abstratos;
- não mostrar o disco encaixado nem confirmar a função da placa;
- manter aparência de fotografia arqueológica documental.

### Estado atual

A imagem gerada apresenta uma placa larga e irregular de pedra escura, vista de
cima. Três canais sinuosos com resíduos azul-esverdeados convergem para uma
cavidade circular central vazia. Marcas gravadas acompanham os canais, e a
escala arqueológica e os fragmentos ao redor mantêm o contexto de escavação.
O resultado reúne características visuais da estela e do Fragmento das Três
Rotas, mas não confirma que o disco oculto pertença à placa.

O prompt foi utilizado no ChatGPT com as imagens das descobertas 06 e 01 como
referências. Modelo específico, seed, outros parâmetros e quantidade de
tentativas não foram informados.

### Decisão

Resultado aceito como a sétima descoberta de **Ecos de uma Civilização**. A
possível relação entre os três trajetos e um ponto central passa a ser uma
hipótese visual da coleção. A função da placa, o significado dos sinais e a
relação com o Disco Oculto permanecem em aberto.

### Direção possível para a descoberta 09

Considerar um material diferente de pedra, como um fragmento de tecido
mineralizado preservado no sedimento. Nele, padrões de fibras, manchas de
cobre ou resíduos poderiam sugerir que objetos circulavam entre pontos
associados às três rotas. Essa direção deve ser tratada como possibilidade,
sem afirmar que o tecido é um mapa ou que comprova uma rede de grupos.

---

## 24/09/2026 — Preparação da descoberta 08

### Conhecimento considerado

A preparação partiu da descoberta 07, A Confluência Vazia, que aproximou
visualmente a placa de três rotas e a estela com linhas convergindo para uma
cavidade central. A função da placa e o significado das três partes continuam
desconhecidos.

### Ponto de partida escolhido

O grupo escolheu procurar um objeto de material diferente das placas de pedra
e dos discos de cobre. A equipe encontra tecido mineralizado ao lado da placa
da descoberta 07. O tecido tem três faixas com tramas diferentes, entrelaçadas
em alguns trechos; uma delas foi remendada com fibras diferentes. A imagem
também apresenta uma estrutura retangular de madeira mineralizada aberta.

### Motivo da escolha

A descoberta introduz um artefato possivelmente utilitário e transportável,
em vez de repetir a forma de uma placa ou disco. As faixas distintas, seus
entrelaçamentos e o remendo podem sugerir partes diferentes mantidas em
relação, ou a manutenção de um objeto importante. A possível correspondência
com os canais da placa permanece parcial e não confirma que o tecido e a pedra
eram usados juntos.

### Decisões para a imagem

- utilizar a imagem 07 como referência do ambiente e da placa;
- representar tecido mineralizado, não outra peça de pedra ou metal;
- mostrar três faixas longitudinais de tramas distintas e pontos de união;
- incluir um remendo antigo feito com fibras diferentes;
- manter a correspondência com os canais apenas parcial;
- não explicar definitivamente a função do tecido.

### Estado atual

A imagem gerada mostra o tecido mineralizado disposto sobre parte da placa da
Confluência Vazia. As três faixas têm tramas diferentes; uma região apresenta
um remendo de fibras mais claras. Uma estrutura retangular de madeira
mineralizada aparece aberta nas proximidades. Em alguns trechos as faixas
acompanham os canais da placa, mas a correspondência não é completa.

A imagem foi gerada com o modelo 5.6-Sol-medium, conforme informado. A seed,
outros parâmetros e a quantidade de tentativas não foram informados. O arquivo
foi armazenado em `colecao/08-descoberta/imagem.png`.

### Decisão

Resultado aceito como a oitava descoberta de **Ecos de uma Civilização**. O
tecido acrescenta uma evidência material nova e sugere uma possível relação
entre as três faixas e os canais da placa, sem confirmar sua função, sua
origem ou o significado social do padrão.

### Direção possível para a descoberta 09

Desenvolver uma pista deixada pelo tecido sem voltar a um artefato de pedra:
por exemplo, encontrar resíduos ou fibras compatíveis em um objeto de uso
cotidiano, ou vestígios de que o tecido servia para envolver ou transportar
algo relacionado às três partes. A descoberta pode começar a dar contexto à
circulação ou manutenção entre diferentes pontos, mantendo a função exata em
aberto.

---

## 24/09/2026 — Preparação da descoberta 09

### Conhecimento considerado

A preparação partiu do Tecido das Três Tramas (08), encontrado sobre a placa da
Confluência Vazia. O tecido possuía três faixas de tramas diferentes, uma delas
reparada, mas ainda não havia evidência suficiente para determinar se sua
função era simbólica, cartográfica, decorativa ou utilitária.

### Ponto de partida escolhido

Ampliar a escavação na mesma área e encontrar um cesto de transporte oblongo,
feito de fibras vegetais e madeira mineralizadas. Três tiras compatíveis com as
faixas da descoberta anterior permanecem presas à armação como alças,
amarrações ou divisórias de carga. A peça recebeu o nome **O Cesto de
Travessia**.

### Motivo da escolha

O grupo decidiu que a nova descoberta deveria começar a revelar aspectos da
vida cotidiana da civilização sem abandonar o conhecimento já construído. O
cesto transforma o tecido de uma evidência ambígua em parte de um objeto
utilitário e introduz as possibilidades de transporte, armazenamento e
distribuição de materiais.

Ao mesmo tempo, a descoberta não confirma que as três faixas correspondam às
rotas das placas, nem que o cesto tenha sido usado em comércio ou por grupos
sociais específicos.

### Decisões para a imagem

- utilizar a descoberta 08 como referência visual das fibras e do ambiente;
- representar um cesto de transporte usado e parcialmente colapsado;
- manter as três tiras como partes funcionais da estrutura;
- incluir resíduos orgânicos, cerâmica e material mineral misturados;
- evitar compartimentos perfeitamente separados;
- não retornar a uma placa, estela ou objeto predominantemente simbólico;
- manter a fotografia arqueológica documental em formato vertical.

### Estado atual

A imagem gerada apresenta um cesto oblongo com armação de madeira, amarrações
de fibras e três tiras têxteis distintas. Uma delas conserva a coloração
azul-esverdeada associada ao cobre, enquanto outra apresenta um reparo antigo.
No interior aparecem resíduos escurecidos, fragmentos cerâmicos e sedimento.

A imagem foi gerada no Codex com o gerador de imagens integrado, utilizando a
descoberta 08 como referência. O modelo específico, a seed e os demais
parâmetros não foram informados. O resultado possui 1122 × 1402 pixels e foi
armazenado em `colecao/09-descoberta/imagem.png`.

### Decisão

Resultado aceito como a nona descoberta de **Ecos de uma Civilização**. O uso
prático das tramas e a existência de um objeto de transporte passam a integrar
o conhecimento acumulado. A identidade dos resíduos e a função original do
cesto permanecem em aberto.

---

## 24/09/2026 — Preparação da descoberta 10

### Conhecimento considerado

A preparação partiu diretamente do Cesto de Travessia (09). A peça demonstrou
que as tramas da descoberta 08 podiam ser usadas em um objeto utilitário e
apresentou resíduos escurecidos, fragmentos cerâmicos e material mineral em seu
interior.

### Primeira direção considerada

Inicialmente foi proposta uma área de preparo de alimentos em uma câmara
adjacente, com fogareiro, pedra de moagem e um recipiente cerâmico reparado. A
imagem correspondente chegou a ser gerada.

Durante a avaliação, o grupo percebeu que essa passagem exigia três conclusões
ainda não sustentadas: tratar os resíduos como alimento, presumir a existência
de uma cozinha próxima e estabelecer uma relação funcional entre os dois
espaços. A geração foi descartada por salto narrativo e preservada em
`descartes/imagens/10-cozinha-salto-narrativo.png`.

### Ponto de partida revisado

Continuar a escavação do próprio Cesto de Travessia. A remoção da camada
superior revela quatro pequenos recipientes cerâmicos de formato semelhante e
em diferentes estados de conservação. A descoberta recebeu o nome **Os
Recipientes do Cesto**.

### Motivo da escolha

A direção revisada acrescenta apenas um novo degrau ao conhecimento: depois de
identificar o transporte de materiais, a coleção passa a investigar como essas
cargas poderiam ser retiradas, separadas, servidas ou medidas.

Os recipientes sugerem uma prática organizada, mas não confirmam padronização,
alimentação, comércio ou administração. Dessa forma, a descoberta amplia a
vida cotidiana sem depender de um novo espaço ou de uma função já definida.

### Decisões para a imagem

- utilizar a imagem 09 como referência direta do mesmo cesto;
- aproximar o enquadramento de seu interior;
- mostrar quatro recipientes, evitando repetir um conjunto de exatamente três;
- variar o estado de conservação das peças;
- manter resíduos escurecidos e material mineral claro;
- incluir marcas de uso e uma ligação por cordão de fibra;
- não introduzir cozinha, casa, mercado ou função alimentar confirmada;
- preservar a fotografia arqueológica documental.

### Estado atual

A segunda imagem gerada mostra o interior do mesmo cesto após a retirada de
parte das fibras e do sedimento. Dois recipientes aparecem relativamente
íntegros, um está rachado e outro fragmentado. Resíduos escurecidos permanecem
em algumas peças, enquanto uma delas contém uma crosta mineral clara. Um
cordão de fibra passa pelo cabo de um dos recipientes.

A imagem foi gerada no Codex com a descoberta 09 como referência. O modelo
específico, a seed e os demais parâmetros não foram informados. O resultado
possui 1122 × 1402 pixels e foi armazenado em
`colecao/10-descoberta/imagem.png`.

### Decisão

Segunda geração aceita como a décima descoberta de **Ecos de uma Civilização**.
A coleção passa a incluir evidências de que os materiais transportados eram
manipulados com um conjunto de recipientes utilitários. Sua função exata e a
identidade dos resíduos continuam abertas.

### Direção possível para a descoberta 11

Uma descoberta posterior pode analisar um dos materiais do cesto ou procurar,
em outro ponto da escavação, uma evidência intermediária de onde esses
recipientes eram utilizados. Para preservar a progressão, a próxima etapa deve
testar apenas uma hipótese — alimentação, distribuição, produção ou outra — em
vez de confirmar várias delas ao mesmo tempo.

### Continuação do registro — descobertas 11 e 12

#### 28/09/2026 - Descoberta 11 — A Grade dos Quatro Espaços

**O que foi feito na mão:** A descrição final registra a decisão conceitual de revelar uma grade interna com três ripas e quatro espaços, aprofundando a separação de materiais e reinterpretando o padrão triplo. O repositório não registra o prompt ou a sessão de geração.

**Resultado registrado:** a retirada dos recipientes revelou uma grade de madeira mineralizada e fibras, composta por três ripas que formavam quatro espaços. Os espaços continham resíduos diferentes e uma das ripas havia sido reparada. A descoberta permitiu considerar que três elementos poderiam funcionar como divisórias de quatro áreas, e não apenas representar três entidades.

#### 28/09/2026 - Descoberta 12 — A Placa das Quatro Partes

**O que foi feito na mão:** A descrição final registra a decisão conceitual de conectar a grade a uma placa portátil com três sulcos e quatro campos, reunindo inscrições, cobre, transporte e separação de materiais. O repositório não registra o prompt ou a sessão de geração.

**Resultado registrado:** uma placa portátil presa à grade apresenta três sulcos que dividem a superfície em quatro campos, com resíduos de cobre, inscrições e vestígios materiais distintos. A peça conecta o sistema de marcas às práticas de separação e transporte sem resolver o significado das inscrições.

---

## 7. Registro manual por descoberta

Esta seção torna explícita a intervenção humana em cada etapa, sem atribuir ao grupo ações que não estejam documentadas.

### 01 — Estela das Três Correntes

O grupo definiu o artefato inicial, seus elementos obrigatórios e os limites do que não deveria ser revelado; avaliou a geração e decidiu incorporá-la à coleção.

### 02 — O Limiar Apagado

O grupo escolheu avançar para o primeiro compartimento, decidiu que o padrão reapareceria na arquitetura com uma faixa apagada, definiu as restrições visuais e avaliou o resultado.

### 03 — A Câmara do Terceiro Vazio

O grupo propôs três receptáculos e uma diferença não violenta na terceira posição. A IA gerou uma protuberância selando o terceiro receptáculo; o grupo decidiu aceitar essa variação e reescreveu a descrição para refletir o selamento.

### 04 — O Disco Oculto

O grupo decidiu introduzir um objeto portátil escondido, estabeleceu que sua relação com os vazios anteriores permaneceria inconclusiva e selecionou o resultado final.

### 05 — A Mesa das Três Ofertas

O grupo direcionou a coleção para uma prática material concreta, definiu três cavidades com tratamentos diferentes e manteve a função da estrutura deliberadamente em aberto.

### 06 — O Fragmento das Três Rotas

O grupo escolheu testar uma possível dimensão espacial do padrão e, ao mesmo tempo, evitar que toda ausência fosse explicada como destruição intencional; por isso a terceira linha termina numa fratura antiga.

### 07 — A Confluência Vazia

O grupo decidiu aproximar os trajetos da descoberta 06 da convergência da descoberta 01, escolheu as duas imagens de referência e manteve a cavidade central sem explicação definitiva.

### 08 — O Tecido das Três Tramas

O grupo escolheu mudar de material e introduzir um objeto flexível, transportável e reparado, preservando apenas uma correspondência parcial com os canais da placa anterior.

### 09 — O Cesto de Travessia

O grupo direcionou a investigação para o cotidiano, escolheu transformar as tramas em partes funcionais de um cesto de transporte e avaliou a geração antes de incorporá-la.

### 10 — Os Recipientes do Cesto

O grupo gerou e rejeitou uma primeira proposta de cozinha por salto narrativo. Depois voltou ao mesmo cesto, definiu uma descoberta intermediária com quatro recipientes e aceitou a segunda geração.

### 11 — A Grade dos Quatro Espaços

A descrição final registra a decisão conceitual de revelar uma grade interna com três ripas e quatro espaços, aprofundando a separação de materiais e reinterpretando o padrão triplo. O repositório não registra o prompt ou a sessão de geração.

### 12 — A Placa das Quatro Partes

A descrição final registra a decisão conceitual de conectar a grade a uma placa portátil com três sulcos e quatro campos, reunindo inscrições, cobre, transporte e separação de materiais. O repositório não registra o prompt ou a sessão de geração.

---

## 8. Prompts na íntegra

A seguir estão os registros completos existentes em `prompts/`. Os blocos de prompt foram preservados integralmente, inclusive instruções negativas, referências, parâmetros e observações de iteração. Isso inclui a primeira tentativa descartada da descoberta 10.



---

# Descoberta 01 — Estela das Três Correntes

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Criar o primeiro artefato da coleção e estabelecer um ponto de partida visual
e narrativo para a construção progressiva da civilização, sem definir
antecipadamente sua história completa ou a causa de seu desaparecimento.

A imagem deve introduzir indícios de escrita, trabalho em pedra, uso de metal
e preservação de objetos importantes. Também deve apresentar elementos
ambíguos que possam ser investigados nas próximas descobertas.

## Contexto

Esta é a primeira descoberta do projeto. Antes dela, sabe-se apenas que uma
civilização desconhecida ocupou o local e desapareceu. Ainda não existem
informações confirmadas sobre seus habitantes, sua organização, suas crenças,
sua tecnologia ou os acontecimentos que levaram ao seu desaparecimento.

## Ponto de partida do grupo

O primeiro artefato será uma estela de pedra escura encontrada durante a
escavação da entrada de uma estrutura subterrânea ainda não explorada.

A estela possui três sulcos sinuosos que convergem para uma cavidade circular
vazia, inscrições desconhecidas e um reparo antigo feito com grampos
metálicos. Esses elementos devem funcionar como evidências, mas seu significado
deve permanecer em aberto.

## Prompt

```text
Fotografia arqueológica documental, extremamente realista, de uma estela
antiga recém-descoberta em uma escavação. A estela está em posição quase
vertical, parcialmente enterrada diante da entrada escura de uma estrutura
subterrânea ainda não explorada. Ela mede aproximadamente um metro de altura,
com uma escala métrica arqueológica discreta ao lado.

A peça é feita de pedra muito escura, entre negra e verde-profunda, com
superfície irregular, bordas quebradas, erosão, terra úmida e marcas de grande
antiguidade. Na face frontal existem exatamente três sulcos sinuosos e
distintos. Os três percorrem a pedra e convergem para uma única cavidade
circular vazia no centro. Restos descontínuos de uma liga de cobre oxidada,
em tons azul-esverdeados, permanecem incrustados dentro dos sulcos. A cavidade
central está vazia: não contém gema, luz, mecanismo visível ou qualquer objeto.

Ao redor dos sulcos há pequenas sequências de símbolos desconhecidos gravados
na pedra. Os símbolos possuem um sistema visual coerente e alguns sinais se
repetem, sugerindo escrita ou notação, mas não formam letras ou palavras de
nenhum idioma moderno. Uma fratura antiga na parte inferior da estela foi
reparada pelos próprios habitantes da civilização com grampos metálicos
envelhecidos e corroídos. O reparo deve parecer funcional e muito anterior à
escavação moderna.

A estela é o foco absoluto da composição. Nas bordas da cena aparecem apenas
elementos discretos de trabalho arqueológico contemporâneo: pincel, pequenas
estacas de marcação, barbante e parte de uma bandeja com terra. Nenhuma pessoa
é visível. Iluminação natural suave e difusa, cores terrosas e pouco saturadas,
texturas físicas convincentes, profundidade de campo moderada, enquadramento
vertical frontal em proporção 4:5, aparência de fotografia de campo feita para
documentar uma descoberta real.

Evitar estética de fantasia, brilho mágico, runas reconhecíveis, hieróglifos
egípcios, letras modernas, texto legível, pedra limpa ou polida, objeto inteiro
perfeitamente preservado, excesso de ornamentos, ouro, joias, esqueletos,
personagens, arquitetura grandiosa, ficção científica explícita, iluminação
cinematográfica dramática e aparência de ilustração ou renderização 3D.
```

## Elementos obrigatórios para avaliação

- estela de pedra escura parcialmente enterrada;
- exatamente três sulcos convergindo para uma cavidade circular vazia;
- resíduos de cobre oxidado nos sulcos;
- inscrições coerentes, mas não pertencentes a um idioma conhecido;
- reparo antigo com grampos metálicos;
- contexto visual de escavação arqueológica;
- aparência de fotografia documental, sem elementos mágicos explícitos.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

Nenhuma imagem de referência foi utilizada na preparação deste primeiro
prompt.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/01-descoberta/imagem.png`](../colecao/01-descoberta/imagem.png).

## Resultado

Resultado aceito e incorporado como a primeira descoberta da coleção.


---

# Descoberta 02 — O Limiar Apagado

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir a segunda descoberta da coleção a partir da exploração inicial da
estrutura subterrânea localizada atrás da Estela das Três Correntes.

O novo artefato deve confirmar que o motivo das três correntes também fazia
parte da arquitetura da civilização e introduzir a primeira evidência de uma
alteração intencional: uma das três linhas foi apagada enquanto as outras duas
foram preservadas.

## Contexto acumulado

A primeira descoberta revelou uma estela de pedra escura com três sulcos
sinuosos convergindo para uma cavidade circular vazia. Os sulcos conservam
resíduos de uma liga à base de cobre, e inscrições desconhecidas aparecem ao
seu redor. A peça também possui um reparo antigo com grampos metálicos.

Até o momento, sabe-se apenas que a civilização produzia inscrições, combinava
pedra e metal e atribuía importância suficiente a determinados objetos para
repará-los. O significado das três linhas e da cavidade permanece desconhecido.

## Ponto de partida do grupo

Ao avançar para o primeiro compartimento da estrutura subterrânea, a equipe
encontra um portal interno construído com a mesma pedra da estela. Três faixas
sinuosas originalmente decoravam seu lintel, acompanhadas por grupos distintos
de inscrições.

Duas faixas ainda preservam cobre oxidado e inscrições. A terceira foi
deliberadamente destruída: o metal foi retirado, os símbolos foram raspados e
a pedra apresenta marcas repetidas de ferramentas antigas.

O artefato não deve revelar o significado das linhas nem quem realizou o
apagamento. A imagem deve mostrar apenas evidências materiais suficientes para
distinguir a destruição intencional do desgaste natural.

## Prompt

Antes da geração, utilizar a imagem da **Estela das Três Correntes** como
referência visual para os materiais, a oxidação do cobre, o estilo das
inscrições e a aparência documental, sem copiar sua composição.

```text
Usando a imagem de referência da Estela das Três Correntes apenas para manter
continuidade visual, crie uma fotografia arqueológica documental extremamente
realista de uma nova descoberta no interior da mesma escavação.

A cena mostra frontalmente um antigo portal de pedra encontrado no primeiro
compartimento subterrâneo. O portal permanece parcialmente em sua posição
original, cercado por rocha escavada, sedimentos compactados e pequenos
fragmentos no chão. O interior além do portal é escuro e não revela novas
salas, pessoas ou objetos. A arquitetura é funcional, pesada e desgastada, sem
monumentalidade exagerada.

O portal é construído com a mesma pedra muito escura, entre negra e
verde-profunda, vista na estela de referência. No lintel largo acima da
abertura existem exatamente três faixas sinuosas distintas, gravadas com o
mesmo vocabulário visual dos três sulcos da primeira descoberta. As três
faixas devem ser fáceis de distinguir.

Duas das faixas permanecem preservadas. Elas conservam incrustações
descontínuas de liga de cobre oxidada em tons azul-esverdeados e são
acompanhadas por pequenas sequências de símbolos desconhecidos. Os símbolos
formam sistemas coerentes e semelhantes aos da estela, mas não correspondem a
letras, palavras, runas ou hieróglifos reconhecíveis.

A terceira faixa foi deliberadamente apagada na Antiguidade. Nessa faixa, o
cobre foi arrancado, os símbolos próximos foram raspados e a superfície possui
marcas profundas e repetidas de cinzel. Ainda devem existir vestígios fracos do
sulco original sob a área destruída, permitindo perceber que ali havia uma
terceira faixa semelhante às outras. O dano intencional deve ser claramente
diferente da erosão natural presente no restante do portal. Não adicionar
símbolos modernos, avisos ou explicações visuais sobre o apagamento.

A fotografia deve parecer um registro feito durante a escavação: iluminação
artificial arqueológica suave e neutra, textura física convincente, cores
terrosas pouco saturadas, poeira, umidade discreta, escala métrica, pequenas
estacas e fios de marcação nas bordas da cena. Nenhuma pessoa aparece. O portal
e, especialmente, o contraste entre as duas faixas preservadas e a terceira
apagada são o foco da composição. Enquadramento frontal vertical em proporção
4:5, profundidade de campo moderada e aparência de fotografia de campo real.

Evitar brilho mágico, símbolos luminosos, fantasia, arquitetura egípcia,
maia, romana ou medieval reconhecível, caveiras, corpos, alta tecnologia,
máquinas, armas, criaturas, personagens, inscrições modernas, texto legível,
ornamentação excessiva, ouro, pedras preciosas, iluminação cinematográfica
dramática, ruína grandiosa, ilustração, pintura ou aparência de renderização
3D. Não transformar a faixa apagada em uma quebra natural: ela deve apresentar
evidência clara de raspagem e golpes intencionais feitos com ferramentas
antigas.
```

## Elementos obrigatórios para avaliação

- portal interno feito de pedra semelhante à da primeira estela;
- exatamente três faixas sinuosas identificáveis no lintel;
- duas faixas preservadas com cobre oxidado e inscrições;
- terceira faixa com metal removido, símbolos raspados e marcas de cinzel;
- diferença visual clara entre dano intencional e erosão natural;
- contexto subterrâneo coerente com a entrada vista na descoberta 01;
- fotografia arqueológica documental, sem elementos mágicos;
- nenhuma explicação definitiva sobre o significado das três faixas.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- [`colecao/01-descoberta/imagem.png`](../colecao/01-descoberta/imagem.png):
  referência para materiais, inscrições, oxidação e linguagem documental;
- [`colecao/01-descoberta/descricao.md`](../colecao/01-descoberta/descricao.md):
  conhecimento estabelecido pela primeira descoberta.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/02-descoberta/imagem.png`](../colecao/02-descoberta/imagem.png).

## Resultado

Resultado aceito e incorporado como a segunda descoberta da coleção.


---

# Descoberta 03 — A Câmara do Terceiro Vazio

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir a terceira descoberta da coleção avançando pela estrutura
subterrânea para além do Limiar Apagado, introduzindo a primeira evidência de
que o motivo das três correntes também estava associado a objetos portáteis,
e não apenas à decoração arquitetônica.

O artefato deve reabrir a interpretação estabelecida na descoberta 02: em vez
de reforçar a ideia de destruição violenta, deve sugerir que o elemento
"apagado" pode ter sido removido com cuidado, e não destruído.

## Contexto acumulado

A primeira descoberta revelou uma estela com três sulcos convergindo para uma
cavidade circular vazia, resíduos de cobre oxidado, inscrições desconhecidas
e um reparo antigo. A segunda descoberta revelou um portal interno com o
mesmo motivo de três faixas, das quais duas permanecem preservadas e uma foi
deliberadamente apagada, com o cobre removido, símbolos raspados e marcas de
cinzel.

Até o momento, sabe-se que o símbolo das três correntes é recorrente na
arquitetura da civilização e que uma de suas partes foi alvo de um apagamento
intencional, de motivação ainda desconhecida.

## Ponto de partida do grupo

Ao ultrapassar o portal danificado, a equipe encontra uma pequena câmara sem
outras saídas visíveis. Ao fundo, um nicho esculpido na rocha contém três
receptáculos circulares. Dois guardam pequenos discos de cobre oxidado; o
terceiro está vazio, mas sem sinais de violência — sua superfície é lisa e
polida, sugerindo remoção cuidadosa, e não destruição.

O artefato não deve explicar o que os discos representam, nem quem retirou o
terceiro objeto. A imagem deve apenas tornar visível o contraste entre a
ausência "violenta" do portal e a ausência "cuidadosa" do nicho.

## Prompt

Antes da geração, utilizar as imagens de referência da **Estela das Três
Correntes** e do **Limiar Apagado** para manter continuidade de materiais,
cor da pedra, oxidação do cobre e linguagem documental, sem repetir suas
composições.

```text
Usando as imagens de referência da Estela das Três Correntes e do Limiar
Apagado apenas para manter continuidade visual, crie uma fotografia
arqueológica documental extremamente realista de uma nova descoberta no
interior da mesma escavação subterrânea.

A cena mostra o interior de uma pequena câmara de pedra escavada na rocha,
vista de frente, logo além do portal danificado. O espaço é baixo, sem
saídas adicionais visíveis, com paredes irregulares e piso coberto por
sedimento fino recém-removido. Ao fundo da câmara, centralizado na
composição, há um nicho esculpido diretamente na rocha, contendo três
receptáculos circulares pequenos e rasos, dispostos lado a lado em uma
fileira horizontal, no mesmo eixo das três faixas do portal de referência.

Dois dos receptáculos contêm pequenos discos de liga de cobre oxidada em
tons azul-esverdeados, parcialmente presos por resíduos de um material
orgânico mineralizado e escurecido. O terceiro receptáculo está vazio, mas
sua superfície interna é lisa, uniforme e polida, sem marcas de impacto,
raspagem ou cinzelamento — claramente diferente da textura danificada da
terceira faixa do portal de referência.

A fotografia deve parecer um registro feito durante a escavação: iluminação
artificial arqueológica suave e neutra, textura física convincente, cores
terrosas pouco saturadas, poeira fina no piso, umidade discreta nas paredes,
escala métrica próxima ao nicho, pequenas estacas e fios de marcação
discretos na borda da cena. Nenhuma pessoa aparece. O nicho e o contraste
entre os dois receptáculos preenchidos e o terceiro vazio e polido são o
foco da composição. Enquadramento frontal vertical em proporção 4:5,
profundidade de campo moderada e aparência de fotografia de campo real.

Evitar brilho mágico, símbolos luminosos, fantasia, arquitetura egípcia,
maia, romana ou medieval reconhecível, caveiras, corpos, alta tecnologia,
máquinas, armas, criaturas, personagens, inscrições modernas, texto legível,
ornamentação excessiva, ouro, pedras preciosas, iluminação cinematográfica
dramática, ruína grandiosa, ilustração, pintura ou aparência de renderização
3D. Não representar o terceiro receptáculo como danificado ou quebrado: ele
deve parecer intacto, apenas vazio, com superfície polida por uso ou remoção
cuidadosa.
```

## Elementos obrigatórios para avaliação

- câmara subterrânea coerente com o acesso visto na descoberta 02;
- nicho de pedra com exatamente três receptáculos circulares alinhados;
- dois receptáculos com discos de cobre oxidado e resíduo orgânico
  mineralizado;
- terceiro receptáculo vazio, liso e polido, sem marcas de violência;
- contraste visual claro entre essa ausência "cuidadosa" e o dano do portal;
- fotografia arqueológica documental, sem elementos mágicos;
- nenhuma explicação definitiva sobre o destino do objeto ausente.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- [`colecao/01-descoberta/imagem.png`](../colecao/01-descoberta/imagem.png):
  referência de materiais, cor da pedra e linguagem documental;
- [`colecao/02-descoberta/imagem.png`](../colecao/02-descoberta/imagem.png):
  referência de oxidação do cobre e do contraste entre preservação e dano;
- [`colecao/02-descoberta/descricao.md`](../colecao/02-descoberta/descricao.md):
  conhecimento estabelecido pela segunda descoberta.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/03-descoberta/imagem.png`](../colecao/03-descoberta/imagem.png).

A imagem gerada não apresentou o terceiro receptáculo como um espaço vazio e
polido, como previsto no prompt, mas como uma protuberância lisa e abaulada
esculpida na pedra, cobrindo completamente o receptáculo. O grupo considerou
o resultado coerente com o objetivo da descoberta — manter o contraste entre
o dano violento do portal e um tratamento cuidadoso, não violento, associado
à terceira corrente — e decidiu aceitá-lo, ajustando a descrição para refletir
um selamento deliberado em vez de uma simples ausência.

## Resultado

Resultado aceito e incorporado como a terceira descoberta da coleção.


---

# Descoberta 04 — O Disco Oculto

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir a quarta descoberta da coleção revelando o objeto que, até então,
apenas se sabia ter sido removido com cuidado do nicho da descoberta 03,
introduzindo a primeira peça portátil isolada da coleção e uma variação
inédita do motivo das três correntes.

O artefato deve sugerir uma ligação com a cavidade vazia da estela (descoberta
01) e com o receptáculo vazio do nicho (descoberta 03), sem confirmar se se
trata do mesmo objeto.

## Contexto acumulado

A estela (01) possui uma cavidade central vazia. O portal (02) teve uma de
suas três faixas deliberadamente apagada, com sinais de violência. O nicho
(03) revelou que um objeto associado à mesma terceira corrente foi retirado
sem danos, com uma remoção cuidadosa em vez de destruição.

Até o momento, permanece em aberto o que ocupava a cavidade da estela e o
receptáculo do nicho, e por que a terceira corrente recebeu tratamentos tão
diferentes — apagamento violento em um local e remoção cautelosa em outro.

## Ponto de partida do grupo

Fora do caminho principal da escavação, um recuo estreito na rocha esconde
uma pequena cavidade selada com argamassa. Dentro dela, embrulhado em tecido
mineralizado, está um disco de cobre oxidado com o padrão das três correntes,
mas com uma variação: as três linhas convergem para uma pequena saliência
central, em vez de um vazio.

O artefato não deve confirmar se esse disco pertence à estela, ao nicho, a
nenhum dos dois, ou a ambos. A imagem deve apenas evidenciar o cuidado com
que o objeto foi escondido e a variação do símbolo em relação às descobertas
anteriores.

## Prompt

Antes da geração, utilizar as imagens de referência da **Estela das Três
Correntes**, do **Limiar Apagado** e da **Câmara do Terceiro Vazio** para
manter continuidade de material, oxidação e linguagem documental.

```text
Usando as imagens de referência das descobertas anteriores apenas para manter
continuidade visual de material e oxidação, crie uma fotografia arqueológica
documental extremamente realista, em plano fechado (macro), de um pequeno
artefato recém-encontrado na mesma escavação subterrânea.

A cena mostra um disco metálico de aproximadamente dez centímetros de
diâmetro, apoiado sobre uma superfície plana de escavação coberta por
sedimento fino, com parte de um tecido escurecido e mineralizado, em
frangalhos, ainda enrolado ao redor de sua borda. Ao fundo, fora de foco,
é possível perceber a abertura estreita e irregular de um recuo na rocha
natural, de onde o objeto foi retirado, e um pequeno fragmento de argamassa
antiga próximo à abertura.

O disco é feito de uma liga de cobre oxidada em tons azul-esverdeados,
consistente com o cobre visto nas descobertas anteriores. Sua superfície
apresenta, em relevo, três linhas sinuosas que se curvam a partir da borda e
convergem para o centro do disco, mas, diferentemente das outras
representações do mesmo motivo, aqui as três linhas se unem em uma pequena
saliência circular elevada no centro, e não em um vazio. O relevo deve ser
nítido o suficiente para que as três linhas sejam claramente distinguíveis.

A fotografia deve parecer um registro de campo: iluminação artificial
arqueológica neutra e direcionada, leve sombra projetada pelo próprio disco,
textura física convincente do metal oxidado e do tecido mineralizado, cores
terrosas pouco saturadas, uma pequena escala métrica de referência ao lado do
objeto. Nenhuma pessoa, mão ou luva aparece na cena. Enquadramento vertical
em proporção 4:5, profundidade de campo rasa que mantém o disco em foco
nítido e o fundo desfocado.

Evitar brilho mágico, símbolos luminosos, fantasia, joias, ouro, pedras
preciosas, arquitetura ou iconografia egípcia, maia, romana, celta ou
medieval reconhecível, caveiras, corpos, alta tecnologia, máquinas, armas,
criaturas, personagens, inscrições modernas, texto legível, ornamentação
excessiva, iluminação cinematográfica dramática, ilustração, pintura ou
aparência de renderização 3D. Não tornar o disco brilhante ou polido como
uma joia nova: ele deve parecer um objeto antigo, oxidado e recém-retirado de
um esconderijo seco.
```

## Elementos obrigatórios para avaliação

- disco metálico único, em plano fechado, com escala de referência visível;
- oxidação de cobre consistente com as descobertas anteriores;
- três linhas sinuosas em relevo convergindo para uma saliência central
  (não para um vazio);
- vestígios de tecido mineralizado ao redor da borda do disco;
- indício ao fundo de um esconderijo selado, sem revelar novas salas;
- fotografia arqueológica documental, sem elementos mágicos;
- nenhuma confirmação visual de que o disco pertence à estela ou ao nicho.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- [`colecao/01-descoberta/descricao.md`](../colecao/01-descoberta/descricao.md):
  cavidade central vazia da estela;
- [`colecao/02-descoberta/imagem.png`](../colecao/02-descoberta/imagem.png):
  referência de oxidação do cobre;
- [`colecao/03-descoberta/descricao.md`](../colecao/03-descoberta/descricao.md):
  remoção cuidadosa do objeto associado à terceira corrente.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/04-descoberta/imagem.png`](../colecao/04-descoberta/imagem.png).

A imagem gerada correspondeu bem ao esperado: disco de cobre oxidado em plano
fechado, com as três linhas sinuosas convergindo para uma saliência central,
vestígios de tecido mineralizado ao redor da borda, escala métrica e um
fragmento de argamassa visível ao fundo, junto à abertura do esconderijo.

## Resultado

Resultado aceito e incorporado como a quarta descoberta da coleção.


---

# Descoberta 05 — A Mesa das Três Ofertas

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir a quinta descoberta da coleção revelando um artefato fixo de função ambígua — entre bancada, mesa de uso coletivo ou estrutura ritual — capaz de mostrar que o padrão triplo já observado nas descobertas anteriores não era apenas um símbolo visual, mas também organizava práticas materiais concretas.

A descoberta deve ampliar o conhecimento sobre a civilização sem determinar de forma definitiva se a peça tinha função religiosa, doméstica, política, funerária ou administrativa.

## Contexto acumulado

A estela (01) apresentou o motivo das três correntes convergindo para uma cavidade central vazia. O portal (02) repetiu esse padrão, mas revelou o apagamento intencional de uma das três correntes. O nicho (03) mostrou três receptáculos, dos quais dois permaneciam associados a discos de cobre, enquanto o terceiro aparecia selado. O disco oculto (04) indicou que o elemento relacionado à terceira corrente não havia sido simplesmente destruído, mas retirado de circulação e preservado em segredo.

Até o momento, o padrão triplo aparece de forma recorrente na arquitetura, na iconografia e nos objetos associados à escavação, sempre com algum tipo de assimetria envolvendo a terceira parte.

## Ponto de partida do grupo

Em uma pequena câmara lateral, além do setor principal já explorado, a equipe encontra um bloco baixo de pedra escura, de superfície superior trabalhada, contendo três cavidades rasas lado a lado. Duas dessas cavidades preservam resíduos orgânicos mineralizados, pequenos fragmentos granulares e manchas de cobre oxidado. A terceira, embora intacta, parece ter sido deliberadamente esvaziada ou limpa, sem marcas de destruição violenta.

A peça deve sugerir uma prática material estruturada em três partes — como oferenda, partilha, preparo, consagração ou outro procedimento repetido — sem confirmar sua função exata. A descoberta precisa reforçar a ideia de que a terceira parte voltou a receber tratamento distinto, agora não por destruição nem por selamento, mas por interrupção ou esvaziamento.

## Prompt

Antes da geração, utilizar as imagens de referência das descobertas anteriores para manter continuidade visual de pedra, cobre oxidado, inscrições e linguagem arqueológica documental.

```text
Usando as imagens de referência das descobertas anteriores apenas para manter continuidade visual de material, oxidação e linguagem arqueológica, crie uma fotografia arqueológica documental extremamente realista de uma nova descoberta feita na mesma estrutura subterrânea.

A cena mostra uma pequena câmara lateral escavada em rocha, com iluminação artificial neutra de campo arqueológico. No centro da composição há um bloco baixo de pedra escura, levemente retangular e fixo ao chão, parcialmente coberto por sedimento fino, visto em ângulo levemente superior para que sua superfície seja claramente legível.

Na superfície superior desse bloco existem três cavidades rasas alinhadas horizontalmente, lado a lado. As duas primeiras cavidades conservam resíduos escurecidos e mineralizados aderidos ao fundo e às bordas, além de pequenos fragmentos granulares e discretas manchas azul-esverdeadas de oxidação de cobre. Próximo a essas cavidades aparecem pequenas sequências de sinais gravados na pedra, visualmente relacionadas às inscrições já vistas nas descobertas anteriores.

A terceira cavidade deve estar intacta, mas visivelmente diferente das outras: seu interior parece ter sido deliberadamente esvaziado ou raspado, com muito menos resíduo, superfície mais limpa e apenas vestígios muito tênues. Não mostrar quebra violenta, impacto ou selamento. A diferença precisa sugerir interrupção de uso, limpeza deliberada ou remoção de conteúdo, sem explicar o motivo.

Ao redor do bloco, incluir apenas alguns pequenos fragmentos cerâmicos discretos, sedimento arqueológico, poeira, textura de rocha e uma pequena escala métrica de referência. Nenhuma pessoa, mão ou luva aparece na cena. A imagem deve parecer um registro de campo sério, sem dramatização cinematográfica, sem fantasia e sem aparência de ilustração.

Manter coerência com o universo visual já estabelecido: pedra escura desgastada, cobre oxidado em tons azul-esverdeados, inscrições não legíveis semelhantes às já observadas, ambiente subterrâneo escavado e estética de fotografia arqueológica documental. Enquadramento vertical em proporção 4:5 ou próximo disso.

Evitar brilho mágico, símbolos luminosos, joias, ouro, pedras preciosas, corpos, caveiras, alta tecnologia, escrita moderna legível, iconografia egípcia, maia, romana, celta ou medieval reconhecível, velas, tochas dramáticas, sacerdotes, personagens, armas, máquinas, criaturas, fumaça cênica, pintura ou aparência de renderização 3D.
```

## Elementos obrigatórios para avaliação

- bloco baixo de pedra escura, fixo ao solo, em pequena câmara lateral;
- três cavidades rasas alinhadas horizontalmente;
- duas cavidades com resíduos mineralizados e vestígios de cobre oxidado;
- terceira cavidade intacta, porém esvaziada ou raspada, sem destruição violenta e sem selamento;
- inscrições discretas próximas às cavidades;
- linguagem de fotografia arqueológica documental;
- pequena escala métrica visível;
- continuidade material e visual com as descobertas anteriores;
- nenhuma explicação visual definitiva sobre a função exata da peça.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- [`colecao/01-descoberta/descricao.md`](../colecao/01-descoberta/descricao.md): introdução do motivo triplo e da cavidade central vazia;
- [`colecao/02-descoberta/imagem.png`](../colecao/02-descoberta/imagem.png): referência de pedra, cobre oxidado e ambiente escavado;
- [`colecao/03-descoberta/descricao.md`](../colecao/03-descoberta/descricao.md): repetição do padrão triplo em receptáculos físicos;
- [`colecao/04-descoberta/descricao.md`](../colecao/04-descoberta/descricao.md): manutenção da assimetria em torno da terceira parte do conjunto.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/05-descoberta/imagem.png`](../colecao/05-descoberta/imagem.png).

A imagem gerada correspondeu bem ao esperado: bloco baixo de pedra escura,
três cavidades rasas alinhadas, duas delas preservando resíduos escurecidos e
vestígios de cobre oxidado, além de inscrições discretas gravadas na
superfície. A terceira cavidade aparece intacta, mas visivelmente mais limpa e
esvaziada, sem sinais de destruição violenta ou selamento, reforçando a ideia
de interrupção deliberada de uso.

O enquadramento em pequena câmara lateral, a presença de escala métrica e a
continuidade visual com os artefatos anteriores mantiveram a linguagem de
fotografia arqueológica documental estabelecida pela coleção.

## Resultado

Resultado aceito e incorporado como a quinta descoberta da coleção.


---

# Descoberta 06 — O Fragmento das Três Rotas

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir a sexta descoberta da coleção introduzindo uma nova dimensão do
conhecimento sobre a civilização: a possibilidade de que o motivo das três
correntes estivesse ligado à maneira como ela representava ou organizava o
espaço.

A descoberta deve revelar uma placa de pedra quebrada, com relevo raso e três
linhas sinuosas distribuídas pela superfície, sugerindo uma representação
espacial, territorial ou de deslocamento, sem confirmar de forma definitiva o
que ela representa.

## Contexto acumulado

A estela (01) apresentou o motivo das três correntes convergindo para uma
cavidade central vazia. O portal (02) repetiu o padrão e revelou o apagamento
intencional de uma das três correntes. O nicho (03) mostrou três receptáculos,
dos quais o terceiro recebeu tratamento distinto. O disco oculto (04) indicou
que o elemento relacionado à terceira corrente não foi simplesmente destruído,
mas retirado de circulação e preservado. A Mesa das Três Ofertas (05)
demonstrou que a estrutura tripla também organizava uma prática material
concreta.

Até o momento, porém, o motivo das três correntes aparecia sobretudo como
símbolo, arranjo ritual ou elemento de objeto. Ainda não havia qualquer
indício de que ele pudesse ter relação com a representação do mundo físico ou
da organização espacial da civilização.

## Ponto de partida do grupo

Em uma área próxima à câmara da descoberta 05, sob fragmentos de rocha e
sedimento compactado, a equipe encontra uma placa larga de pedra escura,
quebrada em uma das extremidades. Em sua superfície há um relevo baixo com
elevações suaves, sulcos e agrupamentos de marcas.

Três linhas sinuosas atravessam a placa e se dirigem a regiões distintas da
superfície. Em duas dessas regiões preservadas, aparecem agrupamentos de sinais
gravados. A terceira linha segue em direção à porção quebrada da peça e se
perde na fratura. Em uma das áreas preservadas, há um pequeno motivo circular
que evoca formalmente o centro do Disco Oculto, sem explicá-lo.

A descoberta deve sugerir que o padrão das três correntes talvez estivesse
ligado a caminhos, regiões, trajetos, territórios ou outra forma de organizar
o espaço, mas sem confirmar qual interpretação é correta.

## Prompt

Antes da geração, utilizar as descobertas anteriores como referência de pedra,
cobre oxidado, inscrições e linguagem arqueológica documental, mantendo a
coerência visual da coleção.

```text
Usando as imagens de referência das descobertas anteriores apenas para manter
continuidade visual de material, linguagem arqueológica e estilo documental,
crie uma fotografia arqueológica documental extremamente realista de uma nova
descoberta feita no mesmo complexo subterrâneo.

A cena mostra uma grande placa de pedra escura caída no chão da escavação,
vista de ângulo quase superior, em um enquadramento que permita compreender bem
sua superfície. A peça está parcialmente cercada por sedimento, pequenos blocos
de rocha desprendidos e poeira arqueológica. A iluminação é neutra, própria de
registro de campo, sem dramatização.

A placa é larga, rasa e apresenta uma extremidade quebrada de forma irregular.
Sua superfície superior possui relevo muito baixo e desgastado, com pequenas
elevações suaves, sulcos e variações de textura, sugerindo uma representação
espacial ou organizacional.

Três linhas sinuosas principais atravessam a superfície da placa em direções
distintas. Elas devem lembrar visualmente o motivo das três correntes já visto
nas descobertas anteriores, mas não convergir para um centro único. Cada linha
leva a uma região diferente da placa.

Em duas dessas regiões preservadas, incluir agrupamentos discretos de sinais
geométricos gravados — pequenos pontos, marcas lineares curtas e formas
abstratas não legíveis — sugerindo locais ou conjuntos associados às rotas.
Em uma dessas áreas, incluir um pequeno motivo circular gravado que evoque
formalmente o elemento central do Disco Oculto, mas sem reproduzi-lo de modo
literal.

A terceira linha deve seguir em direção à área quebrada da placa e desaparecer
na fratura, sugerindo perda de informação por quebra antiga, e não por
apagamento intencional. A fratura deve parecer antiga e natural, com erosão e
lascamento irregulares.

Inserir discretos vestígios azul-esverdeados de cobre oxidado apenas em alguns
trechos das linhas ou sulcos, de modo sutil, coerente com os demais artefatos.
Adicionar uma pequena escala métrica arqueológica ao lado da peça.

A imagem deve parecer um registro de campo sério: extremamente realista,
textura convincente da pedra, sedimento terroso, ambiente escavado, nenhuma
pessoa, mão ou luva na cena. A peça deve parecer arqueológica e coerente com
as descobertas anteriores.

Utilizar enquadramento vertical 4:5 ou próximo disso.

Evitar brilho mágico, símbolos luminosos, escrita moderna legível, mapas
modernos, bússolas, setas, texto, ícones cartográficos contemporâneos, joias,
ouro, armas, corpos, caveiras, alta tecnologia, iconografia egípcia, maia,
romana, celta ou medieval reconhecível, fornalhas, máquinas, pintura ou
aparência de renderização 3D.
```

## Elementos obrigatórios para avaliação

- placa larga de pedra escura, caída no chão da escavação;
- visão quase superior, permitindo ler a superfície;
- relevo raso e desgastado, sugerindo organização espacial;
- três linhas sinuosas principais;
- duas regiões preservadas com agrupamentos de sinais abstratos;
- uma terceira linha perdida na fratura;
- quebra antiga com aparência natural, sem destruição deliberada;
- pequeno motivo circular em uma das regiões preservadas;
- vestígios discretos de cobre oxidado;
- escala métrica arqueológica;
- linguagem de fotografia arqueológica documental.

## Ferramenta

- Ferramenta: ChatGPT;
- 
## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- [`colecao/01-descoberta/imagem.png`](../colecao/01-descoberta/imagem.png):
  linguagem visual da pedra e das inscrições;
- [`colecao/04-descoberta/imagem.png`](../colecao/04-descoberta/imagem.png):
  referência indireta para o pequeno motivo circular;
- [`colecao/05-descoberta/imagem.png`](../colecao/05-descoberta/imagem.png):
  continuidade do ambiente arqueológico e do registro documental.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/06-descoberta/imagem.png`](../colecao/06-descoberta/imagem.png).

A imagem gerada correspondeu bem ao conceito definido: a placa aparece caída
no solo da escavação, vista quase de cima, com três linhas sinuosas distribuídas
pela superfície e vestígios azul-esverdeados em seus sulcos. Agrupamentos de
sinais abstratos aparecem em regiões diferentes, incluindo um pequeno motivo
circular que dialoga visualmente com o Disco Oculto sem reproduzi-lo de forma
literal.

A terceira linha segue até a porção quebrada da placa e desaparece na fratura,
que apresenta aspecto irregular e antigo, sem indícios visuais de apagamento
intencional. A escala arqueológica e o entorno de sedimento e fragmentos de
rocha mantêm a linguagem documental das descobertas anteriores.

## Resultado

Resultado aceito e incorporado como a sexta descoberta da coleção.


---

# Descoberta 07 — A Confluência Vazia

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir uma descoberta que aproxime duas representações anteriores do motivo
triplo: as três correntes convergindo para uma cavidade na Estela das Três
Correntes e as linhas distribuídas pela superfície do Fragmento das Três
Rotas. A nova peça deve sugerir uma conexão entre esses padrões sem determinar
se representam caminhos, territórios, grupos ou outra coisa.

## Contexto acumulado

A estela (01) apresentou três sulcos convergindo para uma cavidade central
vazia. O portal (02) repetiu o motivo e mostrou que uma das correntes foi
apagada intencionalmente. O nicho (03) continha três receptáculos, com o
terceiro selado; o disco oculto (04) mostrou que um objeto associado ao padrão
triplo havia sido cuidadosamente escondido. A mesa (05) sugeriu uma prática
material organizada em três partes, e o Fragmento das Três Rotas (06) trouxe
três linhas distribuídas numa superfície ampla, talvez relacionadas à
organização do espaço.

Ainda não se sabe o significado das três partes, nem se o disco pertence à
cavidade da estela, ao nicho ou a outro objeto. A interpretação da placa como
representação espacial também permanece incerta.

## Ponto de partida do grupo

Encontrar, próximo ao Fragmento das Três Rotas, uma placa de pedra escura na
qual três canais se aproximam de uma cavidade circular central. A descoberta
deve reunir visualmente a convergência da estela e a representação ampla da
placa anterior, mantendo vazia a cavidade e sem confirmar a função do objeto.

## Prompt

```text
Usando as imagens de referência do Fragmento das Três Rotas e da Estela das
Três Correntes apenas para manter continuidade visual de materiais, inscrições
e linguagem arqueológica documental, crie uma fotografia arqueológica
extremamente realista de uma nova descoberta feita no mesmo complexo
subterrâneo.

A cena mostra uma nova peça de pedra escura parcialmente enterrada em uma área
próxima ao local onde foi encontrado o Fragmento das Três Rotas. A peça está
apoiada no piso rochoso, entre sedimentos compactados e pequenos fragmentos de
rocha. Ela deve parecer antiga, desgastada e descoberta durante uma escavação
em andamento, sem revelar novas salas, objetos ou estruturas ao fundo.

Na face visível da peça existem exatamente três sulcos sinuosos que chegam de
direções distintas e se aproximam de uma cavidade circular central. Os sulcos
devem lembrar o motivo das três correntes observado nas descobertas anteriores,
mas sua disposição deve parecer própria desta peça, sem copiar a composição da
estela ou da placa.

Ao redor da cavidade central, mostrar marcas discretas de desgaste e pequenos
vestígios azul-esverdeados de cobre oxidado, como se um objeto circular pudesse
ter sido encaixado ali em algum momento. Não mostrar o objeto encaixado. A
cavidade deve permanecer visível e parcialmente vazia, sem brilho, mecanismo ou
conteúdo identificável.

Adicionar pequenas sequências de sinais geométricos gravados na pedra,
visualmente compatíveis com as inscrições das descobertas anteriores, mas sem
formar palavras, letras ou símbolos de culturas reais. A superfície deve
apresentar erosão, fraturas antigas e depósitos de sedimento, preservando a
aparência de um artefato arqueológico real.

A composição deve destacar a relação entre os três sulcos e a cavidade central.
Incluir uma pequena escala métrica arqueológica próxima à peça e elementos
discretos de escavação nas bordas, como fios de marcação ou uma pequena estaca.
Nenhuma pessoa deve aparecer. Iluminação artificial arqueológica suave e
neutra, cores terrosas pouco saturadas, textura física convincente, enquadramento
frontal levemente superior, profundidade de campo moderada e aparência de
fotografia de campo documental. Formato vertical 4:5 ou próximo disso.

A imagem deve sugerir uma possível relação entre as três rotas do fragmento
anterior, a cavidade central da estela e os discos encontrados na estrutura,
mas não deve confirmar que esses objetos tinham a mesma função ou pertenciam
ao mesmo sistema. A descoberta precisa funcionar como uma nova pista, não como
uma explicação definitiva.

Evitar estética de fantasia, brilho mágico, símbolos luminosos, texto legível,
letras modernas, runas ou hieróglifos reconhecíveis, iconografia egípcia,
maia, romana, celta ou medieval, ouro, joias, corpos, caveiras, armas, máquinas,
alta tecnologia, criaturas, personagens, arquitetura grandiosa, iluminação
cinematográfica dramática, pintura ou aparência de renderização 3D.
```

## Elementos obrigatórios para avaliação

- placa de pedra escura, antiga e parcialmente enterrada;
- exatamente três sulcos sinuosos aproximando-se da cavidade central;
- cavidade central vazia, sem objeto encaixado;
- vestígios discretos de cobre oxidado e sinais geométricos abstratos;
- contexto de escavação próximo ao Fragmento das Três Rotas;
- possível diálogo visual com a estela, sem confirmar a função da peça;
- fotografia arqueológica documental, sem elementos fantásticos.

## Ferramenta

- Ferramenta: ChatGPT;
- Modelo: 5.6-Sol-medium.

## Parâmetros

- Proporção pretendida: 4:5, orientação vertical ou próxima disso;

## Referências

- `colecao/06-descoberta/imagem.png`: referência principal para a placa, os
  canais distribuídos e a linguagem documental;
- `colecao/01-descoberta/imagem.png`: referência para os sulcos convergindo
  para a cavidade central, a pedra e a oxidação do cobre.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/07-descoberta/imagem.png`](../colecao/07-descoberta/imagem.png).

A imagem apresenta uma placa larga e irregular de pedra escura, vista de cima,
com três canais sinuosos revestidos por resíduos azul-esverdeados que convergem
para uma cavidade circular central vazia. Há sequências de marcas gravadas
alinhadas aos canais, fragmentos de rocha ao redor e uma escala arqueológica.
O resultado reúne visualmente características da estela e do Fragmento das
Três Rotas. A cavidade permanece vazia, portanto a imagem não confirma que o
Disco Oculto tenha pertencido a esta peça.

O prompt e as imagens 06 e 01 foram usados como referências, nessa ordem. A
quantidade de tentativas não foi informada.

## Resultado

Resultado aceito e incorporado como a sétima descoberta da coleção.


---

# Descoberta 08 — O Tecido das Três Tramas

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir uma descoberta em material diferente das peças de pedra e dos discos
de cobre anteriores, que revele uma possível dimensão prática do motivo triplo.
O artefato têxtil deve sugerir que as três faixas eram distintas, mas se
mantinham conectadas, sem definir se representavam grupos, territórios, rotas
ou outra organização da civilização.

## Contexto acumulado

A estela (01) apresentou três correntes convergindo para uma cavidade central.
O portal (02) mostrou que uma delas foi apagada intencionalmente. No nicho
(03), o terceiro receptáculo estava selado; o disco oculto (04) indicou que um
objeto associado ao motivo triplo foi preservado em segredo. A Mesa das Três
Ofertas (05) sugeriu uma prática material organizada em três partes. O
Fragmento das Três Rotas (06) trouxe três linhas distribuídas numa superfície
ampla, talvez relacionadas à organização do espaço. A Confluência Vazia (07)
reuniu linhas que se aproximam de uma cavidade central, sem confirmar sua
função ou relação com o disco.

Ainda não se sabe o que as três partes significavam. A hipótese de que placas
como as descobertas 06 e 07 representem rotas ou conexões permanece incerta.

## Ponto de partida do grupo

Encontrar um tecido mineralizado preservado junto a uma estrutura retangular de
madeira também mineralizada, próximo à placa da descoberta 07. O tecido possui
três faixas longitudinais com tramas diferentes, entrelaçadas em alguns
pontos. Uma faixa apresenta um remendo antigo feito com fibras diferentes. A
posição do tecido sobre a placa sugere uma possível correspondência entre as
faixas e os canais, sem provar que os objetos eram usados juntos.

## Prompt

```text
Usando a imagem de referência da Confluência Vazia apenas para manter
continuidade do ambiente arqueológico, dos materiais e do motivo das três
linhas, crie uma fotografia arqueológica documental extremamente realista de
uma nova descoberta no mesmo complexo subterrâneo.

O achado principal não é feito de pedra nem de metal. É um tecido antigo,
mineralizado e parcialmente preservado, desenrolado com cuidado sobre uma
superfície de escavação ao lado da placa da descoberta anterior. O tecido
possui fibras grossas, tramas visíveis e bordas irregulares, endurecidas pelo
tempo. Deve parecer um objeto utilitário antigo, não uma bandeira, roupa
completa ou peça decorativa.

A trama apresenta três faixas longitudinais que percorrem o tecido. Cada faixa
tem um padrão de tecelagem ligeiramente diferente, mas as três se entrelaçam
em vários pontos e voltam a se unir perto do centro. Uma das faixas está
rompida em um trecho e foi remendada com fibras de tom e espessura diferentes.
O remendo é antigo e cuidadoso. A faixa reparada deve continuar visível, sem
parecer uma destruição recente.

O tecido está parcialmente sobre a placa escura da descoberta anterior. Em
alguns trechos, as três faixas do tecido parecem alinhar-se com os três canais
da placa, mas a correspondência não é perfeita nem conclusiva. A imagem deve
sugerir que o tecido e a placa talvez tenham sido usados juntos, sem mostrar
um encaixe exato ou explicar a função.

Próximo ao tecido, incluir uma pequena caixa retangular de madeira petrificada,
aberta e danificada, da qual o material parece ter sido retirado. A caixa deve
ser simples, funcional e sem ornamentos. Pequenos fragmentos orgânicos
mineralizados, sedimento e uma escala métrica arqueológica ajudam a estabelecer
o contexto. Não incluir disco, instrumento de cobre, mapa moderno ou ferramenta
contemporânea em destaque.

A composição deve revelar visualmente que as três faixas eram distintas, mas
também interligadas, e que uma delas precisou ser reparada. Isso pode sugerir
uma sociedade organizada em partes conectadas ou uma relação coletiva
preservada apesar de uma ruptura, mas não deve mostrar pessoas nem representar
grupos de forma literal. A imagem deve funcionar como evidência arqueológica
ambígua, não como uma explicação escrita da civilização.

Fotografia de campo arqueológica, enquadramento vertical 4:5, vista levemente
superior, foco no tecido e no remendo, iluminação de escavação neutra e suave,
cores terrosas pouco saturadas, textura física convincente, profundidade de
campo moderada.

Evitar estética de fantasia, brilho mágico, símbolos luminosos, runas, texto
legível, letras modernas, padrões de culturas reais, ouro, joias, roupas
modernas, bandeiras, pessoas, corpos, caveiras, armas, discos de metal,
instrumentos circulares, engrenagens, tecnologia, máquinas, criaturas,
arquitetura grandiosa, iluminação cinematográfica dramática, pintura ou
aparência de renderização 3D.
```

## Elementos obrigatórios para avaliação

- tecido antigo mineralizado, claramente distinto da pedra e do metal;
- três faixas longitudinais com tramas diferentes e pontos de entrelaçamento;
- uma faixa rompida e reparada com fibras diferentes;
- tecido disposto parcialmente sobre a placa da descoberta 07;
- alinhamento entre faixas e canais apenas parcial, sem encaixe conclusivo;
- estrutura retangular de madeira mineralizada próxima ao tecido;
- fotografia arqueológica documental, sem explicação visual definitiva.

## Ferramenta

- Ferramenta: ChatGPT;
- Modelo informado: 5.6-Sol-medium.

## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;

## Referências

- `colecao/07-descoberta/imagem.png`: referência para o ambiente arqueológico,
  a placa e o motivo das três linhas.

## Resultados e iterações

O resultado selecionado foi armazenado em
[`colecao/08-descoberta/imagem.png`](../colecao/08-descoberta/imagem.png).

A imagem apresenta tecido mineralizado espalhado sobre parte da placa da
Confluência Vazia, com três faixas de tramas distintas e uma região remendada
com fibras mais claras. Também mostra uma estrutura retangular de madeira
mineralizada aberta nas proximidades. As faixas parecem acompanhar os canais
da placa em alguns trechos, embora dobras e perdas impeçam uma correspondência
completa. O resultado introduz um objeto de material diferente e sugere uma
possível relação prática com a placa, sem demonstrar sua função.

O modelo informado para a geração foi 5.6-Sol-medium. A quantidade de
tentativas, a seed e outros parâmetros não foram informados.

## Resultado

Resultado aceito e incorporado como a oitava descoberta da coleção.


---

# Descoberta 09 — O Cesto de Travessia

## Status

Imagem gerada, avaliada e incorporada à coleção.

## Objetivo

Produzir uma descoberta que desenvolva a pista deixada pelo Tecido das Três
Tramas e acrescente informações sobre atividades cotidianas da civilização.

O artefato deve mostrar que as faixas tecidas possuíam uso prático em um objeto
de transporte ou armazenamento, sem confirmar que correspondiam às rotas das
placas ou a grupos sociais específicos.

## Contexto acumulado

As descobertas anteriores mostraram um motivo recorrente de três partes em
estruturas, objetos, práticas materiais e possíveis representações espaciais.
A descoberta 08 apresentou um tecido mineralizado com três faixas de tramas
distintas, uma delas reparada. O tecido estava sobre a placa da Confluência
Vazia, mas a correspondência entre faixas e canais era apenas parcial.

Até esse momento, não havia evidência suficiente para saber se o tecido era
simbólico, cartográfico, decorativo ou utilitário.

## Ponto de partida do grupo

Ampliar a escavação na área do tecido e encontrar um cesto de transporte
parcialmente colapsado. Três tiras de tecido compatíveis com a descoberta 08
permanecem presas à armação e funcionam como alças, amarrações ou divisórias.
Resíduos orgânicos, fragmentos cerâmicos e material mineral aparecem misturados
em seu interior.

## Prompt

Antes da geração, utilizar a imagem da descoberta 08 como referência visual
para o ambiente, as fibras mineralizadas, as três tramas e a linguagem
arqueológica documental.

```text
Use case: photorealistic-natural.
Asset type: imagem vertical de uma descoberta para uma coleção de arqueologia
fictícia.
Input image: a imagem fornecida é somente referência visual para o ambiente
subterrâneo, a fotografia arqueológica documental, a paleta terrosa, a textura
mineralizada e as três faixas têxteis. Gere uma descoberta nova; não edite nem
repita a composição da imagem de referência.

Crie uma fotografia arqueológica documental extremamente realista feita no
mesmo complexo subterrâneo. Em um pequeno nicho de armazenamento recém-escavado,
o achado principal é um cesto de transporte utilitário, grande e oblongo, feito
de fibras vegetais grossas e madeira mineralizada, parcialmente colapsado pelo
tempo. Uma armação simples de madeira preserva parte de sua forma. O cesto não
é cerimonial, luxuoso nem decorativo: deve parecer usado repetidamente no
cotidiano.

Presas à armação existem três tiras longitudinais de tecido resistente, com
padrões de trama compatíveis com o Tecido das Três Tramas da referência: uma
faixa escura e compacta, uma faixa com manchas azul-esverdeadas de cobre oxidado
e uma faixa mais clara que recebeu um remendo antigo feito com fibras
diferentes. As três tiras funcionam claramente como alças, amarrações ou
divisórias de carga, mostrando que aquele padrão têxtil tinha uso prático. Não
formar bandeira, roupa ou símbolo perfeito.

Dentro e ao redor do cesto há apenas vestígios arqueológicos discretos de
cargas cotidianas: sementes e grãos carbonizados, fragmentos de um pequeno
recipiente cerâmico simples com resíduo mineral claro, e poucas partículas
azul-esverdeadas aderidas à fibra. Os materiais aparecem misturados pelo
colapso, sem formar três compartimentos perfeitamente separados. Isso deve
sugerir transporte ou distribuição de alimentos e matérias-primas, sem provar
comércio, mapa ou sistema político.

A cena deve ter sedimento compactado, pequenos fragmentos de rocha, uma escala
métrica arqueológica e fios de marcação discretos nas bordas. Nenhuma pessoa,
mão ou ferramenta moderna em destaque. Vista levemente superior, foco no cesto,
nas alças tecidas e nos resíduos. Formato vertical 4:5, iluminação artificial
neutra e suave de escavação, cores terrosas pouco saturadas, texturas físicas
convincentes, aparência de fotografia de campo real.

Manter continuidade visual com a coleção: pedra escura ao redor, cobre oxidado
azul-esverdeado apenas em detalhes, grande antiguidade, desgaste irregular e
ausência de explicação definitiva.

Evitar placa de pedra com canais, estela, disco circular, três cavidades
alinhadas, texto legível, runas reconhecíveis, símbolos luminosos, brilho
mágico, fantasia, ouro, joias, corpos, caveiras, armas, máquinas, tecnologia
avançada, personagens, arquitetura grandiosa, dramatização cinematográfica,
pintura, ilustração ou aparência de renderização 3D. Não adicionar logotipos,
legendas ou marca-d'água.
```

## Elementos obrigatórios para avaliação

- cesto utilitário de fibras e madeira mineralizadas;
- sinais de desgaste, reforço e uso prolongado;
- três tiras têxteis compatíveis com as tramas da descoberta 08;
- uma das tiras com remendo antigo;
- resíduos orgânicos escurecidos, cerâmica simples e material mineral;
- materiais misturados, sem três compartimentos perfeitamente separados;
- fotografia arqueológica documental em formato vertical;
- nenhuma confirmação de comércio, mapa ou organização política.

## Ferramenta

- Ferramenta: Codex, com gerador de imagens integrado;

## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;
- Dimensões do resultado: 1122 × 1402 pixels;

## Referências

- `colecao/08-descoberta/imagem.png`: referência para as tramas, o ambiente e
  a linguagem visual;
- `colecao/08-descoberta/descricao.md`: conhecimento estabelecido sobre o
  tecido e suas questões ainda abertas.

## Resultados e iterações

Foi realizada uma geração. A imagem resultante apresentou um cesto oblongo com
armação de madeira, três tiras têxteis distintas, fragmentos de cerâmica e
resíduos escurecidos em seu interior. A composição preservou a estética
documental da coleção e tornou visível o uso prático das tramas sem definir a
função exata das cargas.

O resultado selecionado foi armazenado em
`colecao/09-descoberta/imagem.png`.

## Resultado

Resultado aceito e incorporado como a nona descoberta da coleção.


---

# Descoberta 10 — Os Recipientes do Cesto

## Status

Segunda imagem gerada, avaliada e incorporada à coleção. A primeira proposta
foi descartada por introduzir um salto narrativo.

## Objetivo

Aprofundar diretamente a descoberta 09 investigando o conteúdo do Cesto de
Travessia. A nova imagem deve acrescentar indícios de como os materiais eram
manipulados, separados ou distribuídos, sem definir que os resíduos eram
alimento nem introduzir um novo espaço doméstico sem sustentação anterior.

## Contexto acumulado

A descoberta 08 revelou um tecido com três tramas distintas. A descoberta 09
mostrou que tramas compatíveis eram usadas como partes estruturais de um cesto
de transporte. No interior desse cesto havia resíduos escurecidos semelhantes
a grãos ou sementes, fragmentos cerâmicos, material mineral claro e partículas
de cobre oxidado.

A função do cesto e a identidade das cargas permaneciam desconhecidas. Também
não havia evidência suficiente para afirmar que os resíduos eram alimentos, que
o objeto participava de comércio ou que pertencia a um espaço doméstico.

## Primeira tentativa — descartada

### Ponto de partida inicial

A proposta inicial avançava para uma área de preparo de alimentos em uma
câmara adjacente. A cena mostraria um fogareiro, uma pedra de moagem, resíduos
escurecidos e um recipiente cerâmico reparado.

### Prompt da primeira tentativa

```text
Use case: photorealistic-natural.
Asset type: imagem vertical de uma nova descoberta para uma coleção de
arqueologia fictícia.
Input images: Image 1 é referência para o ambiente subterrâneo, os grãos
escurecidos, a cerâmica simples, as fibras e a fotografia documental; Image 2
é referência somente para a pedra escura e para a técnica antiga de reparo com
grampos de cobre. Gere uma descoberta nova; não edite nem reproduza a composição
das referências.

Crie uma fotografia arqueológica documental extremamente realista de um
pequeno espaço doméstico ou de trabalho encontrado numa câmara adjacente ao
nicho onde estava o cesto da descoberta anterior. O achado central é uma área
simples de preparo de alimento, não um santuário.

Mostrar um fogareiro baixo de pedra, circular e parcialmente soterrado, com
cinzas antigas e uma camada escura de carvão. Ao lado dele há uma pedra de
moagem rasa, muito gasta pelo uso, com seu pilão ou pedra de mão repousando
próximo. Sobre a superfície permanecem discretos grãos carbonizados e
fragmentos de sementes visualmente compatíveis com os resíduos encontrados no
cesto da Image 1.

Próximo ao fogareiro existe um recipiente cerâmico de cozinha, simples,
incompleto e coberto de fuligem. Uma fratura antiga nesse recipiente foi
reparada antes do soterramento com dois ou três pequenos grampos de liga de
cobre hoje oxidados em azul-esverdeado, usando uma técnica funcional semelhante
ao reparo visto na Image 2. Preso a uma das alças quebradas ou à borda do
recipiente há um pequeno fragmento mineralizado de tira têxtil, gasto e
enegrecido, com trama compatível com as faixas do cesto, sugerindo uso como
amarração, pega ou proteção térmica, sem permitir afirmar sua função.

A cena deve revelar trabalho diário, moagem, cozimento e reaproveitamento de
utensílios. Não organizar os objetos em três grupos, não incluir o símbolo das
três correntes e não transformar o espaço em altar. A ausência do motivo triplo
explícito deve ajudar a mostrar um contexto cotidiano comum.

Incluir sedimento compactado, fragmentos cerâmicos discretos, uma escala
métrica arqueológica e fios de marcação apenas nas bordas. Nenhuma pessoa, mão
ou ferramenta moderna em destaque. Vista levemente superior, composição
vertical 4:5, foco no fogareiro, na pedra de moagem e no recipiente reparado.
Iluminação neutra e suave de escavação, cores terrosas pouco saturadas,
texturas físicas convincentes, aparência de fotografia de campo real.

Evitar três cavidades, três canais, placa com mapa, estela, disco, altar,
oferendas, utensílios modernos, comida fresca, chama acesa, texto legível,
runas reconhecíveis, brilho mágico, fantasia, ouro, joias, corpos, caveiras,
armas, tecnologia avançada, personagens, arquitetura grandiosa, dramatização
cinematográfica, pintura, ilustração ou renderização 3D. Sem logotipos,
legendas ou marca-d'água.
```

### Avaliação da primeira tentativa

A imagem apresentou os elementos solicitados, mas o grupo identificou um salto
entre as descobertas 09 e 10. A proposta pressupunha simultaneamente que os
resíduos eram alimento, que existia uma cozinha próxima e que os dois espaços
tinham uma relação funcional. Como nenhuma dessas informações estava
estabelecida, a imagem foi retirada da coleção e preservada em
`descartes/imagens/10-cozinha-salto-narrativo.png`.

## Ponto de partida revisado

Continuar a escavação do próprio Cesto de Travessia. Sob a camada superior de
fibras e sedimento, encontrar quatro pequenos recipientes cerâmicos de formato
semelhante, acompanhados pelos mesmos tipos de resíduos já visíveis na
descoberta 09.

Os recipientes podem sugerir medição, separação, serviço ou distribuição de
materiais, mas a imagem não deve determinar qual dessas funções é correta.

## Prompt final

Antes da geração, utilizar a imagem da descoberta 09 como referência direta do
mesmo cesto, de seus materiais e do estado anterior da escavação.

```text
Use case: photorealistic-natural.
Asset type: imagem vertical de uma nova descoberta para uma coleção de
arqueologia fictícia.
Input image: a imagem fornecida é referência direta para o mesmo cesto, suas
fibras mineralizadas, as três tiras tecidas, os resíduos escurecidos, a
cerâmica quebrada, o ambiente subterrâneo e a fotografia arqueológica
documental. A nova imagem deve registrar uma etapa posterior da escavação do
mesmo cesto, não outro lugar.

Crie uma fotografia arqueológica documental extremamente realista feita depois
da retirada cuidadosa da camada superior de sedimento e fibras colapsadas do
Cesto de Travessia. O enquadramento é mais próximo e levemente superior,
concentrado no interior do mesmo cesto antigo de madeira e fibras mineralizadas.
Partes das três tiras têxteis vistas na referência permanecem visíveis nas
bordas, mas não dominam a composição.

Sob os resíduos aparecem quatro pequenos recipientes cerâmicos utilitários, de
formato semelhante e tamanho quase padronizado. Dois estão relativamente
inteiros, um está rachado e incompleto, e o quarto sobrevive apenas em
fragmentos ainda reconhecíveis. Eles são simples, sem decoração cerimonial,
feitos de cerâmica escura e gasta. Marcas rasas de abrasão circundam a parte
interna dos recipientes em alturas semelhantes, podendo indicar uso repetido
para conter, retirar ou medir material, mas sem números, texto ou escala
escrita.

Dentro de dois recipientes e espalhados ao redor permanecem discretos grãos e
sementes carbonizados iguais aos resíduos visíveis na descoberta anterior. Em
outro há apenas resíduo mineral claro aderido ao fundo. Um pequeno trecho de
cordão mineralizado, feito de fibras compatíveis com o cesto, passa pelo cabo
curto de um dos recipientes, sugerindo que as peças podiam ser presas ou
transportadas juntas. Não organizar os objetos em três grupos e não mostrar
exatamente três recipientes.

A imagem deve permitir a hipótese de que os recipientes eram usados para medir,
separar, servir ou distribuir cargas transportadas no cesto, mas não deve
provar qual dessas funções é correta nem afirmar que os grãos eram alimento.
Esta descoberta precisa aprofundar diretamente o conteúdo do cesto, sem
introduzir cozinha, casa, forno, mercado, pessoas ou novo ambiente.

Manter o restante do cesto parcialmente soterrado, com sedimento compactado,
pequenos fragmentos de cerâmica e uma escala métrica arqueológica discreta ao
lado. Nenhuma mão ou ferramenta moderna em destaque. Formato vertical 4:5,
iluminação artificial neutra e suave de escavação, cores terrosas pouco
saturadas, foco nos recipientes, nos resíduos e nas fibras; texturas físicas
convincentes e aparência de fotografia de campo real.

Evitar fogareiro, cozinha, pedra de moagem, altar, oferendas, placa de pedra com
canais, estela, disco circular de cobre, três cavidades, três objetos alinhados,
símbolo das três correntes, texto legível, números modernos, runas reconhecíveis,
brilho mágico, fantasia, ouro, joias, corpos, caveiras, armas, máquinas,
personagens, arquitetura grandiosa, dramatização cinematográfica, pintura,
ilustração ou renderização 3D. Sem logotipos, legendas ou marca-d'água.
```

## Elementos obrigatórios para avaliação

- continuação visual direta da escavação do cesto da descoberta 09;
- quatro recipientes cerâmicos utilitários de formato semelhante;
- diferentes estados de conservação entre os recipientes;
- marcas internas de uso e abrasão;
- resíduos escurecidos e material mineral claro;
- cordão ou fibra associado a um dos recipientes;
- nenhuma cozinha, moradia ou função alimentar confirmada;
- fotografia arqueológica documental em formato vertical.

## Ferramenta

- Ferramenta: Codex, com gerador de imagens integrado;

## Parâmetros

- Proporção pretendida: 4:5, orientação vertical;
- Dimensões dos resultados: 1122 × 1402 pixels;

## Referências

- `colecao/09-descoberta/imagem.png`: referência direta para o cesto, os
  resíduos, as fibras e o ambiente;
- `colecao/09-descoberta/descricao.md`: conhecimento estabelecido pela nona
  descoberta;
- `colecao/01-descoberta/imagem.png`: utilizada somente na primeira tentativa
  como referência da técnica de reparo com grampos metálicos.

## Resultados e iterações

Foram realizadas duas gerações.

A primeira apresentou uma área de preparo com fogareiro, pedra de moagem e
recipiente reparado. Embora visualmente coerente, foi descartada por exigir
inferências ainda não sustentadas pela coleção.

A segunda geração retornou ao interior do mesmo cesto. A imagem mostra quatro
recipientes de cerâmica em diferentes estados de conservação, resíduos
escurecidos, uma crosta mineral clara, fibras e a armação já conhecida. O
resultado permite discutir separação, serviço ou medição de materiais sem
definir a função das peças.

O resultado selecionado foi armazenado em
`colecao/10-descoberta/imagem.png`.

## Resultado

Segunda geração aceita e incorporada como a décima descoberta da coleção.


---

### Descoberta 11 — A Grade dos Quatro Espaços

#### Descrição preservada da descoberta 11

# Descoberta 11 — A Grade dos Quatro Espaços

## Registro da descoberta

Após a retirada dos quatro recipientes cerâmicos encontrados no Cesto de
Travessia, a remoção das camadas inferiores de sedimento revelou uma estrutura
encaixada no fundo do próprio cesto. Trata-se de uma grade feita de madeira
mineralizada e fibras vegetais, composta por três ripas longitudinais que
dividem o espaço interno em quatro faixas estreitas.

As ripas apresentam desgaste, rachaduras e marcas de abrasão compatíveis com o
contato repetido com objetos transportados. A peça central conserva um reparo
feito com fibras mais claras e de espessura diferente das demais amarrações.
Esse material se aproxima visualmente das fibras utilizadas no remendo do
Tecido das Três Tramas, embora ainda não seja possível determinar se ambos
vieram do mesmo objeto ou de uma técnica comum de reparação.

Os quatro espaços formados pela grade preservam resíduos diferentes. Em um
deles há uma concentração de pequenos grãos ou sementes carbonizados; outro
contém uma crosta mineral clara; um terceiro apresenta partículas com oxidação
azul-esverdeada; o último está quase vazio, conservando apenas sedimento fino e
vestígios dispersos. A distribuição atual pode ter sido alterada pelo colapso
do cesto, mas a presença das divisórias indica que alguma separação física era
mantida durante o uso da peça.

## Interpretação inicial

A grade reforça a hipótese de que o Cesto de Travessia não servia apenas para
reunir materiais de maneira indiferenciada. Seus quatro espaços internos podem
ter organizado cargas distintas e ajudam a explicar por que recipientes de
formato semelhante eram transportados juntos. Ainda assim, não é possível
afirmar se cada recipiente ocupava uma posição fixa nem se os resíduos
preservados correspondem à disposição original.

A estrutura também modifica a leitura do padrão triplo recorrente na coleção.
Neste caso, três elementos não produzem três áreas equivalentes: as três ripas
formam quatro espaços. Isso permite considerar que, em alguns objetos, a
recorrência do número três estivesse relacionada a ações de dividir, separar
ou organizar, e não necessariamente à representação de três grupos, rotas ou
substâncias.

O reparo em uma das ripas acrescenta outra evidência de manutenção de objetos
utilitários, aproximando a grade da estela reparada, do tecido remendado e das
amarrações reforçadas do próprio cesto. Por enquanto, a descoberta permite
afirmar apenas que diferentes materiais eram mantidos separados dentro de um
mesmo conjunto de transporte e que essa organização dependia de uma estrutura
interna usada e reparada. Sua relação com práticas de medição, distribuição,
troca ou armazenamento permanece em aberto.

---

### Descoberta 12 — A Placa das Quatro Partes

#### Descrição preservada da descoberta 12

# Descoberta 12 — A Placa das Quatro Partes

## Registro da descoberta

Durante a retirada da Grade dos Quatro Espaços, a equipe identificou uma peça
presa à parte inferior de uma das ripas por um curto cordão de fibras
mineralizadas. A peça estava voltada para baixo e parcialmente comprimida
contra o fundo do Cesto de Travessia, o que explica por que não havia sido
percebida nas etapas anteriores da escavação.

Trata-se de uma placa portátil de pedra escura, fina e aproximadamente do
tamanho de uma mão aberta. Um furo próximo à borda conserva o cordão que a
ligava à grade. As fibras mais claras usadas nessa amarração se assemelham às
do reparo observado na ripa central e no Tecido das Três Tramas, embora essa
semelhança não seja suficiente para atribuir todos os reparos a uma mesma
pessoa ou período.

Três sulcos sinuosos percorrem longitudinalmente a face da placa e dividem sua
superfície em quatro campos. Dentro dos sulcos permanecem resíduos
azul-esverdeados de uma liga à base de cobre. Os quatro campos contêm pequenas
sequências de círculos, pontos e incisões geométricas, visualmente relacionadas
aos sinais registrados na estela, no portal e nas placas das rotas. As marcas
não são idênticas entre si e apresentam desgaste desigual.

Vestígios aderidos à superfície também variam entre os campos. Foram
identificadas partículas carbonizadas, uma crosta mineral clara, traços de
oxidação de cobre e sedimento fino. Ainda não é possível determinar se esses
materiais foram aplicados intencionalmente, transferidos pelo contato com a
carga ou misturados após o colapso do cesto.

## Interpretação inicial

A ligação física entre a placa e a grade mostra que os sinais e os sulcos não
apareciam apenas em monumentos, passagens ou possíveis representações do
espaço. Eles também acompanhavam um objeto utilitário destinado a separar e
transportar materiais. Essa associação aproxima, pela primeira vez, o sistema
de marcas das atividades sugeridas pelo cesto, pelos recipientes e pelos
resíduos preservados.

A organização da placa não repete exatamente as composições anteriores. Na
estela e na Confluência Vazia, três linhas conduziam a um centro; no Fragmento
das Três Rotas, seguiam para regiões distintas. Aqui, três linhas funcionam
como limites entre quatro campos, correspondendo à disposição material da
grade. Isso reforça a possibilidade de que o padrão triplo pudesse expressar
relações entre partes — união, percurso ou separação — em vez de representar
sempre três entidades fixas.

As sequências gravadas podem ter identificado conteúdos, quantidades,
destinos, responsáveis ou etapas de uma atividade. A placa também pode ter
sido apenas uma marca de propriedade, uma instrução cujo código se perdeu ou
um objeto reaproveitado no reparo do cesto. A imagem dos quatro campos não
permite escolher entre essas hipóteses, e as diferenças entre os resíduos não
provam que cada campo correspondesse a um dos compartimentos da grade.

Por enquanto, a descoberta permite afirmar apenas que uma placa inscrita era
mantida fisicamente junto a um conjunto de transporte organizado e muito
usado. A peça conecta os sinais, o cobre, as três correntes, os quatro espaços
e a prática recorrente de reparar objetos, mas preserva a questão central da
coleção: ainda não sabemos se essas relações registravam lugares, materiais,
grupos, ações ou conceitos para os quais não possuímos tradução.

---

## 9. Descarte comentado

O descarte abaixo é parte do processo, não um resultado apagado. Ele mostra como o critério de continuidade foi aplicado a uma imagem que funcionava visualmente, mas introduzia inferências demais de uma só vez. O prompt integral da tentativa descartada está preservado na seção da descoberta 10.

## 24/09/2026 — Primeira proposta para a descoberta 10

### Proposta

A primeira versão da descoberta 10 mostrava uma área de preparo de alimentos
em uma câmara adjacente ao Cesto de Travessia. A imagem continha um fogareiro,
uma pedra de moagem, resíduos escurecidos e um recipiente cerâmico reparado com
grampos de cobre.

### Motivo do descarte

A passagem da descoberta 09 para essa cena exigia aceitar várias informações
que ainda não estavam sustentadas pela coleção:

- que os resíduos do cesto eram alimentos;
- que existia uma cozinha ou área doméstica próxima;
- que os materiais encontrados nos dois espaços tinham relação funcional.

A imagem contribuía para a representação da vida cotidiana, mas introduzia
essas conclusões de uma só vez. O grupo considerou que isso criava um salto
narrativo maior do que o conhecimento acumulado permitia naquele momento.

### Decisão

A imagem foi descartada da coleção e preservada em
`descartes/imagens/10-cozinha-salto-narrativo.png`.

A descoberta 10 foi reformulada para aprofundar o próprio Cesto de Travessia.
Em vez de avançar imediatamente para uma cozinha, a nova geração mostra os
recipientes encontrados sob a camada superior do cesto, permitindo investigar
possíveis práticas de separação, serviço ou medição sem definir ainda a função
dos materiais.

### Aprendizado

Continuidade não significa apenas reutilizar elementos visuais. Uma nova
descoberta também precisa limitar a quantidade de inferências introduzidas de
uma vez. Quando uma imagem depende de várias suposições ainda não estabelecidas,
é preferível inserir uma descoberta intermediária.

## 11. Síntese do processo

O projeto começou com a proposta de um museu de uma civilização desaparecida e ganhou uma estrutura sequencial durante a ideação. O grupo passou a tratar cada imagem como uma descoberta que altera o que pode ser afirmado nas seguintes. As primeiras gerações estabeleceram materiais, inscrições, reparos e transformações de objetos e espaços; as seguintes ampliaram a investigação para organização espacial, tecidos, transporte e manipulação de materiais. Quando uma geração de cozinha tentou transformar resíduos em alimento e o cesto em evidência de um espaço doméstico, ela foi descartada por antecipar conclusões. A coleção final preserva, portanto, não apenas imagens aceitas, mas o processo de decidir até onde cada evidência permite avançar.
