# Credit Card Fraud Detection

## Overview
This project aims to detect fraudulent transactions using machine learning on an imbalanced dataset.

## Dataset
The dataset contains credit card transactions with a strong imbalance between normal and fraudulent operations.

## Methodology
- Data exploration and analysis
- Handling class imbalance using SMOTE
- Train/test split
- Model training (Logistic Regression)
- Model evaluation

## Results
- Accuracy: ~98%
- Recall (fraud): ~90%
- Precision (fraud): low → many false positives

## Key Insight
The model detects most fraud cases but generates false positives, highlighting the trade-off in imbalanced datasets.

## Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
