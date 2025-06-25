# 🧠 Trader Behavior Insights

This project explores the relationship between trader performance and market sentiment using the Bitcoin Fear & Greed Index and historical trading data from Hyperliquid.

## 📌 Objective

- Analyze trader behavior across different sentiment regimes (Fear vs. Greed)
- Identify how average Profit and Loss changes with sentiment
- Deliver actionable insights for sentiment-aware trading strategies

---

## 📁 Project Structure

- `Trader_Sentiment_Analysis.ipynb` — Jupyter notebook with complete analysis, visualizations, and conclusions
- `data.zip` — Contains the two required datasets:
  - `trades.csv` — Historical trader data (exceeds 25MB; zipped for upload)
  - `funding_gov.csv` — Daily Fear & Greed Index

---

## 📊 Datasets

### 1. Fear & Greed Index
- Source: Alternative.me
- File: `funding_gov.csv`
- Columns:
  - `Date`
  - `Value`
  - `Classification` (e.g., Fear, Greed)

### 2. Trader Data from Hyperliquid
- File: `trades.csv`
- Columns:
  - `Account`, `Coin`, `Execution Price`, `Size Tokens`, `Closed PnL`, `Timestamp IST`, and more

---

## 🔍 Insights

- Traders performed significantly better on average during periods of Greed than Fear.
- PnL distributions showed greater variability under Fear conditions.
- These trends suggest behavioral shifts that can be leveraged in future strategy design.

---

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/trader-sentiment-analysis.git
   cd trader-sentiment-analysis
2. Unzip the data:

Extract data.zip in the root directory of the notebook.

3. Run the notebook:

Open Trader_Sentiment_Analysis.ipynb in Jupyter or VSCode and execute each cell in order.

---

## Author
SNEHIL SRIVASTAVA

📧 Email: Snehil1420@gmail.com
