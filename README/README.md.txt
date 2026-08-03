# 📈 Time Series Analysis of Stock Prices

## 📌 Project Overview

This project analyzes historical stock price data to identify trends and patterns over time. It includes data cleaning, visualization, moving average analysis, yearly and monthly trend analysis, rolling statistics, and a 30-day stock price forecast using the ARIMA model.

This project was completed as **Task 7 – Time Series Analysis** for the **Synent Technologies Data Science Internship**.

---

## 🎯 Objective

The objective of this project is to analyze historical stock price data and gain meaningful insights through time series analysis. The project also demonstrates forecasting future stock prices using a machine learning time series model.

---

## 📂 Dataset

* **Dataset Name:** Historical Stock Prices
* **File:** `HistoricalQuotes.csv`

### Dataset Features

* Date
* Open Price
* High Price
* Low Price
* Close/Last Price
* Volume

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Statsmodels (ARIMA)

---

## 📋 Project Workflow

### 1. Data Loading

* Imported the HistoricalQuotes dataset using Pandas.

### 2. Data Cleaning

* Removed extra spaces from column names.
* Converted the Date column into datetime format.
* Removed "$" symbols from price columns.
* Converted price columns to numeric values.
* Sorted the dataset by date.

### 3. Exploratory Data Analysis

* Examined dataset structure.
* Checked data types.
* Generated descriptive statistics.
* Identified missing values.

### 4. Time Series Analysis

* Closing Price Trend
* Monthly Average Closing Price
* Yearly Average Closing Price
* Rolling Mean
* Rolling Standard Deviation
* 30-Day Moving Average

### 5. Forecasting

* Built an ARIMA model.
* Forecasted stock prices for the next 30 days.
* Visualized historical and forecasted values.

---

## 📊 Visualizations

The project includes:

* Closing Price Trend
* 30-Day Moving Average
* Monthly Average Price
* Yearly Average Price
* Rolling Statistics
* 30-Day Stock Forecast

---

## 📈 Results

* Successfully cleaned and prepared the historical stock price dataset.
* Identified overall trends using time series visualizations.
* Smoothed short-term fluctuations using a 30-day moving average.
* Analyzed monthly and yearly average stock prices.
* Forecasted future stock prices using the ARIMA model.

---

## 📁 Project Structure

```text
synent-task7-timeseriesanalysis-dhanyasri/
│── HistoricalQuotes.csv
│── time_series_analysis.ipynb
│── README.md
│── images/
│   ├── closing_price.png
│   ├── moving_average.png
│   ├── monthly_average.png
│   ├── yearly_average.png
│   ├── rolling_statistics.png
│   └── stock_forecast.png
```

---



## 📌 Key Insights

* Stock prices fluctuate over time due to market conditions.
* The moving average smooths daily price variations and highlights long-term trends.
* Monthly and yearly analyses reveal broader market behavior.
* The ARIMA model provides short-term forecasts based on historical data.

---

## 🔮 Future Enhancements

* Improve forecasting accuracy using Facebook Prophet or LSTM.
* Add interactive dashboards using Streamlit or Power BI.
* Incorporate additional technical indicators for enhanced analysis.

---

## 👩‍💻 Author

**Dhanyasri Jilloju**

Data Science Intern – Synent Technologies
