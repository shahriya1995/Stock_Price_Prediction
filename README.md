# Stock Price Prediction Using Regression models

### Problem Statement : Use the daily [Open, High, Low, Volume] to predict [Close] on that day using Regression models.

------------
### Models Used : Linear Regression, Lasso Regression , Ridge Regression

-------------
### Dataset Description :

Yahoo Finance Apple Dataset

	https://finance.yahoo.com/quote/AAPL/history?p=AAPL

Dataset collected of past 5 years to predict results.

--------------

### Requirements:
Yahoo! Finance market data downloader +fix for Pandas Datareader's get_data_yahoo()

	!pip install yfinance --upgrade --no-cache-dir


### Given the input dataset, the following steps are performed:

	Split the input data into their respective training and test sets.
	Fit linear regression to the training data.
	Apply the model to the test data.
	Evaluate the performance of the model.
	Postprocessing: Visualizing the fitted model.
