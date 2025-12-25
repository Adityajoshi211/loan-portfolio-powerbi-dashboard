# loan-portfolio-powerbi-dashboard
End-to-end Loan Portfolio Analysis using MySQL &amp; Power BI; Excel; DAX;

# Loan Portfolio Analysis – Power BI Dashboard

## 📌 Project Overview
This project is an end-to-end Loan Portfolio Analysis dashboard built using Power BI and MySQL.  
It helps analyze loan disbursement, repayments, defaults, and outstanding amounts.

##  Tools & Technologies
- Power BI
- MySQL
- SQL
- DAX
- Excel

## 📊 Key KPIs
- Total Disbursed Amount
- Total Paid Amount
- Outstanding Amount
- Default Rate
- Total Customers

## 📈 Dashboard Features
- Loan Amount by State
- Loan Amount by Loan Type
- Monthly Loan Disbursement Trend
- Payment Status Distribution
- Interactive Slicers
- Drill-through Analysis

## 🗂 Data Model
- Fact Tables: Loans, Payments, Defaults
- Dimension Tables: Customers

##  Dashboard Preview
![Dashboard Overview](Screenshots/dashboard_overview.png.png)


##  Key Learnings
- Star schema data modeling
- Writing optimized DAX measures
- Designing interactive dashboards
- Business-focused KPI analysis
## 🗄 MySQL Database

The project uses a MySQL database (`loan_portfolio`) created using CSV imports and exported for reproducibility.

### Tables
- customers
- loans
- payments
- defaults

### SQL Files
- `SQL/schema.sql` – database and table structure
- `SQL/loan_portfolio.sql` – full database dump (schema + data)
- `SQL/analysis_queries.sql` – business analysis queries
