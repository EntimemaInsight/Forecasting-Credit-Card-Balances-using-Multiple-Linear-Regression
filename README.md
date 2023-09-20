# Forecasting-Credit-Card-Balances-using-Multiple-Linear-Regression
This project aims to analyze a dataset containing information from 29,819 credit card holders and develop a predictive model to estimate a cardholder's credit card balance based on their characteristics. The analysis provides insights into the factors influencing credit card balances and their significance for credit card companies.

## Project Objective
The objective of this project is to:
1. Understand the various factors influencing a credit card holder's balance.
2. Develop a predictive model to estimate credit card balances based on individual characteristics.
3. Provide valuable insights for credit card companies to identify customers at risk of credit default and optimize customer acquisition strategies.

Methodology
The project follows these steps:

1. Data Cleaning and Transformation:

- Remove unnecessary columns and handle outliers.
- Convert categorical data into appropriate data types.

2. Exploratory Data Analysis:

- Analyze the distribution of credit card balances.
- Calculate correlations between variables.

3. Regression Analysis:

- Build an ordinary least squares (OLS) regression model.
- Identify the relationship between predictor variables and the credit card balance.
- Evaluate the statistical significance of the model.

4. Making Predictions:

- Use the regression model coefficients to predict credit card balances for new data.

## Dataset Description

The dataset consists of the following variables:

- CID: Client Identification Number
- Limit: Credit limit
- Age: Age in years
- Gender: Male or Female
- Married: Yes or No
- Education: Education level
- Income: Income in EUR
- Balance: Credit card balance in EUR
- Results

## Prediction Results:

Using the developed regression model, we made predictions for new data based on the coefficients obtained. The df_new DataFrame contains predictor variables (Income, Age, Gender, and Married) for which the credit card balance is predicted. The predictions were added as a new column named "Balance" in the df_new DataFrame. 
These predicted credit card balances are based on the provided predictor variables (Income, Age, Gender, and Married). Please note that these predictions are specific to the model and dataset used in this project. Actual results may vary based on different datasets and models.

## Credits
This project was created by Aleksandar Dimitrov and is licensed under the MIT License. If you have any questions or comments, feel free to contact me at alexi.zein@gmail.com.

