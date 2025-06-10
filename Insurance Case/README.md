# Insurance Premium Prediction

#### Problem Statement
The goal of this dataset is to facilitate the development and testing of regression models for predicting insurance premiums based on various customer characteristics and policy details. Insurance companies often rely on data-driven approaches to estimate premiums, taking into account factors such as age, income, health status, and claim history. This synthetic dataset simulates real-world scenarios to help practitioners practice feature engineering, data cleaning, and model training.

#### Dataset Overview
This dataset contains 1.2 million and 20 features with a mix of categorical, numerical, and text data. It includes missing values, incorrect data types, and skewed distributions to mimic the complexities faced in real-world datasets. The target variable for prediction is the "Premium Amount".

#### Features
Age: Age of the insured individual (Numerical)
Gender: Gender of the insured individual (Categorical: Male, Female)
Annual Income: Annual income of the insured individual (Numerical, skewed)
Marital Status: Marital status of the insured individual (Categorical: Single, Married, Divorced)
Number of Dependents: Number of dependents (Numerical, with missing values)
Education Level: Highest education level attained (Categorical: High School, Bachelor's, Master's, PhD)
Occupation: Occupation of the insured individual (Categorical: Employed, Self-Employed, Unemployed)
Health Score: A score representing the health status (Numerical, skewed)
Location: Type of location (Categorical: Urban, Suburban, Rural)
Policy Type: Type of insurance policy (Categorical: Basic, Comprehensive, Premium)
Previous Claims: Number of previous claims made (Numerical, with outliers)
Vehicle Age: Age of the vehicle insured (Numerical)
Credit Score: Credit score of the insured individual (Numerical, with missing values)
Insurance Duration: Duration of the insurance policy (Numerical, in years)
Premium Amount: Target variable representing the insurance premium amount (Numerical, skewed)
Policy Start Date: Start date of the insurance policy (Text, improperly formatted)
Customer Feedback: Short feedback comments from customers (Text)
Smoking Status: Smoking status of the insured individual (Categorical: Yes, No)
Exercise Frequency: Frequency of exercise (Categorical: Daily, Weekly, Monthly, Rarely)
Property Type: Type of property owned (Categorical: House, Apartment, Condo)
Data Characteristics
Missing Values: Certain features contain missing values to simulate real-world data collection issues.
Incorrect Data Types: Some fields are intentionally set to incorrect data types to practice data cleaning.
Skewed Distributions: Numerical features like Annual Income and Premium Amount have skewed distributions, which can be addressed through transformations.
