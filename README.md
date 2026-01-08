# Student-Depression-Analysis-SQL-Tableau
End-to-end data analysis of student depression using SQL for data processing and Tableau for interactive dashboards.

# Student Depression Data Analysis (SQL & Tableau)

## Project Description
This project analyzes **student depression and mental health patterns** using **SQL for data cleaning, transformation, and analysis**, and **Tableau for interactive visualization**.  
The objective is to identify how academic pressure, lifestyle habits, and stress factors contribute to student depression.

## Project Objectives
- Clean and transform raw student mental health data using SQL  
- Perform exploratory data analysis on academic and lifestyle factors  
- Build interactive Tableau dashboards for insights  
- Identify patterns linked to depression among students  

## Tools & Technologies
- **SQL Server** – Data cleaning, transformation, and analysis  
- **Tableau** – Interactive dashboards and visual storytelling  
- **Excel / CSV** – Raw dataset source  

## Dataset Overview
The dataset contains the following attributes:
- Gender  
- Age  
- Academic Pressure  
- Study Hours  
- Study Satisfaction  
- Sleep Duration  
- Dietary Habits  
- Financial Stress  
- Family History of Mental Illness  
- Suicidal Thoughts  
- Depression Indicator  

## Data Cleaning & Transformation (SQL)
The following SQL operations were performed:
- Imported CSV data into SQL Server  
- Standardized gender values (`Male`, `Female` → `M`, `F`)  
- Created **Age Group** categories  
- Converted binary values (0/1) into readable labels (`Yes` / `No`)  
- Added an **Index Column** using `IDENTITY`  
- Handled NULL and blank values  
- Verified column distributions using `GROUP BY`  

## Analysis Performed
- Academic Pressure vs Student Count  
- Study Satisfaction vs Student Count  
- Sleep Duration Distribution  
- Financial Stress Impact  
- Study Hours Distribution  
- Depression Count Comparison  
- Family History vs Depression  

## Tableau Dashboards
The Tableau dashboard includes:
- Academic Pressure & Student Count  
- Financial Stress & Student Count  
- Study Satisfaction Analysis  
- Sleep Duration Distribution  
- Study Hours Trend  
- Overall Student Mental Health Dashboard  

Each visualization supports **interactive filtering** for deeper insights.

## Key Business Insights
- Higher academic pressure is strongly linked to increased depression cases  
- Low study satisfaction correlates with higher mental stress  
- Poor sleep duration shows a clear relationship with depression  
- Financial stress significantly impacts student mental health  
- Students with a family history of mental illness are more vulnerable  

## 💡 Business Use Case
This project helps:
- Educational institutions identify high-risk students  
- Counselors design targeted mental health programs  
- Universities improve academic and lifestyle support systems  
- Policymakers make data-driven mental health decisions  

## Author
**Sonali Bhosale**
## 📌 Repository Structure

