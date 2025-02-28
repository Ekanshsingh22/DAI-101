# DAI-101-Assignment-1

## **Project Title:**  
**DAI Assignment 1 - Diabetes Dataset Analysis**  

## **Author:**  
**Ekansh Singh - 23112037**  

## **Project Overview:**  
This project analyzes a diabetes dataset containing various health indicators to identify key factors affecting diabetes risk. The analysis includes exploring BMI, glucose levels, insulin levels, and other medical attributes to understand their impact on diabetes outcomes.  

## **Dataset:**  
The dataset consists of various health-related attributes, including:  
- **Numerical Features**: BMI, Glucose Level, Blood Pressure, Insulin, Age.  
- **Categorical Features**: Outcomes (Diabetes Presence: `0 = No, 1 = Yes`).  

## **Workflow:**  

### **Data Cleaning:**  
- Handled missing or inconsistent values in the dataset.  
- Removed irrelevant columns that don't contribute to the analysis.  

### **Univariate Analysis:**  
- Distribution plots for numerical columns (`BMI`, `Glucose`, `Insulin`, `Age`).  
- Count plots for categorical columns (`Diabetes Outcomes`).  

### **Outlier Detection & Handling:**  
- Boxplots have been generated for numerical columns to visualize outliers.  
- Extreme outliers were removed using the Z-score method (`Threshold = 3`).  

### **Bivariate Analysis:**  
- **Correlation Heatmap** to visualize relationships between numerical variables.  
- **Pairplots** to explore feature interactions.  
- **Boxplots** for `BMI vs. Diabetes Outcome`.  
- **Barplots** for average `Glucose Level` and `Insulin` across diabetes categories.  

### **Additional Insights:**  
- **Diabetes Trends Based on Age Groups**  
- **BMI vs. Diabetes Outcomes Analysis**  
- **Glucose Level Distribution Among Diabetic and Non-Diabetic Patients**  
- **Impact of Blood Pressure on Diabetes Risk**  
- **Feature Engineering**: Insulin-to-Glucose Ratio  

## **Results:**  
The project provides comprehensive insights into diabetes risk factors and trends. It highlights how attributes like glucose level, BMI, and insulin impact diabetes outcomes. The analysis helps in identifying significant medical indicators that could aid in early diagnosis and preventive measures.  

## **Dependencies:**  
numpy
- pandas
- matplotlib
- scipy
- seaborn
