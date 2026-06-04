# 📈 Predict Future Stock Prices (Short-Term)

## Objective

This project aims to predict the next day's stock closing price using historical stock market data from Yahoo Finance. Machine learning techniques are used to analyze trading patterns and estimate future stock prices.

---

## Dataset

**Source:** Yahoo Finance API (`yfinance`)

**Stock Selected:** Apple Inc. (AAPL)

### Features Used

* Open Price
* High Price
* Low Price
* Volume

### Target Variable

* Next Day Closing Price (`Next_Close`)

### Data Period

* January 2020 – January 2025

---

## Data Preprocessing

The following steps were performed:

* Downloaded historical stock data using Yahoo Finance.
* Explored the dataset using descriptive statistics and data inspection methods.
* Visualized stock price trends and trading volume.
* Created a target variable (`Next_Close`) by shifting the closing price one day ahead.
* Removed missing values generated during target creation.
* Selected relevant features for model training.

---

## Model Applied

### Linear Regression

The model was trained using:

**Input Features**

* Open
* High
* Low
* Volume

**Target**

* Next Day Closing Price

The dataset was split into training and testing sets using an 80/20 ratio while preserving the chronological order of the data.

---

## Evaluation Metrics

| Metric   | Value |
| -------- | ----- |
| MAE      | 50.97 |
| RMSE     | 57.30 |
| R² Score | -4.05 |

---

## Visualizations

The project includes:

* Stock Closing Price Trend
* Trading Volume Trend
* Actual vs Predicted Closing Prices

---

## Key Results and Findings

The Linear Regression model was trained using Open, High, Low, and Volume features to predict the next day's closing stock price.

The evaluation results indicate that the model was not able to accurately predict future stock prices. The negative R² score suggests that the model performed worse than a simple baseline prediction using the average stock price.

This demonstrates the complexity of stock market forecasting, as stock prices are influenced by many external factors including:

* Market sentiment
* Economic conditions
* Company announcements
* Global events
* Investor behavior

These factors were not included in the model.

### Future Improvements

Potential improvements include:

* Adding technical indicators (RSI, MACD, Moving Averages)
* Feature engineering
* Random Forest Regression
* XGBoost
* LSTM Neural Networks
* Financial news and sentiment analysis

---

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* yfinance

---

## Skills Demonstrated

* Time Series Data Handling
* Data Collection using APIs
* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Regression Modeling
* Model Evaluation
* Machine Learning Workflow

---

## Author

**Mohammad Shafay**

AI/ML Internship Task 2 – Predict Future Stock Prices (Short-Term)
