# 📊 Magic Formula Backtesting - B3 (2019–2025)

This project applies **Joel Greenblatt's Magic Formula** to the Brazilian market, using real data from companies listed on **B3** between 2019 and 2025 (YTD). The goal is to evaluate the performance of the strategy with different portfolio sizes, comparing the results to the **IBOVESPA** index.

## 🧠 About the Strategy

The Magic Formula aims to identify "good and cheap" stocks based on two fundamental indicators:

- **ROIC (Return on Invested Capital)** – measures the quality of the company.
- **Earnings Yield (inverse of EV/EBIT)** – measures how "cheap" the stock is.

Companies are ranked based on a combination of these two factors, and the highest-ranked are selected to build the portfolios.

## 🔬 What Was Tested?

Portfolios were simulated with different numbers of assets:

- 1 asset  
- 5 assets  
- 20 assets  
- 50 assets  
- 90 assets  

Portfolios were rebalanced using the Magic Formula and compared to the performance of the IBOV index.

## 📈 Key Results

- The portfolio with **1 asset** was the most profitable, with a cumulative return of **5.05x** (~**30% annually**).
- The **5-asset** version also performed well: **3.74x**.
- The **IBOVESPA**, used as a benchmark, returned **1.59x** over the same period.

Although no risk metrics were included, the pattern is clear: the lower the diversification, the higher the potential return — and the greater the deviation from the market average.

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- yFinance / local fundamental data (if applicable)  
- Jupyter Notebook
