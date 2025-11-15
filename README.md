📊 Employee Data Analysis – Power BI Dashboard

A complete end-to-end data cleaning, transformation, and visualization project built using Microsoft Power BI. This dashboard helps analyze employee performance, department distribution, promotions, salary trends, and workforce insights.

<img width="896" height="481" alt="image" src="https://github.com/user-attachments/assets/1812622b-3d7c-46be-b479-c13b0167463d" />

🚀 Project Workflow
1️⃣ Data Import

Loaded the raw dataset (emp_data.csv) into Power BI Desktop using Get Data → CSV.

Verified column formats and initial schema.

🧼 2️⃣ Data Cleaning in Power Query

Performed extensive cleaning to prepare high-quality analytical data.

✔ Handling Missing Values

Numeric null values → replaced using mean/median depending on distribution.

Categorical null values → replaced with “Unknown” or most frequent category.

✔ Removing Duplicates

Deleted duplicate entries based on Employee ID to ensure record uniqueness.

✔ Standardizing Data Types

Converted:

Text columns → Categorical

Numeric columns → Whole number / decimal

Date columns → Date format

✔ Text Formatting

Trimmed unwanted spaces

Corrected inconsistent labels (e.g., "hr manager" → "HR Manager")

✔ Feature Engineering

Created additional columns to enhance analysis:

Experience Category

Salary Band

Promotion Flag

Age Group

🔄 3️⃣ Data Transformation

To make the data dashboard-ready:

Applied filters to remove invalid records

Built hierarchies (Department → Role → Employee)

Created DAX measures, including:

Total Employees

Average Salary

Promotion Rate

Employee Retention %

Performance Score Index

📈 4️⃣ Dashboard Development

Designed a clean, interactive & insight-driven Power BI report:

🎨 Visual Components:

KPI Cards → Employee Count, Avg Salary, Promotion Count

Bar Charts → Department-wise & Role-wise distribution

Pie/Donut Charts → Gender ratio, Promotion ratio

Line Graphs → Trends over months/years

Tables → Employee-level performance info

Slicers → Department, Gender, Education, Experience

🎯 Dashboard Highlights:

Fully interactive

Clean professional color theme

Optimized layout for readability

🔍 5️⃣ Key Insights

Some major insights derived from the report:

Departments with highest/lowest headcount

Salary trends and distribution across roles

Promotion patterns & performance indicators

Workforce diversity and education segmentation

High-performing vs low-performing teams

📁 6️⃣ Project Files Included

Finalprojectpowerbi.pbix → Complete Power BI Dashboard

emp_data.csv → Cleaned dataset

README.md → Documentation for project explanation

This project showcases my approach to solving real-world business analytics problems using structured, industry-ready methods.
