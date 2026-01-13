# 📊 Data Analysis Capstone Projects

This repository contains two comprehensive data analysis projects focusing on **real-world datasets**:  
1. Emergency response data (911 Calls)  
2. Financial market data (Stock Prices)

Both projects emphasize **data cleaning, exploratory data analysis (EDA), feature engineering, and visualization** using Python.

---

# 📞 Project 1: 911 Calls Data Analysis

## 📌 Project Overview
This project involves an exploratory data analysis (EDA) of **911 emergency call records** to uncover patterns, trends, and insights related to emergency incidents. The dataset captures information such as the reason for the call, time of the call, and location details.

The goal of this study is to understand:
- The most common reasons for 911 calls
- Temporal trends (daily, monthly, hourly)
- Geographic distribution of emergencies
- Relationships between time, location, and call types

---

## 📂 Dataset Description
The dataset contains the following key fields:

| Column Name | Description |
|------------|------------|
| `lat` | Latitude of the incident |
| `lng` | Longitude of the incident |
| `desc` | Description of the emergency |
| `zip` | Zip code |
| `title` | Emergency type and sub-type |
| `timeStamp` | Date and time of the call |
| `twp` | Township |
| `addr` | Address |
| `e` | Dummy variable (always 1) |

The data originates from **public 911 call records**.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Loading & Cleaning
- Loaded dataset using Pandas
- Converted timestamps into `datetime` objects
- Handled missing and inconsistent values

### 2️⃣ Feature Engineering
- Extracted **emergency reason** (EMS, Fire, Traffic) from the `title`
- Created new time-based features:
  - Hour
  - Month
  - Day of Week

### 3️⃣ Exploratory Data Analysis (EDA)
- Most frequent emergency types
- Call volume trends by hour, day, and month
- Geographic distribution analysis
- Heatmaps for temporal relationships

### 4️⃣ Visualization
- Count plots
- Line plots
- Heatmaps
- Comparative analysis using Seaborn

---

## 📊 Key Insights
- EMS-related calls dominate overall call volume
- Emergency calls peak during daytime hours
- Weekly and monthly trends show consistent patterns
- Certain townships experience higher emergency frequencies

---

## 🎯 Learning Outcomes
- Real-world data cleaning experience
- Feature engineering from unstructured text
- Strong EDA and visualization skills
- Time-series pattern recognition

---

# 📈 Project 2: Finance Data Analysis

## 📌 Project Overview
This project focuses on the **exploratory data analysis (EDA)** of historical stock market data for major publicly traded companies. The analysis examines price movements, daily returns, volatility, and correlations between stocks.

Objectives include:
- Understanding historical stock performance
- Measuring returns and volatility
- Comparing multiple companies
- Identifying market trends and relationships

---

## 📂 Dataset Description
The dataset consists of **historical stock price data** retrieved from **Yahoo Finance**, including:

| Column Name | Description |
|------------|------------|
| `Open` | Opening stock price |
| `High` | Highest price of the day |
| `Low` | Lowest price of the day |
| `Close` | Closing stock price |
| `Adj Close` | Adjusted closing price |
| `Volume` | Number of shares traded |

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  
- yfinance  

---

## 🔍 Key Analysis Steps

### 1️⃣ Data Collection
- Downloaded historical stock data for multiple companies
- Aligned time-series data by date
- Handled missing values

### 2️⃣ Feature Engineering
- Calculated daily returns
- Computed moving averages
- Derived rolling statistics
- Analyzed cumulative returns

### 3️⃣ Exploratory Data Analysis (EDA)
- Stock price trends
- Trading volume behavior
- Daily return distributions
- Volatility comparison
- Correlation analysis across stocks

### 4️⃣ Visualization
- Line plots for prices and moving averages
- Histograms and KDE plots of returns
- Scatter and pair plots
- Correlation heatmaps

---

## 📊 Key Insights
- Stocks show varying volatility profiles
- Strong correlations exist within similar sectors
- Daily returns cluster near zero with rare extreme events
- Market events often impact multiple stocks simultaneously

---

## 🎯 Learning Outcomes
- Financial time-series analysis skills
- Understanding of returns and risk
- Data-driven market comparison
- Improved visualization and analytical thinking

---

## 📌 Future Improvements (Both Projects)
- Predictive modeling using machine learning
- Interactive dashboards (Plotly / Power BI)
- Advanced statistical and risk metrics
- Deeper geographic and temporal clustering

---

## 📜 Disclaimer
These projects are for **educational and research purposes only**.  
The financial analysis does **not** constitute investment advice.

---

## 🙌 Acknowledgements
- Public 911 emergency datasets
- Yahoo Finance
- Python open-source community
