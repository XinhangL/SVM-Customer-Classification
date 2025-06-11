# 🏦 Customer Classification using SVM (Universal Bank Dataset)

This notebook uses a Support Vector Machine (SVM) classifier to predict whether a customer will subscribe to a personal loan product, based on demographic and financial information.

---

## 📌 Project Overview

- **Dataset**: Universal Bank Marketing Data (`UniversalBank.csv`)
- **Objective**: Predict customer response to a personal loan campaign
- **Model**: Support Vector Classifier (SVC) using RBF kernel
- **Focus**: Data preparation, scaling, training/testing split, cross-validation

---

## 🧠 Key Techniques

- Data preprocessing with `pandas`
- Feature extraction from selected columns (columns 1–12)
- Standardization with `StandardScaler`
- Binary classification using `sklearn.svm.SVC`
- Performance evaluation using accuracy and `classification_report`
- 10-fold Cross-validation with `cross_val_score`

---

## 📁 Files

| File                          | Description                          |
|-------------------------------|--------------------------------------|
| `Script SVM UniversalBank.ipynb` | Main notebook                        |
| `UniversalBank.csv`           | Input dataset                        |
| `README.md`                   | Project overview and instructions    |

---

## 🚀 How to Run

1. Make sure `UniversalBank.csv` is in the same folder as the notebook
2. Open the notebook in Jupyter or VS Code
3. Run all cells to train the model and view evaluation metrics

---

## 📈 Outputs

- SVM model predictions on test data
- Accuracy scores from 10-fold cross-validation
- Classification report (precision, recall, F1-score)

---

## 🧰 Tools Used

- Python 3.x
- pandas, numpy
- scikit-learn (SVC, StandardScaler, cross_val_score)

---

This notebook showcases my ability to apply supervised learning to a real-world financial dataset with effective model training and validation techniques.
