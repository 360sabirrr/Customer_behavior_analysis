# 📊 Data Analytics Project

## Overview

This project demonstrates a complete **data analytics workflow**, starting from raw data processing to delivering business insights through interactive dashboards and reports. The project involves **data loading, data cleaning, exploratory data analysis (EDA), SQL-based querying, visualization, and presentation of insights**.

The objective of this project is to showcase practical **data analysis skills using Python, SQL, and Power BI** to extract meaningful insights from structured data and communicate results effectively.

---

## Dataset

The dataset used in this project contains information related to **customer transactions, product purchases, and product reviews**. It includes multiple attributes that allow analysis of customer behavior, product performance, and rating patterns.

Key attributes include:

* Product information
* Customer purchase records
* Review ratings
* Transaction details
* Time-related fields for trend analysis

The dataset is processed and analyzed using Python and SQL tools to uncover patterns and insights.

---

## Tools and Technologies

| Tool / Technology                     | Purpose                                     |
| ------------------------------------- | ------------------------------------------- |
| Python (Pandas)                       | Data loading, preprocessing, and analysis   |
| Matplotlib / Seaborn                  | Data visualization and exploratory analysis |
| SQL (PostgreSQL)                      | Data querying and analytical insights       |
| Power BI                              | Interactive dashboard creation              |
| Jupyter Notebook                      | Data analysis environment                   |
| Gamma                                 | Presentation generation                     |
| GitHub                                | Project documentation and version control   |

---

## Project Workflow

### 1. Data Loading

The dataset was imported using **Python Pandas** and inspected to understand its structure, data types, and overall distribution.

### 2. Data Cleaning

Data preprocessing steps included:

* Handling missing values
* Removing duplicate records
* Correcting inconsistent data types
* Preparing the dataset for analysis

These steps ensure the dataset is reliable and suitable for further analysis.

### 3. Exploratory Data Analysis (EDA)

EDA was conducted to understand patterns and relationships within the dataset. Various visualizations were created to explore:

* Distribution of product ratings
* Customer purchasing patterns
* Product popularity
* Key trends within the data

Visualization libraries such as **Matplotlib and Seaborn** were used.

---

### 4. SQL-Based Analysis

The cleaned dataset was loaded into relational databases such as **PostgreSQL, MySQL, and SQL Server** to perform structured analysis using SQL queries.

SQL analysis included:

* Calculating average product ratings
* Identifying top-performing products
* Analyzing customer purchase behavior
* Generating summary insights

Example SQL query:

```sql
SELECT item_purchased,
ROUND(AVG(review_rating), 2) AS average_rating
FROM customer
GROUP BY item_purchased
ORDER BY average_rating DESC;
```

---

## Power BI Dashboard

An **interactive Power BI dashboard** was developed to visualize key insights derived from the analysis.

Dashboard highlights include:

* Product performance metrics
* Customer purchase trends
* Average product ratings
* Category-level comparisons
* Interactive filters and visual exploration

The dashboard helps convert raw data insights into **clear, actionable visual information**.

---

## Results and Insights

The analysis revealed several valuable insights, including:

* Identification of **top-rated and frequently purchased products**
* Trends in **customer purchasing behavior**
* Product categories with the highest engagement
* Insights that can support **data-driven decision making**

---

## Presentation

A professional presentation summarizing the project findings was created using **Gamma**. The presentation includes:

* Problem overview
* Data analysis methodology
* Key visual insights
* Business recommendations

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/360sabirrr/Customer_behavior_analysis.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

### 4. Execute the Analysis

Open the notebook file and run the cells sequentially to reproduce the data analysis and visualizations.

---

## Project Structure

```
data-analytics-project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── powerbi_dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
└── README.md
```

---

## Author

**Sabir Mahamad Shaikh**
Data Analyst | Python | SQL | Power BI

---

If you want, I can also show you **how to make your GitHub README look like a *Top Data Analyst Portfolio Project*** (with badges, visuals, dashboard preview, and recruiter-friendly formatting).
