# Análise Exploratória do Bitcoin (BTC)

Nesse projeto realizei uma análise exploratória completa do preço do Bitcoin utilizando Python, com foco em estatística descritiva, análise de risco e comportamento de séries temporais.

O objetivo é entender como o ativo se comporta ao longo do tempo, analisando tendência, volatilidade e risco por meio de métricas financeiras amplamente utilizadas.

---

## Objetivos do Projeto

- Coletar dados históricos do Bitcoin via API
- Realizar limpeza e preparação dos dados
- Analisar comportamento do preço ao longo do tempo
- Calcular retornos diários
- Estudar a distribuição dos retornos
- Medir volatilidade
- Avaliar drawdown (queda em relação ao topo histórico)
- Comparar preço com média móvel para identificar tendências

---

## Tecnologias Utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Requests

---

## Coleta de Dados

Os dados foram obtidos via API pública (CoinGecko), contendo preços históricos do Bitcoin em USD.

Após a coleta, os dados passaram por:

- Conversão de timestamp
- Indexação temporal
- Reamostragem diária
- Tratamento de valores ausentes

---

## Análises Realizadas

### 1. Evolução do Preço

Visualização da série temporal para identificar tendência geral e períodos de alta e baixa.

---

### 2. Retorno Diário

Cálculo da variação percentual diária:

\[
Retorno = (P_t - P_{t-1}) / P_{t-1}
\]

O retorno é utilizado para:

- Medir variações reais do ativo
- Avaliar risco
- Analisar distribuição estatística

---

### 3. Distribuição dos Retornos

Análise do histograma dos retornos para observar:

- Frequência de pequenas variações
- Presença de caudas longas (eventos extremos)
- Assimetria
- Comportamento não-normal típico de ativos financeiros

---

### 4. Volatilidade (Rolling 30 dias)

Cálculo do desvio padrão dos retornos em uma janela móvel de 30 dias.

Essa métrica permite identificar períodos de:

- Alta instabilidade
- Maior risco
- Momentos de estresse de mercado

---

### 5. Drawdown

Cálculo da queda percentual em relação ao pico histórico anterior.

O drawdown mede:

- O tamanho das quedas
- Risco de perda acumulada
- Impacto para investidores que compraram no topo

---

### 6. Média Móvel

Comparação do preço com média móvel para identificar:

- Tendência predominante
- Momentos de aceleração
- Possíveis reversões

A média móvel ajuda a suavizar o ruído da série temporal.

---

## Principais Insights

- O Bitcoin apresenta alta volatilidade ao longo do período analisado.
- A distribuição dos retornos mostra presença de caudas pesadas.
- Eventos extremos ocorrem com frequência maior do que uma distribuição normal sugeriria.
- Períodos de forte drawdown indicam risco significativo.
- A média móvel evidencia claramente ciclos de alta e baixa.



Possíveis evoluções do projeto:

- Comparação com outros ativos (ex: S&P500, Ouro)
- Análise de correlação entre ativos
- Aplicação de modelos de previsão
- Backtesting de estratégias simples

---

Autor

Arthur Chagas  
Projeto desenvolvido para fins de estudo e portfólio.
