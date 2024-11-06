# Predicting Employee Attrition with HR Analytics

## Overview
This project focuses on predicting employee attrition using the **HR Analytics Dataset** from Kaggle. The analysis explores various factors that contribute to employee turnover, such as job role, satisfaction levels, and compensation. By conducting exploratory data analysis (EDA), the project aims to uncover actionable insights that can help improve employee retention and inform HR strategies.

## Tools Used
- **Python Libraries**: Pandas, NumPy, Seaborn, Matplotlib
- **Data Visualization**: Bar chart, box plot, correlation heatmap
- **Data Source**: [HR Analytics Dataset]([https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset](https://www.kaggle.com/code/paramarthasengupta/hr-analytics-prediction-why-do-people-resign/notebook)) (CSV format)

## Key Findings
1. **Attrition Distribution**: The dataset indicates variations in attrition rates across different departments and job roles.
2. **Salary and Satisfaction**: Employees with lower monthly income and satisfaction levels tend to have higher attrition rates.
3. **Influential Factors**: Features such as **Job Role**, **Work-Life Balance**, and **Age** are strong indicators of employee turnover.
4. **Recommendations**: Implementing retention strategies targeting departments with higher turnover and improving job satisfaction can reduce attrition.

## Visuals

### 1. Attrition Distribution
This bar chart displays the distribution of attrition (whether an employee has left or stayed) across various departments and job roles. It helps visualize which areas of the organization experience higher turnover.

![Attrition Distribution](images/project3/Attrition%20Distribution.png)

### 2. Box Plot for Distribution Analysis
These box plots represent the distribution of various features in the dataset, allowing us to examine the spread and variation of each variable. The box portion of the plot represents the **interquartile range (IQR)**, which spans from the 25th percentile (Q1) to the 75th percentile (Q3). The line within the box marks the **median** (50th percentile) of the data. 

Outliers, represented as individual points beyond the whiskers of the box, are data points that fall outside the range defined by **Q1 − 1.5 × IQR** and **Q3 + 1.5 × IQR**. These outliers could indicate unusual values that may require further investigation, either as anomalies or as key signals for attrition prediction.

By analyzing the distribution of features such as **Age**, **Monthly Income**, and **Job Satisfaction**, we can identify potential patterns or areas requiring deeper focus to better understand the drivers of employee turnover.

![Box Plot for Distribution Analysis](images/project3/Feature%20Distribution%20Boxplots.png)

### 3. Heatmap Correlation of Features
This heatmap shows the correlation between different features in the dataset, revealing how attributes like **Job Satisfaction**, **Work-Life Balance**, and **Monthly Income** relate to attrition. Features with high correlations to attrition are key indicators that can be used to predict turnover. 

![Correlation Heatmap](images/project3/Correlation%20Heatmap.png)

## Link to Code
The code for this project, including EDA and the analysis leading to the visualizations above, can be found in the following Google Colab space:
[Google Colab Link](https://colab.research.google.com/drive/YourColabLinkHere#scrollTo=some-id)
