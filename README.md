# Customer Churn Prediction

This repository contains a machine learning project aimed at predicting customer churn. By analyzing key customer data, the project builds predictive models that classify customers as likely to churn or stay, assisting businesses in identifying high-risk customers and implementing retention strategies.

## Project Overview

The goal of this project is to develop a model that accurately predicts customer churn using a variety of features. The dataset includes customer demographics, account information, and usage metrics, which provide insights into factors affecting customer retention.

## Dataset

The dataset contains the following key features:

- **CustomerID**: Unique identifier for each customer
- **Demographic Information**: Gender, age, and senior citizen status
- **Account Information**: Tenure, contract type, monthly charges, and payment methods
- **Services**: Details about the services subscribed by each customer, such as internet, phone, and streaming services
- **Churn**: Target variable indicating if a customer has churned (Yes) or is still active (No)

## Models Used

The project explores the following models for churn prediction:

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)

## Key Steps

1. **Data Preprocessing**: This includes handling missing values, encoding categorical variables, scaling features, and balancing the dataset.
2. **Feature Engineering**: Identifying and selecting the most impactful features.
3. **Model Training**: Training each model and fine-tuning hyperparameters using grid search.
4. **Evaluation**: Analyzing model performance with metrics such as:
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Confusion Matrix

## Results

The best-performing model achieved an accuracy of **X%** on the test set, with key findings on customer characteristics and behaviors linked to higher churn risk. Specific insights include:
- **Churn trends** among senior citizens and customers with certain service combinations.
- **Key retention strategies** suggested based on customer attributes correlated with churn.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Llasheen-0/Customer-Churn-Prediction.git
