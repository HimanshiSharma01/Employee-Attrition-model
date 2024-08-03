## Employee Attrition Prediction Model
### Project Overview:
This project aims to predict employee attrition using a variety of machine learning techniques and provide actionable insights for HR professionals to mitigate turnover. The analysis is based on a comprehensive dataset that includes various factors influencing employee retention, such as job satisfaction, income, work-life balance, and relationships with managers.

### Key Highlights:
- **Attrition Rate:** 16.79% of employees have left the company.
- **Data Imbalance:** The dataset is imbalanced, which might introduce bias in the predictive model. The analysis includes both the original imbalanced dataset and a balanced dataset using the Synthetic Minority Oversampling Technique (SMOTE).

### Data Insights:
- **Age:** Employees who left are younger on average (34.3 years) compared to those who stayed (37.5 years), indicating younger employees are more likely to leave.
- **Daily Rate:** Employees who left have a slightly lower average daily rate (742.46) compared to those who stayed (794.44), suggesting pay might be a factor in attrition.
- **Distance from Home:** Those who left live farther from their workplace on average (10.52 units) compared to those who stayed (9.05 units), indicating commute distance might contribute to turnover.
- **Environment Satisfaction:** Employees who stayed have higher environment satisfaction (2.78) than those who left (2.53), suggesting a correlation between work environment satisfaction and retention.
- **Job Satisfaction:** Those who stayed have higher job satisfaction (2.75) compared to those who left (2.40), highlighting job satisfaction as a key factor in retention.
- **Monthly Income:** Significantly higher for those who stayed (6763.14) compared to those who left (4912.21), indicating income level is a major factor in attrition.
   **Total Working Years:** Those who stayed have more working years on average (11.73) compared to those who left (8.45), suggesting more experienced employees are more likely to stay.
- **Years at Company:** Employees who stayed have been with the company longer on average (7.28 years) compared to those who left (5.45 years), indicating tenure is a strong factor in retention.
- **Years with Current Manager:** Employees who stayed have longer average durations with their current manager (4.28 years) compared to those who left (2.98 years), suggesting a stable relationship with managers contributes to lower attrition.

### Additional Insights:
- Younger employees have a higher attrition rate.
- Bachelor's and Master's degree holders are more likely to leave, possibly due to more job opportunities.
- Employees with fewer companies worked and lower salary increases tend to leave more.
- Single employees have a higher attrition rate compared to married and divorced employees.
- Male employees are more likely to quit than female employees.
- Employees in Life Sciences and Medical fields have higher attrition rates.
- Frequent business travel is linked to higher attrition.

### Model Building:
Four machine learning models were built to predict employee attrition:
- Decision Tree
- Random Forest
- SMOTE Random Forest
- AdaBoost

### Best Model: AdaBoost Model
- Cross-validation Accuracy: 0.8425
- Cross-validation Precision: 0.8533
- Cross-validation Recall: 0.8425
- Cross-validation F1-score: 0.8330

**ROC Curve:**
The ROC curve for the AdaBoost model demonstrates a good balance between sensitivity and specificity with an AUC score of 0.7383.

**Feature Importance:**
The top important features identified by the AdaBoost model include Monthly Income, Age, Daily Rate, Hourly Rate, and Training Times Last Year.

## Tableau Dashboard:
A comprehensive Tableau dashboard was created to visualize key metrics and insights derived from the employee attrition dataset. This dashboard is designed to assist HR professionals and organizational leaders by providing a detailed analysis of attrition rates and associated factors, enabling data-driven strategies to improve employee retention.

### Key Metrics and Visualizations:
- Employee Count: Total number of employees analyzed is 1,470.
- Attrition Rate: Out of 1,470 employees, 237 have left, resulting in an attrition rate of 16.12%.
- Average Age: The average age of employees is 36.92 years.
- Average Monthly Income: Employees earn an average of $6,503 per month.
- Average Job Satisfaction: The average job satisfaction rating is 2.729 out of 4.

### Attrition Analysis:
- By Marital Status: Highlights the marital status distribution among employees who have left, showing notable trends in attrition rates among married, single, and divorced employees.
- By Job Satisfaction: Displays the correlation between job satisfaction levels and attrition, indicating that employees with lower job satisfaction are more likely to leave.
- By Gender: Illustrates attrition distribution across male and female employees, with 150 males and 87 females having left the organization.
- Age Group Analysis: Provides a breakdown of attrition by age group, revealing that the 25-35 age group has the highest number of leavers (510), followed by the 36-45 age group (425).
- Travel-Related Attrition: Examines the impact of travel requirements on employee attrition, showing minimal correlation between travel frequency and attrition rates.
- Departmental Attrition: Analyzes attrition rates across different departments, highlighting that Sales and Research & Development departments have higher attrition compared to Human Resources.
- Tenure Analysis: Displays the tenure distribution of employees who left, showing that those with 3-6 years of service have the highest attrition rates, followed by those with 6-10 years.

### Purpose and Impact:
The dashboard aims to provide actionable insights into employee attrition, helping organizations identify key areas for improvement in employee satisfaction and retention strategies. By visualizing complex HR data in an accessible format, it supports data-driven decision-making and strategic planning.













