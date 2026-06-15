# Power BI Project — AdventureWorks Sales Analysis

## 📌 Project Overview

This project is based on the **AdventureWorks Sales dataset**, using **Power BI** to build an end-to-end Business Intelligence (BI) dashboard.

The workflow includes:
- Data cleaning and transformation (Power Query)
- Dimensional modeling (Star Schema)
- Data relationship design and optimization
- Interactive dashboard development
- AI-driven analytics (Key Influencers & Top Segments)

The project aims to analyze:
- Sales performance
- Profit distribution
- Customer and regional insights
- Product and channel performance drivers

---

## 📊 Executive Summary

- Sales show strong seasonality patterns
- The United States and Australia are the primary markets, with the UK steadily growing
- Product structure is highly dependent on the Bike category, while Accessories are increasing
- Warehouse channel significantly outperforms other business types
- Profit distribution is uneven across time and product categories

---

## 📈 Analysis Modules

---

### 1. Sales Trend Analysis

**Key Findings:**
- Sales fluctuate significantly over time
- Peaks typically occur mid-year and year-end
- Overall trend shows stable growth

**Conclusion:**
- Clear seasonality effect in sales performance

**Recommendations:**
- Strengthen inventory and supply chain before peak seasons
- Use promotions during low-demand periods to stabilize revenue

---

### 2. Geographic Performance Analysis

**Key Findings:**
- US and Australia are the dominant markets
- UK, Germany, France, and Canada contribute secondary revenue
- Regional contribution structure is evolving

**Conclusion:**
- Balanced structure of core + diversified markets

**Recommendations:**
- Maintain stability in US, AU, and UK markets
- Expand growth in European and Canadian markets

---

### 3. Product Category Analysis

**Key Findings:**
- Bikes contribute the majority of sales and profit
- Accessories show steady growth but lower share

**Conclusion:**
- Highly concentrated product structure

**Recommendations:**
- Strengthen core Bike product performance
- Expand Accessories through cross-selling and bundling strategies

---

### 4. Business Type / Channel Analysis

**Key Findings:**
- Warehouse channel delivers the highest sales performance
- Specialty Bike Shop underperforms relative to others

**Conclusion:**
- B2B bulk channels drive most revenue

**Recommendations:**
- Strengthen partnerships with high-volume (Warehouse) clients
- Optimize retail channel efficiency
- Implement differentiated pricing strategies across channels

---

### 5. Profit by Time (Quarterly Analysis)

**Key Findings:**
- Profit fluctuates across quarters
- Q1 consistently performs the strongest

**Conclusion:**
- Profitability is strongly time-dependent

**Recommendations:**
- Balance seasonal performance across quarters
- Improve off-peak profitability

---

### 6. Profit by Region

**Key Findings:**
- US and Australia contribute most profit
- UK shows steady growth over time

**Conclusion:**
- Regional profit distribution is becoming more diversified

**Recommendations:**
- Increase investment in the UK market
- Optimize profitability in the Australian market

---

### 7. Key Influencers Analysis

**Key Findings:**
- Warehouse channel strongly correlates with higher sales

**Conclusion:**
- Business type is a major driver of sales performance

**Recommendations:**
- Develop targeted strategies for high-impact channels

---

### 8. Top Segments Analysis

**Key Findings:**
- High-value customer segments are concentrated in specific channel combinations
- Clear revenue concentration effect exists

**Recommendations:**
- Focus on high-value customer groups
- Improve customer lifetime value (LTV)

---

## 🧱 Data Modeling

A **Star Schema** approach was used:

- **Fact Table:** Sales
- **Dimension Tables:**
  - Customer
  - Product
  - Date
  - Reseller
  - Sales Territory

**Modeling Features:**
- Data cleaning and transformation via Power Query
- Hierarchical structures (Date, Geography, Product)
- Optimized model readability by hiding key fields

---

## 📊 Visualizations

### 1. Sales Trend (Area Chart)
- Shows seasonal fluctuations and overall growth

### 2. Geographic Distribution (Map)
- US is the dominant market by order volume

### 3. Product × Channel Matrix
- Bikes dominate all categories
- Warehouse channel outperforms Specialty Bike Shop

### 4. Fiscal Calendar Slicer
- Interactive filtering for 2018–2020

### 5. Profit Analysis (Stacked Bar Chart)
- Q1 consistently has the highest profit
- Bike category dominates profit contribution

### 6. Regional Profit Distribution (Pie Chart)
- US and Australia dominate total profit
- UK shows steady growth

### 7. AI Insights (Key Influencers & Top Segments)
- Identifies key drivers and high-value customer groups

---

## 💡 Business Insights

- Product dependency is heavily centered on Bikes, but diversification is emerging
- Global expansion is evident, especially growth in the UK market
- Warehouse channels are the primary revenue driver
- Accessories represent a growing opportunity segment
- High-value customers are concentrated and should be prioritized

---

## 🛠 Tools Used

- Power BI Desktop
- Power Query
- DAX (Data Analysis Expressions)
- AdventureWorks Sales Dataset

---

## 🎯 Learning Outcomes

- Star schema dimensional modeling
- Power BI data modeling and optimization
- DAX fundamentals
- Advanced dashboard design
- AI-driven analytics (Key Influencers, Top Segments)
- Translating data into actionable business insights

---

## 🚀 Project Highlights

- End-to-end BI workflow (Data → Model → Visuals → Insights)
- Integration of AI-powered analytics features
- Multi-dimensional interactive dashboard
- Business-ready insights for decision-making
