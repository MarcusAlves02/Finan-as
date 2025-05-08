# 📊 Piotroski F-Score Backtesting – B3 (2019–2025)

This project applies the **Piotroski F-Score** strategy to the Brazilian stock market, evaluating annual investment portfolios from **2019 to 2025**. The goal is to assess how portfolios composed of companies with different F-Score levels perform when compared to the **IBOVESPA** index.

---

## 🧠 What is the F-Score?

The **Piotroski F-Score** is a fundamental analysis metric used to measure a company’s financial strength based on **9 accounting signals**, divided into three categories:

- **Profitability**
- **Leverage and Liquidity**
- **Operating Efficiency**

Each signal contributes 1 point if it meets a predefined criterion, producing a total score from **0 to 9**. Higher scores indicate stronger financial health.

---

## 🔬 What was tested?

Annual portfolios were simulated using companies with F-Scores ranging from **0 to 9**, tested **individually**. For each base year, companies with the exact target score and sufficient average trading volume were selected to build an **equally weighted portfolio** for the following year.

These portfolios were benchmarked against the **IBOVESPA** index performance.

---

## 📈 Key Findings

- F-Score 8 had the highest return, multiplying capital by **3.24x**.
- F-Scores 6–8 consistently outperformed the IBOVESPA.
- Low F-Scores (2–4) significantly underperformed.
- F-Score 9 showed weak performance (**0.70x**), possibly due to low diversification in selected assets.

---

## 🚫 Database Access

> ⚠️ Due to GitHub file size limitations, the database file `dados_cvm.db` (over 100 MB) **could not be included** in the repository.

If you are interested in accessing the database used in this project, feel free to contact me directly on **LinkedIn**.

📬 [My LinkedIn](https://www.linkedin.com/in/mp-alves/)

---

## 🛠️ Technologies Used

- Python 3.x  
- Pandas  
- Matplotlib  
- yFinance  
- SQLite3  
- Jupyter Notebook
