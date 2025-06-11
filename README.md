# 📊 Stock Market Movement Prediction Using Reddit Sentiment & LSTM

This project forecasts next-day stock closing prices using a hybrid approach of technical indicators and Reddit-based sentiment scores. It leverages an LSTM model built in PyTorch to capture sequential patterns in financial time series.

## 📌 Key Features

- Combines technical analysis with Reddit sentiment data
- Scalable data preprocessing and feature engineering
- LSTM-based deep learning model with optimized training loop
- Evaluation on top Indian stocks like RELIANCE.NS, INFY.NS, and more

## 🔍 Inputs Used

- Technical Indicators: SMA, EMA, RSI, MACD, Bollinger Bands, OBV, etc.
- Reddit Sentiment: Counts of positive, negative, total mentions, and sentiment ratio
- Dataset: `merged_stock_sentiment_data.csv`

## 📈 Model Overview

- Model: 2-layer LSTM + Fully Connected Layer
- Loss Function: Huber Loss
- Optimizer: Adagrad
- Scheduler: ReduceLROnPlateau
- Framework: PyTorch

## 📊 Sample Predictions

```
RELIANCE.NS: ₹1359.50 (R²: 0.9812)
INFY.NS: ₹1466.85 (R²: 0.9840)
HDFCBANK.NS: ₹1902.69 (R²: 0.9697)
Overall Model R²: 0.9500 | RMSE: 1627.85
```

## 🛠️ Getting Started

Clone the repo and install dependencies:
```bash
git clone https://github.com/yourusername/stock-prediction-reddit-lstm.git
cd stock-prediction-reddit-lstm
pip install -r requirements.txt
```

Run the project:
- Open `code.ipynb` in Jupyter or VS Code
- Ensure `merged_stock_sentiment_data.csv` is in the same directory
- Run all cells to preprocess data, train the model, and view predictions

## 📁 Files Included

- `code.ipynb` – Complete training and inference pipeline
- `requirements.txt` – Python dependencies
- `README.md` – Project description

## 📄 License

MIT License – Free to use with attribution.

```
