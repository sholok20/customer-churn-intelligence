# Customer Churn Intelligence Platform

An end-to-end data analytics and machine learning project designed to analyze customer churn, identify customer retention patterns, and predict customers who are at risk of leaving a telecommunications company.



## Project Overview

Customer churn is a major business challenge for telecommunications companies. Losing customers affects revenue, profitability, and long-term business growth.

This project aims to build an integrated analytics and AI platform that transforms customer data into actionable business insights and machine learning predictions.

The platform will combine data analytics, SQL, machine learning, and an interactive web application.

## Project Objectives

- Analyze customer behavior and identify churn patterns.
- Perform data cleaning and exploratory data analysis.
- Use SQL and PostgreSQL to manage and analyze customer data.
- Build interactive business intelligence dashboards using Power BI.
- Develop and evaluate machine learning models for churn prediction.
- Explain important factors influencing customer churn.
- Build an interactive application for customer churn predictions.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming | Python, SQL |
| Data Analysis | Pandas, NumPy, Matplotlib |
| Database | PostgreSQL |
| Machine Learning | Scikit-learn |
| Visualization | Power BI |
| Application | Streamlit |
| Development | Jupyter Notebook, Google Colab |
| Version Control | Git, GitHub |

## Dataset

**IBM Telco Customer Churn Dataset**

The project will use the publicly available Telco Customer Churn dataset containing customer demographics, subscribed services, contract information, billing details, and churn labels.

Dataset source: [IBM Telco Customer Churn Dataset — Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

## Planned Project Architecture

```text
Customer Churn Dataset
          |
          v
   Data Collection
          |
          v
 Data Cleaning & EDA
          |
          v
     PostgreSQL
          |
          v
   SQL Analysis
          |
          v
    Power BI
  Analytics Dashboard

          |
          v
 Machine Learning Pipeline
          |
          v
 Model Evaluation
          |
          v
 Churn Prediction
          |
          v
   Streamlit App
```

## Machine Learning Approach

The planned machine learning workflow includes:

1. Data preprocessing and feature engineering.
2. Handling missing values and categorical variables.
3. Training and comparing classification algorithms.
4. Evaluating model performance.
5. Identifying important churn-related features.
6. Building a reusable prediction pipeline.

### Planned Models

- Logistic Regression
- Random Forest

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC
- Confusion Matrix

## Planned Repository Structure

```text
customer-churn-intelligence/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_data_cleaning_eda.ipynb
│   ├── 02_sql_analysis.ipynb
│   └── 03_model_training.ipynb
│
├── src/
│   ├── data_processing.py
│   ├── train.py
│   └── predict.py
│
├── dashboard/
│
├── app/
│
├── README.md
├── requirements.txt
└── .gitignore
```

## Development Roadmap

- [ ] Create GitHub repository and project documentation.
- [ ] Collect and inspect the dataset.
- [ ] Clean and preprocess customer data.
- [ ] Perform exploratory data analysis.
- [ ] Design PostgreSQL database schema.
- [ ] Perform SQL-based business analysis.
- [ ] Develop Power BI dashboard.
- [ ] Train machine learning models.
- [ ] Evaluate and compare model performance.
- [ ] Build a reusable prediction pipeline.
- [ ] Develop Streamlit application.
- [ ] Test, document, and deploy the application.

## Expected Outcomes

The completed project aims to deliver:

- A structured customer churn dataset.
- SQL queries answering relevant business questions.
- An interactive Power BI analytics dashboard.
- Evaluated machine learning models.
- A reusable churn prediction pipeline.
- An interactive web application.

## Author

**Omar Khaled**

Computer Science | Aspiring AI Engineer & Data Analyst

GitHub: [@sholok20](https://github.com/sholok20)

---

