# 📈 Sales Forecasting Using Time Series Analysis (ARIMA & SARIMA)

This project focuses on forecasting future sales using **Time Series Analysis techniques**, specifically **ARIMA** and **SARIMA** models. The aim is to provide data-driven insights for business planning and inventory management.

---

## 🚀 Project Highlights

- ✅ Time Series Analysis on real-world sales data
- ✅ Implemented **ARIMA** (AutoRegressive Integrated Moving Average)
- ✅ Enhanced model with **SARIMA** (Seasonal ARIMA) to capture seasonality
- 📊 Visualized trends, seasonality, and model performance

---

## 📂 Dataset

- **Type:** Time-series sales data
- **Format:** Monthly/weekly/daily sales data (e.g., `.csv` format with Date and Sales columns)
- **Preprocessing:** Handled missing values, resampling, and stationarity transformation

---

## 📈 Techniques Used

### 🔹 ARIMA (AutoRegressive Integrated Moving Average)
- Used for non-seasonal sales patterns
- Model optimized using AIC/BIC selection

### 🔹 SARIMA (Seasonal ARIMA)
- Extended ARIMA with seasonal parameters
- Useful for capturing repeating patterns (e.g., monthly sales peaks)

---

## 📊 Visualizations Included

- Line plots of actual sales over time
- ACF and PACF plots for parameter tuning
- Decomposition of trend, seasonality, and residuals
- Forecast vs Actual comparison charts

---

## 🧠 Model Evaluation

- **Metrics used:**
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
- **Validation:** Compared actual vs predicted values using test split

---

## 🧰 Tools & Libraries

- `Python`
- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `statsmodels` – ARIMA and SARIMA implementation
- `pmdarima` – for auto ARIMA tuning (if used)

