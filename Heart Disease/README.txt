Heart Disease Prediction Project - README


---

Project Overview

This project aims to predict the likelihood of heart disease in patients using machine learning. By analyzing a dataset of patient health metrics, the project builds a model to classify individuals as having heart disease or not. The model is deployed as a REST API to allow real-time predictions.


---

Project Workflow

1. Data Collection

Dataset used: Heart Disease UCI Dataset.

Contains 303 records with 14 features such as age, cholesterol levels, and chest pain type.



2. Exploratory Data Analysis (EDA)

Performed data visualization to understand feature distributions and correlations.

Tools used: Matplotlib, Seaborn.



3. Data Preprocessing

Handled missing values and outliers.

Normalized numerical features for better model performance.

Encoded categorical features.



4. Model Building

Algorithm used: Logistic Regression.

Achieved an accuracy of 85% on the test dataset.



5. Model Deployment

Built a REST API using Flask for prediction.

Endpoint /predict accepts patient data and returns the heart disease prediction.