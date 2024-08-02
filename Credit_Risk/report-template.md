# Credit Risk Analysis Report

## Overview of the Analysis

* Purpose of the Analysis
The purpose of this analysis is to develop a machine learning model that can accurately predict loan status, classifying loans as either healthy (0) or high-risk (1). This analysis aims to  build a model that can identify the creditworthiness of borrowers.

* The logistic regression model by using the original traning data sets (X_train, y_train), fitting it to the training sets, and using it to generate predictions.The target variable to predict is the 'loan_status', which indicates whether a loan is healthy (0) or high-risk (1).
* The variable for 'loan_status':
- Healthy loan (0): 18,759
- High-risk loan (1): 625

* Stages of the machine learning process of this analysis
- Data Loading and Preprocessing
- Model Development
- Model Evaluation

* Methods Used - `LogisticRegression`
The primary method used in this analysis was LogisticRegression from the scikit-learn library. 
By following this process, the logistic regression model was able to provide accurate predictions, effectively distinguishing between healthy and high-risk loans based on the given financial data.

## Results

* Machine Learning Model - The logistic regression model:
    *  The logistic regression model exhibits strong performance in predicting both healthy loans and high-risk loans. It achieves an overall accuracy of 99%, indicating that the majority of its predictions are correct. For healthy loans (label 0), the model achieves a precision and recall of 100%, meaning it perfectly identifies all healthy loans without any false positives or false negatives. For high-risk loans (label 1), the model has a precision of 87% and a recall of 95%, indicating it correctly identifies 87% of high-risk loans it predicts and captures 95% of all actual high-risk loans. The macro average precision is 94%, the macro average recall is 97%, and the macro average f1-score is 95%, reflecting the model's overall robust performance.
   

## Summary

The logistic regression model worked very well, with 99% accuracy in predicting loan status. It perfectly identified all healthy loans (0) and correctly predicted 87% of high-risk loans (1), with 95% of actual high-risk loans being found. While it is great at predicting healthy loans, it is more important to improve how it predicts high-risk loans because missing these can lead to big financial losses. So, even though the model is reliable, we should make it better at predicting high-risk loans.
