# Obesity-Level-Prediction-ML-Project
This repository contains a comprehensive project aimed at predicting obesity levels based on individuals' eating habits and physical conditions. Leveraging a dataset from the UCI Machine Learning Repository, this project implements advanced machine learning techniques to generate actionable insights for public health interventions.

# Project Title
Predicting Obesity Levels Using Machine Learning

# Overview
This project predicts obesity levels based on individuals' eating habits and physical conditions. Using data from Mexico, Peru, and Colombia, the analysis identifies high-risk groups and provides actionable recommendations for targeted health interventions.

# Dataset Information
Source: UCI Machine Learning Repository
Name: Estimation of Obesity Levels Based on Eating Habits and Physical Conditions
Attributes: 17 features, including age, weight, height, eating habits, physical activity, and obesity classification.
Records: 2,111 individuals.
Target Variable: Obesity class levels (Noobesity) ranging from Insufficient Weight to Obesity Type III.

# Business Problem
The project aims to assist public health agencies in prioritizing interventions for individuals with obesity risks. It provides data-driven insights for designing campaigns to reduce obesity prevalence.

# Key Steps
# Data Preprocessing:

Identified missing values and duplicates.
Detected outliers using the Local Outlier Factor (LOF).
Handled multicollinearity using the Variance Inflation Factor (VIF).

# Exploratory Data Analysis:

Conducted univariate and bivariate analysis.
Visualized relationships between height, weight, and obesity levels.

# Feature Engineering:

Applied Principal Component Analysis (PCA) for dimensionality reduction.

# Predictive Modeling:

Built classification models using Logistic Regression, Random Forest, and Support Vector Machines (SVM).
Evaluated models on metrics like accuracy, precision, recall, and F1-score.

# Insights and Recommendations:

Identified weight and physical activity as the most influential factors.
Designed actionable interventions for high-risk groups.

# Technical Details

Tech Stack: Python, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn.

# Algorithms Used:

Logistic Regression (87% accuracy).
Random Forest (94% accuracy).
Support Vector Machines (98% accuracy).

# Results

Top Features: Weight, Physical Activity, Age.
Best Model: SVM with 98% accuracy and excellent performance across all obesity levels.
Actionable Insight: High-risk obesity levels (Type II & III) can be mitigated through targeted campaigns focusing on physical activity and weight management.

# Project Highlights

Dataset Preprocessing: Addressed data quality issues and ensured robust feature selection.
Visual Insights: Clustering in PCA highlights distinct obesity categories.
Actionable Outcomes: Models provide data-driven support for health interventions.

# Acknowledgments

Thanks to UCI Machine Learning Repository for the dataset and #GeorgeBrownCollege for guidance. Special thanks to Professor @AmitKukreja for their mentorship and insights.

# References

Dua, D., & Graff, C. (2019). Estimation of Obesity Levels Based on Eating Habits and Physical Condition. UCI Machine Learning Repository.



