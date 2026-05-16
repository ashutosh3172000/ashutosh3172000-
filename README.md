# 📊 Ashutosh Tiwari — Data Analysis Portfolio

> Turning raw datasets into clear, actionable insights using SQL, Python, and Power BI.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ashutosh-tiwari-0a1575312)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tiwariashu3107@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ashutosh3172000)

---

## 🧰 Tech Stack

![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

---

## 🚀 Projects

| # | Project | Tools | Type |
|---|---------|-------|------|
| 1 | [🛒 Online Bookstore SQL Analysis](#-1-online-bookstore-sql-analysis) | SQL, PostgreSQL | Database Design + Querying |
| 2 | [📉 Customer Churn Analysis](#-2-customer-churn-analysis) | Python, Pandas, Matplotlib | EDA + Visualisation |
| 3 | [📈 Sales Performance Dashboard](#-3-sales-performance-dashboard) | Power BI, DAX | Dashboard + Reporting |
| 4 | [🎬 Movie Database Analysis](#-4-movie-database-analysis) | SQL, MySQL | Querying + Aggregations |

---

## 🛒 1. Online Bookstore SQL Analysis

**Tools:** SQL · PostgreSQL · Joins · Aggregations

### Overview
Designed and queried a relational database simulating a real-world online bookstore. Built the schema from scratch, imported CSV data, and wrote 20+ queries to answer business questions around sales, inventory, and customer behaviour.

### Database Schema
```
Books (Book_ID, Title, Author, Genre, Published_Year, Price, Stock)
   ↑
Orders (Order_ID, Customer_ID → Customers, Book_ID → Books, Order_Date, Quantity, Total_Amount)
   ↓
Customers (Customer_ID, Name, Email, Phone, City, Country)
```

### Key Questions Answered
**Basic:**
- Retrieve all Fiction books / books published after 1950
- List customers from Canada and orders from November 2023
- Find the most expensive book and the one with lowest stock
- Calculate total revenue from all orders

**Advanced:**
- Total books sold per genre using JOIN + GROUP BY
- Customers who placed 2+ orders using HAVING
- Most frequently ordered book
- Top-spending customer overall
- Remaining stock after fulfilling all orders using COALESCE + LEFT JOIN

### Key Techniques
`JOIN` · `GROUP BY` · `HAVING` · `COALESCE` · `LEFT JOIN` · `DISTINCT` · `ORDER BY` · `LIMIT` · `BETWEEN`

### Files
| File | Description |
|------|-------------|
| `SQL_project(Online_Bookstore).sql` | Full SQL script |
| `Books.csv` | Book titles, genres, authors, price, stock |
| `Customers.csv` | Customer details |
| `Orders.csv` | Order records |

---

## 📉 2. Customer Churn Analysis

**Tools:** Python · Pandas · Matplotlib

### Overview
Performed end-to-end exploratory data analysis on a 7,043-row telecom dataset to understand why customers leave and identify the highest-risk segments.

### Process
1. **Data Cleaning** — resolved missing values, encoded categorical variables, standardised numeric features
2. **EDA** — computed churn rate, grouped data by contract type, tenure, and monthly charges
3. **Visualisation** — built 8 Matplotlib charts to communicate findings clearly

### Key Findings
- Overall churn rate: **26.5%**
- Top 3 attrition drivers: **contract type**, **tenure**, and **monthly charges**
- Month-to-month customers churn significantly more than long-term contract holders

### Files
| File | Description |
|------|-------------|
| `Customer_Churn_Analysis.ipynb` | Full analysis notebook |

---

## 📈 3. Sales Performance Dashboard

**Tools:** Power BI · DAX · Data Modelling

### Overview
Built an interactive Power BI dashboard to track sales and profit across 4 regional segments, enabling portfolio and retention decisions through visual KPIs.

### Key Features
- 6-KPI interactive dashboard spanning 4 regional segments
- Segment-level filtering to drill down into customer and product performance
- Dynamic DAX measures for revenue, margin, and contribution metrics

### Key Findings
- Identified **3 loss-making product lines** with negative margin in the South region
- Pinpointed the **top 10% of customers** by revenue contribution for prioritised retention

### Files
| File | Description |
|------|-------------|
| `Power_BI_sales_dashboard.pbix` | Full Power BI dashboard file |

---

## 🎬 4. Movie Database Analysis

**Tools:** SQL · MySQL · Aggregations

### Overview
Analysed a 10,000+ record movie dataset using complex SQL queries to uncover revenue trends, genre performance, and industry growth patterns across three decades.

### Key Questions Answered
- Top 20 revenue-generating titles using multi-table JOINs
- Genre-level revenue breakdown and concentration
- Industry growth trends from 1990–2020
- Highest average-revenue decade identification

### Key Findings
- **34% of revenue** concentrated in 3 genres: Action, Drama, Animation
- The **2010s** was the highest average-revenue decade in the dataset

### Files
| File | Description |
|------|-------------|
| `IMDB analysis.sql` | Full SQL query file |

---

## 📫 Contact

Feel free to reach out for collaborations, opportunities, or just to talk data!

- 🔗 [LinkedIn](https://linkedin.com/in/ashutosh-tiwari-0a1575312)
- 📧 [tiwariashu3107@gmail.com](mailto:tiwariashu3107@gmail.com)
- 💻 [GitHub](https://github.com/ashutosh3172000)

---

⭐ *If you found this useful, consider giving the repo a star!*
