# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
Using the credit card credit dataset from LendingClub, we have oversampled the data using the RandomOverSampler and SMOTE algorithms, undersampled using the ClusterCentroids algorithm, and did a combination using the SMOTEENN algorithm. Next, we have compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 

## Results:

Oversampling:

- balanced_accuracy_score  0.6447993752836463
- confusion_matrix  [   70,    31], [ 6933, 10171]
- classification_report_imbalanced

![TBrickey](https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/oversamplingclass.png)
                   
                
SMOTE Oversampling:

- balanced_accuracy_score  0.6628910844779521
- confusion_matrix   [   64,    37], [ 5266, 11838]
- classification_report_imbalanced

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTE%20Oversamplingclass.png)
  

Undersampling:

- balanced_accuracy_score  0.6628910844779521
- confusion_matrix  [   70,    31], [10340,  6764]
- classification_report_imbalanced


SMOTEENN, Combination (Over and Under) Sampling:

- balanced_accuracy_score  0.5442661782548694
- confusion_matrix  [   70,    31], [10340,  6764]
- classification_report_imbalanced

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTEENNclass.png)


Balanced Random Forest Classifier: 

- balanced_accuracy_score  0.7885466545953005
- confusion_matrix  [   71,    30], [ 2153, 14951]
- classification_report_imbalanced

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/BRFClass.png)


Easy Ensemble AdaBoost Classifier

- balanced_accuracy_score  0.9316600714093861
- confusion_matrix  [   93,     8], [  983, 16121]
- classification_report_imbalanced

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/EEAClass.png)



![TBrickey](https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/oversampling.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/undersampling.png)

![TBrickey](https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTE%20Oversampling.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTEENN.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/Balanced%20Random%20Forest%20Classifier.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/Easy%20Ensemble%20AdaBoost%20Classifier.png)


