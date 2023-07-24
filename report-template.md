# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis is to predict loan risk levels for potential borrowers.
* Explain what financial information the data was on, and what you needed to predict.
The data was based on the loan size, interest rate, potential boorower income, debt to income reation, number of borrower accounts, and the number of derogatory marks for eahc potential borrower.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The predictions are for high risk and low risk loans and they were compared to the approval results.
* Describe the stages of the machine learning process you went through as part of this analysis.
First we separate the results from the data set. Then we use the dataset to predict approval or rejection based on all the factors. Then we compare the predictions to the actual approvals / rejections.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
Logistic regression creates a relation between factors in the data and the results. That relation is then used to predict approvals and rejections.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Low-risk Loan
1. Precision: 100%
2. Recall: 99%
3. Accuracy: 100%

High-risk Loan
1. Precision: 86%
2. Recall: 88%
3. Accuracy: 87%


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  Low-risk Loan
1. Precision: 100%
2. Recall: 99%
3. Accuracy: 100%

High-risk Loan
1. Precision: 86%
2. Recall: 100%
3. Accuracy: 92%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Model #2 performs better than Model #1. They have idential precision recall and accuracy for the low risk loans, however model 2 has much higher recall and accuracy than model #1 for high-risk loans.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Performance does not matter since both models scored the same for low-risk loans. Model #2 is the better model to run in any scenario.

If you do not recommend any of the models, please justify your reasoning.
