# Task 02: Stock Price Prediction Using Machine Learning

## Problem Statement

Stock price prediction is an important application of machine learning in finance. The goal of this task is to predict the next day's closing stock price using historical stock market data. A regression model is trained using features such as Open, High, Low, and Volume to estimate future closing prices.

---

## Objective

To develop a machine learning model capable of predicting the next day's closing stock price based on historical stock market information.

---

## Dataset

Source: Yahoo Finance

Stock Selected: Apple Inc. (AAPL)

Data Retrieved Using: yfinance Python Library

Date Range: January 2020 – January 2025

Features Used:

* Open Price
* High Price
* Low Price
* Trading Volume

Target Variable:

* Next Day Closing Price

---

## Project Workflow

### 1. Data Collection

Historical stock market data was downloaded directly from Yahoo Finance using the yfinance library.

### 2. Data Preprocessing

The following preprocessing steps were performed:

* Checked dataset dimensions
* Examined data types
* Generated statistical summaries
* Identified missing values
* Removed missing records
* Created the target variable by shifting the closing price one day forward

### 3. Exploratory Data Analysis

Visualizations were created to understand stock price behavior:

* Historical Closing Price Trend
* Actual vs Predicted Closing Price Comparison

### 4. Model Development

Model Used:

* Linear Regression

Training/Test Split:

* 80% Training Data
* 20% Testing Data

Input Features:

* Open
* High
* Low
* Volume

Target:

* Next Day Close Price

### 5. Model Evaluation

The following evaluation metrics were used:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

---

## Results

The model successfully learned the relationship between stock market indicators and future closing prices.

The Actual vs Predicted graph demonstrates that the model predictions closely follow the actual stock prices, indicating effective learning of market trends.

Evaluation metrics showed that the model achieved strong predictive performance on unseen test data.

---

## Key Findings

* Historical stock data can be used to predict future closing prices.
* Open, High, Low, and Volume significantly influence stock behavior.
* Linear Regression provides a simple yet effective baseline model for stock prediction.
* Financial datasets require careful preprocessing and feature engineering.
* Machine learning can assist investors in understanding market trends.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* yfinance

---

## Files Included

* Stock_Price_Prediction.ipynb
* AAPL_stock_data.csv
* README.md

---

## Author

Saira Ejaz


