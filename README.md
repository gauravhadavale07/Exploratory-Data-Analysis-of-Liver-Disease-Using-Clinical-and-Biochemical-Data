# Exploratory Data Analysis of Liver Disease Using Clinical and Biochemical Data

## Project Description

This project focuses on the exploratory data analysis (EDA) and statistical understanding of liver disease using patient clinical and biochemical data.  
The primary aim is to analyze key liver function indicators, identify meaningful patterns, and study their relationship with liver disease occurrence.

Rather than presenting a full diagnostic system, this project emphasizes data understanding, visualization, and preliminary machine learning analysis, which are essential early steps in medical data science workflows.

---

## Objectives

- Understand the structure and quality of liver disease clinical data  
- Perform data cleaning and preprocessing  
- Conduct exploratory data analysis using statistical measures and visualizations  
- Analyze relationships between biochemical markers and liver disease  
- Apply baseline machine learning models for initial predictive insight  
- Draw data-driven conclusions without overclaiming medical diagnosis  

---

## Dataset Overview

The dataset contains patient demographic information and biochemical test results commonly used in liver function assessment.

### Features
- Age  
- Gender  
- Total Bilirubin  
- Direct Bilirubin  
- Alkaline Phosphatase  
- Alanine Aminotransferase (ALT)  
- Aspartate Aminotransferase (AST)  
- Total Proteins  
- Albumin  
- Albumin and Globulin Ratio  

### Target Variable
- Liver Disease Status  
  - 1: Liver disease present  
  - 0: No liver disease  

---

## Methodology

### Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Basic feature scaling where required  
- Checking data consistency and distributions  

### Exploratory Data Analysis
- Univariate analysis of clinical parameters  
- Bivariate analysis with respect to liver disease status  
- Correlation analysis between biochemical features  
- Visualization to identify trends and anomalies  

### Preliminary Machine Learning
- Training simple classification models to observe patterns  
- Model evaluation using accuracy and confusion matrix  
- Used only for exploratory insight, not clinical deployment  

---

## Key Observations

- Certain biochemical markers vary significantly between healthy and affected patients  
- Liver enzyme levels and bilirubin-related features show strong association with liver disease  
- Data imbalance and variability highlight challenges in medical datasets  
- The analysis provides a foundation for more advanced predictive modeling  

---

## Tools and Technologies

- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## Repository Structure

