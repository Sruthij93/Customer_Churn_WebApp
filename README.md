
# Bank Customer Churn Prediction

This project is part of my work as a Software Engineering Resident in the Headstarter Accelerator program. 
It aims to predict customer churn using a Kaggle dataset of bank customers by analysing customer behavior and building machine learning models that accurately predict whether a customer is likely to leave the bank (churn).

## Project Overview

This project executes different machine learning models for churn prediction.

### Dataset

I used a publicly available dataset from Kaggle, containing bank customer data with features like customer age, account balance, tenure, and whether or not they churned. You can find the dataset [here](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers?resource=download).

### Models Explored

Several machine learning models were trained and tested, including:

- **Decision Trees**
- **Random Forest**
- **Support Vector Machines (SVM)**
- **XGBoost**
- **K-Nearest Neighbors (KNN)**
- **Naive Bayes**
- **Gradient Boosting Classifier**
- **Stacking Classifier**

To further improve model performances, the following techniques were implemented:

### Performance Improvement Techniques

1. **Feature Engineering**

2. **SMOTE (Synthetic Minority Over-sampling Technique)**  

3. **Ensembling**  
  
## WebApp 

The webapp consists of a dashboard with customer profiles and the ML models' predictions. Using Llama 3.1b with Groq API, explanations to the predictions are generated. It explains the reasons as to why the customer maybe at a risk of churning or not. Along with prediction explanations, automated emails are generated that can be sent out to the customers, incentivizing them to stay with the bank. 

The webapp was created using streamlit and deployed on Render. 

Here is the link to the website: https://customer-churn-prediction-oii7.onrender.com





