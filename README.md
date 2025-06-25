# 📊 Trading Behavior Insights

![Project Banner](images/project_banner.png)

This project explores how different market sentiments—**Extreme Greed, Greed, Fear, and Neutral**—influence trader behavior, profitability, trade size, and strategy. Using real-world trading data and statistical methods, we uncover actionable insights to design smarter, sentiment-aware trading strategies.

---

## 🎯 Objective

To explore the relationship between trader performance and market sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading strategies.

---

## 🧠 Project Pipeline

![Project Pipeline](images/project_pipeline.png)

**Steps Involved**:
- Data Collection (Kaggle)
- Data Preprocessing & Cleaning
- Exploratory Data Analysis (EDA)
- Statistical Testing (ANOVA, Chi-squared, Kruskal-Wallis)
- Insight Extraction
- Strategy Recommendation

---

## 📊 Key Insights

- **Greed sentiment** delivers the highest profit, even with lower win rates.
- **Extreme Greed** has the best win rate but smaller profits—likely due to cautious trade sizes.
- **SELL trades outperform BUY** during emotional markets (Fear, Greed).
- **BUY trades work better** in calm, Neutral conditions.
- **SUI coin** shows consistent profitability regardless of sentiment.
- **Neutral sentiment** sees the highest cross-margin usage (~80%), suggesting increased risk.
- Statistical tests confirm strong links between sentiment, PnL, trade size, and direction (p < 0.001).

---

## 📈 Visualizations

### 🔹 Average PnL by Sentiment
![Average_pnl](https://github.com/user-attachments/assets/eda61078-ae44-416d-b675-699a7a42745e)


### 🔹 Win Rate by Sentiment
![Win Rate](images/win_rate_by_sentiment.png)

### 🔹 Trade Size (Buy vs Sell)
![Trade Size](images/trade_size_by_sentiment_side.png)

### 🔹 BUY vs SELL Performance
![Buy vs Sell](images/buy_vs_sell_win_rate.png)

### 🔹 Coin PnL by Sentiment
![Coin Performance](images/coin_pnl_by_sentiment.png)

### 🔹 Cross Margin Usage
![Cross Margin](images/cross_margin_usage.png)

### 🔹 Trade Action Distribution
![Trade Action](images/trade_action_distribution.png)

---

## 🧪 Statistical Methods Used

- **ANOVA** & **Kruskal-Wallis** – Confirm significant difference in PnL and trade size across sentiments.
- **Chi-squared test** – Proves a strong relationship between sentiment and trade direction.
- **Visual EDA** – Used Seaborn and Matplotlib for heatmaps, bar charts, and comparisons.

---

## ⚙️ Tools Used

- Python (Pandas, NumPy)
- Seaborn, Matplotlib
- Jupyter Notebook
- Kaggle Datasets
- GitHub for version control

---

## 📬 About Me

**ShambhO Nangare**  
🎓 MSc Statistics Graduate  
💻 Aspiring Data Scientist  
✉️ [Email me](mailto:nangareshambho@gmail.com)

---

## 📂 Repository Structure

# Trader-Behavior-Insights
