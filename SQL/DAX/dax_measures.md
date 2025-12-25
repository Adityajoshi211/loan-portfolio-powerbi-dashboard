# DAX Measures – Loan Portfolio Analysis

This document contains DAX measures created in Power BI for KPI calculation.

---

## 1️⃣ Total Disbursed Amount

```DAX
Total Disbursed Amount =
SUM ( loans[loan_amount] )

2️⃣ Total Paid Amount
Total Paid Amount =
SUM ( payments[paid_amount] )

3️⃣ Outstanding Amount
Outstanding Amount =
[Total Disbursed Amount] - [Total Paid Amount]

4️⃣ Total Customers
Total Customers =
DISTINCTCOUNT ( customers[customer_id] )

5️⃣ Default Rate
Default Rate =
DIVIDE (
    CALCULATE (
        COUNT ( defaults[loan_id] ),
        defaults[default_flag] = 1
    ),
    COUNT ( defaults[loan_id] ),
    0
)
