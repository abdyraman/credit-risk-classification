# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of the analysis is to predict if the loan is high-risk one or good.
* I was using a dataset consisting of the following fields loan size,	interest rate,	borrower's income,	debt to income,	number of accounts,	derogatory marks,	total debts, and	loan status. We used a loan status as 'y' variable to predict if the loan is good 0 or high risk 1.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
*I used LogisticRegression, standart scaler to transform x variables and oversampling method to predict the second model.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
 This model demonstrates higher accuracy in predicting healthy loans compared to high-risk loans. The precision for predicting high-risk loans is reported to be 84%, with an F1 score of 87%. Conversely, for positive loans, the precision and F1 score are both 100%.
The confusion matrix indicates that there are 66 false negatives and 575 true negtives. Its a high number.



* Machine Learning Model 2:
   The improved model, achieved through the utilization of random oversampling, demonstrates enhanced performance compared to the previous model. This enhancement is attributed to the equalization of the sample count for the class labeled as 1, now matching that of the class labeled as 0, resulting in 56,293 samples for each class.

As a consequence of this adjustment, the number of false negatives in the confusion matrix decreased significantly to just 4. However, it is worth noting that the false positives increased compared to the previous model.

Additionally, the classification report reveals a higher recall of 100% for the class labeled as 0, compared to the previous model's recall of 99%. Furthermore, this improved model exhibits a slight increase in precision and F1 score for the class labeled as 0.

The overall accuracy of the model remained nearly the same, maintaining a high level of 99%, which aligns with the accuracy achieved by the previous model.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
*The model 2 performs better than models 1,because it is important for financial institution to predict the high risk loans.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.
I would use the model 2 as the basis.
