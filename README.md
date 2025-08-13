# 📊 Regional Sales Analysis
**Regional Sales Analysis** is a data-driven project aimed at understanding sales trends, customer behaviors, and product performance across different regions.  
Using **Python (EDA)** and **Power BI Dashboards**, the project transforms raw sales data into actionable business insights, helping stakeholders make informed strategic decisions.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Business Problem](#business-problem)
- [Dataset](#dataset)
- [Tools & Technologies](#tools--technologies)
- [Data Cleaning & Preparation](#data-cleaning--preparation)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Research Questions & Key Findings](#research-questions--key-findings)
- [Dashboards](#dashboards)
- [Final Recommendations](#final-recommendations)
- [Author & Contact](#author--contact)




---

## Overview
This project analyzes **regional sales data** to identify trends, customer patterns, and product performance. Using **EDA in Python** and **interactive Power BI dashboards**, the goal is to provide actionable insights for strategic business decisions.

---

## Business Problem
The sales team lacked a **comprehensive view** of:
- Regional performance trends
- High-value customer segments
- Best-performing products and channels

This project delivers a **data-driven solution** to monitor KPIs and identify opportunities for growth.

---

## Dataset
**Source:** `Regional Sales Dataset.xlsx`  
**Rows:** ~64,000+  
**Key Columns:**
- `Order Date` – Transaction date
- `Region` – Geographic region
- `Product Category` – Furniture, Technology, Office Supplies
- `Sales` – Revenue generated
- `Profit` – Profit earned
- `Quantity` – Number of units sold
- `Customer Segment` – Corporate, Consumer, Home Office
- `Channel` – Online or Retail

---

## Tools & Technologies
- **Python** – Data cleaning & EDA
- **Pandas, Matplotlib, Seaborn** – Visualization & analysis
- **Power BI** – Dashboard creation
- **Excel** – Initial data inspection

---

## Data Cleaning & Preparation
- Removed null values in Sales, Profit, and Customer Segment.
- Standardized region names and product categories for consistency.
- Converted `Order Date` to datetime format.
- Created calculated fields for:
  - **Profit Margin** = Profit / Sales
  - **Year-Month** for time series analysis

---

## Exploratory Data Analysis (EDA)
The EDA was conducted in **Python** using Pandas, Seaborn, and Matplotlib. Key findings include:

### 1. Sales & Profit Trends
- **Seasonality:** Sales peaked in **November and December**, likely due to holiday shopping.
- **Monthly Trend:** Q4 consistently outperforms other quarters.
- **Yearly Growth:** A steady increase in sales over time.

### 2. Regional Performance
- **Top Region:** East region leads in both revenue and profit.
- **Weak Region:** South shows lower sales and negative profit margins in some months.

### 3. Product Category Insights
- **Technology:** Highest profit margin and strong sales.
- **Furniture:** Lower profit margins despite moderate sales volume.
- **Office Supplies:** Stable sales but minimal growth.

### 4. Customer Segment Analysis
- **Corporate customers** have the highest average order value.
- **Consumer segment** contributes significantly to total volume but with lower margins.

### 5. Channel Analysis
- **Online sales** outperform **retail** in revenue and profit margins.
- Retail channel shows higher operational costs.

**Visualization Examples from EDA:**
- **Heatmaps** to detect correlations between discount, sales, and profit.
- **Boxplots** for profit distribution across regions.
- **Time series plots** for monthly sales and profit trends.

---

## Research Questions & Key Findings
1. **Which region has the highest sales and profit?** → East region leads in revenue.
2. **Which customer segment is most valuable?** → Corporate customers show higher order value and repeat purchase rate.
3. **Which product category is most profitable?** → Technology drives the highest margins.
4. **Which sales channels work best?** → Online sales outperform retail in both revenue and growth rate.

---

## Dashboards

### 1️⃣ Executive Overview & Trends Dashboard
**Purpose:**  
High-level KPIs for sales, profit, margins, and seasonal revenue/profit analysis.

**Key Highlights:**
- Total Revenue: **$1.2B**  
- Profit Margin: **37.36%**  
- Monthly revenue rhythm reveals clear seasonality patterns.
- Q4 dominates yearly revenue share.

![Executive Overview & Trends Dashboard](Executive%20Overview%20%26%20Trends%20Dashboard.png)

---

### 2️⃣ Product & Channel Performance Dashboard
**Purpose:**  
Analyze top-selling products, profitable items, and channel-wise contribution.

**Key Highlights:**
- Top 10 products ranked by revenue and profit margin.
- Technology category shows exceptional performance in both revenue and margins.
- Online channel outperforms retail in every key metric.

![Product & Channel Performance Dashboard](Product%20%26%20Channel%20Performance%20Dashboard.png)

---

### 3️⃣ Geographic & Customer Insights Dashboard
**Purpose:**  
Understand **regional contribution**, **top customers**, and **state-wise performance**.

**Key Highlights:**
- California is the largest contributor to revenue.
- West region has the highest margin.
- Identifies top 5 customers contributing the most profit.
- Highlights underperforming states for targeted marketing.

![Geographic & Customer Insights Dashboard](Geographic%20%26%20Customer%20Insights%20Dashboard.png)

---

## Final Recommendations
- **Focus on Technology Category** – High margins and strong sales.
- **Boost Q1 Promotions** – Offset low sales period before peak season.
- **Target East Region Growth** – Already strong but potential for expansion.
- **Expand Online Channels** – Outperforms retail significantly.
- **Loyalty Programs** – For Corporate customers to maintain repeat purchases.

---

##  Author & Contact
- 👨‍💼 **Name:** Omkar Gaurav  
- 📧 **Email:** [omkargaurav11@gmail.com](mailto:omkargaurav11@gmail.com)  
- 💼 **LinkedIn:** [linkedin.com/in/omkar-gaurav-1508b6303](https://www.linkedin.com/in/omkar-gaurav-1508b6303?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
- 🖥️ **GitHub:** [github.com/omkargaurav121](https://github.com/omkargaurav121)
