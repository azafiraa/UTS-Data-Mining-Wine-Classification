# # Wine Quality Prediction Project

## **About The Project**
This project was created to fulfill the Mid-Term Examination (UTS) assignment for the Data Mining course.
The main objective of this project is to build a machine learning classification model capable of predicting wine quality based on physicochemical characteristics contained in the Wine Quality dataset.
The analysis process includes data preprocessing, exploratory data analysis, feature scaling, classification modeling, model evaluation, and prediction generation on unseen testing data.

## **Dataset Information**
The dataset used in this project consists of physicochemical properties of wine samples, including several numerical attributes such as:
- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol

The target variable predicted in this project is:

**Quality** → wine quality score

## **Project Workflow**
**1. Data Understanding**
   - Loading training and testing datasets
   - Checking dataset structure
   - Displaying statistical summaries
   - Identifying feature information

**2. Data Preprocessing**
   - Missing value checking
   - Duplicate data handling
   - Data cleaning
   - Feature scaling using StandardScaler

**3. Exploratory Data Analysis (EDA)**
   - Distribution analysis of wine quality
   - Correlation analysis between variables
   - Heatmap visualization

**4. Machine Learning Classification**
   
   Several classification algorithms were implemented and compared, including:
   - Logistic Regression
   - K-Nearest Neighbor (KNN)
   - Decision Tree
   - Random Forest

**5. Model Evaluation**
   
   The performance of each model was evaluated using:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report

**7. Prediction and Export**
   
   The best-performing model was used to predict wine quality on the testing dataset.
   
   Prediction results were exported into:
   - CSV format
   - XLSX format

## **Technologies and Libraries**
This project was developed using:
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

## **Output**
The final output of this project is a prediction file containing:
- Id
- Quality

which is generated from the trained machine learning classification model.

## **Repository Contents**
This repository contains:
- Jupyter/Google Colab Notebook
- Prediction Results (.csv)
- Prediction Results (.xlsx)
- Documentation and analysis workflow

## **Author**
UTS Data Mining Project – Mathematics Education Study Program

Zafira Anwar - Universitas Negeri Semarang
