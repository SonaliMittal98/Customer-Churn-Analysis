# Databel Customer Churn Analysis & Retention Insights Dashboard | Power BI
An interactive Power BI Document with KPIs, charts, maps, filters and visualizations designed to communicate key findings clearly and support data-driven business decisions.

## Short Description
This project analyzes why customers are leaving Databel, a telecommunications provider in United States, using Microsoft Power BI. The analysis explores customer churn patterns, identifies the key reasons and categories behind customer attrition, and investigates how demographics, age, contract types, payment methods, data and international plans, customer service interactions, and geographic factors influence churn rate.

## Project Objective
The primary objective is to understand why customers are churning, identify customer segments and factors associated with higher churn, and provide actionable insights that can help Databel improve customer retention.

## Dataset used
- <a href="https://github.com/SonaliMittal98/Customer-Churn-Analysis/blob/main/Databel%20-%20Data.csv.xlsx">Databel-data</a>
## Data Source
Source: DataCamp

The Databel – data.csv dataset contains 29 columns, with one row representing each customer. It includes customer identifiers, churn information, demographic characteristics, account details, contract and payment information, service usage, customer service interactions, and various plan-related attributes.
The accompanying metadata document was used to understand the fields and their categories during the analysis.
- <a href="https://github.com/SonaliMittal98/Customer-Churn-Analysis/blob/main/Metadata%20-Analyzing%20Customer%20Churn.pdf">Metadata Sheet</a>

## Business Problem
Databel is experiencing customer churn and wants to understand why customers are leaving the company. A high churn rate can negatively affect revenue because acquiring new customers may not compensate for the loss of existing customers. "Comparing churn with the leaky bucket problem. Fill the bucket with more water (or new customers in this case), but overall revenue won't increase if existing customers are leaving the company.” It's easier to retain customers than to attract new customers, so for many companies it's a priority to reduce churn. Therefore, identifying the factors and customer segments associated with churn is important for improving customer retention.
The analysis investigates churn across multiple dimensions, including churn reasons and categories, demographics, age groups, contract types, payment methods, data and international plans, customer service interactions, and geographic differences across states.

## Key Business Questions
1.	What is Databel's overall customer churn rate, and how significant is customer attrition?
2.	What are the primary reasons and categories driving customers to churn?
3.	Which customer segments have the highest churn risk based on demographics and age?
4.	How do contract types influence customer churn, particularly month-to-month versus longer-term contracts?
5.	How does churn vary across different U.S. states, and which locations require greater attention?
6.	What is the relationship between payment methods and contract categories and customer churn?
7.	How do unlimited data plans and data consumption patterns relate to customer churn?
8.	Does international plan usage influence customer loyalty and churn?
9.	Is there a relationship between customer service interactions and customer churn?
10.	Which high-risk customer segments should Databel prioritize for targeted retention strategies?

-Dashboard Interaction <a href="https://github.com/SonaliMittal98/Customer-Churn-Analysis/blob/main/Analyzing%20Customer%20Churn.pbix">View pbix</a>

## Process
Based on the attached Databel case study, the overall data analysis process can be presented in the following points. The case study describes five broad stages: 
1. Data Collection & Import 
- Import the Databel Customer Churn CSV dataset into Power BI Desktop. 
- Review the accompanying metadata to understand the available fields and their meaning. 
2. Data Check & Validation 
- Check the dataset for duplicate records, missing values, and potential errors. 
-	Validate customer records by comparing the total customer count with the distinct customer count. 
-	Confirm that the dataset contains 6,687 unique customers. 
3. Data Transformation & Calculations 
-	Convert the Churn Label (Yes/No) into a numerical Churned field using conditional logic. 
-	Create measures such as Number of Customers, Number of Churned Customers, and Churn Rate. 
-	Create additional analytical fields such as demographic groups, age bins, contract categories, and grouped data consumption. 
4. Exploratory Data Analysis 
-	Investigate the main reasons and categories behind customer churn. 
-	Analyze churn patterns across demographics, age, contracts, payment methods, group plans, data plans, international activity, and customer service interactions. 
5. Data Analysis & Visualization 
-	Select appropriate Power BI visuals to answer specific business questions. 
-	Use bar charts, column charts, line charts, maps, matrices, tables, pie charts, scatter plots, and KPI cards to identify patterns and communicate findings. 
6. Customer Segmentation & Deep-Dive Analysis 
-	Compare churn across different customer segments. 
-	Identify high-risk groups based on factors such as contract type, age, demographics, payment method, geographic location, and service usage. 
-	Use slicers and filters to interactively investigate specific customer segments.
7. Data Modeling – Star Schema
- Designed a star schema from the original Databel dataset by separating relevant attributes into dimension tables and analytical metrics into a fact table. Established relationships between the tables to create a structured model that supports efficient filtering, aggregation, and analysis. 
8. Dashboard Development 
-	Combine the most important visuals into dashboard-style report pages. 
-	Build an Overview page containing the main KPIs and key churn insights. 
-	Create additional pages focused on age groups, payment and contracts, extra charges, and other insights. 
9. Insight Generation 
-	Identify important findings such as the 26.86% overall churn rate, the dominance of the Competitor churn category, and significant differences in churn across customer segments. 
10. Business Communication 
-	Present the findings through interactive dashboards designed to make the analysis easy for stakeholders to understand. 
-	Use the insights to highlight areas where Databel could investigate and prioritize customer retention opportunities. The case study explicitly identifies communicating insights to stakeholders as the final stage of the analysis flow.
