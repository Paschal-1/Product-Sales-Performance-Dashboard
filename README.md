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
### 📊 Dashboard Overview
<img width="885" height="493" alt="productsales2" src="https://github.com/user-attachments/assets/3a7ff049-0657-45a3-aaba-94d346a1e34f" />
<img width="875" height="479" alt="productsales3" src="https://github.com/user-attachments/assets/f9559b4b-32fe-46be-a7ac-7403ab5de16f" />
<img width="898" height="506" alt="productsales4" src="https://github.com/user-attachments/assets/c602fe40-9874-4abc-9580-b9ff39ffa06e" />



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
