# Stock Analyzer

Análise de ações dos EUA usando Python, Pandas, YFinance, Matplotlib e Seaborn.

## Funcionalidades

- Download de dados históricos de ações (AAPL, MSFT, GOOGL, JPM, BAC)
- Cálculo de retornos diários e estatísticas descritivas
- Visualização de retornos cumulativos
- Médias móveis (20d e 60d) para análise de tendências
- Matriz de correlação entre ativos
- Cálculo de Sharpe Ratio, retorno anualizado e volatilidade

## Requisitos

```bash
pip install pandas yfinance matplotlib seaborn
```

## Como usar

1. Abra o notebook `pandaanalize.ipynb` no Jupyter Notebook
2. Execute todas as células (Cell > Run All)
3. Os resultados serão exibidos inline, incluindo gráficos

## Saídas

- `cumulative_returns.png` - Gráfico de retornos cumulativos
- `moving_averages.png` - Médias móveis da AAPL
- `correlation_matrix.png` - Matriz de correlação dos ativos
- `risk_return_summary.csv` - Resumo de risco/retorno em CSV
