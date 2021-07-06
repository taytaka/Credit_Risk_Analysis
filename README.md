# Credit Risk Analysis
## Purpose
The purpose of this analysis is to evaluate credit card data from LendingClub. This analysis will determine which model of supervised machine learning best predicts a high-risk credit card applicant.

## Results
The below list indicates the accuracy, precision, and recall of all supervised machine learning models used to determine high-risk credit card applicants.
- RandomOverSampler
  - Accuracy: 0.66
  
  ![ros_acc.png](Resources/ros_acc.png)
  
  - Precision: 0.01
  - Recall: 0.70
  
  ![ros_report.png](Resources/ros_report.png)
  
- SMOTE
  - Accuracy: 0.66

  ![smote_acc.png](Resources/smote_acc.png)

  - Precision: 0.01
  - Recall: 0.63

  ![smote_report.png](Resources/smote_report.png)

- ClusterCentroids
  - Accuracy: 0.54

  ![cluster_acc.png](Resources/cluster_acc.png)

  - Precision: 0.01
  - Recall: 0.69

  ![cluster_report.png](Resources/cluster_report.png)

- SMOTEEN
  - Accuracy: 0.64

  ![smoteen_acc.png](Resources/smoteen_acc.png)

  - Precision: 0.01
  - Recall: 0.72

  ![smoteen_report.png](Resources/smoteen_report.png)

- BalancedRandomForestClassifer
  - Accuracy: 0.77

  ![brf_acc.png](Resources/brf_acc.png)

  - Precision: 0.03
  - Recall: 0.66

  ![brf_report.png](Resources/brf_report.png)

- EasyEnsembleClassifier
  - Accuracy: 0.93

   ![ensemble_acc.png](Resources/ensemble_acc.png)

  - Precision: 0.09
  - Recall: 0.92

  ![ensemble_report.png](Resources/ensemble_report.png)
  

## Summary
Overall, the ensemble supervised machine learning models performed the best. The BalancedRandomForestClassifier and the EasyEnsembleClassifier had the highest accuracies, precisions, and recalls of all of the models with the EasyEnsembleClassifier performing the best. I would recommend using the EasyEnsembleClassier as it has the best accuracy, precision, and recall scores. It has a particularly high recall score, which is important in this case as it is more important to catch all of the high-risk applicants than it is to be precise when analyzing credit risk. 
