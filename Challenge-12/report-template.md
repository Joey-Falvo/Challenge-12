# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The puropose of this analysis is to compare the accuracy of the model between the original data and oversampled data using RandomOverSampler.
* Explain what financial information the data was on, and what you needed to predict.
The financial information was based on the borrowers financials including the size of the loan(loan size, interest rate, borrower income, debt to income, total debt). The model was used to predict whether the loan is high or low risk.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
0    75036 - Healthy Loan
1     2500 - High Risk Loan
* Describe the stages of the machine learning process you went through as part of this analysis.
Stages:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Predict a Logistic Regression Model with Resampled Training Data

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
LogisticRegressiona and RandomOverSampler

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
 Accuracy score is adequate for learning Model 1: Accuracy Score = 0.9442676901753825
 
Precision and recall is perfect for healthy loan and under 90% for high risk loan
 precision    recall 
 
      1.00      1.00      Healthy Loan
      0.87      0.87      High Risk Loan



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  Accuracy score is not adequate in Model 2: Accuracy Score = 0.5048884055653287
  
  The precision and recall scores of the high risk loans is terrible in Model 2.  
  
  precision    recall    

      0.97      0.96    Healthy Loan
      0.04      0.04    High Risk Loan

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
Machine learning Model 1 performs best.  Both the precision and recall are great and better then Model 2.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Yes.  It depends on what we are trying to solve.

If you do not recommend any of the models, please justify your reasoning.
I recommend Model 1, performs well.
