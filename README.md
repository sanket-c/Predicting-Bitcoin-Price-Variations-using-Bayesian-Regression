# Predicting-Bitcoin-Price-Variations-using-Bayesian-Regression
Predict the price variations of bitcoin


# Technologies
• Python

# Packages
• numpy

• pandas

• sklearn

• statsmodels

# Dataset
• http://api.bitcoincharts.com/v1/csv/

# Data Preprocessing
To make the data to have evenly space records, we took all the records within a 20 second window and replaced it by a single record as the average of all the transaction prices in that window. Not every 20 second window had a record; therefore those missing entries were filled using the prices of the previous 20 observations and assuming a Gaussian distribution.
