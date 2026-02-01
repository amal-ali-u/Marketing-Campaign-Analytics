
# Marketing Campaign Analytics  

 Project Overview  
This project analyzes **marketing campaign data of 2,240 customers from Maven Marketing**, covering customer profiles, product preferences, campaign performance, and sales channels. The goal was to build a complete **Business Intelligence solution** that transforms raw marketing data into actionable insights.  

##  Workflow & Steps  

### 1. Data Cleaning & Preparation  
- Used **Power Query** to clean and transform raw customer and campaign data.  
- Handled missing values, standardized column names, and ensured consistent data types.  
- Applied business rules to prepare the dataset for integration.  

### 2. ETL & Data Integration  
- Built **ETL workflows in SSIS** to automate data loading into the SQL Data Warehouse.  
- Designed a **Galaxy Schema** with multiple fact tables (campaigns, purchases, complaints) linked to shared dimensions (customer, product, channel).  
- Implemented transformations, lookups, and error handling to ensure reliable data pipelines.  

### 3. Data Warehouse  
- Structured the data in **SQL Server** for centralized storage and optimized querying.  
- Created dimension tables for customers, products, and channels.  
- Fact tables captured campaign responses, purchases, and complaints.  

### 4. Reporting & Visualization  
- Developed **SSRS reports** to provide tabular and paginated insights.  
- Built **Power BI dashboards** for interactive visualization, highlighting:  
  - Customer segmentation (Regular vs High Spenders).  
  - Product preferences (Wines, Meat, Gold, etc.).  
  - Campaign effectiveness (responses vs non-responses).  
  - Channel performance (Store, Web, Catalog).  

##  Business Value  
- Identified low campaign acceptance rates and opportunities for better targeting.  
- Highlighted product categories driving revenue.  
- Showed dominant sales channels and potential growth areas.  
- Enabled clear segmentation to guide marketing strategies.  

## 📂 Repository Structure  
```
/data        → Raw dataset (CSV/Excel)
/etl         → SSIS packages & SQL scripts
/reports     → SSRS reports & Power BI dashboards
/docs        → Project documentation (PDF, overview)
README.md    → Project description & workflow
```

---

