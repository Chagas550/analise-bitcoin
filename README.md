# Análise e Previsão do Preço do Bitcoin

Projeto simples de Análise de Dados usando Python e Prophet para fins de estudo

### Objetivo do Projeto

Este projeto tem como finalidade analisar o comportamento do preço do Bitcoin nos últimos 365 dias e construir um modelo de previsão utilizando o algoritmo Prophet, amplamente usado para séries temporais.

O trabalho combina:

Coleta de dados em API pública

Limpeza e manipulação de dados

Análise exploratória

Visualização gráfica

Modelagem preditiva

Geração de insights financeiros

### Tecnologias Utilizadas

Python

Pandas

Matplotlib

Requests

Prophet

Colab / Jupyter Notebook

### Coleta dos Dados

Os dados foram obtidos diretamente da API do CoinGecko, referente ao preço histórico do Bitcoin em dólares (USD) ao longo de 365 dias.

Endpoint utilizado:

https://api.coingecko.com/api/v3/coins/bitcoin/market_chart

## Análise Exploratória

Foram analisados os seguintes fatores:

Evolução do preço diário

Estatísticas descritivas

Tendência geral

Picos e quedas acentuadas

Volatilidade

Gráficos apresentados:

Série temporal

Média móvel

Distribuição do preço

Tabela descritiva

### Previsão com Prophet

Foi utilizado um modelo Prophet para prever os preços dos próximos 60 dias.

### Resultados e Conclusões

O Bitcoin apresentou forte tendência de alta no período analisado.

A volatilidade foi significativa, com oscilações intensas ao longo do ano, como é de se esperar de criptomoedas.

A análise confirma que o BTC é um ativo de risco, com comportamento não linear e difícil de prever com precisão.
