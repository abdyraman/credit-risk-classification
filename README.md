I used various techniques to train and evaluate a model based on loan risk. 
I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Steps Accomplished:
1. The data from the "lending_data.csv" file was read into a Pandas DataFrame.
2. The labels set (y) was created from the "loan_status" column, and the features (X) DataFrame was generated from the remaining columns.
3. The data was split into training and testing datasets using train_test_split.
4. A logistic regression model was fitted using the training data (X_train and y_train).
5. The predictions on the testing data labels were saved using the testing feature data (X_test) and the fitted model.
6. A confusion matrix was generated to evaluate the model's performance.
7. A classification report was generated to evaluate the model's performance further.
8. The question regarding how well the logistic regression model predicts both the "0" (healthy loan) and "1" (high-risk loan) labels was answered.
9. A Credit Risk Analysis Report was written, providing an overview of the analysis purpose.
10. Using a bulleted list, the accuracy, precision, and recall scores of the machine learning model were described.
11. The results from the machine learning model were summarized, and justification was provided for recommending or not recommending the model's use by the company.
12. Coding conventions and formatting were applied, including proper placement of imports, lowercase names for functions and variables with underscores, adhering to DRY principles, and using concise logic.
13. The code was well-commented with concise and relevant notes to aid other developers' understanding.
