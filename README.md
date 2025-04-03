# credit-risk-classification

Loan Risk Prediction Using Logistic Regression
Overview
This project analyzes the effectiveness of a logistic regression machine learning model in predicting loan outcomes. The goal is to determine whether the model can accurately classify loans as healthy (0) or high-risk (1) by leveraging a dataset of 77,536 loans. The dataset includes various financial attributes such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

Machine Learning Process
The analysis follows a structured machine learning workflow to ensure reliable model evaluation:

Data Preparation – The dataset is imported, structured into a DataFrame, and assessed for relevant features.

Feature and Label Separation – The target variable (loan_status) is isolated, while the remaining columns are used as features for training and testing.

Train-Test Split – The dataset is divided into training and testing sets using the train_test_split function.

Model Initialization and Training – The LogisticRegression model from sklearn is imported, initialized, and trained using the training dataset.

Making Predictions – The trained model generates predictions based on the test dataset.

Model Evaluation – The model's performance is assessed using key metrics such as accuracy score, confusion matrix, and classification report.
