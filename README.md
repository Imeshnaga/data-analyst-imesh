# Descriptive Analysis 
# Project Description: Descriptive Analysis of Occupational health and safety at UCW
# Project Title: Understanding Inspection report of incident happened on 2024
- Objective: The primary goal of this project is to conduct a descriptive analysis of the Inspection report. Through this analysis, I aim to summarize key characteristics of inspection completions, identify trends, and generate insights that can inform health and safety strategies to UCW.
# Dataset: The dataset includes descriptive data from Occupational health and safety at UCW over the recent year 2024, containing the following key features:
- No of incident: Unique identifier for each incident
- Date: Date and time of the incident
- Department: Department name
- Issue : What is the issue for the incident happened 
- Severity : Medium, High , Low
- Location : What is the exact place that incident happened
- Status : Current status
- Action taken : What kind of action taken
# Methodology:
# Steps
# 1- Data Collection and Preparation:
- Load the dataset using data analysis tools (Excel) .
- Perform data cleaning to address missing values, correct data types, and remove duplicates.
# 2- Descriptive Statistics: 
This section should summarize key statistics using data stored in the S3 bucket “ hr-occupational-health-and-safety-imesha “ in its different stages (landing, raw, curated) and processed via an ETL pipeline.
# Landing Zone (S3 Bucket - Landing Folder):
- Upload the original dataset.
- The dataset should contain raw data about incidents such as the incident ID, date, department, severity, and status.
# Raw Zone (S3 Bucket - Raw Folder):
- After the ETL pipeline processes the data from the landing zone, store the cleaned data (with corrected data types, missing values addressed, and duplicates removed) here.
Curated Zone (S3 Bucket - Curated Folder):
- After completing the transformations and aggregations, store the final summarized data here.
- The data here should include cleaned and processed insights ready for analysis and visualization.
# 3- Data Visualization: 
- In this section, use Draw.io for visualizing data insights , for visualizations created based on the curated data in the S3 bucket after ETL processing.
# 4- Recommendations: 
- Improving Health and Safety Protocols:
- Departments with high incident frequency should receive targeted safety training and enhanced protocols.
- Recommend focusing on departments that show high incident counts in the curated data.
- Severity Reduction:
- Suggest additional safety checks in areas with a high percentage of medium to high severity incidents, as identified in your visualizations.
- Incident Tracking and Resolution:
- Use data stored in the curated folder to enhance the tracking of ongoing and pending incidents, recommending an automated process for quick updates and alerts.
# Tools and Technologies:
- Excel , AWS Services, S3 bucket
- Data visualization tools : Draw.io ,ETL pipeline
# Deliverables:
- A detailed report summarizing the methods, findings, and recommendations.
- Visualizations and dashboards to present key insights clearly.
- A presentation for particular department head to communicate important findings and suggestions for future action.
# This descriptive analysis project aims to provide a comprehensive understanding of incidents happened at UCW and to improve health and safety procedures and policies at UCW to mitigate the accidents.
# Screen shot 1 : Operational environment analysis and Data analytics Platform 
![AWS Project 1](https://github.com/Imeshnaga/data-analyst-imesh/blob/main/Screen%20shot%201-Operational%20environment%20analysis%20and%20Data%20analytics%20Platform.png)

