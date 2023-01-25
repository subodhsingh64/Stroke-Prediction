
## Stock Prediction Project
## Problem Statement:
According to the World Health Organization (WHO), stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths. It is another health issue that has found to be rising throughout the world due to the adoption of lifestyle changes that disregards healthy lifestyle & good eating habits. Thus, new emerging electronic devices that record the health vitals have paved the way for creating an automated solution with AI techniques at it's core. Thus, similar to heart diseases, efforts have begun to create lab tests that predict stroke. The dataset presented here has many factors that highlight the lifestyle of the patients and hence gives us an opportunity to create an AI-based solution for it.

## Aim:
To classify / predict whether a patient can suffer a stroke. It is a binary classification problem with multiple numerical and categorical features.

## Dataset Attributes
- id : unique identifier
- gender : "Male", "Female" or "Other"
- age : age of the patient
- hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
- heart_disease : 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
- ever_married : "No" or "Yes"
- work_type : "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
- Residence_type : "Rural" or "Urban"
- avg_glucose_level : average glucose level in blood
- bmi : body mass index
- smoking_status : "formerly smoked", "never smoked", "smokes" or "Unknown"*
- stroke : 1 if the patient had a stroke or 0 if not

## Library used
sklearn pandas numpy seaborn matplotlib
## Method used
Exploratory Data Analysis:
 - Missing Value Imputation 
 - Droping duplicates and columns
- coversion categorical data into numeric
- Standardization of Data using MinmaxScaler
- Splitting the credit_approval_data into training and testing sets
- Model Building using Logistic Regression
- Making predictions and evaluating performance of model using Accuracy Score
