# Project 5: Loan interest rate prediction
Business problem: The goal of this project is to predict loan interest rate by using training and testing dataset

## Data Processing:
Encoded categorical variables, handle missing values.
 
## Feature engineering:
Dropped unnecessary columns, recategorized certain columns, and resolved mismatch issue between training and testing datasets. 

## EDA on training data:
Computed correlation matrix to study multicollinearity among variables

## Models Construction:
Applied linear regression, lasso regression, ridge regression, decision tree, and random forest to training dataset. Since random forest has lowest RMSE, I decided to use this model to predict loan interest rate. I exported the predicted values to a csv file. 
