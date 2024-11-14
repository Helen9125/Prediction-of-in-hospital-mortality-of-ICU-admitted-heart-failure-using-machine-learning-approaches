# Prediction-of-in-hospital-mortality-of-ICU-admitted-heart-failure-using-machine-learning-approaches

## Introduction
* 10% of heart failure (HF) patients were admitted to ICU in the overall hospital-admitted population.
* ICU-admitted HF patients are usually with more complex disease states and relate to a higher mortality rate of around 3.5%

## Purpose
This project aims to build a machine learning model for the in hospital mortality of ICU-admitted-heart-failure and identity factors mainly contribute to survival status.

## Methods
* Data Preprocessing
  - Data cleaning: Delete cases with missing data > 25% or none outcome.
  - Missing value: median imputationedian and min-max scaling.
  - Oversampling: SMOTE
* Models for mortality prediction
  - Random forest classifier (RFC)/ Random forest regression (RFR)
  - Simple vector classifier (SVC)/ Simple vector regression (RFR)
* Feature importance
  - SHAP for analysis and visualization

## Results
* ROC
![image](https://github.com/user-attachments/assets/df29fa0f-fafb-4065-9cff-73ce339a257d)
* Feature importance for random forest models
![image](https://github.com/user-attachments/assets/82656cf8-e118-4d49-9c08-d08e2b08f84c)

## Conclusions
* The values of auroc were over 70% but unable to exceed 80%.
* One of the reasons might be unsuitable models.
* The other reason might be that the features had already been selected by the project from Kaggle.
* The dimension reduction had been tried without better outcomes.
* Origin data was better than selected data on building a model for predicting in-hospital mortality of ICU-admitted heart failure.
* SVR had the best AUROC.
* Random forest models had the best accuracy.
