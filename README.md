# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis
The purpose of this analysis is to use several machine learning models to predict credit risk, and see if they can be used to predict credit risk. Models include:
- RandomOverSampler and SMOTE algorithms
- Cluster Centroids algorithm
- Smoteenn algorithm
- Comparing two machine learning models that reduces bias, BalancedRandomForest Classifier and EasyEnsembleClassifier. 

## Results
**RandomOverSampler model**<br/>
- Balanced accuracy score is 65%.<br/>
- The high_risk precision is about 1%, with 62% sensitivity.The F1 score is about 2% only.<br/>
- low_risk precision is almost about 100% with 68% of sensitivity.<br/><br/>
**SMOTE model**<br/>
- The balanced accuracy score is 64%.<br/>
- The high_risk precision is about 1% only with 63% sensitivity. The F1 score is about 2% only.<br/>
- The low_risk precision is about 100%, with sensitivity of 66%.<br/><br/>
**ClusterCentroids model**<br/>
- The balanced accuracy score is about 52%.<br/>
- The high_risk precision is about 1% with 63% sensitivity.The F1 score is 1%.<br/>
- The low_risk sensitivity is about 40%.<br/><br/>
**SMOTEENN model**<br/>
- The balanced accuracy score is about 62%.<br/>
- The high_risk preicison is about 1% with 68% sensitivity, f1 score is 2%.<br/>
- The low_risk sensitivity is about 57%.<br/><br/>
**BalancedRandomForestClassifier model**<br/>
- The balanced accuracy score is about 79%.<br/>
- The high_risk precision is at 4% with 67% sensitivity. F1 score is 7%.<br/>
- The low_risk sensitivity is at 91%.<br/><br/>
**EasyEnsembleClassifier model**<br/>
- The balanced accuracy score is about 93%<br/>
- The high_risk precision is at 7% with 91% sensitivity. F1 score is 14%.<br/>
- The low_risk precision is at 94%.<br/><br/>

## Summary
After comparing results of these models, I think none of these models should be used to predict credit risk. A lot of low risk credits are being detected as high risk which can mislead bank making debt decisions. 