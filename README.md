# 💳 German Credit Risk Analysis

This capstone project focuses on predicting credit risk based on demographic and financial attributes using machine learning models. The project includes preprocessing, visualization, model evaluation, and hyperparameter tuning.

---

## 📌 Objective

To classify whether a person is a credit risk based on various attributes such as age, job type, housing status, credit amount, duration, and purpose of loan using models like Random Forest, SVC, Logistic Regression, and AdaBoost.

---

## 📊 Dataset Features

- Age, Sex
- Job Type
- Housing (own, rent, free)
- Saving & Checking accounts
- Credit amount & Duration
- Loan Purpose

Target: Credit risk classification (Good/Bad)

---

## 🔍 Workflow

### 📋 Data Preprocessing
- Handled null values
- One-hot encoding for 'Purpose'
- Label encoding for categorical columns
- Feature scaling

### 📈 Data Visualization
- Correlation heatmap
- Bar plots and count plots for categorical analysis

### 🧠 Models Used
- Logistic Regression
- Random Forest (with GridSearchCV for tuning)
- Support Vector Machine (SVC)
- AdaBoost Classifier

### 🧪 Evaluation Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross-Validation Scores

---

## 🧰 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/BasilBiju1217/german-credit-risk-analysis.git
   cd german-credit-risk-analysis
