📈 StockMarket — Automated Daily Market Report Bot

This project is an automated financial reporting bot that runs every day at 9:00 AM, generating a complete market summary for the Top Global Stocks, Major Indexes, Global Indicators, and Sector ETFs.
The bot performs AI-based sentiment analysis, creates a 3-month performance chart, builds a full HTML report, and sends it via email.

🚀 Features
✅ Daily Automatic Execution (Cron)

Runs every morning and generates a fresh market report without manual intervention.

✅ Data Collection via Yahoo Finance

Uses yfinance to download:

Major U.S. indices (S&P 500, Dow Jones)

Global macro indicators (VIX, 10-year rates, Gold, Oil)

Sector ETFs (Tech, Financials, Energy, Health)

Top 20 global stocks (example: AAPL, MSFT, NVDA, GOOGL, MELI, TSLA…)

✅ AI Sentiment Summary

Automatically interprets:

Market risk appetite (Risk-On / Risk-Off)

Volatility conditions

Inflation / macroeconomic pressures

Behavioral signals from gold, oil, interest rates

Generates readable insights for non-technical users

Example:

“Calm session with limited volatility. No clear trend detected today. Tags: Neutral.”

✅ 3-Month Normalized Performance Chart

Generates a combined chart comparing the performance of all tracked stocks over the last 3 months.

✅ HTML Email Report

Beautifully formatted HTML report including:

Main indices table

Global indicators table

Sector ETF heatmap

Stock performance (Daily / Monthly / YTD)

24h prediction using linear regression + momentum

Inline embedded chart

✅ Error-Resistant Architecture

Custom safe_download() function with retries to avoid API failures.

🧠 Technologies

Python

Yahoo Finance API (yfinance)

NumPy + Pandas

Matplotlib

NLP Sentiment Logic

SMTP Email Automation

Cron Scheduling
