📈 StockMarket — Automated Daily Market Report Bot 

A sophisticated bot that automatically generates a comprehensive global market report every morning at 9:00 AM, covering indices, stocks, sectors, and macroeconomic indicators.

🚀 What It Does

🔷 Daily Automated Execution
Runs automatically each day with robust retry logic to ensure data reliability.

🔷 Comprehensive Market Data Aggregation (Yahoo Finance)
Collects up-to-date data on:

Major indices (e.g., Merval, S&P 500)

Key macro indicators (VIX, 10-year Treasury yields, commodities like gold and oil, Bitcoin)

Sector ETFs (Technology, Financial, Energy, Consumer sectors)

Leading stocks (AAPL 
, MSFT 
, NVDA 
, GOOGL 
, MELI 
, TSLA 
, GGAL, YPF)

🔷 AI-Driven Market Sentiment Summary
Produces natural language insights on market trends, risk appetite, volatility, and volume signals, e.g., "A calm session with low volatility and no clear market direction. Tags: Neutral."

🔷 3-Month Normalized Performance Chart
Generates a clean visual comparison of stock and index performance over the last three months.

🔷 Fully Styled HTML Email Report
Sends a visually rich daily email featuring:

Market tiles with price and daily change

Sector performance heatmap

A market calendar highlighting key economic events

Individual stock data including daily change, year-to-date returns, and AI-predicted short-term price movements

Embedded performance charts with logos and branded color styling

🔷 Modular and Extensible Codebase
Employs Python libraries (yfinance, pandas, NumPy, matplotlib) and SMTP for email delivery, with clear separation of data fetching, analysis, reporting, and email formatting components.
