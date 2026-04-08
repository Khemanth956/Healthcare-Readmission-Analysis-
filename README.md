# Healthcare-Readmission-Analysis-
# Hospital-Readmission-Analysis
This project analyzes hospital readmission rates using two different machine learning models: Logistic Regression and Random Forest. The goal is to predict whether a patient will be readmitted to the hospital based on various features in the dataset.

## Data

The original data is provided in an Excel file. The dataset includes features such as patient demographics, hospital admission details, medical history, and treatment information.

## Models

Two models were trained and evaluated:
1. **Logistic Regression**
2. **Random Forest**

### Logistic Regression Model

**Performance Metrics:**
- **Precision:**
  - Class 0: 0.98
  - Class 1: 0.76
- **Recall:**
  - Class 0: 0.84
  - Class 1: 0.96
- **F1-Score:**
  - Class 0: 0.90
  - Class 1: 0.85
- **Accuracy:** 0.88
- **ROC AUC Score:** 0.929

### Random Forest Model

**Performance Metrics:**
- **Precision:**
  - Class 0: 0.99
  - Class 1: 0.76
- **Recall:**
  - Class 0: 0.83
  - Class 1: 0.98
- **F1-Score:**
  - Class 0: 0.90
  - Class 1: 0.86
- **Accuracy:** 0.89
- **ROC AUC Score:** 0.922

Both models perform well in predicting hospital readmissions.
