# Product-Sales-Performance-Dashboard
# 🧩 Product Sales Performance Dashboard (Power BI)

### 📊 Project Overview
This Power BI project visualizes and analyzes **company-wide product sales data** to uncover insights into revenue performance, regional contributions, and product trends.  
The dashboard was built to help stakeholders quickly identify **top-performing products**, **high-revenue territories**, and **sales distribution patterns** — transforming raw sales data into actionable business intelligence.

---

### 🔍 Key Insights
- **$33.93M Total Revenue** generated across multiple product categories and territories.  
- **Canada** and the **Northwest** emerged as the leading markets, contributing over **55%** of total revenue.  
- **Bikes** dominated the product category, driving the largest share of total line sales.  
- **Mountain-200 Black** and **Classic Jerseys** ranked as the **top-selling products** across all markets.  
- Dashboard highlights **Order Status**, **Territory Performance**, and **Salesperson Contribution** — enabling quick identification of bottlenecks and growth areas.

---

### ⚙️ Tools & Techniques Used
| Tool / Technique | Purpose |
|------------------|----------|
| **Power BI** | Data modeling, DAX calculations, and dashboard design |
| **Excel** | Initial data cleaning and transformation |
| **DAX Measures** | Revenue, Orders, YoY Growth %, and Territory-level KPIs |
| **Data Visualization** | Interactive charts and KPIs for quick insight discovery |
| **Data Storytelling** | Translating sales data into strategic business insights |

---

### 🧮 Key Metrics (DAX Measures)
```DAX
Total Line Sales = SUM('Sales'[LineTotal])
Total Revenue = SUM('Sales'[TotalDue])
Total Orders = DISTINCTCOUNT('Sales'[OrderID])
