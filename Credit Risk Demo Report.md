# Module 20 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

**Purpose of the analysis**
The objective of this analysis was to evaluate whether the logistic regression machine learning model could more accurately distinguish between healthy and high-risk loans by applying resampling techniques to expand the minority class within the original dataset.

**The Dataset**
The dataset utilized for this analysis contains information on 77,536 loans. It includes columns such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, total debt, and loan status. The target variable for our prediction is **loan_status**, while the remaining columns serve as features to train the model and guide its predictions.
**Stages of the Machine Learning Process**
The machine learning process follows a structured sequence of stages that, when executed in order, ensure an accurate evaluation of the model's predictive performance. The key stages include:
**Data Preparation** – Import the dataset, establish the DataFrame, and assess the columns and features.
**Data Segmentation** – Divide the dataset into features and labels. The labels represent the target variable, **loan_status**, indicating whether a loan is healthy (0) or high-risk (1). The features consist of all remaining data used to train and evaluate the model.
**Train-Test Split** – Utilize the train_test_split function to divide the features and labels into training and testing datasets, ensuring the model is trained on one subset and evaluated on another for accurate performance assessment.
**Model Import and Initialization** – Import the machine learning model from the appropriate library; in this case, LogisticRegression from sklearn.
**Make Predictions** – Use the trained model to generate predictions based on the test dataset's features.
**Evaluate Performance** – Assess the model’s predictions by calculating key metrics such as accuracy score, confusion matrix, and classification report to measure its effectiveness.
**Model Training** – Initialize the model and fit it using the training data to enable it to learn patterns from the dataset.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model: Logistic Regression
  * Description of Model 1 Accuracy, Precision, and Recall scores.
** Accuracy Score:** 99%
** Precision Scores:**
	*Class 0 (Healthy Loans): 100%
	*Class 1 (High-Risk Loans): 84%
**Recall Scores:**
	*Class 0 (Healthy Loans): 99%
	*Class 1 (High-Risk Loans): 94%

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.

## Summary

The model excelled at utilizing the original data, predicting the healthy loans with 100% precision and 99% recall. The model was not as good at predicting high-risk loans at 84% precision and 94% recall, but still a fair result. Based on this analysis, the logistic regression model demonstrates strong performance in accurately predicting both healthy and high-risk loans, utilizing the provided features for training.
