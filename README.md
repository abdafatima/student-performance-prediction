# Predicting Student Performance for Educational Institutions

A machine learning project to predict student academic outcomes using demographics, attendance, grades, and study habits. Built models and delivered insights to guide data-driven academic support strategies.

## Objective
To analyze student data (demographics, attendance, grades, study habits, etc.) and build a predictive model to assess performance outcomes. The model will also offer recommendations for academic interventions to improve success rates.

## Data Sources
- Kaggle Student Performance Datasets
- UCI Machine Learning Repository
- Open educational datasets from data.gov

## 1. Data Cleaning & Preprocessing
- Loaded datasets into a Python environment (Pandas)
- Addressed missing values, removed outliers, and corrected inconsistencies
- Created new features like attendance rate and study hours per week

## 2. Data Analysis & Visualization
- Summary statistics of academic performance metrics
- Correlation plots between grades, attendance, demographics, and study habits
- Insights into factors linked to low or high academic achievement

## 3. Predictive Modeling
- Built both regression and classification models (e.g., Logistic Regression, Random Forest)
- Target variables: Final grade / Pass-Fail status
- Feature selection based on domain knowledge and correlation analysis
- Train-test split performed; models evaluated using accuracy, F1-score, RMSE, etc.
- Feature importance determined using model-based methods

## 4. Insights & Recommendations
- Top predictors: study time, past grades, absences, family support
- Recommendations:
  - Early tutoring programs for low-performing students
  - Study skills workshops based on attendance and performance patterns
  - Personalized academic intervention plans based on model predictions

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

