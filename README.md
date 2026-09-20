# 📊 Data Analytics Project

## Overview

This project demonstrates an **end-to-end data analytics workflow**, starting from raw data loading and exploratory analysis to SQL-based analysis, interactive Power BI visualization, and final business reporting.

The project focuses on extracting meaningful insights from data using **Python, SQL, PostgreSQL/MySQL/SQL Server, and Power BI**.

### Key Objectives
- Load and understand the dataset using Python
- Perform Exploratory Data Analysis (EDA)
- Clean and preprocess the data
- Perform data analysis using SQL
- Create an interactive Power BI dashboard
- Prepare a detailed analytical report
- Create a project presentation using Gamma

---

## 📂 Dataset

The dataset contains structured business-related information used to analyze trends, patterns, performance, and customer/business behavior.

### Dataset Workflow

**Raw Dataset → Python → Data Cleaning → SQL Analysis → Power BI → Report → Presentation**

The dataset was inspected for:
- Missing values
- Duplicate records
- Incorrect data types
- Outliers
- Inconsistent values
- Data quality issues

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data loading, cleaning and EDA |
| **Pandas** | Data manipulation and analysis |
| **NumPy** | Numerical operations |
| **Matplotlib / Seaborn** | Data visualization |
| **PostgreSQL** | SQL-based data analysis |
| **MySQL / SQL Server** | Database analysis and querying |
| **Power BI** | Interactive dashboard |
| **Gamma** | Project presentation |
| **Jupyter Notebook** | Python analysis |
| **Git & GitHub** | Version control and project sharing |

---

## 🔄 Project Steps

### 1. Data Loading

The dataset was loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
print(df.info())
```

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and characteristics of the dataset.

The analysis included:

- Dataset dimensions
- Column information
- Statistical summary
- Missing-value analysis
- Duplicate-value analysis
- Distribution analysis
- Correlation analysis
- Trend identification
- Outlier detection

---

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Major cleaning activities included:

- Handling missing values
- Removing duplicate records
- Correcting data types
- Standardizing categorical values
- Handling inconsistent records
- Treating outliers where required
- Creating useful derived columns

---

### 4. SQL Analysis

The cleaned data was imported into a relational database for further analysis.

SQL queries were written using **PostgreSQL / MySQL / SQL Server**.

The analysis included:

- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- Aggregate functions
- `CASE WHEN`
- Joins
- Subqueries
- Common Table Expressions (CTEs)
- Window functions

Example:

```sql
SELECT 
    category,
    SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
```

---

### 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive dashboard.

### Dashboard Features

- KPI cards
- Sales/revenue analysis
- Category analysis
- Customer analysis
- Trend analysis
- Interactive filters
- Slicers
- Charts and graphs
- Drill-down analysis

The dashboard provides a visual overview of important business metrics and helps users identify trends and patterns quickly.

---

## 📊 Dashboard

The Power BI dashboard presents key insights through interactive visualizations.

### Key Dashboard Metrics

- Total Revenue
- Total Sales
- Total Customers
- Total Orders
- Average Order Value
- Category/Segment Performance
- Monthly/Yearly Trends

> Add your Power BI dashboard screenshot here.

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

## 📈 Results & Insights

The project helped identify important patterns and trends from the dataset.

### Key Findings

- Identified major revenue and sales trends.
- Compared performance across different categories.
- Analyzed customer and order behavior.
- Identified high-performing and low-performing segments.
- Analyzed changes in performance over time.
- Used SQL to answer important business questions.
- Created an interactive dashboard for easier decision-making.

*The specific findings can be updated based on the actual project dataset.*

---

## 📝 Project Report

A detailed report was prepared covering:

1. Project Introduction
2. Business Problem
3. Dataset Description
4. Data Cleaning
5. Exploratory Data Analysis
6. SQL Analysis
7. Power BI Dashboard
8. Key Insights
9. Conclusion

---

## 🎤 Project Presentation

A presentation was created using **Gamma** to summarize the project.

The presentation includes:

- Project Overview
- Problem Statement
- Dataset
- Methodology
- Python Analysis
- SQL Analysis
- Power BI Dashboard
- Key Insights
- Conclusion

---

## ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
```

### Step 2: Open the Project

```bash
cd data-analytics-project
```

### Step 3: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the Python/EDA notebook and run the cells sequentially.

### Step 5: Run SQL Queries

Import the cleaned dataset into **PostgreSQL, MySQL, or SQL Server** and execute the SQL scripts provided in the `SQL` folder.

### Step 6: Open Power BI Dashboard

Open the `.pbix` file using **Microsoft Power BI Desktop**.

---

## 📁 Project Structure

```text
Data-Analytics-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── EDA_and_Data_Cleaning.ipynb
│
├── SQL/
│   └── analysis_queries.sql
│
├── PowerBI/
│   └── dashboard.pbix
│
├── Report/
│   └── project_report.pdf
│
├── Presentation/
│   └── project_presentation.pdf
│
├── Images/
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Skills Demonstrated

- Python
- Pandas
- NumPy
- Exploratory Data Analysis
- Data Cleaning
- SQL
- PostgreSQL
- MySQL
- SQL Server
- Power BI
- Data Visualization
- Business Analysis
- Dashboard Development
- Data Storytelling
- Git & GitHub

---

## 👨‍💻 Author

**Abhishek Jeeragal**

Aspiring **Data Analyst** with hands-on experience in Python, SQL, Power BI, and data visualization.

---

## ⭐ Conclusion

This project demonstrates a complete **end-to-end data analytics workflow**, transforming raw data into meaningful insights through Python, SQL, Power BI, reporting, and presentation.

It showcases practical skills in **data preparation, analysis, visualization, business intelligence, and data storytelling**.# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python, SQL, power Bi
