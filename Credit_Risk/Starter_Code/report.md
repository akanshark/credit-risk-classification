# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* This model is based on loan risk
* I got financial information about the loan and the borrower
* The target was loan_status, the features are all other financial information given to predict the target
  
## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Precision: 1.00 for 0, 0.86 for 1
  * Recall: 0.99 for 0, 0.9 for 1
  * Accuracy: 0.99
  * 0 (healthy loan) is predicted well but 1 (high risk loan) is not predicted as well



* Machine Learning Model 2:
  * Precision: 0.91 for 0, 0.99 for 1
  * Recall: 0.99 for 0, 0.91 for 1
  * Accuracy: 0.95
  * Predicts 0 accurately, but 1 less accurately (but more accurately than model 1).

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Predicting 1 may be more important, as lenders do not want to give low rates to borrowers with potentially high risks of not paying back the loan.
* Therefore, I do not recommend either model because I think it is important to have a higher accuracy when calculating 1 as well as 0.
* It is good that both models calculate a score effectively, but good models should calculate each score effectively.

If you do not recommend any of the models, please justify your reasoning.
