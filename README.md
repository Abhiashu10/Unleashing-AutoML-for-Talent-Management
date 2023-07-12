# Real-time data provided by Georgetown Analytics and Technology (Unleashing-AutoML-for-Talent-Management)
This project is **sponsored by Georgetown Analytics and Technology and its founder, Ernest Smiley**. I had the opportunity to work with **real-time data provided by Georgetown Analytics and Technology**, gaining valuable insights into the field of talent management. This repository contains the code and data for the project "Unleashing AutoML for Talent Management ATS and HRIS Data." The project aims to leverage AI technologies, specifically Automated Machine Learning (AutoML), in the field of talent management. The goal is to analyze ATS (Applicant Tracking System) and HRIS (Human Resources Information System) data to gain insights into hiring decisions and improve talent management outcomes.

# Abstract

This project explores the potential of AutoML in talent management by utilizing ATS and HRIS data obtained from our sponsor, Georgetown Analytics and Technology. The objectives include understanding patterns in the data, merging datasets from multiple sources, identifying key variables influencing hiring decisions, and developing predictive models to forecast candidate hiring. AutoML techniques are employed to automate the model development and optimization process.

# Introduction

The field of talent management has seen significant advancements with the introduction of AI technologies. This project aims to leverage ATS and HRIS data to gain a deeper understanding of the patterns and information captured within these systems. By merging datasets and applying AutoML techniques, the project aims to identify influential variables in hiring decisions and develop accurate predictive models.

# Problem Statement

The project addresses two specific problem statements: Hired_Status Prediction (Classification) and Salary Prediction (Regression). The classification model predicts the "Hired_Status" based on available features, while the regression model predicts salaries based on individual characteristics and experience.

# Exploratory Data Analysis (EDA)

EDA was performed to gain insights into the data. Various questions were explored, including the distribution of job openings, the most cited reasons for job changes, salary distributions based on years of experience, popular job profiles, and job demand across different cities and countries.

# Merge Dataset

Multiple datasets were merged using Python's merge function, resulting in a consolidated dataset for further analysis and modeling. Categorical variables were one-hot encoded, and numerical variables were standardized to prepare the dataset for machine learning tasks.

# Handling Imbalanced Dataset

Imbalanced datasets were addressed using the **Synthetic Minority Over-sampling Technique (SMOTE)** to create synthetic samples for the minority class. This technique helps balance the dataset and improve the performance of machine learning models.

# Model Building

Two models, Logistic Regression and XGBoost, were developed to analyze the datasets and make predictions. Model performance was evaluated using metrics such as accuracy, precision, recall, and F1-score.

# Feature Importance

Feature importance analysis using Random Forest identified the most influential features for predicting the hiring status of employees.

# AutoML

AutoML was employed to automate the model development and optimization process. It streamlines the recruitment process, enhances candidate screening, mitigates bias, provides a personalized candidate experience, and reduces time-to-hire. AutoML platforms offer scalability and cost efficiency, making them valuable tools for talent acquisition.

# Conclusion & Future Work

The project findings highlight the importance of key numerical features in predicting hiring status. The XGBoost model emerged as the most effective for this task. The analysis provided insights into job demand, job profiles, and popular cities for job seekers. Future work may include utilizing additional datasets, applying deep learning techniques, and exploring the business implications of talent management data through surveys or interviews.
