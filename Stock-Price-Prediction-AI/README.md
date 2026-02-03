# 📈 Stock Price Prediction using Machine Learning

## 🔹 Task Objective
I aimed to predict the next day's closing stock price using historical stock market data. I applied machine learning regression models to analyze stock price patterns and generate short-term predictions.

---

## 🔹 Dataset Used
I retrieved stock data from Yahoo Finance using the yfinance Python library. The dataset contains:

- Open Price
- High Price
- Low Price
- Closing Price
- Volume

Stock Selected: Tesla (TSLA)

---

## 🔹 Models Applied
I applied two regression models:

1. Linear Regression  
2. Random Forest Regression  

---

## 🔹 Methodology
1. I collected stock data using yfinance API.
2. I created the target variable by shifting the closing price by one day.
3. I split the data into training and testing sets.
4. I trained models using Open, High, Low, and Volume as features.
5. I evaluated model performance using MAE, RMSE, and R2 Score.
6. I visualized predictions compared to actual prices.

---

## 🔹 Key Results
- Random Forest provided better prediction accuracy than Linear Regression.
- The models successfully captured short-term trends in stock prices.
- Ensemble methods are more effective for complex financial datasets.

---

## 🔹 Technologies Used
- Python
- Scikit-learn
- Pandas
- Matplotlib
- yfinance API

---

## 🔹 Conclusion
I demonstrated how machine learning can be used for short-term stock price prediction. While the predictions are useful, stock markets remain volatile and uncertain.

---

## 🔹 Author
AI/ML Internship Task Submission
