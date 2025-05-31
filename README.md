# Student Dropout Prediction Using Machine Learning in R

## Project Overview
This project applies logistic regression to predict student dropout risk using academic performance, lifestyle, and family-related data. The objective is to identify high-risk students early and support timely academic interventions.

## Tools & Technologies
- R Programming  
- Packages: `data.table`, `dplyr`, `ggplot2`  
- Model: Logistic Regression  
- Feature Engineering & Visualization

## Key Methods
- Cleaned and preprocessed categorical and numerical features  
- Engineered binary variables (e.g., Gender, Internet Access)  
- Handled missing values and dropped irrelevant columns  
- Performed detailed EDA with:
  - Boxplots and stacked bar charts
  - Correlation analysis  
- Built a logistic regression model using selected predictors  
- Computed **Odds Ratios** and **Economic Importance** for interpretation

## Accuracy Results
| Metric     | Value     |
|------------|-----------|
| Accuracy   | 89.23%    |
| Precision  | 71.05%    |
| Recall     | 72.97%    |
| F1 Score   | 72%       |

## Files Included
- `Student Dropout.R` – Complete script with EDA and model  
- `student dropout.csv` – Input dataset  


## Skills Demonstrated
- Data Preprocessing & Transformation  
- Feature Engineering (binary & factor conversion)  
- Logistic Regression & Model Interpretation  
- Confusion Matrix and Model Evaluation  
- Data Visualization using `ggplot2`  
- Clear Documentation of Insights

## Summary
This project highlights how logistic regression can be used to uncover dropout patterns and predict outcomes. With strong EDA, feature engineering, and performance evaluation, this solution supports institutions in identifying and addressing student attrition risks.
