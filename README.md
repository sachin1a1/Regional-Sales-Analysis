# 📊 Regional Sales Intelligence — EDA for Business Growth Insights

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Status](https://img.shields.io/badge/Status-Complete-success.svg)

## 🏢 Project Overview
The **Regional Sales Analysis** project delivers a data-driven understanding of U.S. regional performance across five years of historical data.  
The aim is to identify growth opportunities, uncover regional patterns, and optimize business strategies through data analytics and visualization.

---

## 🎯 Problem Statement
Inconsistent revenue and profit performance across regions hinder data-backed decision-making.  
Sales teams struggle to identify growth opportunities and optimize channel strategies.

**Objective:**  
Utilize five years of sales data to pinpoint growth levers, analyze profitability, and support strategic decisions.

---

## 🧠 Project Approach

### Workflow Summary
| Step | Phase | Description |
|------|--------|-------------|
| 1️⃣ | Define Business Objective | Understand the core business challenge and expected outcomes. |
| 2️⃣ | Data Collection | Gather multi-source sales data (Excel/CSV) and analyze schemas. |
| 3️⃣ | Data Loading | Import data into Jupyter Notebook for profiling and understanding. |
| 4️⃣ | Pre-processing | Handle nulls, join tables, format dates, and normalize fields. |
| 5️⃣ | Feature Engineering | Derive new columns such as profit and profit margins. |
| 6️⃣ | EDA | Explore data trends, correlations, and anomalies through visuals. |
| 7️⃣ | Visualization | Develop dashboards for regional and channel insights. |
| 8️⃣ | Recommendations | Provide actionable business strategies based on insights. |

---

## 🧩 Tools & Technologies
- **Language:** Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)
- **IDE:** Jupyter Notebook
- **Data Format:** Excel / CSV
- **Environment:** Anaconda Distribution

---

## 📂 Dataset Overview
### Key Entities:
- **Sales** — order details, cost, and revenue metrics
- **Customers** — customer details and geography
- **Products** — SKU-level product data
- **Regions** — state-to-region mapping
- **Budgets** — planned annual budgets (2017)

### Final Dataset Fields:
| Category | Columns |
|-----------|----------|
| Identifiers | order_number, order_date, customer_name, channel, product_name |
| Financials | quantity, unit_price, revenue, cost, profit, profit_margin_pct |
| Calendar | order_month_name, order_month_num, order_year |
| Geography | state_name, us_region, lat, lon |

---

## 📊 Key Insights

| Category | Findings |
|-----------|-----------|
| **Seasonality** | Revenue peaks in May–June; dips occur in January. |
| **Top Products** | Products 25 & 26 account for 25% of total revenue. |
| **Channels** | Wholesale drives 54% of sales; Export yields ~38% margins. |
| **Regions** | California leads with $230M; the West region dominates sales. |
| **Customers** | Aibox Company is the top customer by revenue. |
| **Correlations** | Unit price is the strongest driver of profit and revenue. |

---

## 💡 Strategic Recommendations

1. **Seasonal Promotions** — Launch recovery campaigns in April; boost January offers.  
2. **SKU Optimization** — Focus investment on high-margin SKUs (25 & 26).  
3. **Channel Expansion** — Strengthen Export partnerships for higher profitability.  
4. **Regional Investment** — Replicate California’s success model in other regions.  
5. **Margin Monitoring** — Flag and optimize orders below 80% profit margin.  

---

---

## 🚀 Future Enhancements
- Integrate **Power BI dashboard** for interactive regional analysis.  
- Develop **predictive models** for sales forecasting.  
- Automate **data pipelines** using SQL + Python.  

---

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

