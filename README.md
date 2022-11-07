# Credit-Risk-Classification

## Overview

In this project, I predicted if a bank should approve or reject a loan to clients using machine learning that uses past approvals and rejections for its trainig set and test set. I used data from a CSV file of many clients with many x variables (features), and a y variable of healthy vs high-risk loan classification. I made 2 models: a logistic regression model and another logistic regression model but with the RandomOverSampler module from the imbalanced-learn library to resample the data. I wanted to know which of the 2 models worked best.


## Results

* Machine Learning Model 1:

               precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

* Machine Learning Model 2:

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

## Summary

The first model performed best. This is because what we want is to minimize false positives for high-risk predictions, meaning we want a high precision for 1. 0.85 > 0.84, so model 1 is better. 
