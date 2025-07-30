# Air-Passengers-Time-Series-Forecasting-Project
This project aims to perform time series analysis and forecasting on historical airline passenger data using classical statistical models. The dataset represents the number of international airline passengers per month from 1949 to 1960. The primary goal is to analyze the data for underlying trends and seasonality and apply forecasting.
## 🗂️ Dataset

- **Name**: AirPassengers Dataset
- **Source**: Available in many time series datasets (originally from Box & Jenkins, 1976)
- **Features**:  
  - `Month`: Monthly timestamps from Jan 1949 to Dec 1960  
  - `Passengers`: Number of international airline passengers per month

---

## 🎯 Objective

- Analyze trends and seasonality in historical airline passenger data
- Make short-term forecasts using ARIMA and SARIMA models
- Compare model predictions with actual values
- Evaluate forecast accuracy using error metrics (MSE, RMSE)

---

## 🧪 Methodology

1. **Load and preprocess** the time series data
2. **Visualize** the series to identify trend and seasonality
3. **Test for stationarity** using ADF test
4. **Decompose** the series into trend, seasonal, and residual components
5. **Train ARIMA and SARIMA models** on historical data
6. **Forecast** passenger counts for the next 12 months
7. **Evaluate** forecasts using MSE and RMSE
8. **Plot** actual vs. forecasted values

---

## 🔧 Libraries Used

- `pandas`, `numpy` – Data handling
- `matplotlib`, `seaborn` – Visualization
- `statsmodels` – ARIMA/SARIMA modeling
- `sklearn` – Forecast evaluation

---

## Author

Mayank Bharti
