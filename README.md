# Shield Insurance Analysis Power BI Report for AtliQ Technologies
This project is a part of my internship with Atliq Technologies, guided by the Codebasics Power BI Job-Ready Program. The project aims to analyze and deliver data-driven insights for Shield Insurance, a fictional company offering coverage to both individuals and businesses.<br /><br />

**Shield Insurance Analysis:** [Access Live Report Link](https://app.powerbi.com/view?r=eyJrIjoiMTIxZjgxODctN2M0My00Y2E3LTkyZjYtZWE0NGYzZjA2OGQyIiwidCI6ImRmODY3OWNkLWE4MGUtNDVkOC05OWFjLWM4M2VkN2ZmOTVhMCJ9)<br />
**Project Presentation:** [Audio Presentation]()

## About the Company
Shield Insurance is a trusted insurance provider in India offering comprehensive and reliable plans. The company is focused on customer satisfaction and helping policyholders feel secure through tailored coverage across all age groups and cities.<br /><br />

## Business Objective
- The company wanted to analyze:<br />
- Total revenue and customer growth trends<br />
- Daily KPIs for revenue and customer acquisition<br />
- City-wise and age-wise segmentation<br />
- Sales performance by channel<br />
- Age group behavior with policy preferences and settlement expectations<br />
- The goal was to identify key growth areas, optimize product offerings, and enhance sales channel effectiveness.<br />

## Data Sources
- The project uses 5 main datasets, structured in a star schema:<br />
- dim_customer.csv → Customer details (city, DOB)<br />
- dim_date.csv → Date hierarchy with months, weekdays, and week numbers<br />
- dim_policies.csv → Policy metadata (base cover, base premium)<br />
- fact_premiums.csv → Premium payments, sales mode<br />
- fact_settlements.csv → Settlement percentages by age<br />

## Tools & Technologies Used
- Power BI Desktop<br />
- DAX & Power Query Editor<br />
- Excel/CSV for Data Source<br />
- Microsoft PowerPoint (for final report)<br />

## Data Modelling and Relationships
Data modeling is the process of structuring and organizing data to create relationships, and establish a framework for effective data analysis and reporting. It ensures data accuracy, facilitates complex calculations, and enhances data integration, providing a solid foundation for informed decision-making and business intelligence.<br /><br />
In this project, we followed the **Star Schema** data modeling method.<br /><br />
![Data Model](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Data%20Model.png)<br /><br />

## Report Overview
**Home**<br />
The Home page acts as a navigation panel and welcome screen for users. It includes:<br />
- Shield Insurance logo and branding<br />
- A short description of the purpose and focus areas of the dashboard<br />
- Navigation buttons to:<br />
  - Overview<br />
  - Sales Mode Analysis<br />
  - Age Group Analysis<br />
![Home Page](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Home%20View.png)<br /><br />

**Overview**<br />
This page summarizes the overall business performance with key metrics and visuals:<br />
- **Key KPIs**: Total Revenue, Total Customers, Daily Revenue Growth, Daily Customer Growth<br />
- **Customer Split**: By Age Group<br />
- **Revenue Split**: By City<br />
- **Customer Segmentation**: Shows distribution of customers and revenue across cities<br />
- **Trend by Months**: Line chart tracking total revenue over the last six months<br />
![Overview](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Overview.png)<br /><br />

**Sales**<br />
This page analyzes how different sales channels perform:<br />
- **Customer Split by Sales Mode**: Pie chart showing customer distribution across:<br />
  - Offline-Agent<br />
  - Offline-Direct<br />
  - Online-App<br />
  - Online-Website<br />
- **Revenue Split by Sales Mode**: Corresponding revenue distribution<br />
- **Trend of Sales Mode Over Months**: Line chart comparing each mode's monthly revenue over time<br />
![Sales](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Sales.png)<br /><br />

**Age Group**<br />
This page focuses on how different age segments interact with policies:<br />
- **Age Group vs Policy Preference**: Matrix showing how many customers from each age group opted for each policy<br />
- **Age Group vs Expected Settlements**: Donut chart showing settlement amount vs age group<br />
- **Age Group vs Sales Mode**: Stacked bar showing sales mode preference by age<br />
- **Customers by Age Group**: Horizontal bar graph for customer count<br />
- **Monthly Trends by Age Group**: Area chart visualizing age group activity over time<br />
![Age Group](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Age%20Group.png)<br /><br />

## Final Recommendations
- Retain & Upsell: Focus on 31–40 age group with personalized plans<br />
- Grow Digitally: Strengthen App & Website user experience<br />
- Target Gaps: Invest in outreach for 18–24 and 65+ customers<br />
- City Strategy: Replicate Delhi NCR’s approach in other metros<br />
- Risk Control: Implement smarter pricing for high-settlement age groups<br />

**Novypro Shield Insurance Analysis:** [Access Live Report Link](https://www.novypro.com/create_project/shield-insurance-analysis-9)<br />
[PDF](https://github.com/neha071999/Shield-Insurance-Analysis-Power-BI-Report-for-AtliQ-Technologies/blob/main/Shield_Insurance_Analysis%20-%20Power%20BI_Presentation_Report.pdf)

### Thank You!
