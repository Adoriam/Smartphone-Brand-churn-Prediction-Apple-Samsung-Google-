# Smartphone-Brand-churn-Prediction-Apple-Samsung-Google-
A complete churn analysis of Apple, Samsung, and Google smartphone users using R. This repository includes data preprocessing, exploratory analysis, churn rate computation by brand, machine learning modeling (Random Forest, Logistic Regression, etc.), and visualizations of key insights

Smartphone Brand Churn Analysis
Brands Analyzed: Apple, Samsung, Google
1. Project Overview
This project presents a comprehensive analysis of customer churn across three major smartphone brands—Apple, Samsung, and Google. Using a structured analytical workflow in R, the study explores churn behavior, develops predictive models, and generates insights that can support decision-making in customer retention and product strategy.

The repository contains code and documentation for data preprocessing, exploratory analysis, churn rate estimation, machine-learning modeling, and model evaluation.

2. Objectives
Quantify churn rates for the selected smartphone brands.
Identify customer segments with higher churn likelihood.
Build predictive models capable of estimating churn risk.
Provide insights that may inform retention strategies and brand positioning.
3. Methodology
Data Preparation
Variable cleaning and type conversion
Handling categorical variables
Creation of model matrices for machine learning models
Train–test split with reproducible seeds
Analytical Techniques
Descriptive statistics and churn rate calculations
Exploratory visualizations (ggplot2)
Model performance evaluation using confusion matrices
Machine Learning Models Implemented
Logistic Regression
Random Forest
XGBoost (Gradient Boosted Trees)
Each model was trained and validated to assess predictive performance and identify the most influential features.

4. Key Findings
Churn Rates
Brand	Churn Rate	Percentage
Apple	0.0717	7.17%
Samsung	0.0709	7.09%
Google	0.0668	6.68%
All three brands show relatively similar churn levels.
Google demonstrates the lowest churn rate in the dataset.
Differences in churn appear to be influenced more by customer attributes than brand alone.
5. Tools and Technologies
R Programming Language
tidyverse for data manipulation
ggplot2 for visualization
caret for evaluation
randomForest for ensemble modeling
xgboost for gradient boosting
scales for formatting and reporting
6. Repository Structure
├── data/                 # Raw and processed datasets
├── scripts/              # R scripts for data preparation, analysis, and modeling
├── models/               # Exported model files (if applicable)
├── visualizations/       # Analytical charts and plots
└── README.md             # Project documentation
7. Visualization Example
The project includes visual reporting such as churn-rate comparisons using bar charts and percent-scale summaries generated in R.

8. Conclusion
The analysis provides a structured, data-driven view of smartphone customer churn across three leading brands. While churn rates remain close across the brands, the modeling workflow highlights key predictors that can support targeted retention strategies. The project demonstrates a complete end-to-end analytical pipeline suitable for corporate analytics environments.

9. Author
Pious Kojo Saxon Data Analyst | Machine Learning Practitioner
