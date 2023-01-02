# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
Using the credit card credit dataset from LendingClub, we have oversampled the data using the RandomOverSampler and SMOTE algorithms, undersampled using the ClusterCentroids algorithm, and did a combination using the SMOTEENN algorithm. Next, we have compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk. 

## Results:

Oversampling:

-balanced_accuracy_score 0.6447993752836463
-confusion_matrix(y_test, y_pred) array([[   70,    31], [ 6933, 10171]], dtype=int64)
-print(classification_report_imbalanced(y_test, y_pred))
                   pre       rec       spe        f1       geo       iba       sup

  high_risk       0.01      0.69      0.59      0.02      0.64      0.42       101
   low_risk       1.00      0.59      0.69      0.74      0.64      0.41     17104

avg / total       0.99      0.60      0.69      0.74      0.64      0.41     17205

  

![TBrickey](https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/oversampling.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/undersampling.png)

![TBrickey](https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTE%20Oversampling.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/SMOTEENN.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/Balanced%20Random%20Forest%20Classifier.png)

![TBrickey]( https://github.com/TBrickey/Credit_Risk_Analysis/blob/main/Mod17/Easy%20Ensemble%20AdaBoost%20Classifier.png)


