# Breast Cancer Prediction

This project builds a Logistic Regression model to classify breast tumors as **malignant** or **benign** using the Breast Cancer Wisconsin dataset (from `sklearn`).

## Dataset
- Source: `sklearn.datasets.load_breast_cancer()`
- Features: 30 numeric features
- Dataset shape: 569 samples × 30 features
- Train / Test split: 455 samples (train), 114 samples (test) — ≈ 80 / 20

## Preprocessing
- The notebook loads the sklearn dataset and converts it to a DataFrame.

## Model
- Algorithm: **Logistic Regression** (scikit-learn)

## Results
- Training accuracy: **0.9494505494505494** (~94.95%)
- Test accuracy: **0.9298245614035088** (~92.98%)
