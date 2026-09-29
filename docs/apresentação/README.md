# Material de apresentação

Esta pasta contém o material de apresentação de **Ecos de uma Civilização**.

## Arquivos

- [`Ecos-de-uma-Civilizacao.pptx`](./Ecos-de-uma-Civilizacao.pptx):
  apresentação principal em formato 16:9;
- [`roteiro.md`](./roteiro.md): notas curtas para apoio durante a apresentação
  oral;
- [`gerar_apresentacao.py`](./gerar_apresentacao.py): script utilizado para
  gerar novamente o arquivo PowerPoint a partir das imagens da coleção.

## Organização

A apresentação possui 14 slides:

1. capa;
2. proposta;
3. eixo;
4. processo criativo;
5. descobertas 01–03;
6. descobertas 04–06;
7. descobertas 07–09;
8. descobertas 10–12;
9. progressão do conhecimento;
10. descarte comentado;
11. ferramentas e processo com IA;
12. skills utilizadas;
13. aprendizados;
14. encerramento.

Todo o conteúdo foi elaborado exclusivamente a partir dos registros existentes
no repositório. As imagens são carregadas diretamente de `colecao/` e
`descartes/imagens/` durante a geração.

## Regeneração

Com Python e `python-pptx` instalados, executar na raiz do repositório:

```powershell
python "docs/apresentação/gerar_apresentacao.py"
```
