# 🌟Heart Disease Prediction🌟
***Heart Disease Prediction: Exploratory Data Analysis & Classification***

## Overview
This project focuses on building a system to predict heart disease using patient vital data. It involves comprehensive Exploratory Data Analysis (EDA) to understand the dataset, followed by the application of various classification algorithms to build a predictive model. The ultimate goal is to provide a reliable tool for detecting heart disease.

## Dataset
The dataset used in this project is heart_statlog_cleveland_hungary_final.csv, which contains patient vitals and heart disease status.

***Source:*** The dataset is loaded from /kaggle/input/heart-disease-dataset/heart_statlog_cleveland_hungary_final.csv.

***Initial Shape:*** The raw dataset contains 1190 rows and 12 columns.

***Target Variable:*** The target column indicates the presence (1) or absence (0) of heart disease.

## Exploratory Data Analysis (EDA)
The EDA section focused on understanding the dataset's characteristics and preparing it for modeling:

***Missing Values:*** Checked for missing values and confirmed that there are none in the dataset.

***Duplicate Rows:*** Identified and removed 272 duplicate rows from the dataset, resulting in a clean dataset of 918 unique entries.

***Data Types:*** All columns are numerical (int64 or float64), simplifying preprocessing steps related to categorical encoding.

***Unique Values:*** Explored the number of unique values for each feature to understand their cardinality.

***Statistical Description:*** Provided descriptive statistics for all numerical columns to understand their distribution, central tendency, and spread.

***Visualizations:*** The notebook uses seaborn, plotly.express, and matplotlib.pyplot for various visualizations to understand data distributions and relationships between features.


## Data Preprocessing
The primary preprocessing steps involved:

***Duplicate Removal:*** Ensured data integrity by removing duplicate entries.

***Feature and Target Separation:*** The features (X) and the target variable (target, y) are separated for model training.

***Train-Test Split:*** The dataset is split into training and testing sets to evaluate model performance on unseen data.


## Classification Models
The notebook implements and evaluates various machine learning classification models to predict heart disease:

The models used include:
🪄Logistic Regression

🪄K-Nearest Neighbors (KNN)

🪄Support Vector Machine (SVM)

🪄Decision Tree

🪄Random Forest

🪄Gradient Boosting

🪄LightGBM

🪄XGBoost

## Results
The performance of each classification model is evaluated and compared. The notebook includes metrics such as accuracy, and potentially precision, recall, F1-score, and confusion matrices to assess the models' effectiveness in predicting heart disease. The feature importance for LightGBM is also visualized, indicating the most influential factors in its predictions.

## Dependencies
⚡numpy

⚡pandas

⚡seaborn

⚡plotly.express

⚡matplotlib.pyplot

⚡scikit-learn

⚡xgboost

⚡lightgbm
