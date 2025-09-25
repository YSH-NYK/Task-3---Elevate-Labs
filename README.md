# 📊 Sales & Profit Performance Dashboard (Tableau Project)

## 📌 Objective
Design an **interactive dashboard** in Tableau for business stakeholders to track and analyze **Sales, Profit, and Growth** KPIs. The dashboard enables data-driven decision-making by providing insights into revenue trends, product line performance, and geographical distribution of sales.

---

## 🛠️ Tools & Deliverables
- **Tools Used:** Tableau, PowerPoint, CSV (dataset)
- **Deliverables:**
  - Tableau Dashboard (`.twbx`)
  - PowerPoint summary presentation (`.pptx`)
  - Dataset (CSV file from Kaggle)
  - Screenshots of dashboard and key sheets

---

## 📊 Dashboard Overview
The dashboard consolidates key business metrics with interactive filters and parameters. Stakeholders can analyze performance across time, products, and geography, with flexibility to test assumptions on profit margins.

### Included Visualizations:
1. **KPI Cards**
   - Total Sales → `SUM([Sales])`
   - Estimated Profit → `SUM([Estimated Profit (Row)])`
   - Profit Margin % → `(SUM([Estimated Profit (Row)]) / SUM([Sales]))`
   - Orders (count) → `COUNTD([OrderNumber])`
   - Average Order Value (AOV) → `SUM([Sales]) / COUNTD([OrderNumber])`

2. **Sales Over Time (Time Series)**
   - `Order Date (Month)` vs `SUM([Sales])`
   - Dual-axis with `SUM([Estimated Profit (Row)])` (Line + Area)
   - Trend line + Forecast for predictive insights

3. **Sales by Product Line (Bar)**
   - Horizontal bars: `Product Line` vs `SUM([Sales])`
   - Colored by `Profit Margin %` (continuous gradient)

4. **Geo Map**
   - Country / City level view
   - Bubble size = `SUM([Sales])`
   - Bubble color = `Profit Margin %` or `Estimated Profit`

---

## 🎛️ Interactivity
- **Filters / Slicers**: Order Year, Product Line, Country, Deal Size, Status
- **Parameter Controls**:
  - `Cost % of MSRP` (slider to simulate profit assumptions)
  - `Top N` (for Top Products analysis)
- **Actions**:
  - **Use as Filter** on key sheets
  - **Highlight Action** (hover to emphasize related data)
  - **Cross-filtering** across dashboard components

---

## 🖼️ Screenshots

Dashboard Overview -- ![Dashboard](<Screenshot 2025-09-25 163259.png>)
Sales Over Time -- ![Sales Over Time](<Screenshot 2025-09-25 163333.png>)
Sales by Product Line -- ![Sales by Product Line](<Screenshot 2025-09-25 163322.png>)
Geo Map -- ![Geo Map](<Screenshot 2025-09-25 163311.png>)

---

## 🔑 Key Insights (Example)
- Sales peak in mid-2004, showing strong seasonal trends.  
- Product Line **Classic Cars** generates highest revenue, while **Planes** show lower margins.  
- Sales are concentrated in the USA, but profit margins are stronger in Europe.  
- Average Order Value steadily increased YoY, indicating higher-value orders.  

---

## 🚀 Outcome
- Hands-on experience in building **interactive Tableau dashboards**.  
- Learned to apply **KPIs, time series, bar charts, and geo maps**.  
- Practiced using **parameters, filters, and actions** to enhance interactivity.  
- Delivered **insightful summaries** for stakeholders through PPT.  

---
