# 📊 Trading Behavior Insights

![image-of-a-man-looking-at-a-Forex-chart-with-different-emoticons](https://github.com/user-attachments/assets/d29ed6db-67cc-489e-b829-7b6f7768e022)


This project explores how different market sentiments—**Extreme Greed, Greed, Fear, and Neutral**—influence trader behavior, profitability, trade size, and strategy. Using real-world trading data and statistical methods, we uncover actionable insights to design smarter, sentiment-aware trading strategies.

---

## 🎯 Objective

To explore the relationship between trader performance and market sentiment, uncover hidden patterns, and deliver insights that can drive smarter trading strategies.

---

**🛠 Project Pipeline**:
- 📥 Data Collection
- 🧹 Data Preprocessing & Cleaning
- 📊 Exploratory Data Analysis (EDA)
- 🧪 Statistical Testing (ANOVA, Chi-squared, Kruskal-Wallis)
- 🔍 Insight Extraction
- 🎯 Strategy Recommendation 

---

## 🔍 Key Insights

### 1️⃣ Sentiment-Driven Performance

- 💰 Greed yields the highest overall profits despite a slightly lower win rate — suggesting fewer, more profitable trades.
- 🏆 Extreme Greed has the highest win rate but lower total profit — possibly due to profit-locking or cautious trading.
- ⚠️ Neutral sentiment performs worst, with the lowest win rate and PnL — indicating indecision and poor market timing.

---

### 2️⃣ Trade Size Behavior

- 🚀 Extreme Greed: High average and median trade sizes → strong confidence and aggressive positioning.
- 😨 Fear: High average but low median → a few large traders skewing the average; most remain cautious.
- 😐 Neutral & 😄 Greed: Small, frequent trades → reflecting caution or stable/low-volatility conditions.

---

### 3️⃣ Trade Direction & Market Sentiment

- 📊 A Chi-squared test (p < 0.001) confirms a significant link between market sentiment and trade direction (BUY/SELL).
- 🔻 SELL trades outperform BUY during volatile emotional markets like Fear and Greed.
- 🔼 BUY trades are more successful during Neutral sentiment, where conditions are more stable.

---

### 4️⃣ Coin-Specific Strategy

- 📈 SUI, ETH, and SOL perform better in bearish/fearful market conditions.
- 🏅 SUI is consistently profitable across all sentiment types — making it a strong candidate for sentiment-independent strategies.
- 🎯 Aligning coin selection with market sentiment improves timing and trade outcomes.

---

### 5️⃣ Risk Management & Margin Usage

- ⚠️ Cross margin usage is highest in Neutral (~80%) — showing higher risk despite poor market performance.
- 🛡️ Usage drops during Extreme Greed (~55%) — indicating more cautious and isolated margin strategies.
- 💸 Trading fees are highest during Fear and Neutral — highlighting the need for cost-efficiency in low-profit scenarios.

---

## ✅ Conclusion

Traders can enhance performance by:

- Aligning strategy with market sentiment (direction, size, and frequency)
- Prioritizing high-performing coins (like SUI) across conditions
- Monitoring risk exposure, fee efficiency, and margin behavior
- Adapting trade direction based on emotional market states

These insights support the development of robust, sentiment-aware trading strategies.

---

## 📈 Visualizations

### 🔹 Average PnL by Sentiment
![reshaped_average_pnl2](https://github.com/user-attachments/assets/339bcf5c-a8b6-4a9b-88f4-d270f6055df4)

### 🔹 Win Rate by Sentiment
![reshaped_win_rate](https://github.com/user-attachments/assets/c45834d7-8849-4c14-947e-9b4b8754264b)

### 🔹 Trade Size (Buy vs Sell)
![reshaped_Average_trade_side_](https://github.com/user-attachments/assets/0bd86b5b-27bf-4972-ae66-298ba83abca5)

### 🔹 BUY vs SELL Performance
![reshaped_win_rate_trade_side](https://github.com/user-attachments/assets/13002964-d11b-4d72-8c7b-5f972d62a7ec)

### 🔹 Top 10 Coin PnL by Sentiment
![reshaped_average_pnl_coin2](https://github.com/user-attachments/assets/ce196f41-ba45-47ad-bd2f-82369a6cb8f9)

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
- GitHub for version control

---

## 📬 About Me

**Shambho Nangare**  
🎓 MSc Statistics Graduate  
💻 Aspiring Data Scientist  
✉️ [Email me](mailto:nangareshambho@gmail.com)

---

## 📂 Repository Structure

# Trader-Behavior-Insights
