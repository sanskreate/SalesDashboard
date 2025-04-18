# 📊 Superstore Sales Dashboard Project

## 🗂 Overview

This project presents a **Sales Dashboard** created using Power BI to visualize and analyze sales performance data from a fictional Superstore. It offers insights into sales trends, profitability, regional performance, and product-level metrics. The project includes data cleaning, preparation in Jupyter Notebook, and dashboard development in Power BI.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `SuperStoreOrders.csv` | Raw sales data exported from the Superstore database. |
| `cleaned_Superstore.csv` | Cleaned and pre-processed dataset ready for dashboard visualization. |
| `salescleaned.ipynb` | Jupyter Notebook used to clean and transform the raw data. |
| `SuperstoreSalesDashboard.pbix` | Power BI dashboard file visualizing key sales and performance metrics. |
| `SalesDashboard.png`         | Exported image snapshot of the Power BI dashboard for quick reference or documentation use.   |
| `README.md` | Project overview and documentation. |

---

## ⚙️ Tools & Technologies

- **Power BI** – For data visualization and dashboard creation.
- **Python (Jupyter Notebook)** – For data cleaning and preprocessing.
- **Pandas & NumPy** – Used in data wrangling.

---

## 📈 Key Features of the Dashboard

- **Sales & Profit Overview**: Track total sales and profits over time.
- **Top Products & Categories**: Identify best-selling and most profitable products.
- **Regional Analysis**: Understand performance across different states and regions.
- **Customer Segmentation**: Analyze customer behavior and buying patterns.
- **Order Processing Trends**: Monitor shipping mode, order date, and delivery efficiency.

---

## 🔄 Data Preparation Process

1. Loaded raw data (`SuperStoreOrders.csv`) into a Jupyter Notebook.
2. Cleaned data for inconsistencies, null values, and formatting using `pandas`.
3. Exported cleaned dataset to `cleaned_Superstore.csv` for Power BI.
4. Used `SuperstoreSalesDashboard.pbix` to build an interactive dashboard with slicers and filters.

---

## 🧹 Data Cleaning (`salescleaned.ipynb`)

The raw dataset `SuperStoreOrders.csv` is cleaned in the Jupyter notebook by performing the following steps:

- Loaded using `pandas`
- Parsed and converted `order_date` and `ship_date` into standard datetime formats
- Removed commas and converted the `sales` column to numeric
- Verified and preserved all non-null entries
- Exported to `Cleaned_Superstore.csv` for analysis

---

## 📊 Power BI Dashboard Overview (`SuperstoreSalesDashboard.pbix`)

### 🔍 Key Insights

1. **Technology Drives Profitability**  
   The *Technology* category contributes the highest profit (~45%), even though it doesn't lead in total sales—highlighting strong margins and product efficiency.

2. **Central and Western US Are Top Performers**  
   These regions dominate in terms of sales volume, indicating a strong market presence and effective distribution channels.

3. **Phones Are High-Value, Low-SKU Products**  
   The *Phones* sub-category shows high sales and quantity with fewer SKUs, suggesting efficient inventory management and strong customer demand.

4. **Chairs Have High SKU Count but Lower Efficiency**  
   The *Chairs* sub-category, while extensive in product variety, delivers lower profit efficiency, indicating a need to reassess pricing or marketing.

5. **Consistent Sales Growth Over Time**  
   Yearly trends from 2011 to 2014 reveal steady growth in total sales, reflecting healthy business expansion and customer acquisition.

### 📈 Dashboard Highlights

- **KPIs Tracked**: Total Sales, Profit, Quantity, Discounts, and Shipping Costs.
- **Visuals Included**: Line charts, donut charts, bar graphs, scatter plots, and heatmaps.
- **Filters Available**: Product category, ship mode, sub-category, order priority, segment, market, and country.

---

## 📌 How to Use

1. Open `salescleaned.ipynb` to understand the data cleaning process.
2. Review `cleaned_Superstore.csv` as the input for Power BI.
3. Open `SuperstoreSalesDashboard.pbix` in Power BI Desktop.
4. Interact with filters to explore different aspects of the sales data.

---

## 📬 Feedback

Feel free to raise issues or suggest improvements. This project is open for enhancements!

---
