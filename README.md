# 🧬 ONCO PREDICT – Comprehensive Lung Cancer Prediction System

## 📌 Project Overview

ONCO PREDICT is a machine learning–driven cancer prognosis and analysis system designed to help in the early detection of lung cancer by analyzing patient health data and risk indicators such as age, smoking habits, alcohol consumption, and associated clinical symptoms. The project applies multiple classification algorithms and compares their performance to identify the most accurate model for cancer prediction.

---

## 🎯 Objectives

* Predict lung cancer with high accuracy using machine learning.
* Compare different classification algorithms.
* Analyze the most influential risk factors.
* Improve reliability using preprocessing and feature selection.
* Build a framework expandable to genomic and real-time healthcare data.

---

## 📊 Dataset

* Source: Kaggle Lung Cancer Dataset
* Features include:

  * Demographics: Age, Gender
  * Habits: Smoking, Alcohol Consumption
  * Medical conditions: Chronic Disease, Anxiety
  * Symptoms: Wheezing, Chest Pain, Shortness of Breath
* Target Variable: LUNG_CANCER (YES / NO)

---

## 🔧 Data Preprocessing

* Handled missing values
* Encoded categorical variables
* Normalized numerical data
* Removed noisy and irrelevant features
* Handled class imbalance
* Split data into training and testing sets

---

## 📈 Exploratory Data Analysis (EDA)

* Distribution of lung cancer cases
* Analysis by age group
* Behavioral risk factors (smoking, alcohol)
* Visualization using charts and plots

---

## 🤖 Machine Learning Models Implemented

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree
* Naive Bayes
* Support Vector Machine (Best performer)

---

## 📏 Model Evaluation

Metrics used:

* Accuracy
* Precision
* Recall
* F1 Score

Best Result:
✅ SVM achieved up to **94.7% accuracy** after feature selection.

---

## 🧪 Results & Observations

* Smoking and age are strong indicators of lung cancer risk.
* Feature selection improves model accuracy.
* SVM is more reliable for this dataset compared to other models.
* Preprocessing has a major impact on results.

---

## 🛠 Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Matplotlib / Seaborn
* Jupyter Notebook

---

## 🚀 Future Enhancements

* Add genomic and imaging data
* Implement deep learning models
* Real-time prediction system
* Deploy using Flask / Streamlit
* Build ensemble models
