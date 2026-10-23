# financial-fraud-analysis-sql-powerbi

### Project Overview

The aim of this project is to analyze a large-scale financial transaction dataset using SQL and Power BI to identify **potential fraud patterns**, uncover systemic control weaknesses, and analyze various aspects of financial transactions, including transaction status, card type, payment method, transaction amount, and fraud indicators.

### Objectives

- Analyze large-scale financial transaction data using SQL to identify trends, patterns, and anomalies.
- Generate actionable insights to identify potential risk areas, improve fraud monitoring, and support data-driven decision-making.
- Identify potential fraudulent patterns by analyzing transaction details and fraud indicators.
- Evaluate various aspects of financial transactions, including transaction status, amount, card type, and payment method.
- Develop interactive Power BI dashboards to present key metrics, trends, and insights effectively.

### Dataset Description

The dataset consists of four tables: **Card, Merchant, Customers, and Transaction**. It contains approximately **250,000 financial transaction records**, which are used to analyze transaction patterns, identify potential fraud, and gain insights into customer behavior, merchant activity, and payment methods.

### Data Cleaning and Preparation for Analysis

Created a database in PostgreSQL and imported the dataset into it to perform SQL queries and analyze financial transactions, identify potential fraud patterns, and generate meaningful insights.

Additionally, I used Power Query to clean, transform, and prepare the dataset for analysis. I then imported the prepared data into Power BI and established relationships between the tables using data modeling and create **date table** to support accurate analysis and interactive dashboard development.

Data modeling image

In Dashboard i build Four KPI’s (Fraud Rate%, Fraud Loss Value, Fraud Prevention Rate, Average Transaction Value) and 10 Visuals and 3 Tables

## Key Findings and Business Insights

- Below 5 Lakh has highest fraud report which is around 12898 and lowest is above 15 lakh
- In customer segment **platinum** (1031) and **gold** (1023) has highest successful fraud report
- **Kochi** in top city for fraud report and bottom **jamnagar**
- Insight: Debit cards account for the highest share of reported fraud (50.5%), while net banking has the lowest (2.5%)
- Insight: POS transactions have the highest fraud rate at 2.5%, while online web transactions have the lowest at 0.5%.
- Insights: POS terminals have the highest fraud rate at 2.5%, while Windows PCs have the lowest.
- Customers aged 36–45 account for the highest number of reported fraud cases.

### Conclusion

The analysis identifies key fraud patterns across transaction amounts, customer segments, cities, payment methods, devices, and age groups. Fraud reports are highest for transactions below ₹5 lakh, Platinum and Gold customers, Kochi, debit cards, POS terminals, and customers aged 36–45. These insights can help financial institutions identify high-risk areas, improve fraud detection, and strengthen fraud prevention strategies.
