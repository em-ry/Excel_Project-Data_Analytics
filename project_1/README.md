# My Excel Data Analytics Projects
This repo contains the hands-on projects carried out while taking LukeBarousse's Excel Data Analytics course.

## Introduction
This data jobs salary dashboard was created to help job seekers investigate and have an idea 
of the salaries being offered for their desired job roles.

## Dashboard File
My final dashboard is in [1_Salary_Dashboard.xlsx](1_Salary_Dashboard.xlsx)

## Excel Skill Used
The following excel skills were utilized for analysis:
- 📉Charts
- 🔠Formulas and Functions
- ⛔Data Validation

## Data Jobs Dataset
The dataset used for this project contains real-world data science job information from 2023. It includes detailed information on:
- 👨‍💼Job Titles
- 💰Salaries
- 📍Locations
- 🛠Skills

## Dashboard Build

### 📉Charts
#### Data Science Job Salaries - Bar Chart
(img/gif)

- 🛠Excel Features: Utilized bar chart feature (with formatted salary values) and optimized layout for clarity.
- 🎨Design Choice: Horizontal bar chart for visual comparison of median salaries.
- 📈Data Organization: Sorted job titles in descending order for improved readability.
- 💡Insight Gained: This enables quick identification of salary trends, noting that Senior roles and Engineers are higher-paying than Analyst roles.

#### 🗺Country Median Salaries - Map Chart
(img/gif)

- 🛠Excel Features: Utilized excel's map chart feature to plot median salaries globally.
- 🎨Design Choice: Color coded map to visually differentiate salary levels across regions.
- 📈Data Organization: Plotted median salary for each country with available data.
- 👁visual Enhancement: Improved readability and immediate understanding of geographic salary trends.
- 💡Insight Gained: Enables quick grab of global salary disparities and highlights high/low salary regions.

### 🔠Formulas and Functions
#### 💰Median Salary by Job Titles
(code snippet)

- 🔎Multi-Criteria filtering: Checks job title, country, shedule type, and excludes blank salaries.
- 📊Array Formula: Utilizes MEDIAN() functions with nested IF() to analyze an array.
- 💡Tailored Insights: Provides specific salary information for job titles, regions, and schedule type.
- 🔠Formula Purpose: This formula populates the table below, returning the median salary based on job title, country, and type.

#### Background Table
(table snippet)

#### Dashboard Implementation
(dashboard snippet)

### ⛔Data Validation
#### 🔎Filtered List
- 🔒Enhanced Data Validation: Implementing the filtered list as a data validation rule under the Job Title, Country, and Type option in the data tab ensures:
  - 🎯User input is restricted to predefined validated schedule types,
  - 🚫incorrrect or inconsistent entries are prevented,
  - 👥overall usability of the is enhanced
(data validation snippet)

## Conclusion
This dashboard was created to show/provide insights into salary trends across various data-related job titles. By utilizing the data provided, this dashboard allows users to make informed decisions about their career paths based on the job market.
