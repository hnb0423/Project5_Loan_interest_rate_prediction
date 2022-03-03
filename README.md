# Project 5: Loan interest rate prediction
Business problem: The goal of this project is to predictloan interest rate by using training and testing dataset

## Data Processing:
I encoded categorical variables, handle missing values.
 
## Feature engineering:
I dropped unnecessnary columns, recategorized certain columns, and resolved mismatch issue between training and testing datasets. 

## EDA on training data:
I computed correlation matrix to study multicollinearity among varibles

## Models Construction:
I applied linear regression, lasso regression, ridge regression, decision tree, and random forest to training dataset. Since random forest has lowest RMSE, I decided to use this model to predict loan interest rate. I exported the predicted values to a csv file. 
