# Project-5__Prediction-of-house-prices-Kaggle-data

In the Jupyter notebook I predict house prices based on a set of features such as the number of bedrooms. The data is obtained from Kaggle: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

The target variable is "SalePrice" -i.e., the property's sale price in dollars. 

The features are described in the "data_description.txt" file, and the latter file is included in the "data" folder. For the sake of brevity, I do not report the description of the features here, and I refer the reader to the "data_description.txt" file for the description of all the features.

Some of the (regression) tecniques that I use to predict house prices are:

- Lasso regression;

- Ridge regression;

- SVR (Support Vector Regression);

- Random Forest Regression;

- Polynomial Lasso regression. 

Based on Kaggle's Leaderboard (https://www.kaggle.com/c/house-prices-advanced-regression-techniques/leaderboard), my RMSLE is lower than 62% of all submissions. That is, 62% of the submissions in Kaggle are less precise than my preferred model (Polynomial Lasso regression).
