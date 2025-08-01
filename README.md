

# 📈 Price Prediction App

This is a Streamlit web application built for the Price Prediction Challenge. It uses machine learning (XGBoost) to predict next-day returns of LME commodities based on global market indicators.

## 🚀 Features

* Upload your own data or generate synthetic CSVs for:

  *  Prices
  * JPX Market Data
  * Forex Rates
  * US Stock Index
* Computes advanced financial features like:

  * Log Returns, Volatility, SMA Gap, Momentum, MACD
* Trains an XGBoost regression model
* Displays:

  * 📊 Spearman Correlation
  * 📈 Sharpe Ratio Variant
  * 📉 Prediction vs. Actual Graph
* 330-character model summary included

## 📦 Model Summary

> This model uses XGBoost to predict next-day returns of prices based on market data from JPX, Forex, and US stocks. It includes features like returns, volatility, SMA, momentum, and MACD. XGBoost captures complex patterns for accurate forecasting.

## 🧪 How to Run

1. Install required packages:

```bash
pip install -r requirements.txt
```

2. Run the Streamlit app:

```bash
streamlit run app.py
```

3. Upload your CSVs in the sidebar or generate mock data.

## 📁 Project Structure

```
commodity_prediction_package/
│
├── app.py                # Main Streamlit app
├── requirements.txt      # Python dependencies
├── model/
│   └── xgboost_model.pkl # Saved trained model (optional)
├── data/                 # Sample or user-uploaded CSVs
├── README.md             # This file
```

## 💡 Technologies Used

* Python 3
* Streamlit
* XGBoost
* Pandas / NumPy / Seaborn / Matplotlib
* SciPy (Spearman correlation)

## 📌 Challenge Goal

Develop a resilient and accurate model that can generalize across market regimes to forecast prices.

---

Would you like me to add this directly into your code workspace as `README.md`?
