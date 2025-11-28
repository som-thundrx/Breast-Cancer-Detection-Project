# 🧠 Breast Cancer Detection using Logistic Regression

This project applies **Logistic Regression** to classify tumors as **benign or malignant** using the Breast Cancer dataset. It was built in **Google Colab** using `pandas` and `scikit-learn`.

---

## 📁 Dataset

- File: `breast_cancer.csv`
- Features: Cell measurements like radius, texture, etc.
- Target: Diagnosis (Benign or Malignant)

---

## 🚀 Steps

1. Load dataset using `pandas`
2. Split into training and test sets (80/20)
3. Train using `LogisticRegression`
4. Evaluate using:
   - Confusion Matrix
   - 10-fold Cross Validation

---

## 📊 Results

- Confusion Matrix:
[[84 3]
[ 3 47]]
- Accuracy: **96.70%**
- Standard Deviation: **1.97%**
