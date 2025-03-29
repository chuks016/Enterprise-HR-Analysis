# Enterprise HR Analysis

## Table of Content
- [Project Overview](project-overview)
- [Data Sources](data-sources)
- [Tools](tools)
- [Dataset Description](dataset-description)
- [Exploratory Data Analysis](exploratory-data-analysis)
- [Data Analysis](data-analysis)
- [Results](results)
- [Recommendations](recommendations)
- [Limitations](limitations)
- [References](references)


### Project Overview

This project focuses on analysing an HR dataset to extract actionable insights, enhance decision-making, and support HR strategies. The dataset includes comprehensive information about employees, such as demographic details, performance metrics, training records, and employment classifications. The analysis aims to identify key trends, improve workforce efficiency, and optimise training expenditures.

### Data Sources

The dataset used in this project is structured to simulate real-world HR records for analytical purposes. It encompasses multiple aspects of employee data to facilitate a meaningful exploration of workforce dynamics.

### Tools

- Excel - Used for cleaning and preparing the dataset by removing inconsistencies, formatting data, and performing initial aggregations. [Download here](https://microsoft.com)
- Power BI - Utilised for creating visually engaging and interactive dashboards to summarise and explore trends in the data. [Download here](https://microsoft.com)

### Dataset Description

The dataset contains the following key columns:

1. Employee Information: Emp ID, Start Date, Job Title, Department, Business Unit, Division, Employee Status, Employee Type, Pay Zone, Employee Classification Type.

2. Demographics: DOB, Age, State, Gender, Race, Marital Status.

3. Performance Metrics: Performance Score, Current Employee Rating, Survey Date, Engagement Score, Satisfaction Score, Work-Life Balance Score.

4. Training Data: Training Date, Training Programme Name, Training Type, Training Outcome, Training Duration (Days), Training Cost.

### Exploratory Data Analysis

EDA was conducted to address the following questions:

- Total number of employees.

- Gender distribution of employees.

- Average age of employees and their distribution across age groups.

- Number of employees in each department or business unit.

- Classification of employees (full-time vs. part-time).

- Geographic distribution of employees across states.

- Average training cost per department and identification of cost-effective training programmes.

- Total training expenditure.

- Gender-based training expenditure.

- Total number of currently active employees.

### Data Analysis

Step 1: Data Cleaning & Preparation

- Verified data consistency by checking for duplicates and formatting discrepancies.

- Reformatted and categorised variables such as gender and training outcomes for clarity.

Step 2: Data Aggregation

- Calculated metrics for employee demographics and classifications.

- Segmented training costs by department and gender for further analysis.

Step 3: Data Analysis

- Analysed department-wise distribution of employees to understand organisational structure.

- Examined training costs and outcomes to identify areas of potential savings.

- Evaluated employee engagement and satisfaction scores by gender and age groups.

Step 4: Visualisation & Insights

- Created Power BI dashboards to visualise distributions and trends.

- Highlighted cost-effective training programmes and departments with the highest workforce engagement.

### Results

1. Total Employees: The organisation has a total of 2,845 employees.

2. Gender Distribution: 1,588 females (56%) and 1,257 males (44%).

3. Average Age: The average age of employees is 50 years, with age groups categorised as follows:
   - Advanced: 970 employees
   - Adults: 952 employees
   - Aged Adults: 672 employees
   - Young Adults: 251 employees

4. Departmental Breakdown: Employees are distributed across departments as:
   - Production: 1,910 employees
   - IT/IS: 409 employees
   - Sales: 311 employees
   - Software Engineering: 112 employees
   - Admin Offices: 79 employees
   - Executive Offices: 24 employees
  
5. Employee Classification
   - Full-time: 966 employees (34%)
   - Part-time: 980 employees (34%)
   - Temporary: 899 employees (32%)

6. State Distribution: Employees are spread across various states in the United States as shown in the dashboard, Massachusetts has the highest number of staffs (2523)

7. Training Costs
   - Total Training Cost: £2 million
   - Training Cost by Department:
     - Production: £230.4K
     - IT/IS: £66.32K
     - Sales: £140.5K
     - Software Engineering: £1.36K
    
8. Attrition: 387 employees have left the organisation, giving an attrition rate of 14%.

9. Active Employees: Using attrition data, 2,458 employees are currently active (2,845 total employees minus 387 who departed).

### Recommendations

- Foster gender equity if significant disparities are identified in representation or training opportunities.
- Optimise training expenditures by focusing on departments or programmes with higher cost-effectiveness.
- Address states or business units with lower employee numbers to ensure balanced growth.
- Encourage employee engagement initiatives in age groups or demographics with lower satisfaction scores.
- Continue exploring data to enhance workforce planning and decision-making.

### Limitations

- The dataset might contain simulated data that may not fully represent real-world variations.
- External factors influencing satisfaction, engagement, or performance were not accounted for in this analysis.
- Limited granularity in some fields (e.g., training details) may restrict deeper insights.

### References

1. Data Analytics Made Accessible by Dr. Anil Maheshwari
2. Data Analysis Training/Mentorship by Webdeves Academy
3. [Data Analyst Bootcamp by Alex The Analyst](Data Analyst Bootcamp: http://www.youtube.com/playlist?list=PLUaB-1hjhk8FE_XZ87vPPSfHqb6OcM0cF)
