# 📈 Statistical Arbitrage in Cryptocurrencies

This repository contains research, code, and results for **systematic statistical arbitrage strategies in cryptocurrency markets**. Using Binance OHLCV data (2021–2025), the project develops and backtests momentum and reversal trading strategies, evaluates their performance against Bitcoin buy-and-hold, and explores diversification benefits through combined portfolios.  

---

## 🚀 Overview

We implement and evaluate six strategies:

- **Momentum Strategies**  
  - Channel Breakout  
  - Moving Average Crossover  

- **Reversal Strategies**  
  - Pairs Trading  
  - Time Horizon Reversal  

- **Diversified Portfolios** - inverse-volatility weighted sleeves
  - Momentum Combo (Breakout + Crossover)  
  - Momentum Reversal Combo (Breakout + Crossover + Pairs Trading)  

All strategies are backtested out-of-sample with **20 bps transaction costs** per trade.  

---

## 📊 Key Results

- **All strategies outperformed BTC buy-and-hold** on a risk-adjusted basis  
- **Sharpe Ratios**: 1.4 – 2.1 (vs BTC’s 1.39)  
- **Information Ratios**: 1.6 – 2.1, confirming efficient benchmark outperformance  
- **Alpha**: 80% – 130% annually, showing independence from BTC’s market direction  
- **Drawdowns**: Generally shorter in duration than BTC, with quicker recoveries  

✅ **Best raw return**: *Pairs Trading Reversal* (146% annually, Sharpe 2.10)  
✅ **Most defensive**: *Time Horizon Reversal* (lowest max DD: –25.9%)  
✅ **Most efficient combo**: *Momentum Reversal Combo* (IR 2.11, near-zero beta)  

---
