# 📈 Stock Price Prediction Web App

This is a web-based application that predicts future stock prices using a deep learning model. It also visualizes historical stock data and moving averages. Built using **Flask**, **Keras**, and **Yahoo Finance API**, the app provides a simple interface for analyzing stock trends and forecasting prices.

---

## 🚀 Features

- 📥 Download real-time stock data from Yahoo Finance
- 📊 Visualizations:
  - Closing price with 20 & 50 days Exponential Moving Averages (EMA)
  - Closing price with 100 & 200 days EMA
  - Predicted vs Actual stock prices
- 🤖 Predict stock prices using a pre-trained LSTM deep learning model
- 💾 Download full historical dataset as a CSV

---

## 🧠 Technologies Used

- **Backend**: Python, Flask
- **Machine Learning**: Keras (LSTM model), Scikit-learn (MinMaxScaler)
- **Data Source**: Yahoo Finance via `yfinance`
- **Visualization**: Matplotlib
- **Frontend**: HTML templates (via Flask `render_template`)

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/AK-RoXX/StockMarketPrediction.git
cd stock-price-predictor

### 2. (Optional) Create a virtual environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

### 3. Install dependencies

```bash
pip install -r requirements.txt

### 4. Ensure the trained model is present
Make sure the file stock_dl_model.h5 is in the root directory. This is the pre-trained LSTM model used for predictions.

### 5. Run the Flask application

```bash
python app.py

### 6. Open your browser
Go to http://127.0.0.1:5000 to access the web interface.

