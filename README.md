# Overview

## Purpose
As good loans outweigh risky ones, this demonstrates that credit risk naturally has an unequal distribution of classes. In this analysis, we utilize imbalanced-learn and scikit-learn libraries to help us build and evaluate models for resampling. Two machine learning models that we will use to predict credit risk are BalancedRandomForestClassifier and EasyEnsembleClassifier. We would like to predict if an individual is a high or low credit risk by oversampling our data using RandomOverSampler and SMOTE algorithms. As well as undersampling our data with the ClusterCentroids algorithm.

## Results

<b>RandomOverSampler Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_randomover.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/Random_oversamplerr.png)
- Balanced Accuracy Score for Random OverSampling is approximately 65% with a precision rate of 99% and recall(sensitivity) of 68%.</br></br>


<b>SMOTE Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_smote.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/SMOTE_oversampler.png)
- Balanced Accuracy Score for SMOTE is approximately 62% with a precision rate of 99% and recall(sensitivity) of 64%.</br></br>


<b>ClusterCentroids Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_cluscentt.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/ClusterCentroidss_undersamplerr.png)
- Balanced Accuracy Score for Cluster Centroids is approximately 51% with a precision rate of 99% and recall(sensitivity) of 45%.</br></br>


<b>SMOTEENN Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_smoteenn.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/SMOTEEN_overundersamplerr.png)
- Balanced Accuracy Score for SMOTEENN is approximately 62% with a precision rate of 99% and recall(sensitivity) of 54%.</br></br>


<b>BalancedRandomForest Classifier Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_balranfor.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForest.png)
- Balanced Accuracy Score for Balanced Random Forest is approximately 79% with a precision rate of 99% and recall(sensitivity) of 91%.</br></br>


<b>EasyEnsemble Classifier Model</b></br>
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/BAS_easyens.png)
![alt text](https://github.com/lopezroxann/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.png)
- Balanced Accuracy Score for Easy Ensemble is approximately 92% with a precision rate of 99% and recall(sensitivity) of 94%.</br></br>


## Summary
Looking at all of the results of all six models above, EasyEnsemble Classifier model is the best predictor for assessing indivudals that are high or low credit risks. Although precision is important, sensitivity has a higher value in these assessments. EasyEnsemble had a high sensitivity rate of 94% as well as a high Balanced Accuracy Score of 92%. Having a high recall rate means that 92% of the time it will identify that a high credit risk indivudal is indeed just that. This is something that banks would rather focus on when considering an individual for credit.The high Balanced Accuracy Score validates how correct the model functions in its predictions. Considering all of these factors, EasyEnsemble Classifier is the best choice for this scenario.
