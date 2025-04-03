# Autonomous Vehicle Traffic Accident Analysis

## Project Overview

This repository contains a comprehensive analysis of autonomous vehicle (AV) traffic accident data aimed at identifying key factors contributing to AV crashes. The primary goal is to provide data-driven insights to policymakers for developing effective AV safety regulations.

## Purpose

- Identify and analyze the most significant features contributing to AV crashes
- Develop predictive models to assess accident severity
- Provide actionable insights for policymakers to enhance AV safety regulations
- Compare different machine learning models to determine the most effective approach

## Data Source

The dataset is sourced from the National Highway Traffic Safety Administration (NHTSA) and includes detailed information about AV-related accidents.

## Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- XGBoost Classifier
- Support Vector Machine (SVM)
- AdaBoost Classifier
- Voting Classifier (Random Forest + XGBoost)

**Best Performing Model:** Voting Classifier combining Random Forest and XGBoost achieved 95.61% accuracy in predicting accident severity.

## Tools and Technologies

### Programming Language

- Python 3.x

### Libraries

- pandas: Data manipulation and analysis
- numpy: Numerical computing
- scikit-learn: Machine learning algorithms
- xgboost: Gradient boosting
- matplotlib: Data visualization
- seaborn: Statistical data visualization
- jupyter: Interactive notebook development

## Key Features

- Comprehensive data preprocessing and cleaning
- Feature importance analysis
- Model comparison and evaluation
- Bootstrap sampling for robust model validation
- Advanced ensemble methods implementation

## Results

The analysis revealed that certain features are particularly significant in AV crashes, which can help inform policy decisions. The combination of Random Forest and XGBoost through ensemble methods proved most effective for prediction, achieving 95.61% accuracy.
