# Bank-Loan-Summary
# 📊 Banking Loan Analytics Dashboard

## 🚀 Project Overview
This project focuses on analyzing key banking KPIs related to **loan applications, disbursed amounts, repayments, and borrower financial health**. The data is extracted, transformed, and visualized using **SQL and Power BI** to provide actionable insights.

## 📌 Key Performance Indicators (KPIs)
- **Total Loan Applications** – MTD trends and MoM growth.
- **Total Funded Amount** – Disbursed loan trends and MoM variations.
- **Total Amount Received** – Loan repayment analysis with MTD & MoM insights.
- **Average Interest Rate** – Lending rate trends and MoM fluctuations.
- **Average Debt-to-Income Ratio (DTI)** – Borrower financial health insights.

## 📂 Project Structure
```
├── SQL_Scripts/               # SQL queries used for data extraction and transformation
│   ├── create_database.sql
│   ├── create_tables.sql
│   ├── data_extraction.sql
│   ├── kpi_calculations.sql
│
├── PowerBI_Dashboard/        # Power BI report file (.pbix) & visuals
│   ├── Banking_KPIs.pbix
│   ├── Screenshots/
│
├── Data/                     # Raw and cleaned datasets (CSV/Excel files)
│
├── README.md                 # Project documentation (You're here!)
```

## 💡 Key Learnings
### 🔹 **SQL:**
- Database & Table Creation
- Querying with **SELECT, GROUP BY, ORDER BY**
- Working with Dates (**DATENAME, DATEPART, MONTH, QUARTER, DAY, HOUR**)
- Data Transformation with **CAST, DECIMAL**
- Aggregation Functions (**COUNT, DISTINCT**)
- Advanced Queries (**CTE, PARTITION, LIMIT**)

### 🔹 **Power BI:**
- Connecting to **SQL Server** & Data Cleaning
- **Data Modelling & Processing** with Power Query
- Creating **Date Tables & Time Intelligence Functions**
- Writing **DAX** (Date, Text, Filter, Calculate, SUM/SUMX Functions)
- **KPI Creation, Visual Formatting & Navigation Design**

## 🔧 How to Run the Project
1. **Clone the Repository:**  
   ```bash
   git clone https://github.com/ashishdevi007/Bank-Loan-Summary.git
   ```
2. **Set Up SQL Database:**  
   - Run the scripts in `SQL_Scripts/` to create and populate the database.
3. **Load Data into Power BI:**  
   - Open `Banking_KPIs.pbix` in Power BI Desktop.
   - Ensure the data source is correctly configured.
4. **Explore & Analyze Insights!** 🎯

## 📢 Feedback & Contributions
Would love to hear your thoughts! If you have suggestions or want to contribute, feel free to **fork & pull request**. 🚀

### 🔗 Connect with Me
[![LinkedIn](https://www.linkedin.com/in/ashish-devi-7323a6227/)
