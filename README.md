# AI-Assisted Labor Market Analysis

### Exploring Wage Inequality, Education Returns, and Regional Labor Market Patterns in the United States through Machine Learning and Policy Analytics

## Overview

This project explores labor market outcomes in the United States using applied statistics, machine learning, and public policy analytics.

Using large-scale U.S. labor and socioeconomic datasets, I analyze how education, demographic background, and regional structural conditions shape wage outcomes and labor market inequality.

The project combines econometric modeling, predictive machine learning, and data visualization to study both individual-level and regional-level labor market dynamics.

---

## Research Focus

This project is organized around three related questions:

### 1. Wage Returns to Education

**How does education affect wage outcomes in the U.S. labor market?**

Using individual-level labor and demographic data, this analysis examines the relationship between educational attainment and wages.

Key topics include:

- wage inequality across education groups
- nonlinear returns to schooling
- demographic variation in earnings outcomes

Methods used:

- data cleaning and feature engineering
- regression analysis
- wage distribution analysis
- visualization of nonlinear wage patterns

Notebook:

[01_wage_education_analysis.ipynb](./01_wage_education_analysis.ipynb)

---

### 2. Labor Market Risk Prediction

**Can machine learning help predict labor market risk using worker characteristics?**

This section applies predictive models to classify labor-market-related outcomes using worker demographic and socioeconomic variables.

Methods used:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- model comparison
- ROC / AUC evaluation
- predictive performance analysis

Notebook:

`02_labor_market_risk_prediction.ipynb`

---

### 3. Regional Structural Inequality

**Which regional factors are associated with labor market inequality across U.S. counties?**

This analysis shifts from the individual level to the regional level and explores how county-level structural indicators predict inequality-related outcomes.

Methods used:

- Ordinary Least Squares (OLS)
- Ridge Regression
- Lasso Regression
- cross-validation
- coefficient interpretation and visualization

Notebook:

`03_regional_structural_inequality.ipynb`

---

## Technical Skills Demonstrated

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Statsmodels
- Matplotlib
- Data Cleaning & Transformation
- Feature Engineering
- Regression Modeling
- Machine Learning Model Evaluation
- Data Visualization
- Policy-Oriented Quantitative Analysis

---

## Repository Structure

```bash
AI-Assisted-Labor-Market-Analysis/
│
├── README.md
├── 01_wage_education_analysis.ipynb
├── 02_labor_market_risk_prediction.ipynb
└── 03_regional_structural_inequality.ipynb
