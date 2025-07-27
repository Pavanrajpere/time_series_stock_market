# 📈 Stock Price Forecasting (AAPL)

This project forecasts Apple Inc. (AAPL) stock prices using multiple time series and deep learning models: **ARIMA**, **SARIMA**, **Prophet**, and **LSTM**.
also we can do with other stocks as msft and other by just changing dataset in code it is easy.

---

## 🔍 Objective

Compare different forecasting techniques using:
- **Statistical models:** ARIMA, SARIMA
- **Machine learning models:** Prophet, LSTM
- Visualize forecast and evaluate model performance using RMSE and MAE.

---

## 📊 Results Summary

| Model   | RMSE   | MAE   |
|---------|--------|--------|
| ARIMA   | 69.62  | 63.64  |
| SARIMA  | 55.16  | 50.54  |
| Prophet | 38.77  | 31.86  |
| LSTM    | 10.99  | 9.01   |

✅ **LSTM outperformed all other models**

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/stock-forecasting.git
cd stock-forecasting
pip install -r requirements.txt
