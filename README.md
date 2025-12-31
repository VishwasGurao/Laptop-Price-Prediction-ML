# Laptop Price Prediction using Machine Learning

## Project Overview
This project focuses on predicting laptop prices based on hardware
specifications, brand information, and system configuration. The objective
is to build an end-to-end machine learning solution that delivers accurate
and explainable price predictions.

## Dataset Information
- Dataset Name: laptop_prices.csv
- Total Records: 1275
- Total Features: 23
- Target Variable: Price_euros

## Key Features Used
- Company
- TypeName (Laptop Type)
- RAM (GB)
- CPU Company
- GPU Company
- Operating System
- Screen Size (Inches)
- Weight
- Primary and Secondary Storage

## Exploratory Data Analysis
Complete exploratory data analysis was performed to understand laptop
pricing behavior. Price ranges were used instead of average prices to
reflect real-world market language. The impact of brand, hardware
configuration, laptop type, and operating system on price was analyzed.

## Feature Engineering
Relevant features were selected based on EDA insights. Categorical
variables were encoded using one-hot encoding. The dataset was prepared
carefully to avoid data leakage and ensure machine learning readiness.

## Machine Learning Models
Two regression models were implemented and compared.

### Linear Regression
- Used as a baseline model to establish interpretability
- Achieved approximately 70 percent R2 score
- Provided a clear benchmark for comparison

### Random Forest Regression
- Captured non-linear relationships and feature interactions
- Improved performance to approximately 80 percent R2 score
- Reduced RMSE compared to Linear Regression
- Selected as the final model

## Model Evaluation
R2 score was used to measure how much variance in laptop prices is explained
by the model. RMSE was used to measure the average prediction error in euros.
Random Forest outperformed Linear Regression on both metrics.

## Key Outcomes
- Accurate laptop price prediction based on specifications
- Better understanding of pricing behavior across brands and configurations
- Demonstration of a real-world data science workflow

## Conclusion
This project demonstrates a complete data science pipeline from data
understanding and exploratory analysis to model building, evaluation, and
business interpretation. The Random Forest model provides reliable price
predictions and is suitable for practical use cases.

## Author
Vishwash Gurav
