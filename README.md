# 📊 Superstore Sales Analysis

An exploratory data analysis (EDA) project on global retail sales data, uncovering key profitability drivers, discount impact, seasonal trends, and geographic performance.

## 📁 Dataset
- **Source**: [Global Superstore Dataset - Kaggle](https://www.kaggle.com/datasets/ronysoliman/global-superstore-dataset)
- **Size**: 51,290 rows × 27 columns
- **Coverage**: Global sales data (2011–2014) across multiple countries and regions

## 🎯 Objective
Analyze sales, profit, and discount patterns to identify actionable business insights for improving profitability.

## 🔑 Key Findings
1. **Technology** has the highest profit margin (14%), while **Furniture** has the weakest (7%) due to higher average discounts (16.8%)
2. Discounts above 30–40% generally lead to financial losses
3. Sales show a clear upward trend (2011–2014) with strong Q4 seasonality
4. The company operates globally — the US leads sales by more than double the next closest country (Australia)

## 💡 Recommendations
1. Reassess discount policy on the Furniture category
2. Increase marketing and inventory ahead of Q4 each year
3. Focus growth efforts on high-margin, high-volume categories like Technology

## 🛠️ Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📂 Project Structure
## 👤 Author
Tamam Aldmani
superstore-sales-analysis/
│
├── data/
│   ├── superstore.csv
│   └── superstore.db
├── notebooks/
│   ├── eda_superstore.ipynb
│   └── sql_practice.ipynb
└── README.md
## 🗄️ SQL Analysis
In addition to the Python-based EDA, this project includes a full SQL portfolio (15 analytical queries) built on the same dataset using SQLite, covering:
- Filtering & Aggregation (SELECT, WHERE, GROUP BY, HAVING)
- Subqueries & CTEs
- Window Functions (RANK, Running Totals)

📓 Notebook: `notebooks/sql_practice.ipynb`