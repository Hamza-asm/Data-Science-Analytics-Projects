# Task 3: Fraud Detection System

## Overview

This notebook develops a fraud detection classifier to identify fraudulent transactions in a transactional dataset.

## Project Steps

### Data Loading: Read transaction data with features like amount, time, and user information.

### Data Preprocessing:

Handle missing values and outliers.

Encode categorical features (e.g., one-hot encoding).

Address class imbalance using techniques like SMOTE or undersampling.

### Model Implementation (Scratch):

Build Decision Tree and Random Forest classifiers from scratch.

### Model Training & Evaluation:

Train/test split with stratification.

### Compute metrics: accuracy, precision, recall, F1-score, ROC-AUC.

### Visualization:

Confusion matrix heatmap.

ROC curve.

Feature importance bar chart.

## How to Run

Open TASK 3 Fraud Detection System.ipynb in Jupyter.

Install dependencies:

pip install pandas numpy matplotlib scikit-learn imbalanced-learn

Run through the notebook cells sequentially.

## Observations

High class imbalance: majority of transactions are non-fraudulent.

Undersampling/oversampling improved recall on the fraud class.

Top features influencing fraud predictions include transaction amount and time of day.
