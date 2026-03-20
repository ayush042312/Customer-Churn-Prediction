# 📊 Customer Churn Prediction using Machine Learning

## 🚀 Project Overview

This project aims to predict whether a customer will churn (leave the service) or not using Machine Learning techniques. Customer churn prediction helps businesses take proactive actions to retain customers and reduce revenue loss.

---

## 🎯 Objective

* Identify customers likely to churn
* Analyze key factors influencing churn
* Build a predictive model with good performance
* Improve business decision-making using data insights

---

## 📁 Dataset

* Dataset: Telco Customer Churn Dataset
* Source: Kaggle / IBM Sample Dataset
* Total Records: 7043 customers
* Features: 21 columns

---

## 🧠 Technologies Used

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* XGBoost
* Imbalanced-learn (SMOTE)

---

## 🔍 Exploratory Data Analysis (EDA)

* Analyzed distributions of tenure, MonthlyCharges, and TotalCharges
* Identified relationships between features and churn
* Visualized categorical features using count plots
* Detected important features affecting churn

---

## ⚙️ Data Preprocessing

* Removed irrelevant column: `customerID`
* Handled missing values in `TotalCharges`
* Converted categorical variables using Label Encoding
* Addressed class imbalance using SMOTE

---

## 🤖 Model Building

Models used:

* Logistic Regression
* Random Forest
* XGBoost

Techniques applied:

* Train-Test Split
* Cross Validation
* Hyperparameter Tuning using GridSearchCV

---

## 📊 Model Performance

| Metric         | Value |
| -------------- | ----- |
| Accuracy       | 78%   |
| ROC-AUC Score  | 0.83  |
| Recall (Churn) | 66%   |

---

## 📌 Key Insights

* Customers with low tenure are more likely to churn
* Higher monthly charges increase churn probability
* Contract type plays a major role in customer retention
* Class imbalance significantly affects prediction performance

---

## ⚠️ Challenges

* Imbalanced dataset (handled using SMOTE)
* Multicollinearity between features
* Improving recall for churn prediction

---

## 🚀 Future Improvements

* Improve recall using threshold tuning
* Deploy model using Flask / Streamlit
* Add real-time prediction system
* Use advanced models like LightGBM

---

## 📷 Visualizations

* Distribution plots
* Boxplots
* Correlation heatmap
* Churn vs feature graphs

---

## 💡 Conclusion

The model successfully predicts customer churn with good accuracy and ROC-AUC score. It provides valuable insights that can help businesses improve customer retention strategies.

---

## 👨‍💻 Author

**Ayush Radadiya**
BCA Student | Data Science & Machine Learning Enthusiast

---

## ⭐ If you like this project, give it a star!