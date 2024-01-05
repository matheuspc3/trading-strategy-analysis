# Análise de Estratégia de Trading: Compra e Venda de Ações

Este projeto realiza uma análise de uma estratégia simples de compra e venda de ações usando dados históricos da Petrobras (PETR4.SA) obtidos através da biblioteca `yfinance`. A estratégia visa identificar pontos de compra na baixa e venda na alta com base nas variações diárias do preço de fechamento da ação.

## Conteúdo

1. [Introdução](#introdução)
2. [Requisitos](#requisitos)
3. [instalação](#instalação)
4. [Uso](#uso)
5. [Resultados](#resultados)
6. [Visualizações](#visualizações)
7. [Conclusão](#conclusão)

## Introdução

A estratégia de trading implementada neste projeto baseia-se nas variações diárias do preço de fechamento da ação da Petrobras (PETR4.SA). Os sinais de compra e venda são gerados quando a variação diária é positiva ou negativa, respectivamente. O desempenho da estratégia é avaliado através da evolução do portfólio ao longo do tempo.

## Requisitos

- Python 3.x
- Bibliotecas: `yfinance`, `pandas`, `numpy`, `matplotlib`

## Instalação

```bash
pip install yfinance pandas numpy matplotlib
```
## Uso

1. **Google Colab:**
   - Clique no link abaixo para abrir o notebook no Google Colab:
     [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/matheuspc3/trading-strategy-analysis/blob/main/trading_strategy.ipynb)
   - Execute as células no Colab.

2. **Localmente com Jupyter Notebook:**
   - Baixe o notebook (`trading_strategy.ipynb`) para o seu computador.
   - Abra o Jupyter Notebook.
   - Navegue até o diretório onde o notebook está salvo.
   - Abra o notebook e execute as células.

## Resultados

Os resultados da estratégia, incluindo gráficos de preços, sinais de compra e venda, e a evolução do portfólio, são apresentados durante a execução do notebook.

## Visualizações

### 1. Preço de Fechamento da Ação PETR4.SA:
![Preço de Fechamento](https://github.com/matheuspc3/trading-strategy-analysis/assets/61256001/bc270060-e6e8-4366-a58f-1da25153c704)

### 2. Sinais de Compra e Venda:
![Sinais de Compra e Venda](https://github.com/matheuspc3/trading-strategy-analysis/assets/61256001/b2316e17-4841-4570-bf42-ab6e97a8e608)

### 3. Evolução do Portfólio:
![Evolução do Portfólio](https://github.com/matheuspc3/trading-strategy-analysis/assets/61256001/934c9ad8-21aa-41f5-a5b7-63788bd9f35b)

# Conclusão

Este projeto fornece uma análise visual da estratégia de compra e venda de ações, permitindo uma avaliação do desempenho ao longo do tempo. Os gráficos apresentados podem ser personalizados e utilizados para aprimorar a comunicação dos resultados para diferentes públicos.
