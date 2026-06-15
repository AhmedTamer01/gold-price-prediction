# Gold Price Prediction (Time Series Analysis) 📈💰

A predictive machine learning project utilizing Time Series forecasting techniques to predict future Gold Prices based on historical market data.

## 🚀 Project Overview

Financial markets are highly volatile, and predicting commodity prices like gold requires understanding long-term trends and seasonality. This project leverages historical time-series data of gold prices to build forecasting models that can predict future price movements. 

The analysis involves extensive Exploratory Data Analysis (EDA) to detect trends, stationarity checks (like the Augmented Dickey-Fuller test), and the application of both statistical (ARIMA/SARIMA) and deep learning (LSTM) models for forecasting.

## ⚙️ Methodology & Architecture

1. **Data Preprocessing**: Handled missing values, converted date columns into proper DateTime indices, and normalized the price data for neural network stability.
2. **Exploratory Data Analysis (EDA)**: Visualized rolling means, standard deviations, and seasonal decompositions to understand the underlying patterns.
3. **Modeling**:
   - Built a baseline using traditional time-series forecasting.
   - Designed a Recurrent Neural Network (RNN) using **Long Short-Term Memory (LSTM)** layers to capture long-term dependencies in the sequential data.
4. **Evaluation**: Evaluated the model using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

## 🛠️ Tech Stack & Libraries Used

- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn, Plotly
- **Time Series Utilities:** Statsmodels
- **Deep Learning Framework:** TensorFlow/Keras (for LSTM implementation)

## 📈 Key Results

- Successfully captured the macro trend of gold prices over the dataset period.
- The LSTM model significantly outperformed traditional moving average baselines by learning non-linear temporal patterns.

---
*This repository is part of my AI Engineer / Data Scientist Portfolio.*
