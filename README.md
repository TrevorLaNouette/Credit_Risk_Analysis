# Credit_Risk_Analysis


## Overview of the loan prediction risk analysis:

I was asked to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling. Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I was to oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, I was asked to compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

## Results:

- <B> Naive Random Oversampling</B>

<img width="377" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/82718969/136466010-1776c4ca-18a8-42e8-aeb5-da28d7d669dd.png">

- <B> SMOTE Oversampling</B>

<img width="389" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/82718969/136466104-efd2c3e4-6d15-4e60-b86d-883454369b9a.png">

- <B> Undersampling</B>

<img width="382" alt="Undersampling" src="https://user-images.githubusercontent.com/82718969/136466147-e2b43e40-b900-4730-870b-85766b8e3b53.png">


- <B> Combination (Over and Under) Sampling</B
  
<img width="375" alt="Combination (Over and Under) Sampling" src="https://user-images.githubusercontent.com/82718969/136466225-db3f3e0d-b6db-43a4-856a-2d74285e0aa9.png">

  
- <B> Balanced Random Forest Classifier</B>
  
<img width="389" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/82718969/136466268-2dd05745-3fae-4b7d-a65f-95bfbdc5e587.png">

  
- <B> Easy Ensemble AdaBoost Classifier</B>
  
<img width="380" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/82718969/136466768-1edd204e-e550-4053-b335-d6cffccbe9e9.png">
  

## Summary:

The Easy Ensemble AdaBoost Classifier performed the best of all with the highes average scores in Precision(99%), Recall(94%), and F1 Score(97%). It also had the highest balanced accuracy score of (93%). Most of the methods performed well on low risk credit scores. I would reccomend using the Easy Ensemble AdaBoost Classifier with the help of an underwriter to personally look through all of the high risk identified cases as they had high variablility which was shown in their low precision scores.
