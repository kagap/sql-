# 🐘 SQL Starter Pack (PostgreSQL)

A set of 14 interactive Jupyter Notebook modules for learning SQL with PostgreSQL from scratch, available in both **English** ([`EN/`](EN)) and **Polish** ([`PL/`](PL)). Each notebook is built with a clean layout and locked theory cells to keep the focus entirely on coding practice.

## 📌 What's Inside

| # | Topic |
|---|-------|
| 1 | Getting Started & Installation |
| 2 | Filtering & Sorting |
| 3 | Functions & Expressions |
| 4 | Aggregation |
| 5 | JOINs |
| 6 | Subqueries |
| 7 | Modifying Data & Transactions |
| 8 | Table Design |
| 9 | Indexes & Performance |
| 10 | Views & CTEs |
| 11 | Window Functions |
| 12 | PL/pgSQL Functions & Triggers |
| 13 | JSON in PostgreSQL |
| 14 | Capstone: Python and SQL |

* **Core Theory & Examples:** Clear explanations paired with runnable SQL for each topic.
* **Interactive Exercises:** Hands-on tasks with expandable spoiler solutions.
* **Protected Content:** Theory and description cells are configured as non-editable (`"editable": false`, `"deletable": false`) to prevent accidental changes while working through the material.

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/kagap/sql-.git
   cd sql-
   ```
2. Start a local PostgreSQL instance with Docker:
   ```bash
   docker compose up -d
   ```
   This spins up Postgres on `localhost:5432` with database `sql_course`, user `postgres`, password `course123` — the exact connection string every notebook uses. No Docker? Install PostgreSQL yourself and create a matching `sql_course` database instead.
3. Install the Python dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Pick your language folder ([`EN`](EN) or [`PL`](PL)) and start with Module 1. Each notebook's setup cell (re)creates the tables it needs, so modules can be run in any order.
