# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to create & evaluate a model that can predict if a loan is healthy or high-risk, which is crucial for financial institutions. The dataset consists of a list of past loans with the size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and the loan status.

## Results

The only model used for this analysis was a Logistic Regression Model.

* Logistic Regression Model
    * Accuracy: 0.99
    * Healthy Loans
        * Precision: 1 - model is excellent in predicting healthy loans that were actually healthy.
        * Recall: 0.99 - 99% of healthy loans were correctly identified
        * F1-score: 1
    * High-Risk Loans
        * Precision: 0.85 - model is still very accurate in predicting high-risk loans that were actually healthy.
        * Recall: 0.91 - 91% of high-risk loans were correctly identified.
        * F1-score: 0.88

## Summary

The model used showed excellent accuracy in predicting credit risk with an overall accuracy of 99%. While it performs well in predicting both Healthy Loans and High-Risk Loans, it does a bit better in correctly predicting Healthy Loans. 

Based on this, I would recommend using this model, it is good enough on its own. However, using a second model to further test for credit risk in order to offset this model's favouring of Healthy Loan prediction is not required, but may help out a bit.
