# Data-Analysis-and-Insights-Generation-for-Employee-Dataset
Explore the dataset ,do data cleaning. Perform Exploratory Data Analysis (EDA).Data Visualization anf finally load into oracle database


**Data Exploration and Cleaning:**


Load the dataset and perform basic data exploration to understand the data structure.

Identify and handle any missing values, duplicates, or inconsistencies.

Convert any necessary columns to appropriate data types (e.g., salary to numeric, work_year to integer).

**Exploratory Data Analysis (EDA):**

**Salary Analysis:**

Calculate average and median salary both in salary_currency and salary_in_usd.

Compare salaries across different experience_levels and job_titles.

**Remote Work Trends:**

Analyze the distribution of remote_ratio to identify the prevalence of remote work.

Identify any trends in remote work by job_title and company_location.

**Experience and Employment Insights:**

Create a breakdown of employment_type by experience_level to see which employment types are most common at each level.

Generate counts or percentages of different experience_levels across various company_sizes.

**Data Visualization:**

Visualize the salary distribution across different job roles and experience levels using box plots or violin plots.

Create a bar chart to show the average remote_ratio by job_title.

Use a heatmap to show the correlation between remote_ratio, salary_in_usd, and experience_level.

Plot a bar chart for company_size distribution and how it correlates with employment_type and experience_level.

**Insights and Reporting:**

Summarize key insights found from the analysis, such as:

Which job titles offer the highest remote work ratios.
The most common employment_type and experience_level combinations.
Any interesting trends in salary based on experience_level, job_title, and company_size.
Prepare a report with visualizations and written insights, discussing patterns, trends, and any recommendations.

**Storing Results in Oracle Database:**

Design an Oracle database table schema to store the cleaned and analyzed data.
Insert the analyzed data (e.g., average salary by job_title, remote work trends) into the Oracle database.
Verify the data insertion by querying the database and comparing sample records to ensure consistency.
