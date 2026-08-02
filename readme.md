# Employee Attrition Prediction using Logistic Regression

## Project Overview

This project predicts whether an employee is likely to leave the company or stay using Machine Learning.

A Logistic Regression model is implemented to classify employee attrition based on HR-related features such as age, job role, income, overtime, job satisfaction, and years at company.

## Dataset

Dataset Used:

IBM HR Analytics Employee Attrition & Performance Dataset

The dataset contains employee information including:

- Age
- BusinessTravel
- Department
- JobRole
- MonthlyIncome
- JobSatisfaction
- OverTime
- YearsAtCompany
- WorkLifeBalance
- Attrition (Target Variable)

## Machine Learning Workflow

The project includes:

- Data Loading
- Data Exploration
- Checking Missing Values
- Label Encoding for Categorical Features
- Train-Test Split
- Logistic Regression Model Training
- Model Prediction
- Accuracy Evaluation

## Model Used

Logistic Regression

Logistic Regression is a classification algorithm used to predict binary outcomes.

Target Variable:

Attrition

Classes:

- Yes
- No

## Model Accuracy

The model achieved approximately:

Accuracy: 89%

## Technologies Used

- Python
- Pandas
- Scikit-learn
- NumPy

## Project Structure

Employee-Attrition-Prediction-Logistic-Regression/

─ employee_attrition.py

─ Employee-Attrition.csv

─ requirements.txt

─ README.md

## How to Run

1. Clone the repository

2. Install required libraries:

pip install -r requirements.txt

3. Run the Python file:

python employee_attrition.py
