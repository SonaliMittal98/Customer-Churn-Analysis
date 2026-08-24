# Databel Customer Churn Analysis & Retention Insights Dashboard | Power BI
An interactive Power BI Document with KPIs, charts, maps, filters and visualizations designed to communicate key findings clearly and support data-driven business decisions.

## Short Description
This project analyzes why customers are leaving Databel, a telecommunications provider in United States, using Microsoft Power BI. The analysis explores customer churn patterns, identifies the key reasons and categories behind customer attrition, and investigates how demographics, age, contract types, payment methods, data and international plans, customer service interactions, and geographic factors influence churn rate.

## Project Objective
The primary objective is to understand why customers are churning, identify customer segments and factors associated with higher churn, and provide actionable insights that can help Databel improve customer retention.

## Dataset used
- <a href="https://github.com/SonaliMittal98/Customer-Churn-Analysis/blob/main/Databel%20-%20Data.csv.xlsx">Databel-data.csv</a>
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

## Customer Churn | Power BI
- <a href="https://github.com/SonaliMittal98/Customer-Churn-Analysis/blob/main/Analyzing%20Customer%20Churn.pbix">View pbix</a>

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

## Key Visuals and Insights
- #### KPI Cards – Customer Overview
   The dashboard begins with three key KPIs:
  Number of Customers: 6,687

  Number of Churned Customers: 1,796

  Churn Rate: 26.86%

  These KPIs provide an immediate overview of the company's overall customer retention situation and allow users to monitor the scale of customer attrition.
- #### Churn Reasons
  The bar chart ranks the different reasons why customers leave Databel, allowing users to identify the most significant drivers of customer attrition. The visualization is filtered to churned customers and displays each reason as a percentage of the total churners. This helps Databel understand what is causing customers to churn and where retention efforts should be focused.
- #### Churn Category
  The pie chart visual groups of individual churn reasons into broader categories, making it easier to identify the major themes driving customer attrition. The analysis identifies Competitor as the most prevalent churn category, highlighting competitive pressure as an important area for Databel to investigate.
- #### Geographic Churn Map
  An interactive map displays customer churn rates across U.S. states and allows stakeholders to identify geographical areas with unusually high churn. California (CA) stands out with a particularly high overall churn rate of 63.24% in the analysis.
- #### Contract & Customer Segment Analysis
  The column chart visuals compare customer characteristics and churn across different contract types, including Month-to-Month, One Year and Two Year contracts, revealing substantial differences in churn. The analysis highlights a substantial difference in churn behavior: Month-to-Month customers have a much higher churn rate of 46.29%, while One Year contract has churn rate of  11.29% and Two Year contract customers have a substantially lower churn rate of 2.78%.
- Overview
- <img width="637" height="373" alt="Overview" src="https://github.com/user-attachments/assets/1fbb1e71-7a5d-4391-8673-09038df5623f" />

- #### Age & Demographic Analysis
  The column and line chart visuals analyze churn patterns across customer segments. Customers are categorized into age groups such as Senior, Under 30 and Other, while age is further analyzed using five-year bins.

  The analysis shows that Senior customers have a significantly higher churn rate of 38.46%, helping identify a customer segment that may require additional retention attention.
- Churn Demographics
- <img width="663" height="372" alt="Churn Demographics" src="https://github.com/user-attachments/assets/6ceb059b-079f-47c6-9c31-850961d8cbd6" />
 
- #### Customer Service Analysis
  The line chart compares average customer service calls between churned and non-churned customers and can further be broken down by state.

  The analysis identifies a relationship between customer service calls and churn, indicating that customers who churn tend to have a higher rate of customer service calls than non-churners.
- Customer Service
- <img width="1273" height="745" alt="Insights" src="https://github.com/user-attachments/assets/a9578f86-34be-43c0-b915-7e100bf622c1" />

## Strategic Recommendations & Business Opportunities
Based on the analysis, the following strategic opportunities were identified to help Databel address key churn drivers, improve customer retention, and prioritize high-risk customer segments.
- ##### Strengthen Competitive Position:
  Since Competitor is the leading churn category, Databel should investigate competitor pricing, offers, devices, and services and develop targeted retention offers for customers at risk of switching. 
- ##### Encourage Longer-Term Contracts:
  Month-to-month customers have substantially higher churn than customers on longer-term contracts. Databel could focus on incentives that encourage customers to move toward one-year or two-year contracts. 
- ##### Prioritize High-Risk Customer Segments:
  Segments with elevated churn—such as senior customers and customers with specific combinations of contract, payment, and service characteristics—should receive targeted retention campaigns rather than a one-size-fits-all approach. 
- ##### Investigate High-Churn States:
  California's particularly high churn rate of 63.24% indicates that state-level factors should be investigated separately. Databel could analyze local competition, pricing, service quality, and customer preferences to understand the underlying causes. 
- ##### Improve Customer Service Experience:
  Since churned customers show higher customer-service call activity, Databel should investigate recurring service issues and improve resolution processes to reduce customer dissatisfaction. 
- ##### Optimize Customer Plans:
  Customers whose actual usage does not align with their plans should be identified. For example, customers paying for international plans without using international calling could be contacted and offered a more suitable/downgraded plan. 

## Final Conclusion:
The Databel Customer Churn Analysis provides a comprehensive view of customer attrition, its key drivers, and the customer segments most vulnerable to churn. With an overall churn rate of 26.86%, customer retention represents a significant business challenge. 

The analysis shows that competitive pressure is the leading churn category, while contract type, customer demographics, geography, plan usage, payment methods, and customer service interactions also reveal meaningful differences in churn behavior. In particular, month-to-month customers and senior customers emerge as important segments for further retention analysis. 
Geographic analysis further highlights substantial variation in customer churn, with California recording a 63.24% churn rate in the analysis. The relationship between customer service interactions and churn also suggests that service experiences may be an important area for Databel to investigate. 

Overall, the Power BI dashboard transforms customer-level data into actionable business insights, enabling stakeholders to identify high-risk segments, understand the major factors associated with churn, and focus retention efforts more effectively. The analysis supports a targeted, data-driven retention strategy rather than a one-size-fits-all approach.


