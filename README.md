# Predicting Hospital Stay Duration Using Patient and Admission Data

This project aims to optimize healthcare resources by developing a machine learning model to predict hospital stay durations. By leveraging patient demographics, health conditions, and admission details, the project seeks to enhance hospital resource management, improve patient outcomes, and reduce operational inefficiencies.

## Table of Contents
- [Introduction](#introduction)
- [Scope of the Project](#scope-of-the-project)
- [Challenges Addressed](#challenges-addressed)
- [Dataset Details](#dataset-details)
- [Methodology](#methodology)
- [Model Comparison](#model-comparison)
- [Key Insights and Recommendations](#key-insights-and-recommendations)
- [Future Scope](#future-scope)

## Introduction
In the healthcare sector, accurate prediction of hospital stay durations is essential for effective resource allocation and improved patient care. Traditional methods relying on historical averages lack accuracy. This project uses advanced data analytics and machine learning techniques to forecast hospital stay durations, providing actionable insights for better decision-making.

## Scope of the Project
- Develop a predictive model using patient demographics and admission data.
- Optimize bed utilization, staffing, and other healthcare resources.
- Enhance patient satisfaction by minimizing wait times and improving discharge planning.

## Challenges Addressed
- Unpredictability in hospital stay durations.
- Limited adoption of advanced analytics in hospital resource management.
- Integration of diverse datasets and handling data quality issues.

## Dataset Details
The dataset consists of 15 features, including:
- **Numerical Features**: Age, Admission_Deposit, Visitors_with_Patient, etc.
- **Categorical Features**: Department, Type_of_Admission, Severity_of_Illness, etc.

Target Variable: `Stay_in_days` (hospital stay duration).

## Methodology
### Data Preprocessing
- Handled missing values and outliers while preserving data integrity.
- Encoded categorical variables using binary and frequency encoding.

### Models Evaluated
1. **Baseline Models**: Linear Regression, Ridge, Lasso.
2. **Tree-Based Models**: Decision Tree, Random Forest, Gradient Boosting, XGBoost.
3. **Ensemble Methods**: Bagging, AdaBoost.

### Hyperparameter Tuning
Enhanced model performance using techniques like Grid Search and Randomized Search.

## Model Comparison
The tuned **XGBoost Regressor** and **Random Forest Regressor** were the top-performing models with the following metrics:
- **XGBoost**: R² = 82.68%, RMSE = 3.29
- **Random Forest**: R² = 82.46%, RMSE = 3.31

These models showed strong predictive performance and generalization capabilities.

## Key Insights and Recommendations
### Insights
1. Older patients and severe cases significantly influence hospital stay durations.
2. Departments like surgery and gynecology are major contributors to resource usage.

### Recommendations
1. Implement predictive models for real-time resource allocation.
2. Include additional patient attributes (e.g., socioeconomic status) for improved predictions.
3. Train staff to integrate predictive insights into daily operations.

## Future Scope
- Extend the model to include temporal trends and evolving patient data.
- Explore advanced techniques like Bayesian Optimization for hyperparameter tuning.
- Integrate the model into hospital management systems for seamless deployment.

---

### Team Members
- Abinash Balasubramanian (Team Leader)
- Akash Thiruveedula
- Harshitha Babu
- RajKumar R
- Harish R

**Mentor**: Jatinder Bedi  
**Batch**: DSE - FT - Chennai, May 2024

For more details, refer to the [project report](./DSE-FT-CHN-MAY24-G2-Capstone%20Final%20Report.pdf).
