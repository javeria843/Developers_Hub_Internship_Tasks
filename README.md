📈 AAPL Stock Price Prediction using Linear Regression
🧠 Objective
Build a simple machine learning model to predict the next day's closing price of Apple Inc. (AAPL) stock using historical trading data.

📊 Dataset Used
Source: yfinance API

Period: January 1, 2020 – December 31, 2024

Features: Open, High, Low, Volume

Target: Next day’s Close price (shifted by -1)

🛠️ Model Applied
Linear Regression (scikit-learn)

Training set: 80% of the data

Testing set: 20% of the data

📌 Key Results & Findings
The model successfully learns a linear relationship between daily price movements and volume trends.

Predicted vs actual closing prices are visualized using Matplotlib for evaluation.

Last day prediction (based on final feature row): Predicted next day's closing price: $XXX.XX
