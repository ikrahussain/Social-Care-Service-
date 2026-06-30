# Social-Care-Service-

This data analysis project examined Social Care Service data for new Long Term Support (LTS) service users during the 2023–24 financial year. The dataset included information on new service users, service start dates, service types, waiting times and autism diagnoses. The analysis was carried out to better understand demand for social care services and identify patterns that could support operational and strategic decision-making. The main questions were: How many new people required Long Term Support? Were there seasonal trends in demand? Which service types were most common? What were the typical waiting times for services to begin? The findings provide insights that could help improve workforce planning, resource allocation, service commissioning and performance monitoring within a local authority social care setting.

---

## Table of Contents

- [Overview](#overview)  
- [Dataset](#dataset)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Analysis & Visualizations](#analysis--visualizations)  
- [Conclusion](#conclusion)  
- [Credits](#credits)  
- [License](#license)  

---

## Overview

- **Motivation:**
I chose this Social Care Service dataset because it reflects the type of data used by local authorities to support public services and informed decision-making. As someone interested in Business Intelligence and data analysis, I wanted to explore how data can be used to understand service demand, monitor performance and identify opportunities to improve service delivery. The project also allowed me to apply data analysis and visualisation techniques to a realistic business scenario.

- **Objective:**
The objective of this analysis was to examine new Long Term Support (LTS) service users during the 2023–24 financial year and answer several key questions:
- How many new people accessed Long Term Support services?
- Were there any monthly or seasonal trends in new service starts?
- Which service types were most commonly provided?
- What proportion of new users had a recorded autism diagnosis?
- What was the typical waiting time between assessment completion and service commencement?

The overall aim was to generate insights that could support service planning, resource allocation and performance improvement.

Learning Outcomes  
- **Learning Outcomes:**
Through this project, I strengthened my skills in data cleaning, analysis and dashboard creation using business intelligence tools. I learned how to identify trends, calculate key performance measures such as median waiting times and present findings in a clear and meaningful way for decision-makers. I also gained a better understanding of how social care data can be used to support evidence-based planning, monitor service performance and inform operational and strategic decisions within a local authority.

---

## Dataset

Provide details about the dataset used:

- Source of the dataset:
The dataset used for this project is a fictional Social Care Service dataset created for learning and portfolio purposes. It is designed to resemble data that could be used by a local authority, such as Nottinghamshire County Council, to analyse Long Term Support (LTS) service provision. As the dataset is fictional, there is no public source or download link available.

- Size of the dataset:
The dataset is organised into three worksheets:
Service Users – 5,000 rows containing Person ID, Service Description, Service Class, Start Date, End Date and Service Provider.
Assessments – 1,089 rows containing Person ID, Event, Assessment Start and Assessment End.
Health – 5,001 rows containing Person ID, Gender, Health Condition, Age Band and Accommodation Status.

Key Features/Columns Used
- Key features/columns used:
The analysis used data from all three worksheets, with Person ID serving as the primary key to link records. The main fields included:

Person ID – Unique identifier used to join the datasets.
Service Description – Type of social care service received.
Service Class – Categorisation of the service (e.g., Long Term Support).
Start Date and End Date – Used to identify new service users and analyse monthly service starts.
Service Provider – Organisation delivering the service.
Assessment Start and Assessment End – Used to calculate waiting times between assessment completion and service commencement.
Health Condition – Used to identify service users with recorded autism diagnoses.
Gender, Age Band, and Accommodation Status – Demographic characteristics that provide context about the service user population.

- Data Preprocessing and Cleaning

To prepare the data for analysis, the following steps were completed:

Combined the three worksheets using Person ID as the common key.
Filtered the data to identify 3,937 new Long Term Support service users during the 2023–24 financial year.
Standardised date formats to ensure accurate calculations and trend analysis.
Calculated the waiting time between Assessment End and Service Start Date.
Created a Month of Service Start field to analyse seasonal demand patterns.
Checked for missing values, duplicate records, and inconsistent data types, correcting or excluding records where necessary.
Validated the joined dataset to ensure records were matched correctly before carrying out the analysis.

---

<h2>Technologies Used</h2>

<ul>
  <li><strong>Languages & Libraries:</strong> Excel, Pivottables, Dynamicarrayformatting, SQL, Matplotlib, Seaborn</li>
  <li><strong>Tools:</strong> Conditionalformatting, VS Code, Git, GitHub</li>
  <li><strong>Data Visualization:</strong> Power BI / Tableau (if applicable)</li>
</ul>

<p>
  <img src="https://img.shields.io/badge/Excel-3776AB?style=for-the-badge&logo=excel&logoColor=white" alt="Excel">
  <img src="https://img.shields.io/badge/Pivottable-150458?style=for-the-badge&logo=pivottable&logoColor=white" alt="Pivot Table">
  <img src="https://img.shields.io/badge/Powerquery-013243?style=for-the-badge&logo=powerquery&logoColor=white" alt="Power Query">
  <img src="https://img.shields.io/badge/Dynamicarrayformatting-11557C?style=for-the-badge&logo=dynamicarrayformatting&logoColor=white" alt="Dynamic Array Formatting">
  <img src="https://img.shields.io/badge/Conditionalformatting-4C72B0?style=for-the-badge&logo=conditionalformatting&logoColor=white" alt="Conditional Formatting">
</p>

---

## Usage

Instructions for using the project:

1. Open the main notebook (`analysis.ipynb`)  
2. Run each cell sequentially to reproduce the analysis  
3. Visualizations and results will be generated automatically  

Visualizations:

<img width="1698" height="690" alt="image" src="https://github.com/user-attachments/assets/a6a6e5d2-349a-49ad-8339-2cbea8ac0fca" />

---

## Analysis & Visualizations 

Findings, Insights, and Visualisations
Overview

This analysis examined new Long Term Support service users during the 2023–24 financial year. The aim was to understand demand patterns, user characteristics and service waiting times to support operational and strategic decision-making within social care services.

Key Findings
1. New Service User Demand

A total of 3,937 individuals were identified as new Long Term Support service users during 2023–24.
Insight: This indicates the level of new demand entering social care services and helps the council understand future resource requirements.
Business Impact: Monitoring service user volumes supports workforce planning, budgeting and capacity management.

2. Monthly Trends in New Service Starts

The highest number of new service starts occurred in August, while the lowest occurred in January.
Insight: This suggests clear seasonal variation in demand for Long Term Support services.
Business Impact: Understanding peak periods allows managers to allocate staff and resources more effectively throughout the year.

3. Service Type Distribution

The most common service type among new users was Long Term Support.
Insight: Demand is concentrated within specific service categories.
Business Impact: This supports commissioning decisions and ensures sufficient provision is available where demand is highest.

4. Autism Prevalence

Only 3 service users had a recorded autism diagnosis.
Insight: A small proportion of users may require specialist or tailored support.
Business Impact: This helps inform service design, workforce training and planning for specialist provision.

5. Waiting Time Performance

The median waiting time between assessment completion and service commencement was 28 days.
Insight: The median provides a realistic measure of typical service experience by reducing the impact of extreme values.
Business Impact: Monitoring waiting times helps identify delays and supports service improvement initiatives.

Visualisations

The analysis was supported using charts and graphs to identify patterns and trends in the data.

The visualisation above highlights monthly variation in new Long Term Support service starts, showing clear fluctuations in demand across the year, with a peak in August and a low point in January.

Recommendations
Continue monitoring monthly demand trends to identify emerging changes in service needs.
Investigate months with unusually high or low service starts.
Regularly review waiting time performance to identify process improvements.
Use autism prevalence data to support planning for specialist services and staff training.
Extend analysis across multiple years to identify long-term trends.
Limitations
The dataset is fictional and may not fully reflect real-world social care activity.
The analysis covers only one financial year.
Missing or incomplete records may affect accuracy of results.
Autism is recorded as a simple Yes/No field and does not reflect varying levels of need.
Some individuals may receive multiple services, which may affect categorisation.
Conclusion

The analysis demonstrates how data can be used to understand demand, monitor service performance, and support evidence-based decision-making. In a Business Intelligence Analyst role, these insights could help inform service planning, resource allocation and continuous improvement within social care services.
---

## Conclusion 

Summary of Analysis

This analysis of Social Care Service data examined new Long Term Support service users during the 2023–24 financial year. The aim was to understand demand patterns, user characteristics and service waiting times to support operational and strategic decision-making within social care services.

Main Insights and Takeaways

The analysis identified 3,937 new Long Term Support service users, highlighting a significant level of demand on social care provision. Monthly trends showed clear variation in demand, with a peak in August and a low point in January, indicating seasonal patterns in service uptake.

Service type analysis showed that Long Term Support was the most common service category, demonstrating that ongoing care needs represent a major proportion of demand. Only 3 users had a recorded autism diagnosis, suggesting a relatively small but important cohort requiring potential specialist support. In addition, the median waiting time of 28 days between assessment completion and service start indicates variability in service delivery times and potential areas for improvement.

Impact on Decision-Making

These findings can directly support evidence-based decision-making within a local authority setting. Understanding demand trends can improve workforce planning, budgeting and capacity management, while identifying peak months supports more efficient resource allocation. Waiting time analysis provides insight into operational performance and can highlight delays in service delivery. Service and health-related insights can also support commissioning decisions and future service development.

Recommendations and Next Steps
Continue monitoring monthly demand patterns to identify changes in service usage over time.
Investigate reasons behind peak and low demand periods, particularly in August and January.
Review waiting time performance regularly to identify bottlenecks and improve service efficiency.
Expand the analysis across multiple years to identify long-term trends and improve forecasting accuracy.
Explore deeper demographic breakdowns (e.g., age band, accommodation status and health conditions) to better understand service needs and inequalities in access.

Final Statement

Overall, this analysis demonstrates how social care data can be used to generate meaningful insights that support operational planning, performance monitoring and strategic decision-making. In a Business Intelligence Analyst role at Nottinghamshire County Council, these insights would help improve service delivery, optimise resource allocation and support continuous improvement in social care services.

---

## Credits

- **Collaborators:** Name – [GitHub Profile](https://github.com/USERNAME)  
- **Dataset Source:** [Link](https://link-to-dataset.com)  

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/) – feel free to use and modify it.  

---

<p align="center"><strong>Thanks for visiting! 🚀</strong></p>
