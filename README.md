
# 📈 Stock Market Time Series Forecasting using Python

> **An End-to-End Time Series Analysis Capstone Project completed as part of an IIT-certified Data Science & AI Program.**

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
![Prophet](https://img.shields.io/badge/Facebook-Prophet-blue)
![ARIMA](https://img.shields.io/badge/Model-ARIMA-success)
![Time Series](https://img.shields.io/badge/Domain-Time%20Series%20Analysis-red)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

This repository presents an **end-to-end Stock Market Time Series Forecasting project** completed as part of an **IIT-certified Data Science & Analytics Program**.

The objective of this project is to analyze historical stock market data of selected **NSE-listed companies**, forecast future stock prices using statistical and machine learning time series models, and construct a data-driven investment portfolio.

The project covers the complete analytics workflow—from data collection and preprocessing to forecasting, portfolio allocation, and performance evaluation using the **StockGro virtual trading platform**.

---

# 🎯 Project Objectives

- Collect historical stock market data using Yahoo Finance.
- Perform exploratory data analysis on multiple stocks.
- Analyze trends, seasonality, and volatility.
- Test stationarity using the Augmented Dickey-Fuller (ADF) Test.
- Build forecasting models using Prophet and ARIMA.
- Compare predicted values with actual market prices.
- Create a diversified investment portfolio.
- Evaluate portfolio performance through virtual trading.

---

# 📊 Dataset

The dataset consists of historical stock prices downloaded using the **Yahoo Finance (yfinance)** API.

### Stocks Included

- HDFC Bank
- Infosys (INFY)
- Reliance Industries
- Tata Motors
- TCS
- ITC

The dataset includes:

- Date
- Open Price
- High Price
- Low Price
- Close Price
- Adjusted Close Price
- Trading Volume

---

# 🔄 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning & Preprocessing
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Stationarity Testing (ADF)
        │
        ▼
Time Series Forecasting
(Prophet & ARIMA)
        │
        ▼
Model Evaluation
        │
        ▼
Portfolio Construction
        │
        ▼
Performance Evaluation
```

---

# 🛠 Tech Stack

### Programming Language

- Python

### Libraries

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- yfinance
- Prophet
- Statsmodels
- Scikit-learn
- SciPy

---

# 📈 Time Series Techniques Used

- Time Series Forecasting
- Trend Analysis
- Seasonality Detection
- Rolling Statistics
- Volatility Analysis
- Correlation Analysis
- Stationarity Testing
- Forecast Visualization

---

# 🤖 Forecasting Models

### Facebook Prophet

Used for forecasting stock prices while capturing:

- Trend
- Seasonality
- Holiday effects
- Future predictions

---

### ARIMA

Applied for statistical forecasting after making the series stationary using differencing.

---

# 📉 Model Evaluation Metrics

The forecasting models were evaluated using:

- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)
- MAPE (Mean Absolute Percentage Error)
- Actual vs Predicted Comparison

---

# 💼 Portfolio Analysis

Based on the forecasting results, a diversified stock portfolio was constructed considering:

- Forecasted returns
- Historical volatility
- Risk diversification

The investment strategy was then tested on the **StockGro Virtual Trading Platform** to compare forecasted performance with actual market outcomes.

---

# 📷 Project Visualizations

### Stock Price Trend

![Stock Price](https://github.com/Diyaachoudhary6/stock-market-time-series-analysis/blob/main/images/1.%20Apple%20Stock%20Price%20Before%20and%20After%202021.png)

---

### Correlation Heatmap

![Heatmap](https://github.com/Diyaachoudhary6/stock-market-time-series-analysis/blob/main/images/2.%20Stock%20Price%20Correlation%20Heatmap.png)

---

### Relative Strength Index (RSI)

![RSI](https://github.com/Diyaachoudhary6/stock-market-time-series-analysis/blob/main/images/3.%20RSI%20Analysis.png)

---

### Stock Forecast

![Forecast](https://github.com/Diyaachoudhary6/stock-market-time-series-analysis/blob/main/images/4.%20INFY%20Forecast.png)

---

### Actual vs Predicted Prices

![Prediction](https://github.com/Diyaachoudhary6/stock-market-time-series-analysis/blob/main/images/5.%20Apple%20Stock%20Price%20-%20Real%20vs.%20Predicted.png)

---

# 📂 Repository Structure

```
time-series-stock-price-forecasting/

│

├── data/
│   ├── HDFC_BANK.csv
│   ├── INFY.csv
│   ├── ITC.csv
│   ├── RELIANCE.csv
│   ├── TATA_MOTORS.csv
│   └── TCS.csv

├── notebooks/
│   ├── Data_Collection.ipynb
    └── Stock_Market_Time_Series_Analysis.ipynb

├── reports/
│   ├── Problem_Statement.pdf
    └── StockGro_Final_Report.pdf

├── images/
│   ├── Stock_Price_before_&_after_2021 .png             -> Shows trend analysis (EDA)
│   ├── Stock_Price_Correlation_Heatmap.png              -> Demonstrates exploratory data analysis
│   ├── RSI Analysis.png                                 -> Shows technical indicator analysis
│   ├── INFY_Forecast.png                                -> Shows your forecasting model output
│   └── Actual_vs_predicted.png                          -> Demonstrates model evaluation

└── README.md
```

---

# 📌 Key Learning Outcomes

- Time Series Forecasting
- Financial Data Analysis
- Stock Market Analytics
- Statistical Modeling
- Feature Engineering
- Data Visualization
- Forecast Evaluation
- Portfolio Optimization

---

# 👨‍💻 Author

**Diyaa Choudhary**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Tableau | Time Series Analysis

---

## ⭐ If you found this project useful, consider giving it a Star!
