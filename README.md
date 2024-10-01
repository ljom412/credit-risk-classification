# credit-risk-classification

# Overview
In this challenge, we used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. The dataset included information on loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The purpose was to predict whether loans were "healthy" or "high-risk".

# Process
1. Read the lending data csv into a Pandas DataFrame.
2. Create the labels set and features DataFrame.
3. Split the data into training and testing datasets using train_test_split.
4. Create and fit a Logistic Regression Model.
5. Evaluate the model's performance using a confusion matrix, accuracy score, precision score, and recall score.

# Results
Model Accuracy: 99.37% | Model Precision: 84.37% | Model Recall: 98.55%

# Summary
The model performs very well, predicting the healthy loan labels with 99.4% accuracy and the high-risk loan labels with 98.5% accuracy.
