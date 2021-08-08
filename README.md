# Credit_Risk_Analysis


## Overview of the analysis:
The purpose of this analysis was to oversample and undersample the credit card dataset from LendingClub. This was to be done using the RandomOverSampler and SMOTE algorithms for oversampling and the ClusterCentroids algorithms for undersampling. Overall we wish to structure a machine learning model that is capable of predicting credit risk with the highest accuracy.


## Results: 

### RandomOverSampler
In the machine model, in order to oversample, the RandomOversSampler was used within a Logistic Regression model. The following are key results to note: 
- The Counter:
  - Low risk = 51,366
  - High risk = 51,366
- The Random State = 1. 
- The Accuracy Score = 64%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report



### SMOTE
In the machine model, another method of oversample, is via the SMOTE oversampling within a Logistic Regression model. The following are key results to note: 
- The Counter:
  - Low risk = 51,366
  - High risk = 51,366
- The Random State = 1. 
- The Accuracy Score = 65%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report

*Snaps*


### ClusterCentroids
In the machine model, in order to undersample the data, the ClusterCentroids was used within a Logistic Regression model. The following are key results to note: 
- The Counter:
  - Low risk = 246
  - High risk = 246
- The Random State = 78. 
- The Accuracy Score = 54%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report
*Snaps*


### SMOTEENN
*Description*
In the machine model, we will now perform both oversampling and undersampling combined by using the SMOTEENN algorithm within the Logistic Regression model. The following are key results to note: 
- There is no Counter
- The Random State = 1. 
- The Accuracy Score = 64%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report

*Snaps*


### BalancedRandomForestClassifier
*Description*
In the machine model, we will now use one of two ensemble learning algorithms and decide on the best performance from there. For this section, we are using the Balanced Random Forest Classifier.

The following are key results to note: 
- The Counter is the same for both algorithms:
  - Low risk: 51,357
  - High risk: 255
- n-estimators = 100
- The Random State = 1. 
- The Accuracy Score = 79%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report


*Snaps*


### EasyEnsembleClassifier
*Description*
In the machine model, we will now use one of two ensemble learning algorithms and decide on the best performance from there. For this section, we are using the EasyEnsembleClassifier.

The following are key results to note: 
- The Counter is the same for both algorithms:
  - Low risk: 51,357
  - High risk: 255
- n-estimators = 100
- The Random State = 1. 
- The Accuracy Score = 93%

The confusion matrix and imbalanced classification report are as follows:
- Confusion Matrix



- Imbalanced Classification Report


*Snaps*



Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results. 
There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.


The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
