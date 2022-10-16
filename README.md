# Overview

## Purpose
As good loans outweight risky ones, this demonstrates that credit risk naturally has an unequal distribution of classes. In this analysis, we utilize imbalanced-learn and scikit-learn libraries to help us build and evaluate models for resampling. Two machine learning models that we will use to predict credit risk are BalancedRandomForestClassifier and EasyEnsembleClassifier. We would like to predict if an individual is a high or low credit risk by oversampling our data using RandomOverSampler and SMOTE algorithms. As well as undersampling our data with the ClusterCentroids algorithm.

## Results

<b>RandomOverSampler Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_randomover.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/Random_oversamplerr.png)
- Balanced Accuracy Score for Random OverSampling is approximately 65% with a precision rate of 99% and recall(sensitivity) of 68%.


<b>SMOTE Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_smote.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/SMOTE_oversampler.png)
- Balanced Accuracy Score for SMOTE is approximately 62% with a precision rate of 99% and recall(sensitivity) of 64%.


<b>ClusterCentroids Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_cluscentt.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroidss_undersamplerr.png)
- Balanced Accuracy Score for Cluster Centroids is approximately 51% with a precision rate of 99% and recall(sensitivity) of 45%.


<b>SMOTEENN Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_smoteenn.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/SMOTEEN_overundersamplerr.png)
- Balanced Accuracy Score for SMOTEENN is approximately 62% with a precision rate of 99% and recall(sensitivity) of 54%.


<b>BalancedRandomForest Classifier Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_balranfor.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest.png)
- Balanced Accuracy Score for Balanced Random Forest is approximately 79% with a precision rate of 99% and recall(sensitivity) of 91%.


<b>EasyEnsemble Classifier Model</b>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_easyens.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.png)
- Balanced Accuracy Score for Easy Ensemble is approximately 92% with a precision rate of 99% and recall(sensitivity) of 94%.


## Summary
