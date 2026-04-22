# 📈 AI/ML Based Stock Market Prediction System

## 🚀 Project Overview
This project focuses on building a machine learning system to analyze historical stock market data and predict future price trends. It leverages both traditional machine learning and deep learning techniques to understand market behavior and generate insights.

---

## 📊 Dataset Used
The dataset consists of historical stock price data collected from **Yahoo Finance**, including:

- Open Price  
- High Price  
- Low Price  
- Close Price  
- Volume  

The dataset spans multiple years, enabling analysis of:
- Market trends  
- Seasonality  
- Price patterns  

---

## 🤖 Models Applied
- **Linear Regression** (Baseline Model)  
  Used to understand basic trend behavior and establish a performance benchmark.

- **LSTM (Long Short-Term Memory)**  
  A deep learning model designed for time-series forecasting, used to capture sequential dependencies in stock price movements.

---

## 📉 Results & Findings
- Both models were able to capture overall stock trends.
- **LSTM outperformed Linear Regression** in prediction accuracy.
- Evaluation was done using **RMSE (Root Mean Squared Error)**.
- LSTM showed **lower error values**, indicating better performance.

⚠️ Note: Due to the volatile nature of the stock market, predictions reflect trends rather than exact future prices.

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Matplotlib  
- Jupyter Notebook  

---

## 📁 Project Structure
stock-market-prediction-ml/
│
├── data/ # Dataset (CSV files)
├── notebooks/ # Jupyter notebooks
├── src/ # Source code (optional)
├── README.md

---

## 🚧 Project Status
This project is currently **Work in Progress**.  
Model performance and features are being actively improved.
