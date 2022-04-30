# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis
The purpose of this analysis is to use several machine learning models to predict credit risk, and see if they can be used to predict credit risk. Models include:
- RandomOverSampler and SMOTE algorithms
- Cluster Centroids algorithm
- Smoteenn algorithm
- Comparing two machine learning models that reduces bias, BalancedRandomForest Classifier and EasyEnsembleClassifier. 

## Results
balanced accuracy scores, precision, recall scores
**RandomOverSampler model**
- Balanced accuracy score is 65%.
- The high_risk precision is about 1%, with 62% sensitivity.The F1 score is about 2% only.
- low_risk precision is almost about 100% with 68% of sensitivity.
**SMOTE model**
- The balanced accuracy score is 64%.
- The high_risk precision is about 1% only with 63% sensitivity. The F1 score is about 2% only.
- The low_risk precision is about 100%, with sensitivity of 66%.
**ClusterCentroids model**
- The balanced accuracy score is about 52%.
- The high_risk precision is about 1% with 63% sensitivity.The F1 score is 1%.
- The low_risk sensitivity is about 40%.
**SMOTEENN model**
- The balanced accuracy score is about 62%.
- The high_risk preicison is about 1% with 68% sensitivity, f1 score is 2%.
- The low_risk sensitivity is about 57%.
**BalancedRandomForestClassifier model**
- The balanced accuracy score is about 79%.
- The high_risk precision is at 4% with 67% sensitivity. F1 score is 7%.
- The low_risk sensitivity is at 91%.
**EasyEnsembleClassifier model**
- The balanced accuracy score is about 93%
- The high_risk precision is at 7% with 91% sensitivity. F1 score is 14%.
- The low_risk precision is at 94%.

## Summary
After comparing results of these models, I think none of these models should be used to predict credit risk. A lot of low risk credits are being detected as high risk which can mislead bank making debt decisions. 