# 📈 Stock Market Analysis using Python & PostgreSQL

## 📌 Project Overview

This project focuses on analyzing real-world stock market data using Python, PostgreSQL, and SQL-based financial analysis techniques.

The project begins with data extraction and analysis in Python using Jupyter Notebook and later integrates PostgreSQL for storing and querying financial data. Various analytical techniques such as moving averages, daily returns, volatility analysis, and correlation analysis were performed to generate meaningful financial insights.

### The project demonstrates practical skills in:

Data Analysis
Financial Analytics
SQL Querying
Data Visualization
Time-Series Analysis

### 🎯 Objectives
Analyze historical stock market data
Visualize stock price movements
Perform trend analysis using moving averages
Analyze daily returns and volatility
Study stock correlation between multiple companies
Store financial data in PostgreSQL
Perform SQL-based financial analysis

### 🛠️ Technologies & Tools Used
Programming & Analysis
Python
Jupyter Notebook
Libraries
Pandas
NumPy
Matplotlib
Seaborn
yFinance
SQLAlchemy
psycopg2
Database
PostgreSQL
pgAdmin

### 📥 Data Collection
Historical stock market data was collected using the yfinance library from Yahoo Finance.
Stocks analyzed:
Reliance

## 📊 Project Workflow
1. Data Collection using Python
Fetched stock market data using Yahoo Finance API.

2. Data Cleaning & Preparation
Performed:
Missing value handling
Data inspection
Data formatting
Index resetting for SQL storage

3. Exploratory Data Analysis (EDA)
Analyzed:
Closing prices
Historical trends
Statistical summaries

4. Stock Price Visualization
Visualized stock price movement using line charts to identify trends and market behavior.

5. Moving Average Analysis
Calculated:
50-Day Moving Average (MA50)
200-Day Moving Average (MA200)

Purpose:
Identify long-term and short-term trends
Detect bullish and bearish crossover signals

## 🗄️ PostgreSQL Integration

The analyzed stock data was stored in PostgreSQL for SQL-based financial analysis.
Workflow:
Yahoo Finance → Python/Pandas → PostgreSQL → SQL Analysis

📈 SQL-Based Financial Analysis
Performed financial analysis using PostgreSQL queries.
Analyses Performed
Highest profit day
Biggest loss day
Average daily profit/loss
Profit vs loss day count
Profit day percentage analysis
Volatility analysis

📊 Key SQL Insights
Highest Profit Day
Identified the day with maximum percentage gain.
Biggest Loss Day
Detected the worst-performing trading day.
Profit vs Loss Analysis
Compared bullish and bearish trading sessions.
Profit Day Percentage
Calculated percentage of profitable trading days.
Volatility Analysis
Measured daily stock volatility using High-Low price differences.

## 📚 Concepts Used
Python & Data Analysis
Exploratory Data Analysis (EDA)
Rolling Window Functions
Daily Returns
Moving Averages
Correlation Analysis
SQL & Database
PostgreSQL Integration
Aggregation Functions
Conditional Logic
Financial Metrics
Analytical Queries

## 🔍 Key Insights
IT stocks showed strong positive correlation.
Most daily returns were concentrated near 0%, indicating moderate daily volatility.
Moving averages effectively highlighted trend direction.
SQL analysis helped identify profitable and loss-making trading sessions.
Volatility analysis revealed high-movement trading periods.

## 🚀 Future Improvements
Add Machine Learning-based stock prediction
Implement technical indicators such as RSI and MACD
Build interactive dashboards using Power BI or Plotly
Add portfolio optimization analysis
Perform real-time stock tracking

## 📌 Conclusion
This project demonstrates the integration of Python-based financial analysis with PostgreSQL-driven SQL analytics. It highlights practical applications of stock market analysis, visualization, financial metrics, and database querying using real-world market data.
