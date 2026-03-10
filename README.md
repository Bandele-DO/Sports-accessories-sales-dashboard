# 🏅 Sports & Accessories Sales Performance Dashboard

## 🧾 Project Overview

This project presents a two-page interactive Power BI dashboard analyzing the performance of a **Sports & Accessories retail business**.

The solution provides executive-level visibility into revenue, profit, product performance, and geographic trends using Year-to-Date (YTD) and Previous Year-to-Date (PYTD) comparisons.

The dashboard was designed to support strategic decision-making through clear KPIs, trend analysis, and dynamic metric selection.

---

## 🎯 Problem Statement

The business lacked a centralized reporting system to:

- Monitor sales performance across products and regions  
- Compare current performance against the previous year  
- Identify high-performing and underperforming product categories  
- Understand geographic revenue contribution  
- Track profitability trends  

Decision-makers needed a structured, interactive solution to analyze performance quickly and confidently.

---

## 👥 Stakeholders & Business Questions

### Executive Leadership
- Is the business growing compared to last year?
- Are we improving profitability?
- Which regions drive the most revenue?

### Sales & Product Managers
- Which product subcategories perform best?
- Which products are declining year-over-year?
- Where should sales efforts be focused?

### Regional Managers
- Which countries contribute the most revenue?
- Which regions are driving growth or decline?

---

## 📊 Dashboard Structure

### 🔹 Page 1: Executive Overview & Product Performance
<img width="575" height="326" alt="Dashboard_Screenshot Dark 1A" src="https://github.com/user-attachments/assets/cacca115-ba4a-44b8-86dd-1d19c3783e57" /> 

<img width="578" height="324" alt="Dashboard_Screenshot Light1A" src="https://github.com/user-attachments/assets/5e9cb6f1-19a2-4861-811b-b8ca0d274189" />

**KPIs**
- Total Revenue  
- Total Profit  
- Profit Margin  
- YTD Revenue  
- YTD Profit  

**Visuals**
- Revenue by Month (Trend Analysis)  
- Revenue by Product Subcategory  
- Product YTD vs PYTD Performance Table  
- Revenue by Occupation  
- Revenue by Education  

This page provides a high-level business summary and product-level performance insights.

---

### 🔹 Page 2: Geographic Performance & Trends

<img width="574" height="323" alt="Dashboard_Screenshot Dark 1B" src="https://github.com/user-attachments/assets/94cf1110-4cac-4a65-95da-1e63053e8065" />

<img width="575" height="324" alt="Dashboard_Screenshot Light 1B" src="https://github.com/user-attachments/assets/dde9bf03-d683-479b-89bf-3fbe83350b76" />

**KPIs**
- YTD  
- PYTD  
- YTD vs PYTD Variance  
- Profit Margin  

**Visuals**
- Waterfall Chart (Monthly YTD vs PYTD contribution)  
- Treemap (YTD by Country)  
- Line & Stacked Column Chart (YTD vs PYTD by Month)  
- Map Visualization (Revenue distribution by country)  

This page focuses on regional contribution and year-over-year performance analysis.

---

## ⚙️ Technical Implementation

### 🔄 Data Modeling
- Star schema design  
- Fact table for sales transactions  
- Dimension tables for Date, Product, Customer, and Geography  
- One-to-many relationships with proper filter direction  

### 📐 DAX Measures
- YTD and PYTD calculations  
- Year-over-Year variance  
- Profit Margin calculation  
- Dynamic metric selection using `SWITCH()`  
- Ranking measures for Top-N filtering  

### 🔁 Dynamic Metric Toggle
A switch measure allows users to dynamically change the dashboard metric between:
- Revenue  
- Cost  
- Profit  

This eliminates visual duplication and enhances interactivity.

---

## 🎨 Design Decisions

### Theme
- Custom Dark Theme (#0C2C55 background)
- Complementary Light Theme version
- Consistent teal/blue gradient for hierarchy
- Green (#117865) for positive variance
- Red for negative variance

### Layout Philosophy
- Executive-first structure (KPIs → Trends → Breakdown)
- Clear visual hierarchy
- Minimal clutter
- Consistent color semantics (Hue = meaning, Shade = magnitude)

---

## 📈 Key Insights Enabled

The dashboard helps stakeholders:

- Identify revenue growth or decline trends  
- Detect product subcategories driving profitability  
- Compare YTD vs PYTD performance month-by-month  
- Evaluate regional sales contribution  
- Understand customer demographic revenue distribution  

---

## 🚀 Business Impact

This solution demonstrates how structured data modeling and interactive BI reporting can:

- Improve strategic decision-making  
- Highlight performance gaps  
- Enable proactive product management  
- Support geographic expansion strategies  
- Replace static reports with dynamic analysis  

---

## 🛠 Tools Used

- Power BI (Data Modeling, DAX, Visualization)  
- Excel (Data preparation)  
- DAX (Time Intelligence, Ranking, Conditional Logic)  

---

## 💡 Skills Demonstrated

- Business Intelligence Reporting  
- Data Modeling (Star Schema)  
- Time Intelligence (YTD, PYTD, YoY Analysis)  
- Interactive Dashboard Design  
- KPI Development  
- Data Storytelling  
