# 📈 Time Series Forecasting Project
This project involves time series forecasting using ARIMA and Holt-Winters methods on EUR/CHF exchange rate data. The goal is to analyze and predict future values based on historical data to understand trends and make more informed predictions.

## 📁 Files in the Project
### 1. 📝 ARIMA+HOLT-WINTER.ipynb
- **Description**: A Jupyter Notebook containing Python code for time series analysis and forecasting using ARIMA and Holt-Winters methods.
- **Purpose**: The notebook guides users through loading the data, conducting exploratory data analysis, fitting ARIMA and Holt-Winters models, and evaluating forecast accuracy.
- **Contents**: This notebook typically includes steps like:
  - Loading and visualizing the EUR/CHF exchange rate data.
  - Performing stationarity tests (e.g., Augmented Dickey-Fuller test).
  - Implementing and tuning ARIMA and Holt-Winters models.
  - Evaluating model performance with metrics like MAE, MSE, and RMSE.
  - Forecasting future values and plotting the predictions.

### 2. 📄 EURCHF.csv
- **Description**: A CSV file containing historical EUR/CHF exchange rate data.
- **Purpose**: Serves as the primary dataset for time series analysis and forecasting in the notebook.
- **Contents**: This dataset may include columns such as:
  - `Date`: The date of each recorded exchange rate.
  - `EURCHF`: The exchange rate value between the Euro (EUR) and the Swiss Franc (CHF) on the given date.

## 📊 Project Overview
1. **Data Loading and Exploration**: Load the EUR/CHF exchange rate data, visualize trends, and examine any seasonal or cyclic patterns.
2. **Stationarity Testing**: Conduct tests to determine if the time series is stationary, which is necessary for certain forecasting models.
3. **Modeling**:
   - **ARIMA**: Build and tune an ARIMA model, suitable for non-seasonal data, or add seasonal adjustments as needed.
   - **Holt-Winters**: Apply the Holt-Winters method to model data with potential seasonality.
4. **Evaluation and Forecasting**: Evaluate model accuracy and generate forecasts to predict future exchange rate values.
