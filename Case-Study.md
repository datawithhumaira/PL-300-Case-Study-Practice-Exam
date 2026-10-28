# Case Study
## Background
Northwind Trading operates across the GCC region.

The company uses:
-  An on-premises SQL Server database for sales transactions.
-  Excel files submitted monthly by regional offices.
-  A centralized Power BI environment.

---
## The Power BI team has created:
### Fact Table
-  FactSales
### Dimension Tables
-  DimDate
-  DimCustomer
-  DimProduct
-  DimRegion

---
## The model follows a Star Schema.
### The dataset contains:
-  9 years of historical sales
-  Approximately 80 million rows
Only the most recent month's transactions are updated after loading.
---
## Security Requirements
-  Regional managers must only see data for their own region.
-  The company experiences regular staff turnover, and the administration team wants to minimize maintenance effort.
---
## Reporting Requirements
Executives require:
-  A single-page KPI view showing information from multiple reports.
-  Monthly email delivery of executive dashboards.
-  Notifications when sales exceed AED 5 million.
-  Forecasted sales for the next 12 months.
-  Average sales benchmarks on charts.
---
## Development Requirements
Analysts must:
-  Create their own reports from the published semantic model.
-  Not receive administrative rights in the workspace.
