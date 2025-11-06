# 🧭 Unified-Mentor-Stock-Market-Business-Analyst

📊 Global Stock Market Performance | Business Analytics Dashboard

This project was developed as part of my Business Analyst Internship – Unified Mentor Pvt. Ltd.
The objective was to analyze global stock trends, identify patterns in price movement, measure volatility, and visualize market sentiment & investment recommendations using a combination of Python (data collection) and Power BI (dashboarding).

---

🧠 Project Objective

Specifically, the goal is to:

Identify trends and patterns in stock price movements

Calculate moving averages (7D, 30D) and volatility for each stock

Measure Year-to-Date (YTD) and period-based returns

Integrate financial & analyst recommendation data

Conduct correlation analysis to examine stock relationships

Deliver a visually interactive dashboard for investor decisions

---

⚙️ Tech Stack

Python → Data extraction from Yahoo Finance (yfinance)
Pandas → Data cleaning, feature engineering (Returns, Volatility, VWAP)
Power BI → Visualization (Candlestick, Line, Area, Scatter, Donut charts)
DAX → Custom measures for Return %, Moving Averages, Profit Margins, and Sentiment Logic
Excel / CSV → Supporting Financials and Recommendation datasets

---

🧾 Data Sources
Source	Description
yfinance	Historical OHLC data (2020–2025) for 10 global companies
financials.csv	Revenue, Profit, EPS, Debt, Equity (Quarterly/Annual)
analyst_reco.csv	Analyst Recommendations (Buy / Hold / Sell)
profile.csv	Company Name, Sector, Industry, Web, Logo URL

---
🧩 Dashboard Pages
➡️ Page 1 – Stock Performance Analysis

Focus: Candlestick and Volume visualization by Date & Period
✅ Interactive Time Slicers (1W, 1M, 1Y, 3M, 5Y, YTD)
✅ Dual charts – Candlestick (Open, High, Low, Close) + Volume columns
✅ Live KPIs – Latest Open, Close, Prev Close, 52W High/Low, Trading Cap
✅ Dynamic Return% and color-coded gain/loss indicators

📸 Preview:
stock performance ![new_page-0001](https://github.com/user-attachments/assets/48fea9bd-0969-4e9f-9def-802f77d42f64)


stock trend ![new (1)_page-0001](https://github.com/user-attachments/assets/e5fa37d2-1b1f-4674-8c0f-0cd1e0c5b0a8)


---

➡️ Page 2 – Market Sentiment & Investment Insights

Focus: Financial fundamentals, analyst sentiment, and investment suggestion
✅ Profit Margin trend (YoY) with correlation narrative
✅ EPS vs Revenue scatter to study performance efficiency
✅ Donut chart – Analyst Recommendation Split (% Buy / Hold / Sell)
✅ Automated Decision Flag: “BUY 🟢”, “HOLD 🟡”, “SELL 🔴”

📸 Preview:
market sentiment ![new (2)_page-0001](https://github.com/user-attachments/assets/424ef1ee-d59b-44fa-8340-537b48ea7812)


---

🛠️ Tools & Technologies
Tool	Purpose
Python (yfinance, pandas)	Data collection & preprocessing
Power BI	Visualization and DAX modeling
Excel / CSV	Data integration layer
GitHub	Documentation and versioning

---

🧾 Internship Details

Organization: Unified Mentor Pvt. Ltd.
Domain: Business Analytics
Duration: October 2025 – February 2026
Project: Stock Market & Business Analysis Dashboard
Role: Business Analyst Intern

---

🚀 How to Use

➡️ Step 1: Run the yfinance notebook to generate the dataset
➡️ Step 2: Load the .csv files into Power BI
➡️ Step 3: Refresh relationships (DateTable, Stocks, Financials, Reco, Profile)
➡️ Step 4: Interact via slicers — Year, Period, Company
➡️ Step 5: Switch between Performance Page & Sentiment Page

---

🌐 Project Structure
📂 Unified-Mentor-Stock-Market
│
├── 📁 data/
│   ├── global_stocks.csv
│   ├── financials.csv
│   ├── analyst_reco.csv
│   └── profile.csv
│
├── 📁 notebooks/
│   └── data_collection.ipynb
│
├── 📁 powerbi/
│   └── Global_Stock_Dashboard.pbix
│
└── 📄 README.md

🧩 Acknowledgement

Special thanks to Unified Mentor Pvt. Ltd. for providing the internship opportunity and to all mentors who guided this project on Data Analytics and Business Insights.

💬 “Data tells the story — Visualization gives it life.”
