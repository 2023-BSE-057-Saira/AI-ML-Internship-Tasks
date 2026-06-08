# Task 03: Heart Disease Prediction Using Machine Learning

## Problem Statement

Heart disease is one of the leading causes of death worldwide. Early detection and prediction of heart disease can help healthcare professionals take preventive measures and improve patient outcomes. This project uses machine learning techniques to predict whether a person is at risk of heart disease based on their medical and clinical attributes.

---

## Objective

The objective of this project is to build a classification model that predicts the presence of heart disease using patient health data and to identify the factors that contribute most to the prediction.

---

## Dataset

**Dataset:** Heart Disease UCI Dataset

**Source:** Kaggle

The dataset contains medical information collected from patients, including demographic, clinical, and laboratory measurements.

### Features Included

* Age
* Sex
* Chest Pain Type (cp)
* Resting Blood Pressure (trestbps)
* Cholesterol Level (chol)
* Fasting Blood Sugar (fbs)
* Resting ECG Results (restecg)
* Maximum Heart Rate Achieved (thalch)
* Exercise-Induced Angina (exang)
* ST Depression (oldpeak)
* Slope of Peak Exercise ST Segment (slope)
* Number of Major Vessels (ca)
* Thalassemia (thal)

### Target Variable

* 0 = No Heart Disease
* 1 = Heart Disease Present

---

## Project Workflow

### 1. Data Loading

The Heart Disease UCI dataset was loaded into a Pandas DataFrame for analysis and preprocessing.

### 2. Data Preprocessing

The following preprocessing steps were performed:

* Examined dataset structure and data types
* Identified missing values
* Filled missing numerical values using median imputation
* Filled missing categorical values using mode imputation
* Converted categorical variables into numerical format using Label Encoding
* Created a binary target variable for classification

### 3. Exploratory Data Analysis (EDA)

Several visualizations were created to understand the dataset and identify trends:

* Heart Disease Distribution
* Age Distribution
* Correlation Heatmap
* Feature Relationships

### 4. Model Development

A Logistic Regression model was trained to classify patients into heart disease and non-heart disease categories.

### Training Configuration

* Training Data: 80%
* Testing Data: 20%
* Random State: 42

### 5. Model Evaluation

The model was evaluated using:

* Accuracy Score
* Confusion Matrix
* Classification Report
* ROC Curve
* ROC-AUC Score

### 6. Feature Importance Analysis

Feature coefficients from Logistic Regression were analyzed to identify the most influential factors affecting heart disease prediction.

---

## Results

The Logistic Regression model successfully classified patients based on their medical information and achieved strong predictive performance.

The ROC curve demonstrated the model's ability to distinguish between patients with and without heart disease, while the confusion matrix provided detailed insight into prediction accuracy.

Feature importance analysis highlighted the medical factors that contribute most significantly to heart disease risk.

---

## Key Findings

* Machine learning can effectively assist in heart disease prediction.
* Clinical indicators such as chest pain type, age, cholesterol levels, maximum heart rate, and exercise-induced angina have a significant impact on prediction outcomes.
* Logistic Regression provides a simple and interpretable approach for medical classification problems.
* Proper preprocessing and handling of missing values improve model reliability.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Files Included

* Heart_Disease_Prediction.ipynb
* heart_disease_uci.csv
* README.md

---

## Learning Outcomes

Through this project, the following skills were developed:

* Medical data analysis
* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Binary classification
* Logistic Regression modeling
* Model evaluation using ROC-AUC and confusion matrix
* Feature importance interpretation

---

## Conclusion

This project demonstrates the application of machine learning in healthcare for predicting heart disease risk. The developed model provides valuable insights into important health indicators and showcases how data-driven approaches can support early diagnosis and decision-making in medical settings.

---

## Author

Saira Ejaz


