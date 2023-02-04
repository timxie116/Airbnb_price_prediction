# Airbnb price prediction


# Description
This project was completed by Tian Xie in APANPS5200: Applied Analytics Frameworks and Methods I. This project is a listing of over 41,739 Airbnb rentals in New York City. The goal of this project is to predict the price for a rental using 97 variables on the property, host, and past reviews.

# Goal
The goal is to predict price of an Airbnb rental given its characteristics. Generate a prediction for each id in scoringData.csv.

# Metric
Evaluated based on RMSE (root mean squared error) score. Lower the RMSE score, better the model.

# Steps
1. Install library packages
2. Read a dataset of 41,739 observations and 97 variables
3. Data Wrangling. Improved data quality by changing data structure and transforming variables, including missing data imputation, factor’s levels redefinition, training and testing dataset separation
4. Select significant variables using Exploratory Data Analysis (EDA), feature selection including lasso and Principal Components Regression (PCA)
5.Trained supervised machine learning models, including Linear Regression, Logistic Regression, Random Forest, Ranger, tuneRanger, and XGBoost; XGBoost had the lowest RMSE of 65

