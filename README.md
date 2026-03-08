# Costumer-Churn-Classification
### Background

This project is part of the Tripleten data science practium. Focuses of the project is classification moeling for prediciton of client churn.

## Project Description

This project is tasked with building a classifier model for prediction of client churn using gradient boosting libraries. Factors to consider for project:
- Quality of prediction.
- Time required for training.

## Data

Four available datasets:

`contract.csv` - client contact information

`personal.csv` - client personal data

`internet.csv` - information regarding internet services

`phone.csv` - information about telephone services

Data sets were merged into one containing all revelant features.

**Evaluation metrics:** ROC-AUC, Accuracy, F1 score, average precision score

**Models evaluated:** LogisticRegression, RandomForestClassifier, CatBoostClassifier, XGBClassifier, LightGBMClassifier

## Conclussion report

Training of different boosting models appeared to show no considerable difference from logistic regression, however based on over all highest scores, CatBoost algorithm appears to be best suited for customer churn prediction. 
Testing data evaluation results:

Accuracy: 0.72

F1 score: 0.60

Average precision score: 0.61

ROC-AUC: 0.81

## Software

**Tools:** _python_, _jupyter_

**Libraries:** _pandas_, ,_matplotlib_, _NumPy_, _sklearn_, _LightGBM_, _XGBoost_, __CatBoost_
