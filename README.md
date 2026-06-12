# Edutech_Data_Science_Task4
## Linear Regression Modelling on Housing Dataset
## Project Overview:
This repository contains the implementation of Task 4: Linear Regression for the Edutech Solution Data Science Internship. The objective is to analyse the "HousePrice Dataset" (Housing.csv), train a linear regression model, predict property values for the test set, and evaluate the model's performance using Root Mean Squared Error (RMSE).
## Repository contents:
1. **Housing.csv** - The housing dataset containing continuous features and target labels.
2. **Edutech_Data_Science_Task4.ipynb** - Notebook containing the complete end-to-end Python script.
3. **predicted_values_report.csv** - The final prediction output matching model estimates against test cases.
4. **Readme.md** - Technical project documentation
## Workflow Steps Followed:
1. **Data Preprocessing**: Imported raw files and applied **LabelEncoder** to translate categorical parameters (**mainroad**, **airconditioning**, etc.) into valid mathematical variables.
2. **Data Partitioning**: Segregated data features and target parameters into independent training subsets (80%) and validation testing subsets (20%).
3. **Model Fitting**: Configured and initialised a Scikit-Learn **LinearRegression** engine to map numerical variables to property valuations.
4. **Evaluation**: Computed predictions against unseen baseline scenarios and measured efficiency parameters using RMSE.
---
##  Interview Technical Questions:

### Q1: What is regression?
**Answer:** Regression is a form of supervised machine learning designed to analyse, map, and predict the relationship between a **dependent target continuous variable** (like market price) and one or many **independent attributes or features** (like square footage, bedroom counts, or location metrics). Unlike categorical classification tracking fixed groups, regression handles fluid numeric ranges.

### Q2: What is RMSE, and why is it used?
**Answer:** **Root Mean Squared Error (RMSE)** represents the average absolute variance between your model's projected calculations and actual known ground-truth targets. It squares data variations, takes the mathematical average, and applies a square root modifier.
* **Interpretation Unity:** The mathematical root operation maps variance error levels back into the identical structural unit of measurement as your target variable (such as standard currency values instead of arbitrary squared numbers).
* **Outlier Sensitivity:** Squaring differences means that extreme structural miscalculations carry compounding penalty weights. This helps developers identify when models generate severely flawed predictions on complex entries.

   

