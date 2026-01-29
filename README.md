📊 Trader Behavior vs. Market Sentiment: A Deep Dive
Junior Data Scientist Assignment – Trader Behavior Insights Analyzing how the "Fear & Greed Index" influences performance on Hyperliquid.

🚀 The Big Picture
Every trader has heard the phrase "Buy the fear, sell the greed," but how many actually do it successfully? In this project, I explored the relationship between Bitcoin’s market sentiment and the actual performance of traders on the Hyperliquid exchange.

My goal was to move past the surface-level metrics and find the "hidden patterns"—the specific market conditions where traders either find their edge or lose their cool.

🧠 My Thought Process
I approached this assignment in four distinct stages:

Cleaning the Noise: Trade-level data is naturally messy. I spent a good chunk of time on "Temporal Alignment"—ensuring that every single trade was mapped to the correct daily sentiment score without "look-ahead bias."

The "So What?" Phase: I didn't just want to see if traders made money. I wanted to see how they behaved. Did they trade more often when scared? Did they take bigger risks when greedy?

Visualization: I built a diagnostic dashboard to make these patterns jump off the screen. Sometimes a simple boxplot tells a better story than a complex model.

Strategic Takeaways: I concluded with actual trading insights that could be used to adjust a strategy's risk profile in real-time.

📈 Key Findings (The "Aha!" Moments)
The Fear Premium: Surprisingly, the traders in this dataset saw their highest average profits during Extreme Fear. It turns out, providing liquidity when everyone else is panicking is a high-alpha strategy.

The Greed Trap: While "Extreme Greed" days had an incredibly high 87% win rate, the actual profit-per-trade was lower. Traders are consistent when it's sunny, but they hit their "home runs" during the storms.

Psychological Shift: I found a negative correlation between sentiment and volume. As the market gets "boring" (Greed), these traders actually scale back, showing great discipline.

🛠️ Tech Stack & Tools
Python: My primary engine for data crunching.

Pandas: For the heavy lifting of merging and aggregating 200,000+ rows of trade data.

Seaborn & Matplotlib: To turn rows of numbers into a visual story.

Jupyter Notebook: Where the logic, code, and insights live together.
