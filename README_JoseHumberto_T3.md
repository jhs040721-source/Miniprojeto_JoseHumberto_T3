# Mini-Projeto — Análise da Base Varejo

## Autor

José Humberto de Souza

**Turma:** T3 — Visualização de Dados e Business Intelligence

## Objetivo

Este mini-projeto tem como objetivo importar, diagnosticar, limpar e analisar a base Varejo.csv utilizando Python e a biblioteca pandas no Google Colab.

## Fonte dos dados

A base foi obtida no Kaggle:

https://www.kaggle.com/datasets/namespaiva/base-varejo

## Etapas realizadas

1. Importação automática da base do Kaggle.
2. Diagnóstico inicial dos registros, colunas e tipos de dados.
3. Padronização dos textos e conversão da coluna DATA para datetime.
4. Identificação e tratamento de valores ausentes.
5. Remoção de colunas completamente vazias.
6. Identificação e remoção de registros duplicados.
7. Cálculo das estatísticas descritivas da coluna número de filhos.
8. Agrupamentos por gênero, categoria e segmento.
9. Ranking dos produtos mais comprados.
10. Análise ABC dos produtos pela frequência de compras.
11. Elaboração do relatório e das conclusões finais.

## Principais resultados

- Base original: 830.000 registros e 14 colunas.
- Base limpa: 733.447 registros e 10 colunas.
- Duplicatas removidas: 96.553.
- Colunas completamente vazias removidas: 4.
- Média de filhos por registro: 1,15.
- Gênero feminino: 52,14% das compras.
- Categoria Alimentos: 52,38% das compras.
- Segmento B: 63,88% das compras.
- Produto mais comprado: Presunto Cozido.
- Foram necessários 91 dos 118 produtos para alcançar 80,59% das compras.

## Como executar

1. Abra o arquivo `Miniprojeto_Varejo_JoseHumberto.ipynb` no Google Colab.
2. No menu superior, clique em **Ambiente de execução**.
3. Selecione **Executar tudo**.
4. Aguarde a importação automática da base do Kaggle e a execução das análises.
5. Confira o relatório e as conclusões apresentados no final do notebook.

É necessário possuir conexão com a internet para que a base seja baixada automaticamente do Kaggle.

## Arquivos do projeto

- `Miniprojeto_Varejo_JoseHumberto.ipynb`: notebook com o código comentado.
- `README_JoseHumberto_T3.md`: documentação do projeto.
- `Varejo_limpo.csv.zip`: base limpa compactada. Após baixar o arquivo, extraia o conteúdo para obter o arquivo Varejo_limpo.csv.

## Limitações

A base não apresenta quantidade vendida, preço, faturamento, número da nota fiscal ou identificador da transação. Por isso, as análises representam frequência de registros de compras. A análise ABC não representa participação financeira dos produtos.