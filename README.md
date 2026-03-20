# Trader_sentiment_analysis

# 📊 Trader Behavior vs Market Sentiment Analysis

## 📌 Objective

This project analyzes how Bitcoin market sentiment (Fear vs Greed) impacts trader behavior and performance on Hyperliquid. The goal is to identify patterns that can inform better trading strategies.

---

## 📂 Dataset

1. **Bitcoin Market Sentiment**

   * Columns: Date, Classification (Fear/Greed)

2. **Hyperliquid Trader Data**

   * Includes: account, price, size, side, timestamp, closed PnL, etc.

---

## ⚙️ Methodology

1. **Data Cleaning**

   * Converted timestamps to datetime format
   * Standardized column names
   * Handled missing values and ensured consistency

2. **Data Merging**

   * Aggregated both datasets at daily level
   * Merged on date column

3. **Feature Engineering**

   * Daily PnL per trader
   * Win rate
   * Trade frequency
   * Leverage proxy
   * Long/Short ratio

4. **Segmentation**

   * High vs Low leverage traders
   * Frequent vs Infrequent traders
   * Winners vs Losers

---

## 📊 Key Insights

1. **Higher Risk-Taking in Greed Periods**

   * Traders show higher PnL variance during Greed
   * Indicates aggressive behavior

2. **Risk Aversion During Fear**

   * Reduced leverage and position size
   * Lower trade activity

3. **High Leverage = High Risk**

   * Larger profits but also larger losses
   * Leads to inconsistent performance

---

## 🧠 Strategy Recommendations

1. **Sentiment-Based Leverage Adjustment**

   * Reduce leverage during Fear periods
   * Use moderate leverage during Greed periods

2. **Trade Frequency Optimization**

   * Avoid overtrading during Fear
   * Increase activity during strong Greed trends

3. **Risk Management for High-Leverage Traders**

   * Limit exposure during volatile conditions

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/trader-sentiment-analysis.git
cd trader-sentiment-analysis
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run notebook

```bash
jupyter notebook
```

Open:

```
Assignment_with_markdown.ipynb
```

---

## 📌 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 📎 Output

* Visualizations comparing Fear vs Greed
* Trader segmentation analysis
* Strategy insights

---

## 👤 Author

[Your Name]
