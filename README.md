# 🔬 Regression Analysis On Yes Bank Stock Closing Price Prediction.
![Yes_Bank_Logo-01](https://github.com/user-attachments/assets/b0bad7ef-8949-4840-9748-f37089d3a345)

## Problem Statement
Yes Bank is a prominent financial institution in India. Since 2018, it has been in the spotlight due to a fraud case involving Rana Kapoor. This raised curiosity about its impact on the bank's stock prices and whether Time Series models or other predictive techniques could effectively capture such scenarios. The dataset contains the bank's monthly stock prices from its inception, including the opening, closing, highest, and lowest prices for each month.

## Features
- **Date**:  Date of record.
- **Open**:  Opening price.
- **High**:  Highest price in the month.
- **Low**:   Lowest price in the month.
- **Close**: Closing price.

## 🗺️ Roadmap and Navigation guide
### Step 1: Data Collection
Collect the historical stock prices of Yes Bank from January 2005 to September 2020. Include variables such as opening price, highest price, lowest price, and closing price and date

### Step 2: Data Cleaning and Preprocessing
Clean the dataset by removing any missing values, outliers, or errors. Preprocess the dataset by scaling or normalizing the features as necessary.

### Step 3: Regression Model Building
Divide the dataset into training and testing sets. Implement Multiple Linear Regression ,Lasso Regression, Ridge Regression, Elastic net Regression, knn regressor and Random forest regressor models to predict the closing price of Yes Bank stock. Tune the models by adjusting the hyperparameters to optimize performance.

### Step 4: Model Evaluation
Evaluate the models' performance using root mean squared error (RMSE) and mean absolute error (MAE) metrics. Compare the performance of the models to determine which one performs better.

### Step 5: Results and Conclusion
Present the results of the regression analysis. Discuss the implications of the results and their potential impact on investors. Provide conclusions and suggestions for future research.

## Conclusion
- We got a maximum accuracy of 99%.
- Linear, lasso and ridge regression show almost same R squared values.
- Whereas elastic net model shows lowest R squared value and high MSE, RMSE, MAE & MAPE.
- Close, Open and high price of stock are strongly correlated with each other.
- Regression models namely random forest regressor, xgboost regressor are build
