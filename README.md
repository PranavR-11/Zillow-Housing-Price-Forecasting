# Zillow Housing Market Forecasting 🏡📈
![image](https://github.com/user-attachments/assets/6353d746-a4f6-4399-b68e-d8b302f80e35)


This notebook performs an in-depth time-series forecasting analysis on Zillow's real estate data.  
The goal is to explore housing price trends and build predictive models to forecast future home values using advanced techniques like **Auto-ARIMA**.

## 🚀 Project Overview

A complete end-to-end pipeline including data preprocessing, exploratory data analysis, time series modeling, and forecasting.

## 🧩 Steps Performed

### 1. Data Loading & Cleaning
- Imported Zillow dataset using pandas.
- Handled missing values to ensure robust modeling.
- Reformatted data for time-series analysis (date parsing, region-wise aggregation).

### 2. Exploratory Data Analysis (EDA)
- Visualized housing price trends over time using line plots.
- Compared average home prices across regions.
- Identified seasonality and trend components in the data.

### 3. Time-Series Preparation
- Aggregated monthly/yearly average home values.
- Performed stationarity checks (ADF test).
- Differenced data where required to achieve stationarity.

### 4. Forecasting Models
- **Auto-ARIMA (Auto-Regressive Integrated Moving Average)**
  - Automated selection of optimal (p,d,q) parameters.
  - Seasonal adjustments and model tuning.
  - Evaluated using **AIC** and **BIC** scores.
  - Generated out-of-sample forecasts for future periods.
  
- **Model Evaluation**
  - Visual inspection: plotted actual vs. predicted values.
  - Computed performance metrics: **Mean Absolute Error (MAE)**, **Root Mean Squared Error (RMSE)**, **Mean Absolute Percentage Error (MAPE)**.
  - Cross-validation for time-series splits.

### 5. Visualization
- Forecast plots showing future housing price trends.
- Region-wise comparative visualizations.
- Residual plots to validate model assumptions.

## 📊 Tech Stack

- Python
- pandas
- matplotlib
- seaborn
- pmdarima / statsmodels (for ARIMA modeling)
- scikit-learn (metrics)

## 📈 Results & Insights

- ARIMA models provided accurate forecasts of future housing prices.
- Identified regions showing upward or downward trends in property values.
- Seasonality effects and trend components were successfully modeled and visualized.
- Generated actionable insights into regional housing market performance.
