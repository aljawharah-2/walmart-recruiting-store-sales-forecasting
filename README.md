# walmart-recruiting-store-sales-forecasting

https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

## Dataset

Use historical sales data for 45 Walmart stores located in different regions. Each store contains many departments.

## Target

Forecast the weekly sales for 99 departments at 45 Walmart stores located in different regions. My evaluation procedure is formulated like backtesting for stock trading systems: when predicting the sales of a month, I am only allowed to use all the information available till that month --- cannot peek into the future.

## Main File

Save my main file as Walmart

## Data Preprocessing

I download the train.csv.zip file from Kaggle website. Then use the train_test_split function to take 20% for test data , treate missing values and categrical values.

## Model Prediction

I use simple model multiple regressor like (linear regression , KNN , decision tree , random forest regressor) then I highlight the best accuracy which is here random forest regressor with 97 accuracy.
