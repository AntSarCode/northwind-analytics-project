# Northwind Analytics Project

This repository contains data analysis exercises using SQL and Python based on the classic Northwind sample database. Each prompt focuses on a real-world business question and walks through how to extract, analyze, and present data using relational joins, aggregations, and visualizations.

---

## 📊 Prompt 1: Customer Lifetime Value (LTV)

**Goal:** Identify the top 10 customers by total revenue (lifetime value)

- Joined: Customers → Orders → Order Details
- Metric: `SUM(Quantity × UnitPrice × (1 - Discount))`
- Output: Top 10 customers sorted by revenue
- Technologies: SQLite, pandas, matplotlib

**Status:** ✅ Complete

---

## 📁 Structure

Northwind-Analytics-Project/
├── scripts/ ← Python analysis scripts
├── sql/ ← Raw SQL queries
├── output/ ← CSVs, charts, or reports
├── notebooks/ ← (Optional) Jupyter notebooks
└── README.md


---

## 🛠️ Tools Used

- Python (pandas, matplotlib)
- SQLite (via `sqlite3`)
- Git/GitHub

---

## 🚀 Next Steps

✅ Add new prompts  
✅ Upload chart visualizations  
✅ Expand to other datasets (e.g., Chinook, public sales data)  
✅ Link this repo on your résumé and LinkedIn

## 📦 Database Used

This project uses the [Northwind SQLite database](https://github.com/jpwhite3/northwind-SQLite)  
You can download `northwind.sqlite` and place it in your local working folder.
