Customer Churn Analysis
An interactive Power BI dashboard for exploring customer churn and retention across customer types, contract types, tenure bands, and other service criteria.
Overview
This project analyzes a raw dataset of 7,043 customer records. I used Power Query to prepare the data, created calculated columns and measures with DAX, and built an interactive dashboard in Power BI to help a company examine customer churn.
Tools
- Power BI — dashboard and visualizations
- Power Query — data preparation
- DAX — calculated columns and measures
Data preparation
The raw dataset is included in this repository. Preparation included correcting data types and creating these categories:
- Tenure band: 0–6 months, 6–12 months, and 12+ months
- Risk type: Normal and High Risk
- Customer type: New and Existing
Dashboard
The dashboard includes interactive visuals for exploring:
- Churn rate and customer totals
- Churn by contract type
- Churn rate by tenure band
- Retained customers by risk type
- Monthly charges by customer type and churn status
- Monthly charges by online security and online backup
 
Add a dashboard screenshot to the repository and update dashboard-screenshot.png to match its filename.

DAX measures
- Average monthly charges
- Avg monthly charges (Churned)
- Avg monthly charges (Retained)
- Churned Customer
- Churned Rate %
- Retained Customer
- Total Customer
Key figures shown
- Total customers: 7,043
- Churned customers: 1,869
- Churn rate: 26.54%
The dashboard also shows churn is highest for month-to-month contracts and for customers in the 0–6 month tenure band.
View the dashboard
Open (churn%20analysis.pbix) in Power BI Desktop to explore the interactive report.
Data source
[source name or link].
Project files and dashboard prepared by Samriti.
