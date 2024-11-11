# GMF_investments_time_series

## Project Overview

This project is an exploratory data analysis (EDA) and time series forecasting effort for Guide Me in Finance (GMF) Investments. The goal is to preprocess, analyze, and forecast historical financial data from assets including Tesla (TSLA), Vanguard Total Bond Market ETF (BND), and the S&P 500 ETF (SPY) to optimize portfolio management.

**The project includes:**

Data preprocessing and exploration
Analysis of volatility, trends, and seasonal patterns
Risk assessment using metrics like Value at Risk (VaR) and Sharpe Ratio
Forecasting future prices for informed portfolio optimization
Data Sources
Historical data is sourced from Yahoo Finance using the yfinance Python library, covering the period from January 1, 2015, to October 31, 2024.

**Project Structure**
data/: Contains raw and cleaned CSV data files.
scripts/: Scripts for data extraction, preprocessing, EDA, and forecasting.
notebooks/: Jupyter notebooks for EDA and modeling tasks.
EDA_Interim_Report_GMF_Financial_Analysis.pptx: PowerPoint presentation summarizing the EDA findings.
README.md: Project documentation.
Requirements
Python 3.8+
Libraries: Install with pip install -r requirements.txt
yfinance
pandas
numpy
matplotlib
seaborn
scikit-learn
statsmodels
Setup Instructions
**Clone the Repository:**

```bash
git clone https://github.com/your-username/GMF_investments_time_series.git
cd GMF_investments_time_series
```

**Install Dependencies:**

```bash
pip install -r requirements.txt
```

**Data Collection:**

Run the data extraction script to download data from Yahoo Finance:

## Task 1: Data Preprocessing and EDA

Objective: Clean and explore the data to identify trends and prepare it for forecasting.
Steps:
Data cleaning, missing values handling, and scaling.
Exploratory data analysis (EDA) to identify trends, seasonality, and volatility.
Outlier detection and risk assessment using metrics like VaR and Sharpe Ratio.
Results: Key findings from EDA, including trends, volatility, and seasonality.

## Task 2: Time Series Forecasting Model Development

Objective: Build and evaluate time series forecasting models for predicting TSLA's stock prices.
Steps:
Model selection (ARIMA, SARIMA, or LSTM).
Parameter tuning and model evaluation using MAE, RMSE, and MAPE metrics.

## Task 3: Forecast Analysis

Objective: Use the best-performing model to forecast future prices.
Steps:
Generate forecasts for the next 6-12 months and analyze trends.
Visualize the forecasted values with confidence intervals.

## Task 4: Portfolio Optimization Based on Forecast

Objective: Optimize a sample portfolio of TSLA, BND, and SPY based on forecasted data.
Steps:
Calculate annual returns and risk metrics for each asset.
Optimize asset allocation using the Sharpe Ratio for maximum risk-adjusted returns.
