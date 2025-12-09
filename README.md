# S-P-500-Stock-Ranking-System
This project builds an ML pipeline that ranks S&amp;P 500 stocks as Buy, Hold, or Sell using Yahoo Finance data. Stocks are scored on valuation, profitability, growth, and financial health metrics. Multiple ML models train on these scores to predict rankings. The workflow produces a CSV with predictions and includes a backtest against the S&amp;P 500.

**Overview**
This project automatically pulls stock data from Yahoo Finance, scores companies based on key financial metrics (valuation, profitability, growth, and financial health), and applies multiple machine learning models to predict stock recommendations.
Features

Automated Data Collection: Fetches real-time data using yfinance
Fundamental Analysis Scoring: Evaluates stocks on 7 key metrics
Multiple ML Models: Compares 8 different algorithms including ensemble methods
Configurable Thresholds: Easy-to-adjust scoring criteria
Performance Metrics: Detailed classification reports and accuracy scores


**Limitations**
Uses historical data (not real-time trading)
Fundamental analysis only (no technical indicators)
Simplified scoring system
Educational purpose only - not financial advice

**Future Enhancements**
Add technical indicators (RSI, MACD, Bollinger Bands)
Implement sector-specific thresholds
Include sentiment analysis from news
Build backtesting framework
Create interactive dashboard
**Data Source**
All financial data is sourced from Yahoo Finance via the yfinance library.
