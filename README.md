# credit-risk-classification

## Overview of Analysis
With this analysis, we want to creaing a learning model that will be able to predict whether a loan is healthy or high risk based on a borrower's loan size, the loan's interest rate, their income, their debt to income ratio, how many accounts they have, how many derogatory marks they have, and their total debt.

## Results
* Healthy Loans (0)
    * Precision: 1.00
    * Recall: 1.00
    * F-1 Score: 1.00
* High-Risk Loans (1)
    * Precision: 0.87
    * Recall: 1.00
    * F-1 Score: 0.93
* Accuracy
    * F-1 Score: 1.00
* Macro Average
    * Precision: 0.94
    * Recall: 1.00
    * F-1 Score: 0.96
* Weighted Average
    * Precision: 1.00
    * Recall: 1.00
    * F-1 Score: 1.00

## Summary
From the results, this model is very good at determining Healthy Loans. With precision and recall having scores of 1.0, we see that it does not give false positives and false negatives, so the model can accurately determine Healthy Loans. With High-Risk Loans, we see that the model has a precision score of 0.87 and a recall score of 1.00. This means that the model gives us false positives on High-Risk Loans, but does not give us false negatives. Overall, this model is very good, and we recommend that the company to use this model. The model gives us almost complete accuracy on Healthy-Loans and does not fail to miss High-Risk Loans. The only downside of this model is that it can incorrectly mark some people as High-Risk Loans when they are actually Healthy Loans, but this is the best case scenario for the model to be wrong. Incorrectly marking High-Risk Loans prevents us from giving loans that are not favorable and allows us to review those who were incorrectly marked.
