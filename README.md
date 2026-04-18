# AI Trading Bot

A machine learning powered crypto trading research project that combines technical indicators, volatility analysis, strategy rules, signal generation, and risk management.

This repository is public and is intended to show the project structure, trading logic, and ML workflow behind an automated crypto bot concept.

## Overview

The bot is designed to analyze market data, generate trading signals, and support a configurable hybrid strategy that combines rule-based technical analysis with machine learning prediction.

Core goals:

- Predict short-term crypto price movement
- Engineer useful features from OHLCV market data
- Generate trading signals from ML and technical indicators
- Apply position sizing and risk controls
- Support backtesting and strategy experimentation

## Features

### Machine Learning Prediction

- Short-term price movement prediction
- Feature engineering from OHLCV candles
- Support for sklearn-style models, XGBoost, or custom ML models
- Training and evaluation workflow for strategy research

### Technical Indicators

The strategy engine can use common technical analysis indicators such as:

- EMA and SMA
- RSI
- MACD
- Bollinger Bands
- ATR
- Volume-based signals
- Volatility features

### Signal and Strategy Engine

- Hybrid rule-based plus ML trading logic
- Configurable buy and sell conditions
- Signal generation for long and short setups
- Market scanning for high-volatility pairs
- Backtesting support for safer experimentation

### Risk Management

- Position sizing logic
- Stop-loss and take-profit rules
- Maximum drawdown controls
- Cooldown after losing trades
- Configurable leverage limits

## Tech Stack

- Python
- Pandas and NumPy
- Scikit-learn compatible ML workflow
- Technical indicator feature engineering
- Crypto market data processing
- Backtesting and signal generation logic

## How It Works

1. Load or stream market data.
2. Build features from price, volume, volatility, and indicators.
3. Run strategy rules and ML prediction.
4. Generate trade signals.
5. Apply risk management and position sizing.
6. Evaluate performance through backtesting or controlled execution.

## Disclaimer

This project is for educational and research purposes only. Crypto trading is risky and can result in financial loss. Nothing in this repository is financial advice. Use any live-trading logic only after careful review, paper trading, and risk testing.

## License and Commercial Use

No commercial license is granted unless written permission is provided by the author. Contact me before using this project in a commercial product, company workflow, or paid service.

## Author

Kareem Radwan

- LinkedIn: [kareem-radwan-11515b2a8](https://www.linkedin.com/in/kareem-radwan-11515b2a8)
- Email: [kareemradwan09@gmail.com](mailto:kareemradwan09@gmail.com)
