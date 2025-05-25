# Task 2: Text Sentiment Analysis

## Overview

This notebook builds a sentiment analysis pipeline to classify text data (e.g., reviews, tweets) into positive, negative, or neutral categories.

## Project Steps

Data Loading: Import textual dataset (CSV/JSON).

### Text Preprocessing:

Lowercasing, removal of punctuation and stop words.

Tokenization and optional lemmatization/stemming.

### Feature Extraction:

Convert text to numerical features using TF-IDF or Bag-of-Words.

### Model Implementation (Scratch):

Implement Naive Bayes and Logistic Regression from scratch.

### Model Training & Evaluation:

Split data into train/test sets.

Train models and predict on the test set.

Evaluate using accuracy, precision, recall, F1-score.

### Visualization:

Confusion matrix heatmap.

ROC and Precision-Recall curves.

## How to Run

Open TASK 2 Text Sentiment Analysis.ipynb in Jupyter.

Install dependencies:

```pip install pandas numpy matplotlib scikit-learn```  

Execute each cell in order.

## Observations

Data imbalance issues observed in class distribution.

Naive Bayes performs well on short texts; Logistic Regression yields higher precision on longer texts.

Common misclassifications identified via confusion matrix (e.g., neutral vs. positive).
