# Rental Portfolio Operations & Performance Analytics  
### SQL Data Mart + Excel Controls + Power BI Executive Intelligence (Mock Dataset)

---

## Overview

This project demonstrates an **operations analytics system** for rental portfolio performance using structured financial and transaction data.

It models rental income, expenses, collections activity, and capital expenditures to provide decision-ready KPIs that improve operational visibility and financial control.

All data is simulated or anonymized to protect confidentiality while reflecting realistic rental portfolio workflows.

---

## Business Context

Rental portfolios operate like small production systems. Financial stability depends on:

- Consistent rent collection
- Controlled operating expenses
- Margin discipline (NOI stability)
- Managed capital expenditures
- Property-level performance benchmarking

Without structured analytics, operators lose visibility into:

- Expense spikes
- Margin drift
- Cash flow volatility
- Delinquency risk
- Underperforming properties

This project simulates how an Operations Analyst would structure and monitor a rental portfolio using clean data modeling and executive KPI reporting.

---

## Project Objectives

- Track portfolio-level **NOI and cash flow trends**
- Identify expense variance drivers
- Monitor collection stability and payment timing
- Benchmark property performance
- Surface operational risk indicators
- Provide executive-level decision visibility

---

## Dataset Structure

The system models rental portfolio activity using structured operational tables.

### 1️⃣ Transactions (Income / Expense / CAPEX)

Tracks financial events across properties.

Key Fields:
- Date
- Property_ID
- Category (Income / Expense / CAPEX)
- Subcategory
- Amount
- Vendor (if applicable)

---

### 2️⃣ Payments / Collections (If Included)

Tracks billing vs payment timing.

Key Fields:
- Date_Billed
- Date_Paid
- Property_ID
- Amount
- Late_Flag
- Days_Late

---

## Analytical KPIs

The dashboard includes:

- Total Income
- Total Expenses
- Net Operating Income (NOI)
- Cash Flow (Monthly / Rolling)
- Expense Variance by Category
- CAPEX Tracking
- Late Payment Rate (%)
- Property Performance Ranking
- Margin Stability Over Time

---

## Core Analytical Questions Answered

- Which properties generate the highest NOI?
- What expense categories drive the most volatility?
- Is cash flow stable month-over-month?
- Where are late payments increasing?
- Which properties are operationally high-risk?
- How is CAPEX impacting margin performance?

---

## Tools Used

- SQL (PostgreSQL / MySQL)
  - Structured schema
  - KPI queries
  - Aggregations & trend analysis
- Microsoft Excel
  - Data staging
  - Validation checks
  - Structured calculations
- Power BI
  - Executive dashboard
  - Property drilldowns
  - KPI visualization

---

## Data Governance Features

- Structured relational schema (facts + dimensions)
- Controlled income/expense categorization
- Standardized KPI definitions
- Repeatable refresh workflow
- Validation checks for duplicates and missing values

---

## Why This Project Matters

Operations analytics is not limited to manufacturing. Any system with recurring financial flows requires:

- Margin discipline
- Variance control
- Cash flow monitoring
- Risk detection
- Structured decision support

This project demonstrates:

- Operations-focused thinking
- Structured KPI modeling
- Relational data design
- Executive-level reporting

It reflects how an Operations Analyst would manage performance, stability, and risk in a real-world portfolio environment.

---

## Repository Structure

```
.
├── Data/                 # Source datasets (CSV/Excel)
├── SQL/                  # Schema, load scripts, KPI queries
├── Excel/                # Data controls and validation workbook
├── Dashboard/            # Power BI .pbix file + screenshots
└── README.md
```

---

## Future Enhancements

- Exception views in SQL for expense spikes
- Variance decomposition modeling
- Scenario simulation (rent increase, vacancy impact)
- Rolling 90-day risk scoring logic
- Automated KPI export workflows

---

## Author

Yengkong Sayaovong  
Manufacturing & Operations Analytics Focus  
LinkedIn: https://www.linkedin.com/in/ysayaovong
