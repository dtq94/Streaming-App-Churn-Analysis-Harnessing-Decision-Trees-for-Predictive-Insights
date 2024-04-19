# Streaming Service Churn Analyis Harnessing Decision Trees

This project aims to predict churn in a streaming service using machine learning techniques, particularly focusing on decision tree models and addressing class imbalance using ```SMOTE (Synthetic Minority Over-sampling Technique)```. It also includes the evaluation of model performance through ```ROC curve analysis and confusion matrix```.

## Overview

Churn prediction is crucial for businesses, especially in industries where subscription-based services are prevalent. Understanding and predicting customer churn can help businesses identify at-risk customers and take proactive measures to retain them.

In this project, we use a dataset from a streaming service containing various features related to customer behavior and demographics. We leverage decision tree models to predict churn and address **class imbalance using SMOTE**. Additionally, we evaluate model performance using **ROC curve analysis and confusion matrix**.

## Approach
### 1. Data Preparation:
- Imported necessary libraries and read the dataset.

### 2. Feature Engineering:
- Dropped irrelevant columns from the dataset.

### 3. Model Building:
- Split the dataset into training and testing sets.
- Trained a Decision Tree model to predict churn.

### 4. Model Validation:
- Evaluated model performance using:
  - Accuracy
  - Confusion Matrix
  - ROC Curve
  - Recall
  - Precision
  - F1-score

### 5. Feature Importance:
- Identified important features using the Decision Tree model.
- Plotted feature importance to understand their impact on churn prediction.

## Requirements

- Python 3.x
- scikit-learn
- imbalanced-learn
- pandas
- matplotlib

## Project Structure
```
|-- InputFiles
    -- data_set.csv
|-- SourceFolder
    |-- ML_Pipeline
        -- ml_model.py
        -- feature_imp.py
        -- utils.py
        -- plot_model.py
        -- evaluate_metrics.py
    |-- Engine.py
