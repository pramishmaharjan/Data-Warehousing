# 🧩 Data Warehousing – ETL & Power BI Project

This project demonstrates an **end-to-end ETL pipeline**, starting from raw **CSV files** and ending with an interactive **Power BI dashboard** providing insights into processed call-center data.

## ⚙️ Tools Used
- **SQL Server Integration Services (SSIS)** – for Extract, Transform, Load (ETL) workflow  
- **SQL Server Management Studio (SSMS)** – for database design and queries  
- **Power BI** – for visualization and KPI reporting

## 🧱 Architecture
The project follows a three-layer data warehousing design:
1. **Staging (STA)** – Raw CSV import into SQL tables  
2. **Operational Data Store (ODS)** – Data cleaning, deduplication, and transformation  
3. **Data Warehouse (DWH)** – Star schema (Fact + Dimension tables) optimized for analytics

## 📊 Dashboard Highlights
- SLA compliance: **88.07 %**
- Call Abandon Rate: **0.34 %**
- Year-over-year performance trends and KPI monitoring

## 🚀 How to Reproduce
1. Create the databases using the SQL scripts in `/sql_scripts/`.  
2. Open the `.dtsx` file in **SSIS** and run the package to load and transform the data.  
3. Connect **Power BI** to your SQL Server and import the DWH tables for reporting.

## 🧠 Key Learnings
- Building automated ETL pipelines with SSIS  
- Implementing a Star Schema for analytical performance  
- Creating operational KPI dashboards in Power BI  

---

> Developed by **Pramish Maharjan**  
> [LinkedIn](https://linkedin.com/in/pramishmaharjan) · [GitHub](https://github.com/pramishmaharjan)
