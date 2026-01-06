# Online Retail Analytics

Projeto de análise de dados utilizando Python e Pandas com o objetivo de
explorar o comportamento de vendas de uma empresa de varejo online.

## Dataset
Base de dados pública disponibilizada no Kaggle, contendo transações de uma
loja online entre 2010 e 2011.

## Objetivos da análise
- Limpeza e tratamento dos dados
- Cálculo do faturamento total da empresa
- Análise do faturamento por país
- Análise da quantidade de pedidos por país
- Visualização dos dados com gráficos

## Tratamento dos dados
- Remoção de registros sem identificação de cliente (CustomerID)
- Exclusão de registros com quantidades negativas (devoluções)
- Conversão de tipos de dados (datas e IDs)
- Criação da coluna `TotalPrice`

## Principais análises realizadas
- Faturamento total da empresa
- Top 10 países por faturamento
- Top 10 países por quantidade de pedidos

## Visualizações
Os gráficos foram gerados utilizando a biblioteca Matplotlib e estão disponíveis
na pasta `images/`.

## Tecnologias utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook
