# ✈️ Air Passengers Time Series Forecasting

A time series forecasting project to predict monthly air passenger traffic using SARIMA modeling. The project analyzes historical trends and seasonality, forecasts future capacity, and validates model performance using statistical tests.

---

## 🧰 Technologies Used

- Python
- Statsmodels
- Pandas, NumPy, Matplotlib, Seaborn
- SARIMA (Seasonal ARIMA)
- Time Series Analysis

---

## 📌 Features

- **SARIMA Modeling**  
  Built and tuned a seasonal SARIMA model `(2,1,1)(1,0,3,12)` for forecasting passenger traffic based on monthly time series data.

- **Capacity Forecasting**  
  Forecasted air passenger traffic 24 months into the future with 95% confidence intervals.

- **Trend and Seasonality Detection**  
  Identified strong 12-month seasonal patterns and long-term upward trends through exploratory data analysis (EDA).

- **Model Validation**  
  Used Augmented Dickey-Fuller (ADF) test for stationarity and residual analysis to evaluate model assumptions and performance.

---

## 📈 Results

- Accurate 2-year forecast of passenger volumes
- Visualization of historical vs. predicted trends
- Residual plots confirming model adequacy
