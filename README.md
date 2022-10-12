# Credit Risk Analysis

## Purpose
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, we will employ different techniques to train and evaluate models with unbalanced classes.We will use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we'll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, we’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, we’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally, we’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.


## Results
Displayed below is the results and performace metrics of the various models:

### Random Over Sampler
- Accuracy score: 0.6640245116653853
- Precision:
  - High Risk: 0.01
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.71
  - Low Risk: 0.62
  - Average: 0.62
![This is an image]()
### SMOTE
- Accuracy score: 0.6556413183413758
- Precision:
  - High Risk: 0.01
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.63
  - Low Risk: 0.68
  - Average: 0.68
![This is an image]()
### Cluster Centroids
- Accuracy score: 0.5447339051023905
- Precision:
  - High Risk: 0.01
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.69
  - Low Risk: 0.40
  - Average: 0.40
![This is an image]()
### SMOTEENN
- Accuracy score: 0.6477226680806527
- Precision:
  - High Risk: 0.01
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.72
  - Low Risk: 0.57
  - Average: 0.57
![This is an image]()
### Balanced Random Forest Classifier
- Accuracy score: 0.7831183024757107
- Precision:
  - High Risk: 0.03
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.68
  - Low Risk: 0.88
  - Average: 0.88
![This is an image]()
### Easy Ensemble Classifier
- Accuracy score: 0.9316600714093861
- Precision:
  - High Risk: 0.09
  - Low Risk: 1.00
  - Average: 0.99
- Recall:
  - High Risk: 0.92
  - Low Risk: 0.94
  - Average: 0.94
![This is an image]()
## Summary