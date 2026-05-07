# Credit Card Fraud Detection using Machine Learning

## Project Overview

This project detects fraudulent credit card transactions using Machine Learning algorithms.

The model is trained on transaction data to classify whether a transaction is:
- Legitimate Transaction (`0`)
- Fraudulent Transaction (`1`)

Fraud detection is an important real-world banking and financial security application.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## Dataset Information

Dataset contains anonymized transaction features:
- `V1` to `V28`
- `Time`
- `Amount`
- `Class` (Target)

### Target Column

| Value | Meaning |
|---|---|
| 0 | Normal Transaction |
| 1 | Fraud Transaction |

---

## Workflow

### 1. Data Collection
- Loaded credit card transaction dataset

### 2. Data Preprocessing
- Checked missing values
- Analyzed class imbalance
- Split features and target

### 3. Train-Test Split
- Divided dataset into training and testing data

### 4. Model Training
Implemented:
- Logistic Regression

### 5. Model Evaluation
Evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## Model Performance

| Metric | Score |
|---|---|
| Training Accuracy | 98.50% |
| Testing Accuracy | 98.52% |

The model achieved high accuracy in detecting fraudulent transactions.

---

## Libraries Used

```python
import pandas as pd
import numpy as np
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score
