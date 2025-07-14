# Professional Data Survey Analysis – Power BI Project

# Overview

This project presents an interactive Power BI dashboard based on responses from 290 data professionals. The dashboard explores key factors such as career background, job roles, satisfaction levels, salary ranges, education, gender, and age distribution. The goal is to uncover workforce trends, highlight diversity gaps, and support data-driven HR and industry insights.

# Dataset Summary

* Total Respondents: 290
* Typical Age: Early 20s
* Education: Predominantly Bachelor’s and Master’s degree holders

## Data Processing Steps

# Data Cleaning & Transformation

* Removed irrelevant columns and rows with missing values in key fields (salary, gender, role)
* Split 'Current Yearly Salary (in USD)' into minimum and maximum salary values
* Created an **Estimated Salary** column using the average of Min and Max
* Grouped ages into brackets (e.g., 18–24, 25–34) using Power BI's Group feature

# DAX Measures

* Career Switch Percentage
* Average Job Satisfaction
* Gender Ratio (Male vs. Female %)
* Count of Data Analysts

# Slicer Setup

* Slicers for Gender and Job Title
* Reset Filters button created using a Bookmark tied to default settings

# Branding & Layout

* Custom logo generated using prompt engineering (GenAI)
* Organized visuals with the Selection Pane for clean alignment

## Key Insights

* Average Estimated Salary: **\$114,820**
* Career Switchers: **61%** of respondents
* Average Job Satisfaction: **6.27 / 10**
* Gender Split: **70% male**, **30% female**
* Highest Paying Role: **Data Scientist** (\~\$200,000/year)

# Trends & Implications

* A majority of respondents are career switchers, showing the accessibility of data roles
* Higher satisfaction is linked to high-paying, specialized data roles
* Gender and age disparities point to a need for more inclusive hiring strategies

*Business Recommendations:

* Support career switchers with flexible training and onboarding programs
* Retain talent by investing in high-satisfaction, high-impact roles
* Expand recruitment efforts to improve gender and age diversity in data fields

# Dashboard Features

* KPI Cards showing Salary, Satisfaction, Gender Ratio, and Role Counts
* Slicers for filtering by Gender and Job Title
* Charts visualizing Salary Distribution, Job Satisfaction, and Role Frequency
* Reset Filters button using Power BI Bookmarks
* Clean layout with a custom logo and interactive visuals

# How to Use

1. Clone or download this repository
2. Open `Data_Professionals_Dashboard.pbix` in Power BI Desktop
3. Use slicers and visuals to explore career trends and workforce metrics
4. Share insights or customize the dashboard for presentations and decision-making

# Author

Olanireti


