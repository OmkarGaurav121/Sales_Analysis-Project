# 📊 Sales Analysis Dashboard — Power BI

## 📁 Project Overview

This project presents a comprehensive sales analysis using Power BI, leveraging a structured dataset derived from regional sales performance across products, channels, and geography. The objective is to provide actionable insights into sales revenue, profit margins, customer behavior, and market trends—empowering stakeholders to make data-driven decisions.

> **Tools Used**: Power BI | Excel Power Query | DAX  
> **Dataset**: Regional Sales Dataset (Cleaned and transformed in Excel)  
> **Visualization Pages**:  
> - Executive Overview & Trends  
> - Product & Channel Performance  
> - Geographic & Customer Insights  

---

## 🔍 Data Cleaning & Preparation

The raw Excel data was cleaned and pre-processed using **Excel Power Query**, where I:

- Removed duplicate records  
- Filled missing values (e.g., "Unknown" for missing states/products)  
- Created custom calculated columns such as:
  - `Revenue per Order`
  - `Profit Margin %`
  - `Order Value Bins` for histogram  
- Normalized data for consistent date formats and product categories  
- Exported the clean dataset to CSV for visualization in Power BI  

---

## 🧠 Executive Overview & Trends

![Executive Overview](./Executive%20Overview%20&%20Trends%20Dashboard.png)

### ✅ Key KPIs:
- **Total Revenue**: `$1.2B`
- **Total Profit**: `$461.8M`
- **Profit Margin**: `37.36%`
- **Total Orders**: `64K`
- **Revenue per Order**: `$19.3K`

### 📈 Visual Insights:
- **Seasonality in Revenue**: Peaks observed in April, June, and October; lowest in February.
- **Profit Fluctuations**: Aligned closely with revenue trend; suggests consistent cost structure.
- **Order Value Spectrum**: Most orders fall under $100K, with few high-value transactions beyond $300K.
- **Profit Margin vs Unit Price**: Products priced between $1K–$3K yield more consistent high margins.

---

## 🌎 Geographic & Customer Insights

![Geographic Insights](./Geographic%20&%20Customer%20Insights%20Dashboard.png)

### 🧩 Regional Analysis:
- **Top Revenue State**: California — contributes **19.5%** of revenue ($228.8M)
- **Top Profit Region**: West — **37.5%** average margin
- **Top 5 Customers**:
  - **By Revenue**: Aibox Company, State Ltd, Pixoboo Corp...
  - **By Profit Margin**: Neutrogena Ltd, Avamba Company…

### 🗺️ Map & Distribution:
- **Revenue by Region**:
  - Midwest: $372M (30.1%)
  - South: $335M (27.1%)
  - Northeast: $320M (25.9%)
  - West: $208M (16.9%)
- **Profit Margin by Region** shows West is most efficient in earnings despite lower total revenue.

---

## 📦 Product & Channel Performance

![Product & Channel](./Product%20&%20Channel%20Performance%20Dashboard.png)

### 🔝 Product Insights:
- **Top Revenue Product**: Product 26 ($117M)
- **Most Efficient Products**: Product 9, 30, and 28 with margins > 39%
- **Revenue vs Profitability** Scatter: Reveals outliers with high revenue but low margins.

### 📦 Channel Analysis:
- **Revenue by Channel**:
  - Wholesale: $668M (54.1%)
  - Distributor: $387M (31.3%)
  - Export: $180M (14.6%)
- **Profit by Channel**:
  - Export shows highest **profit efficiency** despite lowest volume.
- **Channel Margin Scorecard**: Distributor yields highest margin per sale (38.01%)

---

## 📌 Key Business Insights

- **Export Channel is Most Profitable**: Despite lower revenue, it yields highest margins.
- **California is Critical Market**: Drives nearly 1/5th of revenue.
- **High-Value Orders Are Rare**: Majority of customer base consists of mid-tier spenders.
- **Product Pricing Strategy Matters**: Mid-priced products between $1K–$3K show optimal performance.
- **West Region Needs Growth Focus**: High margins but untapped revenue potential.

---

## 🛠️ Future Improvements

- Integrate time-series forecasting for demand planning.  
- Add customer segmentation using clustering techniques.  
- Enable drill-through for sales rep-level insights.  
- Automate data refresh via Power BI service.  

---

## 📂 Dataset

- `Regional Sales Dataset.xlsx` — Raw source data (cleaned in Excel)
- `Sales_data(EDA Exported).csv` — Cleaned dataset used in Power BI

---

## 🔗 GitHub Repository

👉 [Sales Analysis Power BI Project](https://github.com/OmkarGaurav121/Sales_Analysis-Project)
