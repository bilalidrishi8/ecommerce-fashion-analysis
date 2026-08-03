# 👕 Fashion Hub SQL Data Analysis

## 📌 Project Overview

**Fashion Hub SQL Data Analysis** is an end-to-end SQL project that analyzes fashion retail sales data using **PostgreSQL**. The project focuses on exploring sales performance, product trends, customer locations, order status, and category-wise insights through real-world business problems.

This project demonstrates SQL skills from beginner to advanced by using aggregate functions, subqueries, Common Table Expressions (CTEs), and window functions to generate business insights that support data-driven decision-making.

---

# 🎯 Project Objectives

* Analyze fashion retail sales performance.
* Identify top-selling products and categories.
* Compare sales across states and cities.
* Evaluate order fulfillment status.
* Measure category-wise revenue.
* Rank products using SQL window functions.
* Build business reports using SQL.

---

# 🛠️ Tools & Technologies

* PostgreSQL
* SQL
* pgAdmin 4
* Git
* GitHub

---

# 📂 Repository Structure

```text
fashion-hub-sql-data-analysis/
│
├── Dataset/
│   └── Fashion_Hub_June.csv
│
├── Database/
│   ├── create_table.sql
│   └── import_data.sql
│
├── SQL Queries/
│   ├── 01_Beginner_Queries.sql
│   ├── 02_Intermediate_Queries.sql
│   ├── 03_Advanced_Queries.sql
│   ├── 04_Window_Functions.sql
│   └── 05_Business_Insights.sql
│
├── Images/
│   ├── database_schema.png
│   ├── query_results.png
│   └── dashboard_preview.png
│
├── README.md
└── LICENSE
```

---

# 📊 Dataset Description

The dataset contains order and product information for a fashion retail business.

### Dataset Columns

| Column        | Description                          |
| ------------- | ------------------------------------ |
| Number        | Record number                        |
| Order ID      | Unique order identifier              |
| Order Date    | Date of purchase                     |
| SKU           | Product stock keeping unit           |
| Product Name  | Product name                         |
| Category      | Product category                     |
| Qty           | Quantity sold                        |
| Selling Price | Product selling price                |
| Customer City | Customer's city                      |
| State         | Customer's state                     |
| Order Status  | Delivered, Cancelled, Returned, etc. |

---

# 📚 SQL Concepts Covered

## Beginner

* SELECT
* WHERE
* ORDER BY
* LIMIT
* DISTINCT
* COUNT()
* SUM()
* AVG()
* MIN()
* MAX()

## Intermediate

* GROUP BY
* HAVING
* CASE
* Aggregate Functions
* Subqueries
* Correlated Subqueries

## Advanced

* Common Table Expressions (CTEs)
* Window Functions
* ROW_NUMBER()
* RANK()
* DENSE_RANK()
* LAG()
* LEAD()
* Running Totals
* Percentage Contribution
* Business KPI Reporting

---

# 📈 Business Questions Solved

### Beginner

* Count total orders.
* Find total sales revenue.
* Display all product categories.
* Count orders by status.
* Find the top 10 most expensive products.

### Intermediate

* Total sales by state.
* Total sales by city.
* Average selling price by category.
* Top-selling products.
* Orders by category.
* Categories with above-average sales.
* State contribution to total revenue.
* Average quantity sold by product.
* Compare delivered vs returned orders.

### Advanced

* Rank products by sales within each category.
* Top-selling product in every state.
* Running total of sales by order date.
* Month-over-Month (MoM) sales growth.
* Category contribution to total revenue.
* Revenue ranking by state.
* Detect sales outliers.
* Pareto (80/20) revenue analysis.
* Executive sales performance report.

---

# 📊 Key Business Insights

* Best-selling products and categories.
* States generating the highest revenue.
* Cities with the largest customer base.
* Products contributing the highest sales.
* Order status distribution.
* Revenue contribution by category.
* Sales trends over time.
* Product rankings using SQL window functions.

---

# 💡 SQL Skills Demonstrated

* Data Exploration
* Data Cleaning
* Aggregate Functions
* GROUP BY & HAVING
* CASE Statements
* Subqueries
* Correlated Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* Ranking Functions
* Running Totals
* Percentage Calculations
* Retail Sales Analytics

---

# 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/fashion-hub-sql-data-analysis.git
```

### 2. Create the Database Table

Run:

```sql
create_table.sql
```

### 3. Import the Dataset

Import **Fashion_Hub_June.csv** into PostgreSQL using **pgAdmin** or the `COPY` command.

### 4. Execute SQL Queries

Run the SQL files in the following order:

1. Beginner Queries
2. Intermediate Queries
3. Advanced Queries
4. Window Function Queries
5. Business Insight Queries

---

# 📸 Project Preview

Add screenshots of:

* PostgreSQL database
* SQL query outputs
* Business insights
* Query execution results
* Power BI dashboard (optional)

Store all screenshots in the **Images** folder.

---

# 📖 Learning Outcomes

By completing this project, you will learn how to:

* Analyze retail sales data using SQL.
* Explore product and customer trends.
* Perform sales and category analysis.
* Use window functions for ranking and reporting.
* Generate business-ready insights from transactional data.
* Build a portfolio-ready SQL analytics project.

---

# 🔮 Future Enhancements

* Build an interactive Power BI dashboard.
* Perform Exploratory Data Analysis (EDA) using Python.
* Create Tableau visualizations.
* Develop sales forecasting models.
* Build executive KPI dashboards.

---

# 👨‍💻 Author

**Your Name**

**Aspiring Data Analyst**

**Skills:** SQL | PostgreSQL | Power BI | Python | Excel

---

# ⭐ Support

If you found this project helpful, please consider giving it a **⭐ Star** on GitHub.

Happy Learning and Happy Querying! 🚀
