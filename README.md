# Yield Curve Strategy Research

This project explores the structure and trading opportunities in interest rate markets using yield curve modeling techniques like the Nelson-Siegel model.

## 🧠 Project Goal

The goal of this notebook is to **learn and experiment** with how yield curves behave, how to model them using parametric fits (like Nelson-Siegel), and how to backtest simple trading strategies based on deviations from model expectations.

## 📦 What's Inside

- Downloading historical yield data from FRED
- Fitting the Nelson-Siegel yield curve daily
- Computing residuals and z-scores
- Designing a hedged mean-reversion strategy
- Backtesting with PnL in dollars
- Adding realistic features like transaction costs and risk metrics

## 📈 Performance Analysis

At the end of the notebook, key statistics are calculated:
- Sharpe Ratio
- Max Drawdown
- Win Rate
- Average PnL per Trade
- Total and Cumulative PnL

## 🚀 Getting Started

Install the required packages:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook main.ipynb
```

## 🛠 Requirements

See `requirements.txt`

## 📚 Learning Focus

- Term structure modeling
- Strategy construction in fixed income
- Realistic backtesting practices
- Python skills for quant research
