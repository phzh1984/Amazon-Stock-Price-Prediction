# Amazon-Stock-Price-Prediction


This GitHub repository contains a time series forecasting project that focuses on Amazon Stock, employing various forecasting techniques, including Linear Regression, Long Short-Term Memory (LSTM), and Prophet models. The project aims to provide a simplified workflow for building forecasting models, demonstrating the process and steps involved in creating predictive models for stock prices.

Business Case

In this project, we analyze historical data related to Amazon Stock. The primary goal is not to create the most powerful forecasting model but to establish a structured workflow for forecasting. The dataset includes several important features:

Date: The time feature for the data, which is crucial for feature engineering.

Open: The stock's opening price at 9:00 am ET.

High: The highest stock price during the trading day.

Low: The lowest stock price during the trading day.

Close: The closing price of the stock at 5:00 pm ET.

Volume: The number of shares traded during the day.

Dataset


This dataset is designed for both fundamental and technical analysis of Amazon Stock. With the significant role of machine-generated trading in today's financial markets, this dataset offers an opportunity to explore the feasibility of fully automated trading systems and to learn valuable insights from historical stock price data.

Contents

This repository includes the following files:

prices.csv: This file contains raw daily stock prices. Most of the data spans from 2010 to the end of 2016. Please note that it does not account for approximately 140 stock splits that occurred during this time.

prices-split-adjusted.csv: Similar to "prices.csv," this file includes adjusted prices to account for stock splits.

securities.csv: This file provides general descriptions of each company, categorized by sectors.

fundamentals.csv: This file includes metrics extracted from annual SEC 10K filings for the years 2012 to 2016. These metrics are sufficient for deriving popular fundamental indicators.

Project Objectives

The primary objectives of this project are as follows:

Exploratory Data Analysis (EDA): Conduct a comprehensive exploratory analysis of the dataset to gain insights into Amazon Stock's historical performance.

Feature Engineering: Create relevant features that can improve forecasting model accuracy.

Forecasting Models: Implement three distinct forecasting models - Linear Regression, LSTM, and Prophet - to predict future stock prices.

Workflow Documentation: Clearly outline the steps and procedures involved in building forecasting models for future reference.
