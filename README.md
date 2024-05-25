# Project Case Study - Miami Housing Dataset

## Project Goals
The main goal of this project is to predict the Sale Price ($) of different houses based on the given data through different algorithms. This project also aims to give insights into the relationship between different features and their influence on the sale price of the houses. The algorithms that we will be focusing on are Linear Regression and Random Forest.

## Dataset Description:
This dataset was collected from Kaggle and comprises of Housing Data in Miami Florida area. The dataset focuses on the single family homes sold during the year 2016. The Dataset contains information of about approximately 13,932 single family homes.

## Exploratory Data Analysis:
Thw following exploratory data analysis was done in the dataset:
1. Dataset Summary
2. Data Types
3. Missing or Null Values analysis
4. Uniqueness and Duplicity analysis
5. Statistical Analysis
6. Univariate Analysis
7. Correlation analysis
8. Multivariate Analysis (Sale price vs other variables)

## Important Feature selection
SelectKBest class was used to select features according to the k highest scores.

## Data split ratio
For performing the analysis we split the data into three sets: training dataset, cross-validation dataset and test dataset, in the ratio of 70:15:15. The training dataset will be used for training the model based on an algorithm, cross-validation dataset will be used to see how the model performs by comparing the predicted sale price with the actual sale price and test dataset will be used for predicting the sale price of houses that are new to the model.

## Feature Scaling 
Since most of our data are not normally distributed, that is, extremely skewed and have outliers, also have very different scales, so we decided to do a feature scaling.
The method of scaling that we used is Normalization or MinMax Scaler. With this the values are rescaled so that the minimum and maximum value of each column falls within 0 and 1.

## Models Used
1. Linear Regression
2. Random Forest

## Metrics Used
1. Mean Absolute Error
2. Mean Squared Error
3. Root Mean Squared Error
4. R-squared

## Result Conclusion:
Through the evaluation we found which one works better in predicting the sale price. It was found that Random Forest Regressor is far better in predicting the sale price of houses. The reasoning behind this it is not effected by outliers use an ensemble method of decision trees to come to the result. Whereas simple linear regression algorithm tends to be heavily affected by the presence of outliers.
