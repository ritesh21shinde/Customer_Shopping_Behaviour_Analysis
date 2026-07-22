# Customer_Shopping_Behaviour_Analysis
# 🛍️ Customer Shopping Behavior Analysis | Python + MySQL + Power BI

## 📌 Project Overview

This project is an end-to-end Data Analytics solution built using **Python, Pandas, MySQL, and Power BI**. The objective is to analyze customer shopping behavior, identify purchasing trends, and create an interactive business dashboard for data-driven decision making.

The project demonstrates the complete analytics workflow:

- Data Loading
- Data Cleaning
- Exploratory Data Analysis (EDA)
- SQL Analysis
- Interactive Dashboard Development
- Business Insights

---

## 🎯 Objectives

- Analyze customer purchasing behavior.
- Identify top-performing product categories.
- Measure the impact of discounts on sales.
- Compare revenue across customer demographics.
- Build an interactive dashboard for business users.

---

# 📂 Dataset

**Dataset Name:** Customer Shopping Behavior Dataset

The dataset contains customer purchase records including:

- Customer ID
- Age
- Gender
- Item Purchased
- Category
- Purchase Amount (USD)
- Location
- Size
- Color
- Season
- Review Rating
- Subscription Status
- Shipping Type
- Discount Applied
- Promo Code Used
- Previous Purchases
- Payment Method
- Frequency of Purchases

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|------|----------|
| Python | Data Processing |
| Pandas | Data Cleaning & Analysis |
| Jupyter Notebook | Data Exploration |
| MySQL | Data Storage & SQL Analysis |
| SQL | Business Queries |
| Power BI | Dashboard & Visualization |
| GitHub | Version Control |

---

# 📁 Project Workflow

## 1️⃣ Data Loading

- Loaded CSV dataset using Pandas
- Checked data types
- Imported data into MySQL database

```python
import pandas as pd

df = pd.read_csv("customer_shopping_behavior.csv")
```

---

## 2️⃣ Data Cleaning

Performed:

- Missing value check
- Duplicate removal
- Data type validation
- Column formatting

---

## 3️⃣ Exploratory Data Analysis (EDA)

Performed analysis on:

- Customer demographics
- Revenue distribution
- Product categories
- Seasonal trends
- Customer purchasing behavior
- Discount analysis

Libraries used:

- Pandas
- Matplotlib

---

## 4️⃣ SQL Analysis (MySQL)

Imported cleaned dataset into MySQL and executed business queries.

Example analyses:

- Total Revenue
- Revenue by Gender
- Revenue by Category
- Top Selling Products
- Discount Analysis
- Average Purchase Amount
- Revenue by Age Group
- Customer Segmentation
- Shipping Type Analysis
- Seasonal Sales Analysis

Example Query:

```sql
SELECT Gender,
SUM(`Purchase Amount (USD)`) AS Revenue
FROM customer
GROUP BY Gender;
```

---

## 5️⃣ Power BI Dashboard

Created an interactive dashboard containing:

### KPI Cards

- Total Revenue
- Total Customers
- Average Purchase Amount
- Average Review Rating
- Discount Usage %
- Total Orders

### Visualizations

- Revenue by Category
- Revenue by Gender
- Revenue by Age Group
- Revenue by Season
- Revenue by Location
- Top Selling Products
- Shipping Type Analysis
- Subscription Status
- Payment Method Analysis

### Interactive Filters

- Gender
- Category
- Season
- Age Group
- Subscription Status
- Discount Applied

---

# 📊 Dashboard Preview

> Add dashboard screenshots here.

Example:

```
Dashboard/
│
├── Dashboard.png
├── Sales Overview.png
├── Customer Insights.png
```

---

# 📈 Key Business Insights

- Clothing generated the highest revenue.
- Customers aged 31–50 contributed the highest sales.
- Discount campaigns significantly increased purchase frequency.
- Subscribers spent more than non-subscribers.
- Winter season generated higher overall revenue.
- Certain locations consistently outperformed others in sales.

---

# 📂 Project Structure

```
Customer-Shopping-Analysis/
│
├── Data/
│   └── customer_shopping_behavior.csv
│
├── Python/
│   └── EDA.ipynb
│
├── SQL/
│   └── SQL_Queries.sql
│
├── Dashboard/
│   ├── Customer_Shopping_Dashboard.pbix
│   └── Dashboard.png
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run

## Step 1

Clone the repository

```bash
git clone https://github.com/yourusername/customer-shopping-analysis.git
```

---

## Step 2

Install required libraries

```bash
pip install pandas matplotlib sqlalchemy pymysql
```

---

## Step 3

Open Jupyter Notebook

```bash
jupyter notebook
```

Run the EDA notebook.

---

## Step 4

Create MySQL database

```sql
CREATE DATABASE customer_db;
```

Import the cleaned dataset into MySQL.

---

## Step 5

Execute SQL queries

Run all queries from:

```
SQL/SQL_Queries.sql
```

---

## Step 6

Open Power BI Desktop

Open:

```
Customer_Shopping_Dashboard.pbix
```

Refresh the data source if required.

---

# 📌 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- SQL
- MySQL
- Python Programming
- Pandas
- Business Intelligence
- Power BI
- Dashboard Design
- Data Visualization
- Business Insights
- Git & GitHub

---

# 🚀 Future Improvements

- Add predictive sales forecasting.
- Integrate real-time database updates.
- Deploy dashboard using Power BI Service.
- Add customer segmentation using Machine Learning.
- Build automated ETL pipeline.

---

# 👨‍💻 Author

**Ritesh**

Aspiring Data Analyst

### Connect with me

- LinkedIn: *(Add your LinkedIn profile)*
- GitHub: *(Add your GitHub profile)*

---

## ⭐ If you found this project useful, consider giving it a star!


