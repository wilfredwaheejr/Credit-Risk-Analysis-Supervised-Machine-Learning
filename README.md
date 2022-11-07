# Credit Risk Analysis

## Overview
### Purpose 
The purpose of this analysis is to determine the effectiveness of machine learning models in predicting credit risk. 

## Results

There is a list that describes the balanced accuracy score, precision, and recall scores of all six machine learning models:

### Oversampling
#### Naive Random Oversampling
The balanced accuracy score is 65%. The precision score is 1% and the recall score is 72%.

<img width="630" alt="Screenshot 2022-11-07 at 3 08 33 AM" src="https://user-images.githubusercontent.com/107484694/200258131-44a888a9-4ca9-43c7-9296-8024f5ae4168.png">

#### SMOTE Oversampling
The balanced accuracy score is 66%. The precision score is 1% and the recall score is 63%.

<img width="630" alt="Screenshot 2022-11-07 at 3 10 31 AM" src="https://user-images.githubusercontent.com/107484694/200258520-b5171410-991b-43a4-8925-db0d1ca85c95.png">

### Undersampling
The balanced accuracy score is 66%. The precision score is 99% and the recall score is 69%.

<img width="630" alt="Screenshot 2022-11-07 at 3 12 09 AM" src="https://user-images.githubusercontent.com/107484694/200258818-1c447b48-4a4f-4a46-8403-4d12b62868f7.png">

### Combination Sampling 
The balanced accuracy score is 64%. The precision score is 99% and the recall score is 57%.

<img width="630" alt="Screenshot 2022-11-07 at 3 13 56 AM" src="https://user-images.githubusercontent.com/107484694/200259168-c796b6c5-1c72-4178-b5bf-e7a60d203bc9.png">

SMOTE oversampling and undersampling predict the highest balanced accuracy score. These models give us the highest probability to correctly predict credit risk.

Naive random oversampling predicts the highest recall score. This model gives us the highest number of positive samples that are correct.

## Summary
### Recommendation and Justification
Naive random oversampling predicts the highest recall score and a balanced accuracy score of 65% making it the best model in predicting credit risk. 
