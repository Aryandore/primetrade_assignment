**Junior Data Scientist Assignment | Trader Behavior Insights** *An analysis of Hyperliquid trader performance correlated with the Bitcoin Fear & Greed Index.*

---

## 🚀 Project Overview
In the world of Web3 trading, sentiment is often as important as price action. This project investigates whether the **Bitcoin Fear & Greed Index** serves as a reliable indicator for trader profitability. Using a dataset of over 200,000 trades from Hyperliquid, I've mapped individual trade outcomes to daily market psychology to uncover how "fear" and "greed" actually impact the bottom line.

## 🧠 The "Human" Approach
I didn't want to just merge two CSVs and call it a day. I focused on three specific areas to ensure the results were meaningful:
1.  **Temporal Alignment:** Trade data is high-frequency (seconds), while sentiment is low-frequency (daily). I aggregated the trades into daily "snapshots" to ensure a fair comparison without any look-ahead bias.
2.  **Behavioral Metrics:** Beyond just profit (PnL), I looked at **Win Rate** and **Trading Volume**. This helped me see if traders were getting "emotional"—trading more or taking bigger risks—when the market moved into extreme sentiment zones.
3.  **Clean Code:** I handled modern Pandas deprecation warnings to ensure the notebook is future-proof and professionally formatted.

## 📉 Key Insights Discovered
* **The Alpha in Fear:** My analysis shows that the highest average daily profits actually occurred during **Extreme Fear**. This suggests that successful traders in this dataset are likely contrarians who provide liquidity when others are panicking.
* **High Probability in Greed:** While "Extreme Greed" days offered lower average profits, they had the highest **Win Rate (87%)**. It’s a lower-reward but much "safer" environment for trend-following.
* **Volume Spike:** There is a notable increase in trading activity as sentiment drops. Traders aren't walking away when things get scary; they are scaling up their activity to capture volatility.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Analysis:** Pandas, NumPy
* **Visualization:** Seaborn, Matplotlib
* **Environment:** Jupyter Notebook

## 📂 Repository Structure
* `Trader_Insights_Analysis.ipynb` - The complete analysis with code, charts, and commentary.
* `historical_data.csv` - Raw trade data from Hyperliquid.
* `fear_greed_index.csv` - Historical Bitcoin sentiment data.

---
**Author:** [Aryan Dore]  
*Junior Data Scientist Applicant*
