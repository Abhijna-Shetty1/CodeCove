Credit Card Fraud Detection Project

---

Introduction

This project aims to detect fraudulent credit card transactions using machine learning techniques. The goal is to build a reliable model that identifies fraud while minimizing false alarms.


---

Dataset

Source: Kaggle Credit Card Fraud Dataset

Size: 284,807 transactions, with 492 fraudulent transactions (highly imbalanced).

Features: 30 columns, including anonymized principal components (V1 to V28), Time, and Amount.

Target: Class (0 = Legitimate, 1 = Fraudulent).



---

Steps Involved

1. Data Preprocessing:

Normalized Amount and Time columns.

Addressed class imbalance using SMOTE (Synthetic Minority Oversampling Technique).



2. Exploratory Data Analysis (EDA):

Visualized fraud patterns (e.g., amount distribution, time analysis).

Highlighted correlations using heatmaps.



3. Model Training and Evaluation:

Models used: Logistic Regression, Decision Tree, Random Forest, XGBoost.

Metrics: Accuracy, Precision, Recall, F1-Score, AUC-ROC.





---

Key Results


---

Data Visualizations

1. Class imbalance (pie chart).


2. Fraud vs. Non-Fraud transaction amounts (boxplot).


3. Transaction time patterns (KDE plot).


4. Fraud percentage by transaction amount range (bar chart).


5. Feature importance (bar plot).
6.