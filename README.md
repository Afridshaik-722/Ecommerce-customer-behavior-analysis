# 🛒 E-Commerce Customer Behavior Analysis

> **An end-to-end data analytics project** uncovering customer purchase patterns, segmentation insights, and revenue trends from a real-world e-commerce dataset — using SQL, Python, and Power BI.

---

## 📌 Project Summary

Businesses lose revenue when they don't understand their customers. This project dives deep into **3,900+ e-commerce transactions** to answer critical business questions:

- Who are the most valuable customers?
- Which product categories drive the most revenue?
- What behavioral patterns predict repeat purchases?
- How do demographics influence buying decisions?

Every insight in this project is backed by data — and presented in a way any business stakeholder can act on.

---

## 🧰 Tools & Technologies

| Layer | Tool |
|---|---|
| Data Cleaning & EDA | Python (Pandas) |
| Business Analysis | SQL (PostgreSQL) |
| Dashboard & Visualization | Power BI |
| Dataset | [Customer Shopping Behavior CSV](https://github.com/Afridshaik-722/Ecommerce-customer-behavior-analysis/blob/main/customer_shopping_Dataset.csv) |

---

## 🔄 Project Workflow

```
Raw Dataset
    ↓
🐍 Python (Pandas) — Data Cleaning & EDA
    ↓
🗄️ PostgreSQL — Business Question Answering via SQL Queries
    ↓
📊 Power BI — Interactive Dashboard & Visualizations
    ↓
📝 Insights & Business Recommendations
```

---

## 📊 Key Business Questions Answered

✅ What is the overall revenue breakdown by product category?

✅ Which customer segments (age, gender, location) generate the highest lifetime value?

✅ What are the peak purchase seasons and shopping frequency trends?

✅ Which payment methods are most preferred, and does it correlate with order size?

✅ How does discount usage affect customer retention and average order value?

✅ Who are the top repeat customers, and what do they have in common?

---

## 💡 Key Insights Discovered

> *(Summarized from analysis — see notebooks and dashboard for full details)*

- 📦 **Top 3 categories** account for over 60% of total revenue
- 👥 Customers aged **25–40** show the highest purchase frequency and average order value
- 🔁 Repeat customers spend **2.3x more** per order than one-time buyers
- 💳 A specific payment method correlates strongly with higher-value transactions
- 📅 Revenue peaks observed in specific months — enabling targeted promotional planning

---

## 📁 Repository Structure

```
📦 ecommerce-customer-behavior-analysis
 ┣ 📂 data/
 ┃ ┗ customer_shopping_behavior.csv        # Raw dataset
 ┣ 📂 notebooks/
 ┃ ┗ customer_behavior_analysis.ipynb      # Python EDA & Cleaning
 ┣ 📂 sql/
 ┃ ┗ business_questions_queries.sql        # All SQL analysis queries
 ┣ 📂 dashboard/
 ┃ ┣ customer_behavior_dashboard.pbix      # Power BI Dashboard file
 ┃ ┗ dashboard_screenshot.png             # Dashboard preview image
 ┣ 📂 reports/
 ┃ ┗ project_report.pdf                   # Final insights report
 ┣ README.md
 ┗ requirements.txt                        # Python dependencies
```

---

## 🚀 How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/Afridshaik-722/ecommerce-customer-behavior-analysis.git
cd ecommerce-customer-behavior-analysis
```

### 2. Install Python Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Python Notebook
- Open `notebooks/customer_behavior_analysis.ipynb`
- Execute all cells for data cleaning, EDA, and feature engineering

### 4. Set Up SQL Database
- Create a database in MySQL or PostgreSQL
- Load the cleaned data from the Python notebook
- Open and run `sql/business_questions_queries.sql`

### 5. Explore the Power BI Dashboard
- Open `dashboard/customer_behavior_dashboard.pbix` in Power BI Desktop
- Connect to your SQL database if prompted
- Interact with filters and visuals to explore insights

---



## 🧠 Skills Demonstrated

- ✅ Real-world data cleaning and handling missing/inconsistent values using Pandas
- ✅ Exploratory Data Analysis with Pandas to understand data shape and distributions
- ✅ Writing optimized SQL queries in PostgreSQL for business intelligence
- ✅ Building interactive, stakeholder-ready Power BI dashboards
- ✅ Translating data findings into clear business recommendations

---

## 📄 License

MIT — Free to fork, reference, and build upon.

---

## 🙋‍♂️ About Me

I'm **Afrid Shaik**, an aspiring Data Analyst passionate about turning raw data into decisions that matter.

This project reflects my ability to handle a complete analytics workflow — from messy data to boardroom-ready insights.

📧 Connect with me on [LinkedIn](https://www.linkedin.com/in/afrid-shaik-868624214)

