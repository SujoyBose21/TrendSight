# 🧠 TrendSight: Stock Price Prediction Web App using Neural Networks

**TrendSight** is a machine learning-powered web application built with Python that predicts stock prices using a neural network. It provides visual insights into historical stock performance and forecasts future trends to assist users in making data-driven investment decisions.

---

## 🔍 Features

- 📈 **Stock Price Prediction**: Utilizes a trained neural network model to predict future stock prices based on historical data.
- 📊 **Comparison Graphs**:
  - Original stock prices vs 250-day moving average
  - Original stock prices vs 200-day moving average
  - Original stock prices vs 100-day moving average
- 📅 **Historical Data**: Analyzes the last 10 years of stock market data for more accurate trend prediction.
- 📋 **Prediction Table**: Displays a comparison between actual stock prices and predicted prices in a tabular format.
- 🌐 **Web Interface**: Interactive and user-friendly web application to input stock symbols and view visual results instantly.

---

## 🚀 Tech Stack

- **Backend**: Python, TensorFlow/Keras (Neural Networks), Pandas, NumPy
- **Frontend**: Flask
- **Data Source**: Yahoo Finance (via `yfinance` or similar APIs)
- **Visualization**: Matplotlib, Seaborn, Plotly

---

## 📁 Folder Structure (Sample)
```
trendsight/
├── app.py
├── model/
│   └── stock_predictor.h5
├── utils/
│   ├── data_loader.py
│   └── visualization.py
├── templates/
│   └── dashboard.html
├── requirements.txt
```
