# credit-risk-classification

# Background 
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Overview of the Analysis
The purpose of this module analysis was to determine the creditworthiness of  borrowers. A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting. This analysis was collected using variables such as: loan size, interest rate, borrower's income, number of accounts, total debt, etc.

To begin the data was separated into two groups. The first would be used for training with the second being used for tests. With the two groups I'm interested in determining the number of "healthy" and "non-healthy" loans within the data set and the number of people who fall into one of those two categories. 

The process for the machine learning first began with assigning the loan status to the y-variable and the other variables to the x-variable. Following that a logistic regression model was created to allow predictions within the training set between the loan status (y) and the other creditworhiness variables (x). Logistic regression allows for predictions within a dataset and in this instance it played an important part with determining the potential borrowers worthiness. 

## Results

"Healthy" = 0
"Non-healthy" = 1

* Machine Learning Model 1:
    * Accuracy: 0.9520479254722232 or 95%
    * Precision (Healthy borrowers): 100% 
    * Precision (Non-healthy borrowers): 85%
    * Recall scores (Healthy borrowers): 99%
    * Recall scores (Non-Healthy borrowers): 91%  

* Machine Learning Model 2:
    * Accuracy: 0.9936781215845847 or 99%
    * Precision (Healthy borrowers): 100% 
    * Precision (Non-healthy borrowers): 84%
    * Recall scores (Healthy borrowers): 99%
    * Recall scores (Non-Healthy borrowers): 99% 

## Summary
Overall after completing the two machine learning models the second model has the advantage of a higher recall score for both healthy and non-healthy borrowers with 99% accuracy. This model has the advantage over the first model because in order for a bank or a financial insitution to be successful with lending it needs to ensure to minimize any possible risk. The second model provided a higher accuracy that would help with predicting whether a borrower is a risky investment for the firm. 