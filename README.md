# Credit-risk-classification

![small](https://user-images.githubusercontent.com/112433621/227211600-3291d7f7-92c7-4cb0-a934-55d1febfce49.jpg)


In this Challenge, We’ll use various techniques to train and evaluate a model based on loan risk. We’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

**Instructions**

- The instructions for this Challenge are divided into the following subsections:

- Split the Data into Training and Testing Sets

- Create a Logistic Regression Model with the Original Data

- Predict a Logistic Regression Model with Resampled Training Data

- Write a Credit Risk Analysis Report

# Credit Risk Report 
![s](https://user-images.githubusercontent.com/112433621/227235577-60f43006-3c23-4a69-b808-f826b9f0e046.jpg)


## Analysis Overview

In this Challenge, We used various techniques to train and evaluate a model based on loan risk. 
We used a dataset of historical lending activity from a peer-to-peer lending services company. 
The data was used to build a model that can identify the creditworthiness of borrowers.


In order to achieve this, we first had to seperate the data in two seperate parts, one was for training the model and the second set of data was to test the perfomance of the model.Once this was done we created a Logistic Regression Model and carried out some analysis.

<img width="637" alt="splitting" src="https://user-images.githubusercontent.com/112433621/227233743-e4986c47-a1c2-4744-a62b-96d0965b0ba2.png">
 

## The Results

### Logistic Regression Model Scoring
<img width="498" alt="Classification report testing" src="https://user-images.githubusercontent.com/112433621/227234221-aec57f12-db76-4b40-983c-db5b229cde82.png">

##### Healthy Loans
- Precision 100%
- Recall 99%
- F1-Score 100%

##### High Risk Loans
- Precision 85%
- Recall 91%
- F1-Score 88%

### OverSampled Data Model Scoring
<img width="521" alt="Classification report training" src="https://user-images.githubusercontent.com/112433621/227234404-26057714-0bde-41d7-8af3-bb139feacb23.png">

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
