# SQL Summative Lab

A SQL and data analysis project exploring customer, product, sales, and movie-industry datasets using **SQLite, Python, Pandas, and Matplotlib**.

This project was completed as a summative assessment focused on translating business questions into SQL queries, analyzing relational data, and communicating findings through visualizations.

## Project Overview

The project is divided into two parts.

### Part 1 — Guided SQL Analysis

The first section analyzes a wholesale model-product company's customer and sales database.

The analysis includes:

- Identifying high-credit customers in California
- Finding international customers for a collectible marketing campaign
- Comparing average customer credit limits across U.S. states
- Identifying the top 10 customers by total payments
- Analyzing customer purchasing quantities by product
- Comparing product-line variety with total order demand
- Identifying employees working in offices with fewer than five employees

The queries demonstrate:

- `SELECT`
- `WHERE`
- `LIKE`
- `JOIN`
- `GROUP BY`
- `HAVING`
- `ORDER BY`
- `SUM`
- `AVG`
- `COUNT`
- `COUNT(DISTINCT ...)`
- Subqueries
- Type casting and null handling

Visualizations were created with Matplotlib to communicate several of the results.

## Part 2 — Exploratory IMDB Analysis

The second section uses an IMDB movie database to conduct an open-ended exploratory analysis of movies released between **2010 and 2019**.

The analysis combines SQL and Pandas to investigate relationships between:

- Movie genres
- IMDB ratings
- Audience voting engagement
- Runtime
- Release year

After excluding records with missing fields required for the analysis, the complete-case dataset contains **65,720 rated movies**.

One pattern explored is the difference between **audience satisfaction and audience engagement across genres**. Some genres achieve relatively high average ratings while generating lower typical voting activity, while others attract substantially more audience engagement.

### Business Question

> Which established movie genres offer the strongest combination of audience satisfaction (IMDB rating) and audience engagement (vote activity), and does that relationship remain consistent across release years from 2010 through 2019?

The exploratory analysis also identifies several considerations for deeper analysis, including null values, multi-value genre fields, highly skewed vote counts, extreme runtime values, join duplication, and differences in dataset coverage by year.

## Technologies

- SQL
- SQLite
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Repository Structure

```text
dsc-sql-summative-lab/
├── images/
├── data.sqlite
├── im.db.zip
├── SQLSummativeLab.ipynb
└── README.md
