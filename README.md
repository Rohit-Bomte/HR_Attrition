# HR_Attrition

Introduction:
This report provides a comprehensive analysis of employee attrition within the organization. The dataset includes various employee-related features such as age, job role, department, salary, job satisfaction, work-life balance, and years of service. The objective of this report is to gain insights into the factors that contribute to employee turnover, identify key patterns and trends, and provide recommendations to improve employee retention.
This report aims to explore and analyze the dataset on HR attrition. Let’s delve into the details:

1.	Data Overview:

•	The dataset contains employee details such as age, department, job role, salary, job satisfaction, work-life balance, and years at the company.
These features help identify patterns and reasons behind employee attrition.

•	The target variable is 'Attrition', which shows whether an employee has left the company (Yes) or is still working (No).
This helps in analyzing which factors are most linked to employees leaving.

2.	Data Preparation:
To ensure accurate and meaningful analysis, several data preparation steps were carried out before exploring the dataset. These steps included:

•	Data Cleaning:

-	Checked for missing or null values and handled them appropriately.
-	Verified data types for each column and made necessary conversions for consistency.

•	Data Filtering:

-	Filtered the dataset by selecting only the relevant columns that contribute to attrition analysis, such as age, department, job role, income, satisfaction scores, and years at the company.

3.	Exploratory Data Analysis(EDA)

The EDA phase involved analyzing various features to understand the factors influencing employee attrition. Key steps included:

•	Attrition Distribution
-	Checked the overall count of employees who left the company vs. those who stayed using value counts.

•	Demographic Analysis
-	Analyzed attrition patterns across different age groups, genders, and marital statuses to identify high-risk segments.

•	Job-Related Factors
-	Explored attrition in relation to job roles, departments, and years at company using count plots and groupby functions.
-	Evaluated how job satisfaction, work-life balance, and environment satisfaction affected employee decisions to leave.

•	Income & Promotion Trends
-	Investigated how monthly income and years since last promotion correlated with attrition.


4.	Data Visualization:

•	Count plot was used to visualize overall attrition distribution.
•	Bar plots showed attrition across different age groups, departments, and job roles.
•	A heatmap was created to visualize the correlation between different features and identify which ones are closely related to attrition.
•	Monthly income distribution between employees who stayed and left was visualized using boxplots.
•	Count plots were used to analyze attrition trends by marital status and gender.
•	Visualizations helped highlight key patterns and high-risk groups contributing to employee turnover.

Conclusion:

•	The data analysis of the HR attrition dataset revealed meaningful patterns related to employee turnover. 
•	Key factors such as age, department, job role, marital status, and years at the company were found to influence attrition rates.
•	Correlation analysis highlighted important features like Monthly Income and Years Since Last Promotion as potential drivers of attrition.
This report provides an initial exploration of the HR data and highlights the importance of identifying employee segments at risk. Further analysis and strategic planning can help HR teams improve retention and workplace satisfaction.
