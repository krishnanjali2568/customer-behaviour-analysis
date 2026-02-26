# 📊 Customer Shopping Behavior Analysis

An end-to-end data analytics project analyzing 3,900 customer transactions to uncover shopping patterns, customer segments, and revenue drivers — using Python, SQL (PostgreSQL), and Power BI.

---

## 🗂️ Project Overview

A retail company wants to better understand its customers' shopping behavior to improve sales, customer satisfaction, and long-term loyalty. This project analyzes transactional data across demographics, product categories, and sales channels to answer:

> **"How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?"**

---

## 📁 Repository Structure

```
customer-behaviour-analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb   # Python EDA & data cleaning
├── customer_behavior_sql_queries.sql           # 10 business SQL queries
├── customer_behavior_dashboard.pbix            # Interactive Power BI dashboard
├── customer_shopping_behavior.csv              # Raw dataset (Kaggle)
├── Customer Shopping Behavior Analysis.pdf     # Full project report
├── Customer-Shopping-Behavior-Analysis.pptx   # Executive presentation
└── Business Problem Document.pdf              # Problem statement
```

---

## 📦 Dataset

- **Source:** Kaggle — Customer Shopping Behavior Dataset
- **Rows:** 3,900 transactions
- **Columns:** 18 features including:
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item, Category, Purchase Amount (USD), Season
  - Behavior: Discount Applied, Previous Purchases, Review Rating, Shipping Type

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning & EDA |
| PostgreSQL | SQL analysis & querying |
| Power BI | Interactive dashboard |
| Jupyter Notebook | Analysis environment |
| GitHub | Version control |

---

## 🔍 Project Steps

### 1. Data Cleaning & Preparation (Python)
- Imported dataset using Pandas and verified structure with `df.info()` and `.describe()`
- Handled 37 missing values in the `review_rating` column using median imputation per product category
- Renamed columns to snake_case for consistency
- Engineered new features: `age_group` (binned) and `purchase_frequency_days`
- Verified redundancy between `discount_applied` and `promo_code_used` — dropped `promo_code_used`
- Connected Python to PostgreSQL and loaded the cleaned DataFrame for SQL analysis

### 2. SQL Analysis (PostgreSQL)
Wrote 10 business queries covering:
- Revenue by gender
- High-spending discount users
- Top 5 products by review rating
- Shipping type comparison
- Subscriber vs. non-subscriber spend
- Discount-dependent products
- Customer segmentation (New / Returning / Loyal)
- Top 3 products per category
- Repeat buyers and subscription behavior
- Revenue contribution by age group

### 3. Power BI Dashboard
Built an interactive dashboard with:
- KPI cards: 3.9K customers, $59.76 avg purchase, 3.75 avg rating
- Revenue and sales by category
- Revenue and sales by age group
- Subscription status breakdown
- Interactive filters: Gender, Category, Shipping Type, Subscription Status

---

## 📈 Key Findings

| Insight | Finding |
|--------|---------|
| 💰 Revenue by Gender | Male customers generated $157,890 vs. Female $75,191 |
| 🏆 Top Age Group by Revenue | Young Adults contributed the highest revenue at $62,143 |
| ⭐ Highest Rated Product | Gloves (avg rating 3.86), followed by Sandals (3.84) |
| 📦 Top Category | Clothing — Blouse and Pants were the most purchased items (171 orders each) |
| 🔖 Most Discount-Dependent Product | Hat (50% of purchases used a discount) |
| 🚚 Shipping Preference | Express shipping users spent slightly more ($60.48) vs. Standard ($58.46) |
| 👥 Customer Segments | 3,116 Loyal customers, 701 Returning, 83 New |
| 📋 Subscription Impact | 73% of customers are non-subscribers; both groups have similar avg spend (~$59) |
| 🔁 Repeat Buyers | Among customers with >5 purchases, 2,518 are non-subscribers vs. 958 subscribers |
| 💡 High-Value Discount Users | 839 customers used discounts but still spent above average purchase amount |

---

## 💡 Business Recommendations

- **Boost Subscriptions** — Introduce exclusive perks for subscribers since avg spend is similar; loyalty programs could convert the 73% non-subscribers
- **Target Young Adults** — Highest revenue segment; prioritize marketing campaigns toward this age group
- **Focus on Clothing Category** — Highest sales volume; expand product range and seasonal promotions
- **Revise Discount Strategy** — Hat, Sneakers, and Coat have ~50% discount rates; review margin impact
- **Reward Loyal Customers** — 80% of customers are in the Loyal segment; implement tiered loyalty rewards
- **Leverage Express Shipping** — Higher spend in express users; offer express shipping promotions to increase basket size

---

## ▶️ How to Run

### Clone the repository
```bash
git clone https://github.com/krishnanjali2568/customer-behaviour-analysis.git
```

### Install Python dependencies
```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Run the analysis
- Open `Customer_Shopping_Behavior_Analysis.ipynb` in Jupyter Notebook
- Run all cells sequentially

### Run SQL queries
- Import `customer_shopping_behavior.csv` into PostgreSQL
- Execute queries from `customer_behavior_sql_queries.sql`

### View Power BI dashboard
- Open `customer_behavior_dashboard.pbix` in Power BI Desktop
- Refresh the data source if needed

---

## 🧠 Skills Demonstrated

`Data Cleaning` `Exploratory Data Analysis` `Feature Engineering` `SQL Querying` `Window Functions` `CTEs` `PostgreSQL` `Power BI Dashboard` `KPI Design` `Business Reporting` `Data Visualization` `Customer Segmentation`

---

## 👩‍💻 Author

**Krishnanjali R**  
Aspiring Data Analyst | Python | SQL | Power BI  
📧 krishnanjali2568@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/krishnanjalir-b2b449363) | [GitHub](https://github.com/krishnanjali2568)
