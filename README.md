![small](https://user-images.githubusercontent.com/112433621/227211600-3291d7f7-92c7-4cb0-a934-55d1febfce49.jpg)


**Credit-risk-classification**

In this Challenge, We’ll use various techniques to train and evaluate a model based on loan risk. We’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**Instructions**

- The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Predict a Logistic Regression Model with Resampled Training Data

- Write a Credit Risk Analysis Report


## Analysis Overview

In this Challenge, We used various techniques to train and evaluate a model based on loan risk. 
We used a dataset of historical lending activity from a peer-to-peer lending services company. 
The data was used to build a model that can identify the creditworthiness of borrowers.


In order to achieve this, we first had to seperate the data in two seperate parts, one was for training the model and the second set of data was to test the perfomance of the model.Once this was done we created a Logistic Regression Model and carried out some analysis.

#### add image of spliting 

## The Results

### Logistic Regression Model Scoring

##### Healthy Loans
- Precision 100%
- Recall 99%
- F1-Score 100%

##### High Risk Loans
- Precision 85%
- Recall 91%
- F1-Score 88%

### OverSampled Data Model Scoring

##### Healthy Loans
- Precision 100%
- Recall 100%
- F1-Score 100%

##### High Risk Loans
- Precision 86%
- Recall 90%
- F1-Score 88%

## A Summary

As shown in the scoring records above, we can see that the model with OverSampled data had an outstanding perfomance concerning healthy loans calculations. There is some slight improvement with the high risk loan statistics too however it is only slight. Regardless of this the oversampled data model would be the one recommended for the test since it technically had a higher perfomance scoring for both high risk and healthy loans.
