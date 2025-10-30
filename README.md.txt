# 📊 Sales Analysis Dashboard — Day 1

A beginner data analysis project using Excel and SQL.  
Goal: Convert raw sales data into meaningful business insights.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| **sales_data.xlsx** | Raw data, formulas, pivot tables |
| **Sales Dashboard - Day1.pdf** | Final clean dashboard report |
| **sales_data.sql** | SQL table + data insert statements |

---

## 📸 Dashboard Preview
*(Screenshot of dashboard will be shown here in next update)*

---

## 📌 Key Insights
- Total Revenue: **3,420 BDT**
- Top Region: **South**
- Highest Selling Product: **Laptop**
- No missing or incorrect records found ✅

---

## 🛠️ Tools Used
- Microsoft Excel
- SQL (SQLite)
- GitHub for version control

---

## ▶️ How to Run SQL
1. Go to https://sqliteonline.com
2. Open / paste `sales_data.sql`
3. Run:
```sql
SELECT Region, SUM(Total_Sales) AS revenue 
FROM sales_data 
GROUP BY Region 
ORDER BY revenue DESC;

