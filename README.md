# data-analyst-sql
# SQL Basics (Filtering, Sorting & Aggregations)

## Objective
The objective of this task is to practice basic SQL operations such as filtering, sorting, and aggregation on a sales dataset. This task helps in building confidence with real-world SQL querying used by data analysts.

---

## Tools Used
- SQLite (Command Line)
- Command Prompt (CMD)
- GitHub (for submission)

---

## Dataset Used
- File name: `sales_data_task3.csv`
- Records: 100+
- Columns:
  - Order_ID
  - Order_Date
  - Customer_Name
  - Category
  - Region
  - Sales
  - Profit

---

## SQL Operations Performed

### 1. Data Verification
- Checked total number of records
- Viewed sample rows using `LIMIT`

### 2. Filtering
- Used `WHERE` clause to filter data by category and region

### 3. Sorting
- Used `ORDER BY` to sort records based on sales in descending order

### 4. Aggregations
- Used aggregate functions:
  - `SUM(Sales)`
  - `AVG(Profit)`
  - `COUNT(*)`
- Grouped data using `GROUP BY`

### 5. Group Filtering
- Used `HAVING` clause to filter grouped results

### 6. Advanced Conditions
- Used `BETWEEN` for date range filtering
- Used `LIKE` for pattern matching in customer names

### 7. Business Query
- Identified top 5 customers based on total sales

---

## Output Generated
- File name: `sales_summary.csv`
- Contains category-wise total sales generated using aggregation queries

---

## Files Included
- `sales_data_task3.csv` – Original dataset
- `queries_task3.sql` – SQL queries written for the task
- `sales_summary.csv` – Exported summary report
- `task3.db` – SQLite database file
- `README.md` – Task explanation
