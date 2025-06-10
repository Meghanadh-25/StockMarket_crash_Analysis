📉 Stock Market Crash Analysis (Sensex Index)
This project analyzes historical Sensex data to identify daily crashes, drawdowns, and market crash clusters using Python and visualizes the results with Plotly.

🚀 Overview
Analyzed stock closing price data for the Sensex index

Calculated:

Daily returns

Drawdowns from historical peaks

Days with crashes (return ≤ -5%)

Clusters of crashes (drawdowns ≤ -20% grouped by 3-day windows)

Visualized results with interactive line plots and markers for crash events

🛠️ Tech Stack
Python (Pandas, NumPy)

Plotly for interactive visualization

Matplotlib for auxiliary plots

Jupyter Notebook for development

📊 Key Features
✅ Convert and sort date-indexed time series data

✅ Calculate and plot drawdowns

✅ Identify & count major daily crashes

✅ Group drawdown periods into logical crash clusters

✅ Generate meaningful visualizations

📈 Sample Output
Daily Return %

Drawdown % from peak

Crash markers plotted on line charts

Cluster detection based on rolling window

📁 Dataset
Historical Sensex data was loaded from a cleaned CSV file prepared in advance (user-collected dataset).

🧠 Key Learnings
Time-series data manipulation using datetime indexing

Conditional logic for cluster grouping in financial analysis

Data visualization using Plotly for storytelling

# StockMarket_crash_Analysis
Using Python
stock market crash analysis

The firm has provided you with 30 years of historical data to analyze market crashes.

goal is to identify precursors to crashes by extracting key features from the data:

Daily Returns: Percentage change in closing prices to detect abrupt drops.
Drawdowns: The decline from a market peak, which signals the severity of market downturns.
Rolling Metrics: A 10-day rolling average return and a 10-day rolling volatility to capture trends and market instability over short periods.

The problem is to detect patterns that precede market crashes and understand how the market behaves during these periods. Your objective is to develop an early warning system that triggers an alert when the 10-day average return falls below -0.5% and volatility exceeds 2%, providing proactive signals to adjust the firm’s portfolio before a potential downturn.

In this task, we will use 30 years of historical Indian stock market data. We will focus on the Sensex to analyze and understand market crashes.

We will start by cleaning and processing the financial data for analysis. Then, we will calculate daily returns, drawdowns, and rolling 10-day average returns and volatility. These metrics will help us identify and cluster periods of high market stress. We will highlight major crash events such as those in 1997, 2008–2009, and 2024. Using rolling metrics, we will build an early warning system to detect signs of an upcoming crash. This system will help data scientists and analysts manage risk and make informed investment decisions.
