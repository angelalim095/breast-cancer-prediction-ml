# Breast Cancer Prediction using Machine Learning

## Project Overview
This project builds a machine learning classification model to predict whether a breast tumour is malignant (cancerous) or benign (non-cancerous) based on cell nucleus measurements.

The goal is to demonstrate end-to-end data analysis skills:
- Data Loading & Initial Exploration
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Preprocessing
- Model Training & Comparison
- Model Evaluation
- Feature Importance & Clinical Insights
- Threshold Tuning to Improve Recall
- ROC Curve & AUC Score

---

## Dataset
- Source: UCI Breast Cancer Wisconsin (Diagnostic)
- Features: 30 numerical features computed from digitized images of a breast mass
- Target:
  - M = Malignant
  - B = Benign

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Loading
- Imported dataset and inspected structure

### 2. Data Cleaning
- Dropped unnecessary columns 
- Checked for missing values

### 3. Exploratory Data Analysis (EDA)
- Class distribution visualization
- Feature means and distribution
- Correlation heatmap

### 4. Data Preprocessing
- Encoding target variable (M → 1, B → 0)
- Feature scaling (StandardScaler)

### 5. Model Building
Models used:
- Random Forest 

### 6. Model Evaluation
- Accuracy score
- Confusion matrix
- Classification report

---

## Results
- Model successfully distinguishes malignant vs benign cases
- Achieved high accuracy, recall and AUC in predicting tumor classification
- Accuracy = 97.37%
- Recall = 92.86%
- AUC = 99.29%
