# AI-ML-internship-tasks02
**Task Objective**

The objective of this task is to predict the next day’s stock closing price using historical stock market data. Machine learning techniques are used to analyze patterns in stock behavior and make future predictions.

**📊 Dataset Used**
Dataset Source: Yahoo Finance (via yfinance library)
Stock Selected: Apple Inc. (AAPL)
Time Period: 2020 – 2025
Features Used:
Open Price
High Price
Low Price
Volume
Target Variable:
Next Day Close Price


**🤖 Models Applied**
Random Forest Regressor
n_estimators = 100
random_state = 42
Data split method:
Train-Test Split (80% training, 20% testing)
No shuffling (time-series data preserved)

**📈 Methodology**

Data fetched using yfinance
Feature selection from OHLC + Volume
Target created using shift(-1) (next day prediction)
Model trained using Random Forest
Predictions generated for test dataset
Results visualized using line plot
**📊 Key Results & Findings**
Model successfully learned patterns from historical stock data
Predicted values closely follow actual closing price trends
