# Ecos de uma Civilização

Projeto desenvolvido para a disciplina de Criatividade Computacional
do Centro de Informática da UFPE (CIn-UFPE).

## Sobre o projeto

**Ecos de uma Civilização** é um museu virtual de uma civilização fictícia desaparecida,
construída progressivamente por meio de uma sequência de descobertas.

Em vez de definir previamente toda a história dessa civilização e utilizar
IA apenas para ilustrá-la, partimos de um contexto inicial e construímos
seu passado durante o próprio processo de geração.

Cada nova descoberta parte do conhecimento acumulado pelas anteriores e
pode complementar, aprofundar ou contradizer interpretações já estabelecidas.

O grupo participa da construção escolhendo os pontos de partida das novas
descobertas, avaliando os resultados gerados e decidindo quais elementos
entram ou não na coleção.

## Modalidade

**Imagem**

## Tema / Área de exploração

**Arqueologia fictícia e construção generativa de uma civilização
desaparecida por meio de IA.**

## Eixo

A ideia do grupo é criar um museu virtual de uma civilização fictícia
desaparecida, que será construída progressivamente ao longo das descobertas.
Partiremos de uma imagem e de um contexto inicial, e cada nova imagem deverá
estar ligada a uma descoberta que faça sentido a partir do conhecimento
acumulado até aquele momento. As imagens podem representar objetos,
documentos, vestígios ou até cenas do passado. O que varia é o tipo de
descoberta e aquilo que ela revela; o que se repete é que toda descoberta
precisa acrescentar alguma informação relevante sobre a civilização. Para
fazer parte da coleção, não basta a imagem ser visualmente interessante:
ela precisa complementar, aprofundar ou contradizer de forma coerente algo
que já tenha sido estabelecido anteriormente.

## Estrutura do repositório

| Pasta | Conteúdo |
|---|---|
| [`docs/`](./docs/) | Documentação geral do projeto e material de apresentação |
| [`caderno-de-bordo/`](./caderno-de-bordo/) | Registro cronológico das decisões e experimentações |
| [`colecao/`](./colecao/) | Descobertas que fazem parte da coleção final |
| [`descartes/`](./descartes/) | Gerações que não entraram na coleção e seus motivos |
| [`prompts/`](./prompts/) | Prompts, parâmetros e contexto das gerações |
| [`ferramentas/`](./ferramentas/) | Ferramentas e capacidades utilizadas no projeto |

## Processo

De forma geral, cada nova descoberta segue o fluxo:

1. Analisamos o conhecimento acumulado sobre a civilização.
2. O grupo escolhe um ponto de partida para a próxima descoberta.
3. Construímos o prompt utilizando o contexto anterior.
4. Geramos uma ou mais possibilidades.
5. Analisamos imagem e descrição.
6. Aceitamos, ajustamos ou descartamos o resultado.
7. Uma descoberta aceita passa a integrar o contexto das próximas.

Dessa forma, a civilização não possui uma história completamente definida
antes da produção: ela emerge progressivamente das descobertas e das
decisões tomadas durante o processo.

## Integrantes

- Ellian Rodrigues (esr2)
- Fabriely Santos(flps)
- Aline Marianna (amms)
- Monyque Lima (mgbl)
- Amanda Arruda (aams2)
- Nícolas Veiga (nvgb)

## Disciplina

**Criatividade Computacional — CIn/UFPE — 2026.2**