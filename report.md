## Overview of the Analysis


* The main goal of the analysis is to predict whether a loan falls into the high-risk or good category.
* The dataset I utilized included various factors such as loan size, interest rate, borrower's income, debt to income ratio, number of accounts, derogatory marks, total debts, and loan status. The loan status was the dependent variable ('y') that was used to determine if the loan is considered healthy (0) or high risk (1) for the financial institution. All other variables were considered as independent variables ('x').
* To make accurate predictions, I applied standard scaling to normalize the independent variables ('x'). Subsequently, I employed Logistic Regression as the predictive model. However, since the number of high-risk loan samples (1) was relatively smaller, in the second model, I used an oversampling technique to increase the number of high-risk samples to match the number of healthy ones.

## Results

* Machine Learning Model 1:
 This model demonstrates higher accuracy in predicting healthy loans compared to high-risk loans. The precision for predicting high-risk loans is reported to be 84%, with an F1 score of 87%. Conversely, for positive loans, the precision and F1 score are both 100%.
The confusion matrix indicates that there are 66 false negatives and 575 true negtives. Its a high number.



* Machine Learning Model 2:
   The improved model, achieved through the utilization of random oversampling, demonstrates enhanced performance compared to the previous model. This enhancement is attributed to the equalization of the sample count for the class labeled as 1, now matching that of the class labeled as 0, resulting in 56,293 samples for each class.

As a consequence of this adjustment, the number of false negatives in the confusion matrix decreased significantly to just 4. However, it is worth noting that the false positives increased compared to the previous model.

Additionally, the classification report reveals a higher recall of 100% for the class labeled as 0, compared to the previous model's recall of 99%. Furthermore, this improved model exhibits a slight increase in precision and F1 score for the class labeled as 0.

The overall accuracy of the model remained nearly the same, maintaining a high level of 99%, which aligns with the accuracy achieved by the previous model.

## Summary

Model 2 outperforms Model 1 due to its ability to accurately predict high-risk loans, which is crucial for financial institutions.

