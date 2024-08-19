# CodeAlpha_Disease_Prediction_from_Medical_Data
Code Alpha "Machine Learning" Internship Task

This project aims to predict medical diseases using various machine learning models and data preprocessing techniques. The project involves data cleaning, feature engineering, model training, and evaluation. The results are visualized using plots to better understand the performance of the models.

# Project Overview
This project focuses on predicting diseases from medical data using machine learning techniques. The goal is to preprocess the data, select the best features, and apply various classifiers to make accurate predictions.

## Requirements
The project requires the following libraries:

1. Python 3.x
2. pandas
3. matplotlib
4. seaborn
4. scikit-learn
5. xgboost

# Data
The dataset used in this project is sourced from the Heart Disease Data (https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data) on Kaggle. This dataset contains a range of medical information about patients, which is used to predict the likelihood of heart disease.

## Dataset Description
The dataset includes 14 attributes that capture demographic, clinical, and laboratory information about patients. The target variable is the presence or absence of heart disease. Below is a brief description of the features:

1. **Age:** The age of the patient.
2. **Sex:** Gender of the patient (1 = male; 0 = female).
3. **Chest Pain Type (cp):** Type of chest pain experienced by the patient, categorized into four types:
   * 0: Typical angina
   * 1: Atypical angina
   * 2: Non-anginal pain
   * 3: Asymptomatic
4. **Resting Blood Pressure (trestbps):** The resting blood pressure in mm Hg.
5. **Cholesterol (chol):** Serum cholesterol in mg/dl.
6. **Fasting Blood Sugar (fbs):** Fasting blood sugar > 120 mg/dl (1 = true; 0 = false).
7. **Resting ECG (restecg):** Resting electrocardiographic results:
   * 0: Normal
   * 1: Having ST-T wave abnormality
   * 2: Showing probable or definite left ventricular hypertrophy.
8. **Maximum Heart Rate Achieved (thalach):** The maximum heart rate achieved during physical activity. Exercise-Induced Angina (exang): Exercise-induced angina (1 = yes; 0 = no).
9. **ST Depression (oldpeak):** Depression induced by exercise relative to rest.
10. **Slope:** The slope of the peak exercise ST segment:
    * 0: Upsloping
    * 1: Flat
    * 2: Downsloping
11. **Number of Major Vessels (ca):** Number of major blood vessels (0–3) colored by fluoroscopy.
12. **Thalassemia (thal):** A blood disorder status (1 = normal; 2 = fixed defect; 3 = reversible defect).
13. **Target:** The presence of heart disease (1 = disease; 0 = no disease).

## Dataset Usage
The dataset was used for the following purposes:

1. **Exploratory Data Analysis (EDA):** To understand the distribution of features, detect outliers, and examine relationships between features.
2. **Data Preprocessing:** Handling missing values, encoding categorical variables, and feature scaling to prepare the data for model training.
3. **Model Training:** Using the dataset to train various machine learning models to predict the likelihood of heart disease based on the provided attributes.


# Code:
1. **Data Loading and Exploration:** Loading the dataset and performing basic exploratory data analysis (EDA) to understand the data structure.
2. **Data Preprocessing:** Handling missing data, encoding categorical variables, and feature scaling.
3. **Model Training:** Training various machine learning models, including Logistic Regression, Decision Trees, Random Forest, and XGBoost.
4. **Model Evaluation:** Evaluating the models using accuracy, confusion matrix, and other relevant metrics.
5. **Visualization:** Visualizing the results using plots to compare the performance of different models.

# Models Used
XGBoost Classifier

# Results
The models were evaluated based on their accuracy, precision, recall, F1-score, and other relevant metrics. The Random Forest and XGBoost classifiers provided the best performance in this project.


