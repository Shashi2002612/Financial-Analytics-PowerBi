# 📊 Financial Analytics Dashboard — Power BI

A 3-page enterprise-grade Financial Analytics Dashboard built in Power BI using the Microsoft Financial Sample Dataset.

## 📌 Pages

### Page 1 — Executive Summary
- 5 KPI Cards: Total Revenue, Gross Profit, Profit Margin %, Revenue YTD, Units Sold
- Revenue Trend Line Chart (YTD vs Actual)
- Revenue by Country (Bar Chart + Map)
- Revenue by Segment (Donut Chart)

### Page 2 — MoM & YoY Analysis
- Month-over-Month % change tracking
- Year-over-Year comparison (2013 vs 2014)
- Matrix visual: Revenue breakdown by Month & Year

### Page 3 — Product & Segment Analysis
- Treemap: Gross Profit by Product
- Clustered Column: Revenue vs Profit by Segment
- Scatter Chart: Sale Price vs Units Sold by Product

## 🔒 Row-Level Security (RLS)
- USA Manager role — restricted to United States data only
- Same dashboard, different data per user

## 🛠️ Tech Stack
Power BI Desktop · DAX · Date Table · Star Schema · RLS

## 💡 Key DAX Measures
| Measure | DAX Function |
|---|---|
| Revenue YTD | TOTALYTD |
| Revenue MoM % | DATEADD |
| Revenue YoY % | SAMEPERIODLASTYEAR |
| Profit Margin % | DIVIDE |

## 💡 Key Insights
- Government segment drives 44.22% of total revenue
- Paseo = highest profit product
- Government profit margin lower than Small Business — pricing opportunity
