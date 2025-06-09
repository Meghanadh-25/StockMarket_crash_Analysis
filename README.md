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
