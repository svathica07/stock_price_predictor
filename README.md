# stock_price_predictor
Machine learning project that predicts stock closing prices using historical data, feature engineering, and Linear Regression.
# Stock Price Predictor

## Project Overview

This project uses Machine Learning to predict stock closing prices based on historical stock market data.

It is an AI internship project completed as part of the Codec Technologies AI Internship.

## Objectives

* Analyze historical stock price data.
* Visualize stock closing price trends.
* Use previous closing prices to predict the next day's price.
* Evaluate prediction performance using regression metrics.

## Technologies Used

* Python
* yfinance
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook / Google Colab

## Dataset

Historical stock market data is downloaded using the `yfinance` library.

The default stock symbol is `AAPL` (Apple Inc.), and the notebook uses data from 2018 to 2024.

You can change the ticker symbol to other supported stocks, such as `TCS.NS` or `INFY.NS`.

## Methodology

1. Download historical stock price data.
2. Visualize closing price trends.
3. Scale the data using MinMaxScaler.
4. Use the previous 5 days' closing prices as input features.
5. Split the data chronologically into training and testing sets.
6. Train a Linear Regression model.
7. Evaluate predictions using MAE, RMSE, and R².
8. Predict the next day's closing price.

## Machine Learning Model

**Linear Regression** is used to predict stock closing prices based on the previous five days of closing price data.

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries.
3. Run the notebook cells in order.
4. Change the ticker symbol if needed.
5. View the predicted closing price and evaluation results.

## Output

* Historical stock price graph.
* Actual vs. predicted closing price graph.
* Regression evaluation metrics.
* Predicted next-day closing price.

## Future Improvements

* Include additional market indicators and features.
* Experiment with other forecasting models.
* Develop an interactive stock prediction dashboard.

## Internship

Codec Technologies – AI Internship

## Disclaimer

This project is for educational purposes only. Stock price predictions are uncertain and should not be used as financial advice.
