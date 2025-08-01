TASK1:
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



TASK 2:

🌸 Iris Dataset Analysis & Visualization
🎯 Objective
Explore and visualize the famous Iris dataset to understand feature distributions and relationships between species.

📁 Dataset Used
Source: seaborn.load_dataset('iris')

Features: sepal_length, sepal_width, petal_length, petal_width

Target: species (Setosa, Versicolor, Virginica)

Shape: 150 rows × 5 columns

🧪 Exploratory Data Analysis (EDA)
Dataset overview: .shape, .columns, .head(), .info(), .describe()

Visualization techniques:

Pairplot (sns.pairplot) showing feature relationships by species

Histogram of each feature with bin and edge styling

Boxplot for all features grouped by species to highlight median, spread, and outliers

📌 Insights
Petal features are more distinguishing between species than sepal features.

Pairplots reveal clear cluster separation among species.

Boxplots show species-specific ranges and variance across feature dimensions.

📌 Key Results & Findings
The model successfully learns a linear relationship between daily price movements and volume trends.

Predicted vs actual closing prices are visualized using Matplotlib for evaluation.


TASK 3:


🏠 Housing Price Prediction: Regression Model Comparison
🎯 Objective
Predict house prices using multiple regression models and compare their performance for accuracy and reliability.

📁 Dataset Used
Source: Uploaded CSV (Housing.csv)

Features: Area, bedrooms, bathrooms, furnishing status, road access, etc.

Target Variable: price

🧼 Data Preprocessing
Binary categorical features (yes/no) encoded to 0/1

furnishingstatus handled via one-hot encoding (semi, unfurnished)

Numerical features scaled with StandardScaler for model fairness

🤖 Models Applied
Model	Technique
Linear Regression	Baseline model
Gradient Boosting Regressor	Ensemble method with 100 trees
📊 Evaluation Metrics
Model	MAE (Mean Absolute Error)	RMSE (Root Mean Squared Error)
Linear Regression	MAE_X, RMSE_X
Gradient Boosting	MAE_Y, RMSE_Y
Replace MAE_X, RMSE_X, etc. with your actual printed scores.

📉 Visualization
Scatter plot comparing predicted vs. actual prices for both models

Diagonal line (k--) added to highlight ideal prediction

📌 Key Findings
Gradient Boosting provides improved accuracy over simple linear regression.

Encoding and scaling significantly enhance model performance and generalization.




Last day prediction (based on final feature row): Predicted next day's closing price: $XXX.XX
