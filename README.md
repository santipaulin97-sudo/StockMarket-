📈 StockMarket — Automated Daily Market Report Bot

Un bot que genera todos los días a las 9:00 AM un reporte completo del mercado global: índices, acciones, sectores e indicadores macro — todo automáticamente.

🚀 What It Does

🔷 Daily Automated Run (Cron)
Generates a fresh market report every morning — no manual work.

🔷 Smart Data Collection (Yahoo Finance)
Fetches:

Major U.S. indices

Global macro indicators (VIX, rates, gold, oil)

Sector ETFs

Top global stocks (AAPL, MSFT, NVDA, GOOGL, MELI, TSLA…)

🔷 AI Sentiment Analysis
Interprets the market environment:

Risk-On / Risk-Off

Volatility context

Inflation & macro pressure

Commodity + rates behavior

Example:

“Calm session with low volatility and no major trend. Tags: Neutral.”

🔷 3-Month Performance Chart
A clean, normalized chart comparing all tracked tickers.

🔷 HTML Email Report
Fully formatted daily email including:

Index performance

Global indicators

Sector ETF heatmap

Daily / Monthly / YTD stock returns

24h prediction (regression + momentum)

Inline embedded chart

🔷 Robust Architecture
Retry-safe downloader prevents API failures.

🧠 Tech Stack

Python

Yahoo Finance (yfinance)

Pandas + NumPy

Matplotlib

Custom NLP logic

SMTP automation

Cron scheduling
