# SQL + Python Hybrid E-Commerce Analytics Project  
From Business Questions to Data-Driven Insights

This project demonstrates a hybrid analytics workflow using **SQL Server and Python** to solve business problem statements.  
Starting with only a text file containing analytical questions, a complete pipeline was built to load data, execute SQL analysis, and generate visual insights using Python.

---

## 📌 Project Overview

Unlike traditional projects that begin with dashboards or predefined schemas, this project started with:

- A text file containing business problem statements
- Raw CSV datasets

The objective was to design a structured solution that:

- Loads raw data into SQL Server
- Solves analytical questions using SQL
- Connects Python with SQL Server
- Visualizes results using Python libraries

The result is a fully reproducible hybrid analytics workflow inside Jupyter Notebook.

---

## 🛠️ Tech Stack

- **SQL Server (SSMS)** – Data storage and querying
- **Python** – Data handling and visualization
- **Jupyter Notebook** – Development environment
- **pandas** – Data manipulation
- **matplotlib** – Data visualization
- **seaborn** – Statistical visualization
- **pyodbc / SQLAlchemy** – Database connectivity

---

## 🔄 Project Workflow

### 1️⃣ Data Loading (Python → SQL Server)

- Imported raw CSV files into SQL Server using Python
- Programmatically created database tables
- Assigned appropriate data types
- Validated successful data insertion

This ensured a structured database ready for analysis.

---

### 2️⃣ SQL Analysis (Executed Inside Jupyter)

- Connected Python to SQL Server
- Executed SQL queries directly within Jupyter Notebook
- Solved business questions using:
  - Joins
  - Aggregations
  - Filtering
  - Grouping
  - Ranking logic
- Retrieved query results into pandas DataFrames

This approach allowed seamless integration between database analysis and Python.

---

### 3️⃣ Data Visualization (Python)

Where applicable, insights were visualized using:

- **matplotlib** for structured charts
- **seaborn** for enhanced statistical graphics

Visualizations were created to:
- Compare category performance
- Identify trends
- Highlight outliers
- Provide clear answers to business questions
