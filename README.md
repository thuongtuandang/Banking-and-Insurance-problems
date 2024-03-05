# Banking-and-Insurance-problems

Here are my projects on insurance and banking problems.

# Car insurance

The data consists of 10k records and 19 features. It is available at: 

https://www.kaggle.com/datasets/sagnik1511/car-insurance-data

There are missing values in the data, and I used LGBM for imputation. The best accuracy score is 85% with LGBM.

# Credit score classification

The data consists of 100k rows and 28 features. It is available at:

https://www.kaggle.com/datasets/parisrohan/credit-score-classification

The data requires heavy cleaning job due to the following issues:

- Incorrect formats and inputs that necessitate the use of regular expressions for handling.
- Unusually high or low values, which may stem from initial testing when the database was first designed.
- A significant number of missing values.

The best accuracy score with LGBM is 77%

# Insurance charges

The data consists of more than 1.3k records and 7 features. It is available at:

https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset

I used linear regression and LGBM to predict the insurance charges, and the best R^2 score with LGBM is 0.85.