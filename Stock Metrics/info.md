# S&P 500 Stock Ranking System 📊

## What is the S&P 500?
The **S&P 500 (Standard & Poor's 500)** is a stock market index tracking the performance of 500 of the largest publicly traded companies in the United States. It represents approximately **80% of the total U.S. stock market capitalization** and is widely considered the best gauge of large-cap U.S. equities.

**Key Facts:**
- 500 companies across 11 major sectors
- Market-cap weighted index (larger companies have more influence)
- Includes companies like Apple, Microsoft, Amazon, Google, NVIDIA
- Established in 1957 by Standard & Poor's
- Used as a benchmark for portfolio performance

---

## 📈 Financial Metrics Explained
Our scoring system evaluates stocks based on **7 key fundamental metrics** divided into **4 categories**:

### 1️⃣ Valuation Metrics
**P/E Ratio (Price-to-Earnings Ratio)**  
- **What it is:** Stock price divided by earnings per share  
- **Formula:** `P/E = Stock Price / Earnings Per Share`  
- **Why we use it:** Indicates if a stock is overvalued or undervalued  
- **Our criterion:** `P/E < 25` → Stock is reasonably priced  
- **Example:** A P/E of 15 means investors pay $15 for every $1 of earnings  

### 2️⃣ Profitability Metrics
**ROE (Return on Equity)**  
- **What it is:** Measures how efficiently a company uses shareholder equity to generate profit  
- **Formula:** `ROE = (Net Income / Shareholder Equity) × 100`  
- **Why we use it:** Shows management's effectiveness at generating returns  
- **Our criterion:** `ROE > 15%` → Company is profitable and efficient  
- **Example:** ROE of 20% means the company generates $0.20 profit for every $1 of equity  

**Profit Margin**  
- **What it is:** Percentage of revenue that becomes profit  
- **Formula:** `Profit Margin = (Net Income / Revenue) × 100`  
- **Why we use it:** Indicates how much profit a company makes per dollar of sales  
- **Our criterion:** `Profit Margin > 10%` → Strong profitability  
- **Example:** 15% profit margin means $0.15 profit from every $1 of sales  

### 3️⃣ Growth Metrics
**Revenue Growth**  
- **What it is:** Year-over-year increase in total revenue  
- **Formula:** `Revenue Growth = ((Current Revenue - Previous Revenue) / Previous Revenue) × 100`  
- **Why we use it:** Shows company's ability to expand and capture market share  
- **Our criterion:** `Revenue Growth > 10%` → Strong growth trajectory  
- **Example:** 15% growth means revenue increased from $100M to $115M  

**1-Year Returns**  
- **What it is:** Stock price appreciation over the past year  
- **Formula:** `Returns = ((Current Price - Price 1Y Ago) / Price 1Y Ago) × 100`  
- **Why we use it:** Reflects market confidence and momentum  
- **Our criterion:** `Returns > 15%` → Positive market performance  
- **Example:** 20% return means $100 investment is now worth $120  

### 4️⃣ Financial Health Metrics
**Debt-to-Equity Ratio**  
- **What it is:** Measures company's financial leverage (how much debt vs equity)  
- **Formula:** `Debt/Equity = Total Debt / Total Equity`  
- **Why we use it:** Indicates financial risk and stability  
- **Our criterion:** `Debt/Equity < 100` → Healthy balance sheet  
- **Example:** Ratio of 50 means $0.50 of debt for every $1 of equity  

**Current Ratio**  
- **What it is:** Measures ability to pay short-term obligations  
- **Formula:** `Current Ratio = Current Assets / Current Liabilities`  
- **Why we use it:** Shows liquidity and financial stability  
- **Our criterion:** `Current Ratio > 1.5` → Strong liquidity position  
- **Example:** Ratio of 2.0 means $2 of assets for every $1 of liabilities  

---

## 🎯 Why These Metrics Matter

| Metric         | Investor Insight                                  |
|----------------|--------------------------------------------------|
| P/E Ratio      | Is the stock fairly priced compared to earnings? |
| ROE            | Is management creating value for shareholders?   |
| Profit Margin  | How efficient is the business model?            |
| Revenue Growth | Is the company expanding its market?            |
| 1Y Returns     | Does the market have confidence in the stock?   |
| Debt/Equity    | Can the company survive economic downturns?     |
| Current Ratio  | Can it pay its bills in the next 12 months?     |

---

## 📊 Scoring System Summary
Each stock receives **0–7 points** based on these metrics:

- ✅ **Score 5–7: BUY** → Strong fundamentals across multiple areas  
- ✅ **Score 3–4: HOLD** → Moderate fundamentals, wait and watch  
- ❌ **Score 0–2: SELL** → Weak fundamentals, high risk  

**Examples:**
- NVDA scores 5 points → Strong ROE (107%), high growth (62.5%), good liquidity → **BUY**  
- AAPL scores 1 point → High debt/equity (152), low growth (7.9%) → **SELL**  

---

## 🔍 Data Source
All financial data is sourced from **Yahoo Finance** using the `yfinance` Python library, which provides:  
- Real-time and historical stock prices  
- Company fundamentals (balance sheet, income statement)  
- Key financial ratios  
- Market capitalization data  

**Last Updated:** Data reflects the most recent fiscal year and trailing 12-month metrics.

