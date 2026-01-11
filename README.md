📊 HR Analytics Dashboard – Power BI
📌 Project Overview

This project focuses on analyzing Human Resources data to gain insights into workforce trends, employee distribution, attrition, and key HR performance indicators. The dashboard is designed to support HR teams and management in making data driven decisions related to employee retention, hiring, and workforce planning.

The analysis and visualization were performed using Microsoft Power BI, transforming raw HR data into meaningful and interactive insights.

🎯 Objectives
Analyze employee demographics and workforce composition
Track employee attrition and retention trends
Identify patterns based on department, job role, gender, and experience
Provide HR friendly KPIs for quick decision making

📂 Dataset Description
The dataset contains employee level HR information, including:
Employee ID
Age
Gender
Department
Job Role
Education
Years of Experience
Attrition Status
Salary and Performance related fields
(Dataset used only for analysis and learning purposes)

🛠 Tools & Technologies
Power BI Desktop
Power Query for data cleaning and transformation
DAX for calculated measures and KPIs
Excel / CSV as data source

📊 Key KPIs & Metrics
Total Employees
Attrition Rate
Active vs Attrited Employees
Average Age
Average Salary
Department wise Employee Count
Gender Distribution

📈 Dashboard Features
Interactive slicers for Department, Gender, and Job Role
Attrition analysis by age group, department, and experience
Employee distribution across departments
Clear KPI cards for quick insights
User friendly and business oriented layout

🔄 Data Processing Steps
Imported HR dataset into Power BI
Cleaned and transformed data using Power Query
Created calculated columns and measures using DAX
Designed interactive visuals and dashboards
Applied filters and slicers for dynamic analysis

🧮 Sample DAX Measures
Attrition Rate = 
DIVIDE(
    CALCULATE(COUNT(Employee[EmployeeID]), Employee[Attrition] = "Yes"),
    COUNT(Employee[EmployeeID])
)

📌 Insights Generated
Certain departments show higher attrition rates
Attrition is more common within specific experience ranges
Gender wise distribution highlights workforce imbalance in some roles
Younger employees show higher movement compared to senior staff

🚀 Future Improvements
Add salary band and performance based analysis
Include hiring trends over time
Integrate forecasting for attrition prediction
Connect with live HR data sources

📁 Project File
HR Dashboard.pbix – Power BI dashboard file

👤 Author
Aman Shingane
Aspiring Data Analyst | Power BI | SQL | Excel
