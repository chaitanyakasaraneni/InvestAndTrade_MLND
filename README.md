# Capstone Project

This repository consists of the proposal, data, code, and report for Udacity's Machine Learning Nanodegree Capstone Project.<br>
**Area: Investment and Trading**<br>
**Project: Build a Stock Price Indicator**<br>

In this capstone project, I leveraged the knowledge gained from Udacity's Machine Learning Nanodegree.
### Table of Contents
1. [ Project description](#intro)
2. [Files](#files)
3. [Data Collection](#data)
4. [Project Design](#design)

## Project description<a name="intro"></a>
A stock price indicator was built using machine learning in this capstone project.

Investment firms, hedge funds and even individuals have been using financial models to better understand market behavior and make profitable investments and trades. A wealth of information is available in the form of historical stock prices and company performance data, suitable for machine learning algorithms to process.

For this project, I built a stock price predictor that takes daily trading data over a certain date range as input, and outputs projected estimates for given query dates. 

## Folders and Files<a name="files"></a>
- **[`data`](https://github.com/chaitanyakasaraneni/InvestAndTrade_MLND/tree/master/data)**: This folder contains the data files used for Investment and Trading Project. All the files are in `.csv` format
- **[`stockAnalysis_and_Predictions.ipynb`](https://github.com/chaitanyakasaraneni/InvestAndTrade_MLND/blob/master/stockAnalysis_and_Predictions.ipynb)**: This file contains code for exploring the data, processing the data, and predicting stock prices
- **[`proposal.pdf`](https://github.com/chaitanyakasaraneni/InvestAndTrade_MLND/blob/master/proposal.pdf)**: This file contains the proposal (approved) for this project
- **[`project_report.pdf`](https://github.com/chaitanyakasaraneni/InvestAndTrade_MLND/blob/master/project_report.pdf)**: This file contains the report for this project

## Data Collection<a name="data"></a>
This project will use open source historical stock price data from **[Yahoo! Finance](https://finance.yahoo.com)** website. Yahoo finance provides a relatively simple process of obtaining basic financial information. Information available includes financial statements and price and volume data. You can directly query for a stock through the web API, or download a dump of .csv files and use them.

If you want to download the data, follow the below steps
 - Search the company for which you want to download the data
 - Select the `Historical Data` tab
 - Click Download to get the data in `.csv` format
 
## Project Design<a name="design"></a>
The project was implemented with Python notebook and the corresponding python machine learning packages. It includes the following different stages.
1.	**Setting Up Infrastructure:** 
Python notebook and corresponding Python packages such as sklearn were imported
2.	**Data preparation and exploration:**
Stock data was imported from csv, and the data was explored by calculating statistics and making plots. The data was also split into training model and testing model.
3.	**Develop supervised learning model:**
Models such as linear regression and KNN were developed to fit the training data. The model parameters was adjusted to avoid overfitting and underfitting.
4.	**Model evaluation:**
The model was tested against testing data. The result was measured against the evaluation metrics and be compared with the benchmark model.
5.	**Discussion and conclusion:**
The result was discussed, and the conclusion was recorded into the project report.

*Coming in future: A fully developed and deployed web application using flask*
