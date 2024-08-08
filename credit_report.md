# Credit Risk Model Report

## Overview
The purpose of this analysis is to evaluate the performance of a machine learning model used to predict credit risk. The model's performance was assessed using metrics such as accuracy, precision, recall, and F1-score. These metrics provide insights into the model's ability to make correct predictions.

## Data Collected
The data used for this analysis is historical lending activity from peer-to-peer lending services that includes variables such as loan size, interest rate, borrower income, debt to income ratio and total debt.

## Process
We first read in the lending data CSV in pandas and seperated the loan status variable. We then ran train test split to train the model and test the data. We then created a Logistic Regression model and used it to make a prediction. We than evaluated the performance of the model.

## Results

              precision    recall  f1-score   support

           0       1.00      1.00      1.00     18759
           1       0.87      0.89      0.88       625

    accuracy                           0.99     19384
   macro avg       0.94      0.94      0.94     19384
weighted avg       0.99      0.99      0.99     19384

## Summary
The credit risk model demonstrated strong performance in predicting outcomes based on our data, with an overall average accuracy of 99%. The model had perfect precision for predicting low-risk loands, and strong performance in prediction high-risk loands with a precion of 0.87 and recall of 0.89. These results indicate the model is reliable for predicting credit risk.

