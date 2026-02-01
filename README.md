## 📊 Data Source & Confidentiality

The data used in this project was accessed through internal company database credentials.
Due to data privacy and confidentiality policies, the raw dataset cannot be shared publicly.

However, the SQL queries provided in this repository are reusable and can be executed on
any database with a similar schema to reproduce the analysis.



## 📌 Project Overview

This project focuses on analyzing customer shopping behavior using SQL.
The objective is to identify trends across customer demographics,
purchase categories, payment methods, and revenue contribution
to support data-driven business decisions.

## ❓ Business Questions Answered

- How is the shopping distribution across genders?
- Which gender contributes more to total revenue?
- How does shopping behavior vary across age groups?
- Which age group generates the highest revenue?
- How do purchase categories differ across demographics?
- What payment methods are most preferred by customers?

## 🗄️ Database Schema

**Table: customer**

| Column Name     | Description |
|-----------------|-------------|
| invoice_no      | Unique transaction identifier |
| gender          | Customer gender |
| age             | Customer age |
| category        | Product category |
| quantity        | Number of items purchased |
| price           | Transaction amount |
| payment_method  | Mode of payment |
| shopping_mall   | Mall location |
| invoice_date    | Date of purchase |

## 🧠 SQL Analysis Performed

- Used `COUNT()` to measure transaction volume
- Applied `SUM()` to calculate total revenue
- Grouped data using `GROUP BY`
- Filtered records using `WHERE`
- Categorized age groups using `CASE WHEN`
- Performed date-based analysis using `YEAR(invoice_date)`


## 🔍 Key Insights

- Female customers recorded a higher number of transactions than male customers.
- The 26–35 age group generated the highest overall revenue.
- Clothing was the most frequently purchased product category.
- Credit card payments were the most preferred payment method.


## 📁 Project Structure

## ▶️ How to Run This Project

1. Install MySQL or any compatible SQL database.
2. Create a new database (example: `customer_analytics`).
3. Create the `customer` table using the schema described above.
4. Import or insert customer data into the table.
5. Open and execute SQL files from the `sql` folder one by one.
6. Analyze query outputs to derive business insights.




