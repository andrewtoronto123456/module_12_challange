# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Analysing credit risk poses a computatonal imnbalanced issue. The issue is healthy loans are better proportion than the riskier loans. In order to resolve this issue, we analysied the date in two scenerios. The data was processed as it is in the first analysis. In the seocnd analysis a over sampling stratagy was introduced. And the esults betrween the two scenarios was examined. 
* Explain what financial information the data was on, and what you needed to predict.
* The independent vaiables were: loan size,	interest rate, borrower income,	debt to income,	num of accounts, derogatory marks, total debt
* We needed to predict the loan status
*  Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
*  0  healthy     75036
*  1  high risk   2500
* Describe the stages of the machine learning process you went through as part of this analysis.
* Describing  x and y
* Seperation of y
* Train, test split
* Instaniate, fit, predicted for both models
* Analysing of the results predicted for both models
  
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
* LogisticRegression which is a standard for binary outcomes was used.
* Oversampling method was used to compromise the unbalanced data. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  * class 0       1.00      0.99      1.00     
    class 1       0.85      0.91      0.88     

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
    class 0       0.99      1.00      0.99     
    class 1       0.99      0.84      0.99     

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Model 2 predicts the high risk loans better.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
* Yes, it's imperative to predict Class 1 accurately, since it's critical and under represented.
* If you do not recommend any of the models, please justify your reasoning.
* Model 2 is recommended, because of it's accuracy in predicting class 1.
