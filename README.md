# 📊 E-Commerce Sales Analytics with SQL

## 📌 Overview

This project analyzes an e-commerce business using SQL to uncover customer purchasing behavior, sales performance, product trends, and business profitability. By querying a relational database containing customers, orders, products, payments, and shipping information, the project transforms raw transactional data into actionable business insights.

The goal is to demonstrate how SQL can answer real-world business questions that support data-driven decision-making in retail and e-commerce environments.

---

## 🎯 Business Objectives

* Analyze customer purchasing behavior.
* Identify top-performing products and categories.
* Measure revenue, profit, and sales trends.
* Evaluate customer lifetime value.
* Discover operational opportunities through business metrics.
* Build a foundation for business intelligence dashboards.

---

# 📂 Project Structure

```text
ecommerce-sales-analytics-sql/
│
├── database/
│   ├── ecommerce_database.sql
│   └── schema.sql
│
├── sql/
│   ├── basic_queries.sql
│   ├── business_questions.sql
│   ├── customer_analysis.sql
│   ├── sales_analysis.sql
│   └── advanced_queries.sql
│
├── dashboards/
│   ├── powerbi_dashboard.pbix
│   └── dashboard_images/
│
├── notebooks/
│   └── exploratory_analysis.ipynb
│
├── datasets/
│
├── README.md
└── requirements.txt
```

---

# 🛠️ Technologies

### Languages

* SQL
* Python

### Database

* MySQL

### Python Libraries

* Pandas
* NumPy
* Matplotlib

### Visualization

* Power BI
* Excel

---

# 🗄️ Database

The project uses a relational e-commerce database consisting of multiple connected tables, including:

* Customers
* Orders
* Order Details
* Products
* Categories
* Suppliers
* Shippers
* Payments

The relationships between these tables allow for advanced SQL analysis using joins, aggregations, window functions, and common table expressions.

---

# 📈 Business Questions Answered

## Sales Performance

* What is the total revenue generated?
* Which months produce the highest sales?
* Which products generate the highest revenue?
* Which categories are the most profitable?

## Customer Analytics

* Who are the highest-value customers?
* Which customers place orders most frequently?
* What is the average customer lifetime value?
* Which countries contribute the most revenue?

## Product Performance

* Best-selling products
* Slow-moving inventory
* Highest profit margin products
* Product category comparison

## Order Analysis

* Average order value
* Order frequency
* Shipping performance
* Payment method trends

---

# 📊 Dashboard

The Power BI dashboard provides an executive overview of business performance, including:

* Revenue KPIs
* Sales Trends
* Customer Analysis
* Product Performance
* Geographic Sales
* Category Profitability

---

# 🔍 SQL Concepts Demonstrated

* SELECT
* WHERE
* GROUP BY
* HAVING
* ORDER BY
* INNER JOIN
* LEFT JOIN
* CASE Statements
* Aggregate Functions
* Window Functions
* Common Table Expressions (CTEs)
* Subqueries

---

# 📌 Key Insights

Some examples of insights generated from the analysis include:

* Identification of the company's highest-value customers.
* Seasonal sales trends across multiple years.
* Best-performing product categories.
* Revenue contribution by country.
* Products with declining sales performance.
* Customer purchasing frequency and spending behavior.

---

# 🚀 Future Improvements

* Build an interactive Streamlit application.
* Add customer segmentation using RFM analysis.
* Develop sales forecasting models.
* Integrate customer churn prediction.
* Connect to a live SQL database.
* Automate dashboard refresh using scheduled ETL pipelines.

---

# ▶️ Getting Started

Clone the repository:

```bash
git clone https://github.com/ahmedkhozeim/ecommerce-sales-analytics-sql.git
```

Create the database and import the provided dataset.

Run the SQL scripts in your preferred SQL environment (MySQL Workbench, PostgreSQL, or SQLite).

Open the Power BI dashboard to explore interactive business insights.

---

# 👨‍💻 Author

**Ahmed Khozeim**

Computer Science & Business Student at Minerva University

Interested in Data Analytics, Business Intelligence, SQL, Python, and Machine Learning.

LinkedIn:
https://linkedin.com/in/ahmedkhozeim

---

# 📄 License

This project is licensed under the MIT License.
