# Capstone-Project-2-Yes-Bank-Stocks-Closing-Price-Predication
Capstone Project 2 Yes Bank Stocks Closing Price Predication

Yes Bank Stock Closing Price Prediction is a project about "YES Bank" Share price Fluctuation , This stock was listed in indian share market during the 2005 and it is in the news after ED suspected and Fraud in the Yes Bank and according to ED MD and CEO of YES Bank was invovlevd in the fraud , This stock is in the news from the starting of 2017 , and SEBI and ED bothe the regulatory agensies are invoved in the Investigation. We have a CSV file of some prices of YES Bank Stock , in the CSV we have monthely high , monthly open , monthly close for the YES Bank Stock, and by using different models and libreries we are going to predict the closing price of the stock on the monthely basis.

For the analysis first we will upload the data in the colab and we will do some data cleaning , We will add some important column and we will remove some unwanted column , we will rename some columns after that we will do data wrangling , After that we will excute some programes for getting our specific result. Here we are going to use feature engineering which will use the raw data and use it in Predctive Modeling.

**Problem Statement**

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock's closing price of the month.

**Data Set Explanation**

You can see the data set has zero null values and zero duplicate values, the data set is having 185 rows and the 5 columns, we will try to find the prediction of the closing price by using the above data set and will check the prediction is accurate or not. So in the data set closing price will work as the dependent variable and other four columns will work as independent variable.

**Variables Description**


Date - In Given data set month and years is mentioned in date column

High -Highest price of the stock for the given month

Low -Lowest price of the stock for the given the month

Close -Price of the stock at the end of the month
