# 📊 Regional Sales Intelligence — EDA for Business Growth Insights

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

**Objective:**  
To analyze 5 years of U.S. regional sales data and uncover insights into revenue performance, seasonal trends, product profitability, and customer behavior — enabling data-driven business decisions and sales optimization.

---

## 📊 Project Overview

The project addresses **inconsistent revenue and profit performance across U.S. regions** and the **lack of visibility** into seasonal fluctuations, top-performing products (SKUs), and sales channels.

### 🎯 Business Goals
- Identify key growth drivers across regions, products, and channels.  
- Detect seasonality patterns and optimize inventory planning.  
- Improve profit margins through channel and SKU performance insights.  
- Enable real-time, self-service analytics through a Power BI dashboard.

---

## 🧠 Approach

A **two-phase analytical solution**:

### **Phase 1 – Exploratory Data Analysis (EDA)**
- Profiled historical sales data using **Python (Pandas, Matplotlib, Seaborn)**.  
- Cleaned, merged, and normalized multiple datasets (Sales, Customers, Products, Regions, Budgets).  
- Engineered new metrics like `profit` and `profit_margin_pct`.

### **Phase 2 – Interactive Dashboard Development**
- Built an **interactive Power BI dashboard** for regional and product-level insights.  
- Designed visualizations for trends, profitability, and customer segmentation.  
- Enabled ad-hoc slicing by **time, product, region, and channel**.

---

## 🗂️ Dataset Description

| Category     | Example Columns                            | Purpose                            |
|---------------|---------------------------------------------|------------------------------------|
| **Identifiers** | `order_number`, `order_date`, `customer_name` | Transaction tracking |
| **Financials** | `quantity`, `unit_price`, `revenue`, `cost`, `profit`, `profit_margin_pct` | Financial performance |
| **Calendar** | `order_month_name`, `order_month_num` | Trend analysis |
| **Geography** | `state`, `state_name`, `us_region`, `lat`, `lon` | Regional segmentation |
| **Planning** | `budget_2017` | Forecast comparison |

✅ No missing or duplicate records after preprocessing.

---

## 🔍 Key Insights

- **Seasonality:** Peak sales during May–June; lowest in January.  
- **Product Performance:** Products #26 and #25 contribute ~25% of total revenue.  
- **Channel Mix:**  
  - Wholesale: 54% of sales volume  
  - Export: Highest margins (~38%)  
- **Regional Trends:**  
  - California dominates in revenue and order volume.  
  - West region leads overall; Northeast lags behind.  
- **Customer Insights:**  
  - Top clients (e.g., *Aibox Company*) drive majority revenue.  
  - Margins vary across large accounts — optimization opportunity.

---

## 💡 Recommendations

| Focus Area | Recommendation |
|-------------|----------------|
| **Seasonality** | Launch April recovery campaigns and January boost offers. |
| **SKU Strategy** | Reinforce top SKUs (#25, #26); reprice or phase out low-margin ones. |
| **Channel Optimization** | Expand Export partnerships; incentivize Wholesale with volume deals. |
| **Regional Expansion** | Replicate California’s strategy in Northeast and Midwest. |
| **Margin Monitoring** | Track and improve any orders below 80% profit margin. |

---

## 📈 Dashboard Highlights (Power BI)

- **Performance Summary** – Revenue, profit, and seasonality overview.  
- **Customer Segmentation** – Revenue vs. profit margin scatter and top clients.  
- **Revenue Scenarios** – “What-if” analysis for pricing and channel adjustments.  
- **Regional Sales Map** – Choropleth map by U.S. state and region.

---

## 🧰 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| **Data Cleaning & EDA** | Python, Pandas, NumPy, Matplotlib, Seaborn |
| **Visualization & Reporting** | Microsoft Power BI |
| **Data Storage** | Excel / CSV files |
| **Documentation** | MS PowerPoint, Markdown |

---

## 📦 Project Workflow

1. **Define Business Objectives** – Clarify KPIs and performance goals.  
2. **Collect & Consolidate Data** – Combine multi-source datasets.  
3. **Pre-process & Clean** – Handle nulls, join tables, normalize columns.  
4. **Exploratory Data Analysis** – Identify trends, outliers, and key drivers.  
5. **Dashboarding** – Build Power BI visuals for stakeholder insights.  
6. **Recommendations** – Derive actionable business strategies.

---

## 📚 Deliverables

- **EDA Notebook (Python)** – Data cleaning, transformation, visualization.  
- **Interactive Power BI Dashboard** – Business-ready analytics tool.  
- **Executive Summary Report** – Actionable insights and recommendations.

---

## 🧩 Outcomes

- Achieved **clear visibility** into regional and product-level sales performance.  
- Improved decision-making for **marketing, inventory, and pricing teams**.  
- Empowered stakeholders with **real-time insights** through Power BI.  
- Framework ready for integration with new datasets and automated reporting.

---

## 🏁 Conclusion

This project demonstrates the full **data analytics lifecycle** — from raw data cleaning to business insights visualization — driving measurable value for sales strategy and planning.


## 🚀 How to Run
```bash
git clone https://github.com/sachin1a1/Regional-Sales-Analysis.git
cd Regional-Sales-Analysis
pip install -r requirements.txt
jupyter notebook
```

## 👤 Author
**Sachin**
- GitHub: [@sachin1a1](https://github.com/sachin1a1)
- LinkedIn: www.linkedin.com/in/sachin1a1

