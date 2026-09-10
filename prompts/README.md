# Prompts

Esta pasta reúne os prompts e as informações utilizadas nas gerações do projeto **Ecos de uma Civilização**.

O objetivo é registrar o processo de criação de cada descoberta, permitindo acompanhar as informações fornecidas à IA, as decisões tomadas pelo grupo e o caminho percorrido até cada resultado.

## Estrutura da pasta

Cada descoberta possui seu próprio arquivo, identificado pela mesma numeração utilizada na coleção:

```text
prompts/
├── 01-descoberta.md
├── 02-descoberta.md
├── 03-descoberta.md
├── ...
└── README.md
```

Por exemplo, `01-descoberta.md` documenta o processo de geração do artefato armazenado em `colecao/01-descoberta/`.

## O que registrar

Sempre que possível, cada arquivo deve conter:

- o objetivo da geração;
- o contexto acumulado até aquele momento;
- o ponto de partida escolhido pelo grupo;
- o prompt completo enviado à ferramenta;
- a ferramenta e o modelo utilizados;
- os parâmetros utilizados;
- a seed, quando disponível;
- as imagens ou outras referências utilizadas;
- os resultados obtidos;
- as alterações realizadas entre as diferentes tentativas.

Quando uma informação não for disponibilizada pela ferramenta, como a seed ou algum parâmetro, essa ausência deve ser indicada no registro.

## Modelo de registro

Um arquivo de descoberta pode seguir esta estrutura:

```markdown
# Descoberta 01

## Objetivo

O que buscamos explorar nesta geração.

## Contexto

Informações sobre a civilização disponíveis antes desta geração.

## Ponto de partida do grupo

Ideia ou direção escolhida pelo grupo para orientar a nova descoberta.

## Prompt

Prompt completo utilizado na geração.

## Ferramenta

- Ferramenta:
- Modelo:

## Parâmetros

- Seed:
- Outros parâmetros:

## Referências

Imagens ou outros materiais utilizados como referência, caso existam.

## Resultados e iterações

Registro das principais tentativas e das alterações realizadas nos prompts.

## Resultado

Indicação do resultado escolhido ou, caso nenhuma tentativa tenha sido aproveitada, do descarte da geração.
```

## Relação com o projeto

- Os resultados aceitos são armazenados em [`colecao/`](../colecao/).
- Os resultados relevantes que não entraram na coleção são preservados em [`descartes/`](../descartes/).
- As discussões e decisões tomadas durante o processo são registradas em [`caderno de bordo/`](../caderno%20de%20bordo/).
