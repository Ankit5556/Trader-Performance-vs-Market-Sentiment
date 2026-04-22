# 📊 Trader Behavior vs Market Sentiment Analysis

## 📌 Overview

This project analyzes how trader performance and behavior change under different market sentiment conditions (Fear vs Greed). It combines trade-level data with the Fear & Greed Index to uncover patterns in profitability, risk-taking, and trading activity.

---

## 📁 Project Structure


project/
│── data/
│   ├── historical_data.csv
│   ├── fear_greed_index.csv
│
│── notebook.ipynb
│── README.md
│── outputs/
│   ├── pnl_chart.png
│   ├── winrate_chart.png
│   ├── drawdown_chart.png


## ⚙️ Setup Instructions

### 1. Clone repository

```bash
git clone <your-repo-link>
cd project
```

### 2. Install dependencies

```bash
pip install pandas numpy matplotlib seaborn streamlit
```

---

## ▶️ How to Run

### Run Notebook

```bash
jupyter notebook
```


```

---

## 📊 Output

The project generates:

* Performance comparison charts (PnL, Win Rate)
* Behavioral charts (Trade Frequency, Trade Size)
* Segmentation analysis
* Interactive dashboard

---

## 🧠 Key Questions Answered

* Does performance differ in Fear vs Greed markets?
* Do traders change behavior based on sentiment?
* Which trader segments perform best?

---

## 🚀 Technologies Used

* Python (Pandas, NumPy)
* Visualization (Matplotlib, Seaborn)

---
# 📊 Analysis Summary: Trader Behavior vs Market Sentiment

## 🔹 Methodology

The analysis combines trade-level data with the Fear & Greed Index to evaluate how trader performance and behavior vary under different market conditions.

Data preprocessing involved:

* Cleaning and standardizing column names
* Converting timestamps to daily format
* Aggregating trades at a daily trader level
* Creating key metrics such as daily PnL, win rate, trade frequency, and average trade size
* Merging with sentiment data and categorizing days into Fear (index < 50) and Greed (index ≥ 50)

Additional analysis included:

* Behavioral segmentation (frequent vs infrequent traders, high vs low trade size)
* Consistency analysis based on PnL volatility

---

## 🔹 Project Summary

### 1. Performance differs across sentiment

Traders tend to achieve higher average PnL and win rates during Greed periods compared to Fear periods. This suggests that bullish conditions provide more favorable trading opportunities.

### 2. Behavior changes during Fear

Trade frequency increases during Fear periods, indicating reactive or panic-driven trading behavior. However, this does not translate into better performance.

### 3. Risk-taking increases in Greed

Average trade size is higher during Greed periods, suggesting increased confidence and willingness to take larger positions.

### 4. Consistency matters more than activity

Traders with lower PnL volatility (consistent traders) show higher win rates compared to inconsistent traders, highlighting the importance of stable strategies over aggressive trading.

---

## 🔹 Strategy Recommendations

### ✅ Strategy 1: Risk Control During Fear

During Fear periods, traders should reduce trade frequency and position size to avoid losses caused by emotional trading.

### ✅ Strategy 2: Controlled Aggression in Greed

During Greed periods, traders can increase participation but should maintain disciplined risk management to avoid overexposure.

### ✅ Strategy 3: Focus on Consistency

Traders should prioritize stable strategies with controlled risk rather than chasing high returns through volatile trading behavior.

---

## 🔹 Conclusion

Market sentiment significantly influences both trader performance and behavior. While Greed conditions generally lead to better outcomes, disciplined and consistent trading strategies outperform reactive and high-risk approaches across all market conditions.




---

## 👨‍💻 Author
Ankit Jadhav
