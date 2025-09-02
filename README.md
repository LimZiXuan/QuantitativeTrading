Quantitative Trading Bot

This repository contains a quantitative trading framework built in Python.
It is designed for data collection, backtesting, and automated execution of trading strategies.

✨ Features

📈 Data Fetching: Market data via Yahoo Finance
 (can be extended to brokers/exchanges).

🔍 Backtesting: Test trading strategies on historical data.

🤖 Automation: Runs on schedule using GitHub Actions (no server required).

🔐 Secure API Keys: Uses GitHub Secrets for exchange/broker authentication.

📊 Extensible: Add technical indicators, risk management rules, and position sizing.

⚙️ Tech Stack

Python 3.10+

Pandas, NumPy

yfinance (for market data)

Matplotlib (for visualization)

GitHub Actions (for cron jobs)

🚀 How It Works

Strategy code is in trade.py (replace with your own logic).

GitHub Actions (.github/workflows/trading.yml) schedules the script daily.

Logs can be checked in the Actions tab after each run.

Extend with broker APIs (Binance, Alpaca, Interactive Brokers) for real execution.

📌 Roadmap

 Add more trading indicators

 Implement portfolio backtesting

 Connect to real broker/exchange APIs

 Build dashboard for monitoring
