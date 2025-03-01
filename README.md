# Sales-Insights-DB
# README - Sales Report & Database Dump

## Introduction
This repository contains a **Sales Report** in PDF format and a **Database Dump** in SQL format. The files provide insights into sales data, including revenue, sales quantity, and market trends, along with a database backup for further analysis.

## Files Included
1. **Sales report.pdf** - A detailed PDF report of sales performance, including revenue, sales quantity, and customer insights.
2. **db_dump.sql** - A database dump file containing structured data related to sales, customers, and market trends.

## Sales Report Overview
- **Total Revenue**: 984.81M
- **Total Sales Quantity**: 2M
- **Revenue by Market**:
  - Delhi NCR: 519.51M
  - Mumbai: 150.08M
  - Ahmedabad, Bhopal, Nagpur, and more...
- **Sales Quantity by Market**:
  - Delhi NCR: 988K
  - Mumbai: 384K
  - Nagpur, Kochi, Ahmedabad, and others...
- **Top 5 Customers**:
  - Electricalsara Stores
  - Premium Stores
  - Excel Stores
  - Nixon
  - Electricalslytical
- **Top 5 Products** by sales quantity
- **Revenue Trends** from 2017 to 2020

## Database Dump Overview
The `db_dump.sql` file contains:
- **Tables** for storing sales data, customer details, product details, and market trends.
- **Relationships** between customers, products, and transactions.
- **Historical sales data** from 2017 to 2020 for analysis and reporting.

## How to Use
### 1. Viewing the Sales Report
- Open `Sales report.pdf` using any PDF viewer.
- Analyze the revenue, sales trends, and customer insights.

### 2. Importing the Database
To restore the SQL dump into a database:
1. Open **MySQL/MSSQL/PostgreSQL** (depending on the database type).
2. Create a new database:
   ```sql
   CREATE DATABASE sales_db;
   ```
3. Import the SQL dump:
   ```bash
   mysql -u username -p sales_db < db_dump.sql
   ```
4. Run queries to analyze the data:
   ```sql
   SELECT * FROM sales;
   ```

## Contribution
If you need modifications or additional features, feel free to fork the repository and submit pull requests.

## License
This project is licensed under the MIT License.
---
This README provides essential details about the Sales Report and Database Dump. 🚀

