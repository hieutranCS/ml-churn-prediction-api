# ML Churn Prediction API

This project is an end-to-end machine learning backend application that predicts customer churn using Python and scikit-learn. The long-term goal is to expose predictions through FastAPI and store prediction records in PostgreSQL.

## Week 1 Progress
- Set up project structure
- Loaded and explored the IBM Telco Customer Churn dataset
- Identified target column and candidate input features
- Started exploratory data analysis

## Dataset
IBM Telco Customer Churn dataset

## Planned Stack
- Python
- pandas
- scikit-learn
- FastAPI
- PostgreSQL
- SQLAlchemy
- Docker


Target variable: `Churn Value`  
The dataset also includes `Churn Label`, `Churn Score`, and `Churn Reason`, but these were excluded from model inputs to avoid target leakage.