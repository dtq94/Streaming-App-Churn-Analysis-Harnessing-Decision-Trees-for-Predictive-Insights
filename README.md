# Streaming Service Churn Analyis Harnessing Decision Trees

This project aims to predict churn in a streaming service using machine learning techniques, particularly focusing on decision tree models and addressing class imbalance using SMOTE (Synthetic Minority Over-sampling Technique). It also includes the evaluation of model performance through ROC curve analysis and confusion matrix.

## Overview

Churn prediction is crucial for businesses, especially in industries where subscription-based services are prevalent. Understanding and predicting customer churn can help businesses identify at-risk customers and take proactive measures to retain them.

In this project, we use a dataset from a streaming service containing various features related to customer behavior and demographics. We leverage decision tree models to predict churn and address **class imbalance using SMOTE**. Additionally, we evaluate model performance using **ROC curve analysis and confusion matrix**.

## Project Structure

The project is structured as follows:

- `ML_Pipeline`: Contains utility functions, data preprocessing, model training, evaluation metrics, and visualization.
  - `utils.py`: Utility functions for reading data, inspection, handling null values, etc.
  - `ml_model.py`: Functions for preparing the model with SMOTE, running the model, etc.
  - `evaluate_metrics.py`: Functions for evaluating model performance, including confusion matrix and ROC curve.
  - `feature_imp.py`: Function for plotting feature importances.
  - `plot_model.py`: Function for plotting decision tree.

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
