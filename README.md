# NIFTY 50 Stock Market Analytics & Power BI Dashboard

## 📊 Project Overview

This is an end-to-end data analytics project on historical NIFTY 50 stock market data.

The project combines Python-based data cleaning and exploratory data analysis with an interactive Power BI dashboard to analyze stock performance, returns, volatility, trading activity, and industry-level trends.

## 🔄 Project Workflow

Raw Market Data
↓
Data Cleaning
↓
Exploratory Data Analysis
↓
Feature Engineering
↓
Clean Dataset
↓
Power BI Dashboard
↓
Market & Industry Insights

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Microsoft Power BI
- DAX
- CSV
- Parquet

## 📈 Dataset

The final dataset contains:

- 470,000+ historical records
- 65 stocks
- Historical data from 2000 to 2021
- 13 industries

The datasets are available in the `data/` folder.

## 🔍 Exploratory Data Analysis

The EDA was performed using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The notebook covers:

- Dataset exploration
- Data types
- Missing-value analysis
- Duplicate checking
- Data cleaning
- Descriptive statistics
- Correlation analysis
- Daily return analysis
- Trading volume analysis
- Turnover analysis
- Volatility analysis
- Stock-level analysis
- Industry-level analysis

The complete notebook(EDA) is available in:

`NIFTY50_Data_Analysis_Project.ipynb.`

## 📊 Power BI Dashboard

The dashboard contains three pages.

### 1. Market Overview

Provides an overall view of NIFTY 50 market activity, including:

- Total stocks
- Total records
- Average closing price
- Average daily return
- Trading volume
- Turnover
- Historical trends

### 2. Stock Performance

Allows users to select individual stocks and analyze:

- Average price
- Average daily return
- Trading volume
- Volatility
- Stock price trends
- Daily return trends

### 3. Industry & Sector Analysis

Compares industries based on:

- Average daily return
- Volatility
- Trading volume
- Turnover
- Number of stocks

Interactive filters allow users to analyze different industries and years.


## 📁 Project Structure

```text
NIFT50-Stock-Market-Analytics/
│
├── README.md
│
├── data/
│   ├── nifty50_powerbi.csv
│   └── nifty50_clean_final.parquet
│
├──notebook/
|      └── NIFTY50_Data_Analysis_Project.ipynb
|
└── powerbi/
    └── NIFT50_Historical_Market_Analysis.pbix

