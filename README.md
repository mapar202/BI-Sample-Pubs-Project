# 📊 BI Solution for Microsoft Pubs Database

This project showcases a full **Business Intelligence (BI)** pipeline using the classic **Microsoft Pubs database**, demonstrating hands-on experience with:

- 🔄 **ETL** using **SQL Server Integration Services (SSIS)**
- 📦 **Data Modeling and OLAP** using **SQL Server Analysis Services (SSAS)**
- 📈 **Reporting** using **SQL Server Reporting Services (SSRS)**
- 🧩 **Interactive Dashboards** using **Power BI**

## 📁 Project Structure

This Visual Studio 2022 solution includes 3 main BI projects and a Power BI dashboard:

1. **ETL_Pubs**
   - Contains multiple `.dtsx` packages
   - Extracts data from the Pubs source database
   - Transforms and loads into the data warehouse schema
###  Project_Flow_package Preview:
![Project_Flow](https://github.com/user-attachments/assets/e42906ad-60b2-481e-95b9-ef36e66297fe)

2. **OLAP_MD_Pubs**
   - Multidimensional model (MD)
   - Cubes built on the transformed data
   - Dimensions: Authors, Titles, Publishers, Sales, etc.
###  Sales Cube Preview:
![Sales_Cube](https://github.com/user-attachments/assets/13b94a29-cf19-4c45-82cb-a4bf2dcecee6)

 3. **Report_Pubs**
   - Contains `.rdl` report files designed in SQL Server Reporting Services (SSRS)
   - Interactive reports include:
     - **📍 Store Directory by Location** – Lists all bookstores, filterable by **City** and **State**
     - **📚 Book Titles Explorer** – Displays all available titles with filters by **Book Title**
     - **💰 Sales Summary by Store** – Aggregates total sales per store, searchable by **City** and **State**, and grouped by store


## 📊 Dashboard Pubs (Power Bi Dashboard): Book Sales Analysis

This Power BI dashboard provides interactive visual insights based on the Microsoft Pubs database, helping stakeholders understand key metrics in book sales performance.

### 🔍 Features & Visuals:
- **KPIs**:
  - Total Sales, Average Monthly Sales, Total Quantity Sold
  - Highest Selling Book Value
- **Top Authors by Sales**: Highlights the 5 most successful authors
- **Top Books by Sales**: Identifies the best-performing books
- **Sales by Publishers**: Pie chart showing market share by publisher
- **Monthly Sales Trend**: Line chart to analyze sales seasonality
- **Sales by Stores**: Bar chart summarizing performance by store location

### 🖼️ Dashboard Preview:
![Dashboard_Overview](https://github.com/user-attachments/assets/f74f02e4-9d72-499a-8250-426941baf064)



## 🛠 Technologies Used

- Microsoft SQL Server 2019
- SQL Server Data Tools (SSDT)
- Visual Studio 2022
- SSIS, SSAS (Multidimensional), SSRS
- Power BI Desktop
- T-SQL
