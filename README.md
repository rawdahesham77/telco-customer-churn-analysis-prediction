# Customer Churn Analysis and Prediction

An end-to-end data analysis and machine learning project designed to identify customers at risk of churn and provide actionable business insights to improve customer retention.

## Project Overview

Customer churn is one of the most critical challenges for subscription-based businesses. This project analyzes customer behavior, identifies churn patterns, and builds predictive models to estimate the likelihood of customer churn.

The project combines data preprocessing, exploratory data analysis, machine learning, and business intelligence visualization to support data-driven decision making.

## Objectives

- Analyze customer behavior and churn trends
- Identify the main factors influencing customer churn
- Build and evaluate machine learning models for churn prediction
- Generate actionable business insights
- Create an interactive Power BI dashboard for stakeholders

## Dataset
ة’ة
The dataset used in this project is the Telco Customer Churn dataset, which contains information about:

- Customer demographics
- Services subscribed to
- Contract details
- Payment methods
- Monthly and total charges
- Customer tenure
- Churn status

## Data Preprocessing

Several preprocessing techniques were applied to prepare the data for analysis and modeling, including:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Encoding categorical features
- Outlier detection and treatment
- Feature scaling
- Feature engineering

## Exploratory Data Analysis

EDA was conducted to uncover trends and patterns related to churn. Key variables analyzed include:

- Contract type
- Tenure
- Monthly charges
- Internet service type
- Payment method
- Senior citizen status

## Machine Learning Models

The following models were used to predict customer churn:

- Logistic Regression
- Random Forest Classifier

## Model Evaluation

The models were evaluated using multiple performance metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Dashboard

An interactive Power BI dashboard was developed to visualize:

- Overall churn distribution
- Churn by contract type
- Churn by payment method
- Customer demographics
- Revenue analysis
- Monthly charges and tenure trends

## Project Structure

```text
Customer-Churn-Project/
│
├── data/
│   ├── Telco-Customer-Churn.csv
│   ├── customer_churn_dataset_cleaned.xlsx
│
├── notebooks/
│   └── churn_prediction_model.ipynb
│
├── models/
│   └── churn_model.pkl
│
├── reports/
│   ├── ai_insights.html
│   ├── customer_churn_dataset_cleaned.html
│   └── churn_predictions.xlsx
│
├── dashboard/
│   └── final_project.pbix
│
├── presentation/
│   └── rawda_churn_presentation.pptx
│
└── README.md


