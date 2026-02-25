# 📊 Customer Churn Prediction for Telecom

## 📌 Project Overview
This project predicts which telecom customers are likely to churn (leave) based on their usage and demographic data. It uses Machine Learning classification models to identify at-risk customers so the company can take action to retain them.

---

## 🏭 Industry
Telecommunications

## 📁 Dataset
- **Name:** Telco Customer Churn Dataset
- **Source:** [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **File:** `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Rows:** 7,043 customers
- **Columns:** 21 features

---

## 🛠️ Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pandas | Data manipulation |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| Seaborn | Statistical plots |
| Scikit-learn | Machine Learning models |
| Jupyter Notebook | Development environment |

---

## 📂 Project Structure
```
📦 Customer-Churn-Prediction
 ┣ 📓 Customer_Churn_Prediction.ipynb   # Main notebook
 ┣ 📊 WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dataset
 ┗ 📄 README.md                         # Project documentation

---

---


## 📋 Project Steps

| Step | Description |
|------|-------------|
| 1 | Import Libraries |
| 2 | Load Dataset |
| 3 | Clean & Encode Data |
| 4 | Exploratory Data Analysis (EDA) |
| 5 | Train Decision Tree & Gradient Boosting |
| 6 | Hyperparameter Tuning (GridSearchCV) |
| 7 | Model Evaluation (Confusion Matrix + ROC Curve) |
| 8 | Feature Importance Plot |
| 9 | Predict Single Customer Churn |

---

## 📈 Models Used
- **Decision Tree Classifier**
- **Gradient Boosting Classifier** ✅ *(Best Model)*

---

## 🎯 Key Results
- Model evaluated using **ROC AUC Score**, **Precision**, **Recall**, and **F1-Score**
- Top features identified: `tenure`, `MonthlyCharges`, `Contract type`, `TotalCharges`
- Best model selected via **GridSearchCV** with cross-validation
# 👤 Author
   HR PRASITH  
AI & ML Intern — InLighnX Global Pvt. Ltd.
