# Hk-yes-bank-stock-closing-price-prediction
# Overview
Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations..

# Objective
This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

# Dataset Summary
We have Yes Bank monthly stock price dataset. It has following features (Columns):
1) Open : Opening price of the stock of particular day
2) High : It's the highest price at which a stock traded during a period
3) Low : It’s the lowest price at which stock traded during a period
4) Close : Closing price of a stock at the end of a Trading Day
5) Date : We will use it as a index

# Final Result

![image](https://user-images.githubusercontent.com/90507696/155869701-662ea116-2345-40ea-a38f-03663fb7f8d6.png)

In this combined comparison graph among actual closing price and Predicted closing price predicted by all four models, Linear Regression and Lasso are predicting closing price of next month better than Ridge and ElasticNet. All four models have good R2 and Adjusted R2.
