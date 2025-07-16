# 📊 TCS Stock Price Forecasting

This project aims to forecast the closing stock prices of Tata Consultancy Services (TCS) using machine learning techniques — specifically focusing on **Linear Regression**, which outperformed other models in this study.

---

## 🧠 Business Problem

Investors, analysts, and financial planners require **accurate and interpretable stock price forecasts** to make strategic decisions. Traditional methods like moving averages or trendlines often fail to capture underlying patterns in historical data. This project presents a **data-driven solution** using machine learning.

---

## ✅ Proposed Solution

- Use machine learning models to forecast the **closing price** of TCS stock.
- Train and compare models including:
  - Linear Regression (Best Performing)
  - Random Forest Regressor
  - Extreme gradient Boosting Algorithm
  - LSTM (Basic)

---

## 📂 Dataset Overview

- **Source:** [Kaggle – TCS Stock Data](https://www.kaggle.com)
- **Date Range:** January 2002 – December 2016
- **Features:**
  - Date, Open, High, Low, Close, Last
  - Total Trade Quantity
  - Turnover (INR Cr)
- **Target Variable:** `Close` Price

---

## 🔧 Preprocessing

- Converted `Date` to datetime format
- Sorted data chronologically
- Created lag features (e.g., previous day’s close)
- Scaled using MinMaxScaler
- Split into training (80%) and test (20%) sets

---


## 🏆 Best Performing Model: Linear Regression

- Achieved the **highest R² score** and lowest RMSE/MAE
- Simple to train, fast to compute, easy to interpret
- Ideal for structured, trend-based stock data like TCS

---

## 📊 Visualizations

- Actual vs Predicted line plots (Train/Test)
- Zoom-in on final 2 years (2015–2016)
- Evaluation metrics plotted

---

## 💡 Business Impact

- Improved prediction of stock movements
- Enhances decision-making for:
  - Traders and investors
  - Financial analysts
  - Treasury and corporate planners

---

## 🚀 Future Improvements

- Integrate news sentiment and macro indicators
- Build ensemble models (stacking)
- Expand forecasting to multiple stocks in the IT sector

---

## 📁 Files Included

- `tcs_stock_forecasting.ipynb` – Main notebook
- `TCS_Stock_Forecasting_Presentation.pptx` – Final presentation
- `README.md` – Project documentation
- `data/` – Preprocessed dataset

---

## 📜 License

This project is for educational and research purposes. Use responsibly. Attribution appreciated if reused.

---

