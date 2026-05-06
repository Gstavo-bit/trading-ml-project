# trading-ml-project
Quantitative trading strategy using MACD, EMA trend filtering, and ATR-based risk management for financial market analysis.
⭐ If you find this project interesting, feel free to connect with me on LinkedIn. Gustavo Alvares Pereira de Melo
# 📊 Financial Market Trading Strategy (MACD + Trend + Risk Management)

## 🚀 Overview
This project implements a quantitative trading strategy designed to analyze financial markets using technical indicators and structured decision-making logic.

The strategy combines momentum, trend filtering, and volatility-based risk management to identify potential trading opportunities.

## ⚙️ Strategy Components

### 📈 Momentum (MACD)
- Detects trend reversals and momentum shifts
- Generates buy/sell signals based on crossovers

### 📉 Trend Filter (EMA)
- Uses a long-term Exponential Moving Average (EMA)
- Only allows long positions in uptrends and short positions in downtrends

### ⚖️ Risk Management (ATR)
- Stop-loss and take-profit levels are dynamically defined using ATR
- Helps control risk and adapt to market volatility

---

## 🧠 Strategy Logic

### ✅ Long Entry
- MACD crosses above signal line  
- Price is above EMA (uptrend confirmation)

### ❌ Short Entry
- MACD crosses below signal line  
- Price is below EMA (downtrend confirmation)

### 🔒 Exit Strategy
- Stop-loss based on ATR  
- Take-profit using risk/reward ratio  

---

## 📊 Features
- Trend-following system  
- Volatility-adjusted risk management  
- Backtesting-ready (TradingView)  
- Clean and modular structure  

---

## 🛠 Technologies
- Pine Script (TradingView)
- Technical Analysis
- Quantitative Trading Concepts

---

## 📈 Results
*(Add screenshots here from TradingView)*

Examples:
- Backtest performance
- Trade entries/exits
- Equity curve

---


---

## ⚠️ Disclaimer
This project is for educational purposes only.  
It does not guarantee profits or financial returns.

---

## 👨‍💻 Author
Gustavo — Data Science & AI Student  

## 📁 Project Structure
