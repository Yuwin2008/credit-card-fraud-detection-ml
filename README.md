#  Credit Card Fraud Detection using Machine Learning

> Detecting fraudulent credit card transactions using supervised machine learning and evaluating multiple classification algorithms on a highly imbalanced dataset.

---

![Python](https://img.shields.io/badge/Python-3.12-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-green)

---

##  Project Overview

Credit card fraud detection is a real-world binary classification problem where fraudulent transactions represent only a tiny fraction of all transactions. The objective of this project is to build and compare multiple machine learning models capable of identifying fraudulent transactions while minimizing false negatives.

Since the dataset is highly imbalanced, model performance is evaluated using **Precision**, **Recall**, **F1 Score**, and **Cross Validation** rather than relying solely on Accuracy.

---

##  Objectives

* Perform Exploratory Data Analysis (EDA)
* Clean and preprocess the dataset
* Handle severe class imbalance
* Train multiple machine learning models
* Compare model performance using appropriate evaluation metrics
* Perform hyperparameter tuning
* Select the best-performing model

---

##  Dataset

* **Source:** Kaggle – Credit Card Fraud Detection Dataset
* **Total Transactions:** 284,807
* **Fraudulent Transactions:** 492 (~0.17%)
* **Features:** 30 numerical features + Target
* **Target Variable:**

  * **0** → Legitimate Transaction
  * **1** → Fraudulent Transaction

Most features are anonymized using **Principal Component Analysis (PCA)**.

---

##  Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

##  Project Workflow

* Data Loading
* Exploratory Data Analysis
* Missing Value Check
* Duplicate Removal
* Class Distribution Analysis
* Train-Test Split
* Model Training
* Hyperparameter Tuning
* Cross Validation
* Model Evaluation
* Model Comparison

---

##  Models Implemented

* Decision Tree Classifier
* Logistic Regression
* Linear Support Vector Classifier (LinearSVC)
* Random Forest Classifier

---

##  Evaluation Metrics

Since fraud detection is an imbalanced classification problem, the following metrics were used:

* Accuracy
* Precision
* Recall
* F1 Score
* Cross Validation (Mean F1 Score)

---

##  Best Performing Model

**Random Forest Classifier**

After hyperparameter tuning and cross-validation, Random Forest achieved the strongest balance between Precision and Recall, resulting in the highest overall F1 Score.

---

##  Repository Structure

credit-card-fraud-detection/
│
├── notebooks/
│   └── credit_card_fraud_detection.ipynb
│
├── images/
│   ├── class_distribution.png
│   ├── confusion_matrix_rf.png
│   ├── confusion_matrix_decision_tree.png
│   ├── confusion_matrix_linear_svc.png
│   ├── confusion_matrix_log_reg.png
│   └── model_comparison.png
│
├── README.md
├── requirements.txt
├── LICENSE
└── dataset_link.txt

---

##  Future Improvements

* XGBoost
* LightGBM
* CatBoost
* Stacking Classifier
* Threshold Optimization
* SHAP Explainability
* SMOTE for handling class imbalance

---

##  Key Learning Outcomes

This project demonstrates practical experience with:

* Binary Classification
* Data Preprocessing
* Handling Imbalanced Datasets
* Model Evaluation
* Cross Validation
* Hyperparameter Tuning
* Ensemble Learning
* Machine Learning Workflow

---

##  Connect With Me

If you have suggestions or feedback, feel free to connect or open an issue.

If you found this project useful, consider giving the repository a star!
