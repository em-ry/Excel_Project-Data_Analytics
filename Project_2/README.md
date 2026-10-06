# Project Analysis
## Introduction
Here we set out to understand what skills top employers are looking for and which of them lands you a higher pay check.

## Questions to Analyze
To understand the data science job market, we asked the following:
1. Do more skills get you better pay?
2. What's the salary for data jobs in different regions?
3. What are the top skills of data professionals?
4. What's the pay for the top 10 skills?

## Excel Skills Used
The following Excel skills were utilized for analysis:
- 📊 Pivot Tables
- 📉 Pivot Chart
- 🧮 DAX(Data Analysis Expressions)
- 🔎 Power Query
- 💪 Power Pivot

## Data Jobs Dataset
The dataset used for this project contains real-world data science job information from 2023. 
It includes detailed information on:
- 👨‍💼 Job titles
- 💰 Salaries
- 📍 Locations
- 🛠️ Skills

## (For first question)Do more skills get you better pay?
We used:
### 🔍Skill: Power Query (ETL)
#### 📥Extracting:
- I first used Power Query to extract the original data (data_salary_all.xlsx) and create two queries:
  - 🗃️ First one with all the data jobs information.
  - 🔧 The second listing the skills for each job ID.
#### 🔄Transform
- Then, I transformed each query by changing column types, removing unnecessary columns, cleaning text to eliminate specific words, and trimming excess whitespace.
  - 📊 data_jobs_all
    (img)
  - 🛠️ data_job_skills
    (img)

#### 🔗Load
- Finally, I loaded both transformed queries into the workbook, setting the foundation for my subsequent analysis.
  - 📊 data_jobs_all
    (img)
  - 🛠️ data_job_skills
    (img)

### 📊Analysis
#### 💡Insights
- 📈 There is a positive correlation between the number of skills requested in job postings and the median salary, particularly in roles like Senior Data Engineer and Data Scientist.
- 💼 Roles that require fewer skills, like Business Analyst, tend to offer lower salaries, suggesting that more specialized skill sets command higher market value.
  
  (chart img)
  
#### 🤔Final thought
- This trend emphasizes the value of acquiring multiple relevant skills, particularly for individuals aiming for higher-paying roles.


## To Answer The 3 Remaining Questions, I used:
### Skills: PivotTables & DAX, Power Pivot, and Advanced Charts (Pivot Chart) respectively.
### Charts & Insights:

#### (Second Question)What's the salary for data jobs in different regions?
  
  (chart img)

💡Insights
- 💼 Job roles like Senior Data Engineer and Data Scientist command higher median salaries both in the US and internationally, showcasing the global demand for high-level data expertise.
- 💰 The salary disparity between US and Non-US roles is particularly notable in high-tech jobs, which might be influenced by the concentration of tech industries in the US.
 
🤔Final thought
- These salary insights are important for planning and salary negotiations, helping professionals and companies align their offers with market standards while considering geographical variations.


#### (Third Question)What are the top skills of data professionals?
  
  (chart img)

💡Insights
- 💻 SQL and Python dominate as top skills in data-related jobs, reflecting their foundational role in data processing and analysis.
- ☁️ Emerging technologies like AWS and Azure also show significant presence, underlining the industry's shift towards cloud services and big data technologies.
 
🤔Final thought
- Understanding prevalent skills in the industry not only helps professionals stay competitive but also guides training and educational programs to focus on the most impactful technologies.


#### (Fourth Question)What’s the pay of the top 10 skills?
  
  (chart img)

💡Insights
- 💰 Higher median salaries are associated with skills like Python, Oracle, and SQL, suggesting their critical role in high-paying tech jobs.
- 📉 Skills like PowerPoint and Word have the lowest median salaries and likelihood, indicating less specialization and demand in high-salary sectors.
 
🤔Final thought
- This chart highlights the importance of investing time in learning high-value skills like Python and SQL, which are evidently tied to higher paying roles, especially for those looking to maximize their salary in the tech industry.


## Conclusion
By leveraging Excel features like Power Query, PivotTables, DAX, and charts, I was able to find key correlations between multiple skills and higher salaries, particularly in Python, SQL, and cloud technologies.
I hope this project is found useful as a practical guide for data professionals and provides an overview of the skills needed for higher-paying roles.
