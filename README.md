# AlphaCare Insurance Solutions - Marketing Analytics Project
## Overview
This repository hosts the code and documentation for the marketing analytics project at AlphaCare Insurance Solutions (ACIS). The project focuses on analyzing historical car insurance claim data in South Africa to optimize marketing strategies and identify low-risk targets for premium adjustments. The analysis includes exploratory data analysis (EDA), hypothesis testing, and predictive modeling to support risk-based pricing and customer segmentation.
## Objectives

Perform Exploratory Data Analysis (EDA) to understand data quality, patterns, and trends.
Implement Data Version Control (DVC) for reproducible data pipelines.
Conduct A/B hypothesis testing to validate risk and margin differences across key features.
Develop machine learning models to predict claim severity and optimize premium pricing.

## Repository Structure

**data/: Stores datasets (tracked with DVC).**
notebooks/: Jupyter notebooks for EDA, hypothesis testing, and modeling.
scripts/: Python scripts for data processing and modeling.
reports/: Analysis reports and visualizations.
.github/workflows/: CI/CD configuration for GitHub Actions.

**Setup Instructions**

Clone the Repository:git clone https://github.com/Insurance-risk-analytics-predictive-modeling.git

cd Insurance-risk-analytics-predictive-modeling


Install Dependencies:pip install -r requirements.txt


**Initialize DVC:dvc init**
dvc remote add -d localstorage /path/to/local/storage
dvc pull



### **Usage**

**Run EDA notebooks in notebooks/ for data exploration.**
Execute hypothesis testing scripts in scripts/hypothesis_testing/ for statistical analysis.
Train and evaluate models using scripts in scripts/models/.

View results and visualizations.

**CI/CD**
GitHub Actions is configured for automated testing and linting. See .github/workflows/ci.yml for details.

