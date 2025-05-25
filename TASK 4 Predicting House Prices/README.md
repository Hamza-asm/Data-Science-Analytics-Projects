# Task 4: Boston Housing Price Prediction

## Overview

This notebook implements regression models from scratch to predict Boston housing prices using features like average rooms (RM), lower status percentage (LSTAT), and pupil-teacher ratio (PTRATIO).

## Project Steps

### Data Loading: Load the Boston housing CSV.

### Data Preprocessing:

Train/test split.

Standardize numerical features with a custom scaler.

### Model Implementation (Scratch):

Linear Regression via gradient descent.

Random Forest: bootstrap aggregating of decision trees.

XGBoost-like Gradient Boosting: sequential trees on residuals.

Model Training & Evaluation:

Fit each model on training data.

Predict on test data.

Compute RMSE and R² for each.

### Feature Importance:

Count split frequencies in tree-based models.

Visualize relative importance via bar charts.

## How to Run

Open Boston Houseing Dataset.ipynb in Jupyter.

Install dependencies:

```pip install pandas numpy matplotlib```

Execute cells in order.

## Observations

Linear Regression converges with moderate error but underfits non-linear patterns.

Random Forest reduces RMSE and improves R² by capturing interactions.

Gradient Boosting further refines predictions with lowest RMSE.

Most important feature: % lower status (LSTAT) consistently has the highest split frequency.
