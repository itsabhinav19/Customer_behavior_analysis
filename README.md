# Customer_behavior_analysis
Customer Behavior analysis using Power BI
# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, starting from raw dataset exploration and data cleaning to SQL-based analysis and interactive dashboard creation.

The project uses **Python for data analysis and EDA, SQL for querying and extracting insights, and Power BI for data visualization and reporting**.

### Project Workflow

**Dataset → Data Loading → EDA → Data Cleaning → SQL Analysis → Power BI Dashboard → Results & Insights**

---

## 📁 Dataset

The project uses a structured dataset containing relevant business/analytical data.

The dataset is:

* Loaded and explored using Python
* Checked for missing values and duplicate records
* Cleaned and transformed for analysis
* Used for SQL-based analysis
* Connected to Power BI for visualization

> **Dataset:** `customer_shopping_behavior.csv`

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                                            |
| ----------------------------------- | -------------------------------------------------- |
| **Python**                          | Data loading, cleaning, preprocessing and analysis |
| **Pandas**                          | Data manipulation and transformation               |
| **NumPy**                           | Numerical operations                               |
| **Matplotlib / Seaborn**            | Exploratory data visualization                     |
| **PostgreSQL / MySQL / SQL Server** | SQL queries and data analysis                      |
| **Power BI**                        | Interactive dashboard and visualization            |
| **Jupyter Notebook / Google Colab** | Python-based analysis                              |
| **Git & GitHub**                    | Version control and project management             |

---

## 🔍 Project Steps

### 1. Data Loading

The dataset is imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

Initial checks are performed to understand the structure and quality of the data.

```python
df.head()
df.shape
df.info()
df.describe()
```

---

### 2. Exploratory Data Analysis (EDA)

EDA is performed to identify patterns, trends, relationships, and potential data-quality issues.

Key activities include:

* Understanding dataset dimensions
* Analyzing data types
* Identifying missing values
* Detecting duplicate records
* Examining numerical and categorical variables
* Analyzing distributions
* Identifying outliers
* Creating visualizations

---

### 3. Data Cleaning

The dataset is cleaned and prepared for further analysis.

Major preprocessing steps include:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing categorical values
* Handling inconsistent data
* Treating outliers where required
* Creating derived/feature columns

The cleaned dataset is then prepared for SQL analysis and Power BI visualization.

---

### 4. SQL Analysis

The cleaned data is loaded into a relational database such as:

* PostgreSQL
* MySQL
* SQL Server

SQL queries are used to extract meaningful insights from the dataset.

Example analysis includes:

* Aggregations using `SUM()`, `AVG()`, `COUNT()`
* Grouping using `GROUP BY`
* Filtering using `WHERE` and `HAVING`
* Sorting and ranking
* Joins between tables
* Subqueries
* Common Table Expressions (CTEs)
* Window functions

Example:

```sql
SELECT
    category,
    COUNT(*) AS total_records,
    AVG(value) AS average_value
FROM dataset
GROUP BY category
ORDER BY total_records DESC;
```

---

## 📈 Power BI Dashboard

An interactive **Power BI dashboard** is created to present the key findings in an easy-to-understand format.

The dashboard includes relevant:

* KPI cards
* Charts and graphs
* Category-wise analysis
* Trend analysis
* Filters and slicers
* Interactive visualizations

### Dashboard Objectives

The dashboard helps users:

* Monitor important KPIs
* Identify trends and patterns
* Compare different categories
* Explore the data interactively
* Support data-driven decision making

> 📌 Add your Power BI dashboard screenshot here.

```text
![Power BI Dashboard](images/dashboard.png)
```

---

## 📊 Results & Key Insights

The analysis provides insights into the dataset by combining statistical analysis, SQL queries, and interactive visualizations.

Key findings include:

* Identification of important trends and patterns
* Comparison of key categories and metrics
* Detection of significant variations in the data
* Identification of factors influencing important metrics
* Interactive exploration of results through Power BI

Detailed findings are documented in the project report.

---

## 📄 Project Report

A detailed report is included to document:

* Problem statement
* Dataset description
* Data preprocessing
* Exploratory data analysis
* SQL analysis
* Power BI dashboard
* Key findings
* Business/analytical insights
* Conclusion

📄 **Report:** `report/project_report.pdf`

---

## 🚀 How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/data-analytics-project.git
cd data-analytics-project
```

### Step 2: Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install the dependencies using:

```bash
pip install -r requirements.txt
```

### Step 3: Run the Python Analysis

Open the Jupyter Notebook or Google Colab file:

```text
notebooks/data_analysis.ipynb
```

Run the notebook to perform:

**Data Loading → EDA → Data Cleaning → Analysis**

### Step 4: Run SQL Queries

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL scripts available in:

```text
sql/
```

### Step 5: Open the Power BI Dashboard

Open the Power BI file:

```text
powerbi/data_analytics_dashboard.pbix
```

If required, update the database connection settings before refreshing the dashboard.

---

## 📂 Project Structure

```text
Data-Analytics-Project/
│
├── dataset/
│   └── dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── data_analytics_dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── requirements.txt
│
└── README.md
```

---

## 🎯 Skills Demonstrated

* Data Analysis
* Exploratory Data Analysis (EDA)
* Data Cleaning & Preprocessing
* Python & Pandas
* SQL
* PostgreSQL / MySQL / SQL Server
* Data Visualization
* Power BI
* Dashboard Development
* Business Intelligence
* Data-driven Insights
* Reporting

---

## 👨‍💻 Author

**Abhinav Kashyap**

Computer Science Student | Data Analytics & Machine Learning

---

## ⭐ Project Highlights

This project demonstrates an end-to-end approach to transforming **raw data into actionable insights** using Python, SQL, and Power BI.

**Python → Clean Data → SQL → Insights → Power BI → Report**
