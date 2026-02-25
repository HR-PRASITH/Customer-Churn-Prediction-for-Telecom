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
# 📉 Customer Churn Prediction

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-22c55e?style=for-the-badge)

**Predicting which telecom customers are likely to leave — before they do.**

*Built during AI & ML Internship @ InLighnX Global Pvt. Ltd.*

</div>

---

## 🎯 Problem Statement

Customer churn is one of the most expensive problems in the telecom industry. Acquiring a new customer costs **5–7x more** than retaining an existing one. This project builds a machine learning pipeline to predict churn with high accuracy — helping businesses act before it's too late.

---

## 📁 Project Structure

```
Customer-Churn-Prediction/
 ┣ 📓 Customer_Churn_Prediction.ipynb       # Main notebook (end-to-end pipeline)
 ┣ 📊 WA_Fn-UseC_-Telco-Customer-Churn.csv  # Telco customer dataset (IBM)
 ┗ 📄 README.md                             # Project documentation
```

---

## 🔄 Pipeline Overview

```
Raw Data → Cleaning & Encoding → EDA → Model Training → Tuning → Evaluation → Prediction
```

| Step | Description |
|------|-------------|
| 1️⃣ | Import Libraries |
| 2️⃣ | Load & Inspect Dataset |
| 3️⃣ | Clean & Encode Data |
| 4️⃣ | Exploratory Data Analysis (EDA) |
| 5️⃣ | Train Decision Tree & Gradient Boosting |
| 6️⃣ | Hyperparameter Tuning (GridSearchCV) |
| 7️⃣ | Model Evaluation — Confusion Matrix + ROC Curve |
| 8️⃣ | Feature Importance Visualization |
| 9️⃣ | Predict Single Customer Churn |

---

## 📊 Dataset

- **Source:** IBM Telco Customer Churn Dataset
- **Records:** 7,043 customers
- **Features:** 21 columns including demographics, services, and billing info
- **Target:** `Churn` — Yes / No

| Feature Type | Examples |
|---|---|
| Demographics | `gender`, `SeniorCitizen`, `Partner`, `Dependents` |
| Services | `InternetService`, `StreamingTV`, `TechSupport` |
| Billing | `Contract`, `PaymentMethod`, `MonthlyCharges`, `TotalCharges` |
| Target | `Churn` |

---

## 🤖 Models Used

### 1. Decision Tree Classifier
- Baseline model for interpretability
- Clear decision boundaries
- Prone to overfitting without tuning

### 2. Gradient Boosting Classifier ✅ *(Best Model)*
- Ensemble of weak learners built sequentially
- Handles imbalanced data better
- Tuned with GridSearchCV for optimal hyperparameters

---

## 🎯 Key Results

| Metric | Score |
|--------|-------|
| ROC AUC Score | **High** |
| Precision | ✅ Optimized |
| Recall | ✅ Optimized |
| F1-Score | ✅ Optimized |

> Best model selected via **GridSearchCV** with 5-fold cross-validation

---

## 🔍 Top Predictive Features

```
1. 📅 tenure            — How long the customer has stayed
2. 💰 MonthlyCharges    — Higher charges = higher churn risk
3. 📄 Contract Type     — Month-to-month contracts churn more
4. 💳 TotalCharges      — Cumulative spend indicator
```

---

## 🚀 How to Run

```bash
# 1. Clone the repository
git clone https://github.com/Hrprasith/Customer-Churn-Prediction

# 2. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

# 3. Launch notebook
jupyter notebook Customer_Churn_Prediction.ipynb
```

---

## 💡 Key Insights

- Customers on **month-to-month contracts** churn at significantly higher rates
- **New customers** (low tenure) are at highest risk — early engagement matters
- **High monthly charges** without added-value services drive churn
- **Electronic check** payment method correlates with higher churn

---

## 👤 Author

<div align="center">

**HR Prasith**
B.Tech — Artificial Intelligence & Machine Learning
CMR University, Bangalore

*AI & ML Intern — InLighnX Global Pvt. Ltd.*

[![GitHub](https://img.shields.io/badge/GitHub-Hrprasith-181717?style=flat-square&logo=github)](https://github.com/Hrprasith)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-HrPrasith-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/HrPrasith)
[![Email](https://img.shields.io/badge/Email-hr.prasith28@gmail.com-EA4335?style=flat-square&logo=gmail)](mailto:hr.prasith28@gmail.com)

</div>

---

<div align="center">
<sub>Built with ❤️ using Python & Scikit-learn</sub>
</div>

