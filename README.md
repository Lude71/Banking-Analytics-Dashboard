# Banking Analytics Dashboard

An interactive and professional Power BI dashboard project designed to analyze banking operations, customer behavior, transaction trends, and branch performance using data visualization and business intelligence techniques.

---

# Project Overview

This project demonstrates how Power BI can be used to transform raw banking data into meaningful business insights through interactive dashboards, KPI monitoring, trend analysis, customer segmentation, and multi-page reporting.

The dashboard enables users to:
- Monitor branch performance
- Analyze customer account balances
- Track transaction trends
- Identify top customers
- Filter data dynamically using slicers
- Navigate between multiple report pages

---

# Dashboard Features

## Executive Overview Page
- Financial KPI cards
- Branch account balance analysis
- Transaction type distribution
- Monthly transaction trends
- Interactive slicers
- Customer insights table
- Conditional formatting

## Customer Analysis Page
- Total customer analysis
- Average account balance tracking
- Average credit score analysis
- Top 10 customers by balance
- Customer account segmentation
- Interactive page navigation

---

# Key Insights Generated

- Identified highest-performing bank branches
- Analyzed monthly transaction trends
- Ranked top customers by account balance
- Visualized customer account distribution
- Evaluated average customer credit scores
- Enabled interactive filtering by branch and account type

---

# Tools & Technologies Used

- Microsoft Power BI
- DAX (Data Analysis Expressions)
- Power Query
- Data Visualization Techniques
- Interactive Dashboard Design

---

# Power BI Concepts Applied

- KPI Cards
- Clustered Column Charts
- Pie Charts
- Donut Charts
- Line Charts
- Slicers
- Conditional Formatting
- DAX Measures
- Multi-page Navigation
- Interactive Analytics

---

# DAX Measures Used

```DAX
Average Balance = AVERAGE(BankingData[AccountBalance])

Total Customers = DISTINCTCOUNT(BankingData[CustomerID])

Average Transaction = AVERAGE(BankingData[TransactionAmount])
