# Credit-Card-Financial-Dashboard

## Problem Statement  
This project addresses the need for real-time monitoring of credit card operations through the development of a dynamic financial dashboard. Traditional reporting tools often fall short in tracking revenue fluctuations, customer demographics, delinquency risks, and transactional trends. The dashboard solves this challenge by providing a comprehensive weekly overview, helping financial institutions make data-driven decisions, identify high-performing segments, and uncover growth opportunities.

## Tools Used  
- Power BI – Dashboard creation, KPI modeling, and visual analytics  
- MySQL – Relational data storage and structured querying  
- SQL – Data processing, transformation, and import  
- CSV – Raw data format for both customer and transaction-level details

---

## Process Breakdown  

### 1. SQL Database Setup & Data Ingestion  
- Designed a PostgreSQL database named `ccdb` with separate tables for transactional data and customer demographics.  
- Imported raw CSV files into respective tables, resolved date format inconsistencies, and appended Week 53 data for a complete year-to-date (YTD) view.

### 2. Data Modeling & Metric Calculations (Power BI)  
- Categorized customers based on age, income, education, and marital status  
- Built time-based metrics using week numbers to standardize weekly trend analysis  
- Created essential measures such as total revenue, income, interest earned, and weekly revenue comparisons

### 3. Dashboard Development & Key Insights  
- Developed an interactive Power BI dashboard with filters for quarter, gender, card tier, and transaction type  
- Visualized:
  - Revenue by week, age group, education level, income group, marital status, and dependents  
  - Customer segmentation based on job types and geographic contribution (Top 5 states)  
  - Overall portfolio performance including interest earned and customer spend score (CSS)

---

## Outcome / Impact  

- **Real-Time Insights:** Enabled stakeholders to track week-on-week performance metrics including revenue growth and delinquency trends  
- **Targeted Optimization:** Provided granular insights into high-value segments such as high-income customers in Texas, New York, and California  
- **Risk Mitigation:** Highlighted a delinquency rate of 6.06%, supporting early intervention strategies  
- **Strategic Growth:** Identified emerging opportunities within female customers and medium-income individuals aged 30–40—segments with untapped revenue potential

---

## Business Value  
The dashboard led to a 28.8% revenue increase in Week 53 by spotlighting high-performing segments and operational inefficiencies. It empowers financial decision-makers to optimize marketing strategies, improve customer acquisition and retention programs, and mitigate risks in the credit card portfolio—all in real time.
