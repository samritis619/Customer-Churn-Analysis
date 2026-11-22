# Customer Churn Analysis

An **interactive Power BI dashboard** for exploring customer churn and retention across customer types, contract types, tenure bands, and other service criteria.

## Project Overview

This project analyzes a raw dataset containing **7,043 customer records**. I used **Power Query** to prepare the data, created calculated columns and measures with **DAX**, and built an interactive dashboard in **Power BI** to help a company examine customer churn.

## Tools Used

- **Power BI** — dashboard and visualizations
- **Power Query** — data preparation
- **DAX** — calculated columns and measures

## Data Preparation

The raw dataset is included in this repository. Preparation included correcting data types and creating the following categories:

- **Tenure band:** 0–6 months, 6–12 months, and 12+ months
- **Risk type:** Normal and High Risk
- **Customer type:** New and Existing

## Dashboard

The dashboard includes interactive visuals for exploring:

- **Churn rate** and customer totals
- **Churn by contract type**
- **Churn rate by tenure band**
- **Retained customers by risk type**
- **Monthly charges by customer type and churn status**
- **Monthly charges by online security and online backup**

![Customer Churn Analysis dashboard]
<img width="1470" height="829" alt="image" src="https://github.com/user-attachments/assets/97557606-b113-4732-8d13-667ebc4bb35d" />


## DAX Measures

- **Average monthly charges**
- **Avg monthly charges (Churned)**
- **Avg monthly charges (Retained)**
- **Churned Customer**
- **Churned Rate %**
- **Retained Customer**
- **Total Customer**

## Key Figures

- **Total customers:** 7,043
- **Churned customers:** 1,869
- **Churn rate:** 26.54%

The dashboard also shows that churn is highest for **month-to-month contracts** and customers in the **0–6 month tenure band**.

## How to View the Dashboard

Open "churn analysis.pbix" in **Power BI Desktop** to explore the interactive report.

## Data Source

Add the dataset’s source here: **telco_churn_unclean.csv**.

---

**Project files and dashboard prepared by Samriti.**
