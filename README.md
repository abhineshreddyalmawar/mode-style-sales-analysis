# 📊 Mode-Style Sales Analysis

[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-17-336791?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-yellow?logo=plotly&logoColor=white)](https://matplotlib.org/)

> A simple project that replicates the [Mode Analytics](https://mode.com) workflow (SQL → Python → Dashboard) using **PostgreSQL + Jupyter Notebook**.

This project mimics the [Mode Analytics](https://mode.com) workflow:
- **SQL Query**: Run in PostgreSQL (Top 5 customers by sales).
- **Python Analysis**: Pandas to calculate monthly trends.
- **Visualization**: Matplotlib charts for insights.
- **Dashboard**: Export notebook to HTML (simulating Mode report).

---

## 📂 Project Structure

Mode/
├── Data/
│ └── sales_data.csv
├── notebooks/
│ └── Modeminiproject.ipynb
├── Outputs/
│ ├── monthly_sales_trend.png
│ └── top_customers.png
├── requirements.txt
├── .gitignore
└── README.md


---

## ⚙️ Tech Stack
- PostgreSQL 17
- Python 3.x
- Pandas, Matplotlib, SQLAlchemy, Psycopg2, Jupyter

---

## 🚀 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/YOUR-USERNAME/mode-style-sales-analysis.git
   cd mode-style-sales-analysis


pip install -r requirements.txt

jupyter notebook

## 🌟 Project Highlights
- Built an **end-to-end analytics workflow** (SQL → Python → Dashboard) replicating Mode Analytics.
- Queried **PostgreSQL 17** with SQLAlchemy to calculate **Top 5 Customers by Sales**.
- Performed **data analysis with Pandas** to compute monthly sales trends.
- Created **visualizations with Matplotlib** and exported charts as part of the report.
- Organized project with a **clean folder structure** (data, notebooks, outputs) for GitHub publishing.
- Published results in a **Jupyter Notebook + README with screenshots**, simulating a Mode dashboard.



📈 Sample Outputs

## 🖼️ Project Demo Screenshots

### Top 5 Customers by Total Sales
<img src="Outputs/top_customers.png" alt="Top Customers by Sales" width="500"/>

### Monthly Sales Trend
<img src="Outputs/monthly_sales_trend.png" alt="Monthly Sales Trend" width="500"/>

### (Optional) Revenue by Product
<img src="Outputs/revenue_by_product.png" alt="Revenue by Product" width="500"/>



