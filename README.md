# SQL Sales and Forecast Analysis – Master’s Coursework

This repository contains a SQL assignment completed as part of my Master’s program, focused on **using SQL to explore, aggregate, and analyze sales and forecast data stored in a relational database**.

The project reflects my **practical experience applying SQL to answer structured analytical questions**, with an emphasis on clarity, correctness, and understanding the underlying data.

---

## 🗄️ Dataset Description

The analysis is based on a relational database with three main tables:

- **ACCOUNTS** – Account-level information, including industry
- **SALES** – Historical sales data (revenue, units, profit, year, and product categories)
- **FORECASTS** – Forecasted sales values classified by confidence levels

The tables are combined to perform **basic analytical and comparative queries** across accounts, industries, and time periods.

---

## 📊 Analysis Scope

The assignment addresses several analytical tasks, including:

- Aggregated sales and profit analysis by **product category**
- Breakdown of total sales into maintenance, product, parts, and support
- Calculation of **percentage contribution** by category
- Account-level sales analysis for selected customers
- **Year-over-year sales comparisons**
- Introductory forecast analysis by industry using confidence-weighted values

The focus is on **understanding the data and answering the questions posed in the assignment**, rather than on query optimization or advanced database features.

---

## 🧠 SQL Concepts Practiced

- `SELECT` queries with filtering (`WHERE`)
- Aggregate functions (`SUM`, `COUNT`, `ROUND`)
- Grouped analysis using `GROUP BY`
- Sorting results with `ORDER BY`
- `INNER JOIN` operations across multiple tables
- Conditional logic with `CASE WHEN`
- Construction of simple analytical metrics (percentages and weighted values)

---

## 🔮 Forecasting Logic

Forecast values are adjusted using predefined confidence weights:

- `Pipeline` → 30%  
- `Upside` → 60%  
- `Commit` → 90%  

This allows for a **basic comparison of expected forecast values across industries**, using SQL-based calculations.

---

## 🛠️ Tools & Technologies

- **SQL**  
  Used to query relational databases and perform structured analytical tasks.

- **Relational Databases**  
  Academic database schema designed for learning analytical querying.

- **Documentation and reporting**  
  Queries and results are written and explained as part of the coursework.

---

## 💡 Learning Outcomes

This project helped me strengthen:

- My **SQL fundamentals** for data analysis  
- My ability to **translate questions into structured queries**  
- My understanding of **sales and forecast data structures**  
- My confidence working with **multi-table relational datasets**

---

## 📁 Repository Contents

- `Queries_Jose_Filgueira.txt` – SQL queries developed for the assignment  
- `TAREA_SQL.pdf` – Assignment description and reference material  

---

## 👤 Author

**Jose Filgueira Orge**  
Master’s student in Data Science / Analytics  
