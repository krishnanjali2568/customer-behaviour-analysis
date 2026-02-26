# 📊 Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing customer shopping patterns using Python, SQL, and Power BI — transforming raw transaction data into actionable business insights.

---

## 📌 Project Overview

This project analyzes a structured retail dataset of **3,900 customer transactions** across 18 features including demographics, purchase categories, payment methods, seasonal trends, and review ratings.

The goal was to identify customer behavior patterns, top-performing product categories, and revenue drivers to support data-driven business decision-making.

---

## 📂 Dataset

- **Source:** Customer Shopping Behavior Dataset (CSV)
- **Records:** 3,900 transactions
- **Features:** 18 columns including Age, Gender, Category, Purchase Amount, Season, Payment Method, Subscription Status, Review Rating, and more

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning, EDA |
| SQL (PostgreSQL) | Data querying and aggregation |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Analysis environment |
| GitHub | Version control |

---

## 🔍 Project Steps

### 1. Data Loading & Inspection
- Imported dataset using Pandas
- Checked for null values, data types, and structure
- Dataset had 3,900 rows and 18 columns with no major missing values

### 2. Data Cleaning & Preprocessing
- Handled missing Review Rating values
- Standardized categorical columns (Gender, Season, Category)
- Created Age Group bins (18–25, 26–35, 36–50, 51–70) for segmentation analysis
- Verified data types and converted where necessary

### 3. Exploratory Data Analysis (EDA)
- Performed descriptive statistics on purchase amounts and ratings
- Analyzed distribution of purchases across categories, seasons, and age groups
- Identified trends in payment preferences and subscription behavior

### 4. SQL Analysis (PostgreSQL)
- Loaded cleaned dataset into PostgreSQL
- Wrote queries using GROUP BY, JOINS, aggregations (SUM, AVG, COUNT)
- Extracted insights on revenue by category, season, and customer segment

### 5. Power BI Dashboard
- Connected Power BI to cleaned dataset
- Built interactive dashboard with KPIs, filters, and slicers
- Visualized revenue trends, customer segmentation, and product performance

---

## 📊 Key Insights & Findings

- **Clothing dominated purchases** with 1,737 transactions (44.5% of total), followed by Accessories (1,240) and Footwear (599)
- **Footwear had the highest average purchase value** at $60.26, slightly above Clothing ($60.03)
- **Fall was the top revenue season** generating $60,018, while Summer was the lowest at $55,777
- **18–25 age group had the highest average spend** at $60.65 per transaction
- **Only 27% of customers are subscribers** (1,053 out of 3,900) — indicating a significant opportunity for subscription growth
- **Average review rating was 3.75/5** — suggesting room to improve customer satisfaction
- **Payment methods were evenly distributed** — PayPal (677), Credit Card (671), and Cash (670) were the top three
- **Discount impact was minimal** — discounted purchases averaged $59.28 vs $60.13 without discounts, suggesting customers buy regardless of discounts

---

## 💡 Business Recommendations

- Focus marketing campaigns on **Fall and Spring seasons** for maximum revenue
- Target **18–25 age group** with premium product offers as they show highest spend
- Invest in **subscription conversion strategies** — only 27% are subscribers
- Review discount strategy — discounts are not significantly driving higher purchase amounts
- Improve customer experience to push average rating above 4.0

---

## 📁 Repository Structure

```
customer-behaviour-analysis/
│
├── customer_shopping_behavior.csv         # Raw dataset
├── Customer_Shopping_Behavior_Analysis.ipynb  # Python EDA notebook
├── customer_behavior_sql_queries.sql      # SQL queries
├── customer_behavior_dashboard.pbix       # Power BI dashboard
├── Customer Shopping Behavior Analysis.pdf  # Business report
├── Business Problem Document.pdf          # Problem statement
├── Customer-Shopping-Behavior-Analysis.pptx  # Presentation
└── README.md
```

---

## ▶️ How to Run

### Clone the repository
```bash
git clone https://github.com/krishnanjali2568/customer-behaviour-analysis.git
```

### Install dependencies
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Run Python analysis
- Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook
- Run all cells

### Run SQL queries
- Import `customer_shopping_behavior.csv` into PostgreSQL
- Execute queries from `customer_behavior_sql_queries.sql`

### Open Power BI Dashboard
- Open `customer_behavior_dashboard.pbix` in Power BI Desktop
- Refresh data source if needed

---

## ✅ Skills Demonstrated

- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- SQL Querying & Database Management
- Power BI Dashboard Development
- Business Reporting & Insights Generation
- Data-Driven Decision Making

---

## 👩‍💻 Author

**Krishnanjali R**
Aspiring Data Analyst
Python | SQL | Power BI | Data Analytics

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/krishnanjalir-b2b449363)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/krishnanjali2568)
