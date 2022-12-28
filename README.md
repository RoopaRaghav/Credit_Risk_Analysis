# Credit_Risk_Analysis
# Credit_Risk_Analysis
Supervised Machine Learning and Credit Risk

## Overview of the loan prediction risk analysis:   
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Various libraries and algorithms were used to build and evaluate models using resampling including: 
1. imbalanced-learn 
2. scikit-learn
# Over Sampling Techniques with Linear Regression Model
3. RandomOverSampler
4. SMOTE algorithms
# Under sampling Technique with Linear Regression Model
5. ClusterCentroids algorithm
# Combination of Over- and Under- Sampling with Linear Regression Model 
6. SMOTEENN algorithm
# Bias Reduction Models
7. BalancedRandomForestClassifier 
8. EasyEnsembleClassifier 

## Background:
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk. 


## Results:
The results for the six machine learning models are shown below:      

### Naive Random Oversampling


### SMOTE Oversampling


### Undersampling


### Combination Under-Over Sampling


### Balanced Random Forest Classifier


### Easy Ensemble AdaBoost Classifier


## Summary:
All the models bal accuracy score, precision, recall are with in ranges between 0 and 1. The model that is close to 1 is considered to be best ML model.

For the Lending Club Credit card dataset, the Easy Ensemble AdaBoost Classifier is the best model with its .93 balanced accuracy.So I would start any further analysis with this model.

After looking into the classification report for imbalanced dataset The Easy Ensemble AdaBoost Classifier has the highest recall score, making it best machine learning model.   
