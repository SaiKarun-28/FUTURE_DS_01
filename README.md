# 📈 Superstore Sales Dashboard

This repository contains the Power BI Desktop file (`Superstore Sales Dashboard.pbix`) for an interactive dashboard designed to analyze and visualize sales performance for a global superstore chain.

The dashboard provides key insights into revenue, profit, and order metrics segmented by various dimensions like geography, product categories, and customer segments.

---

## ✨ Key Features of the Dashboard

* **Sales Performance Overview:** Track total sales, total profit, and key financial ratios.
* **Geographic Analysis:** Visualize performance across different regions, countries, and states.
* **Product Insights:** Analyze sales and profit broken down by product **Category** and **Sub-Category** to identify top and underperforming items.
* **Customer Segmentation:** Understand sales contribution and profitability across different **Customer Segments** (e.g., Consumer, Corporate, Home Office).
* **Time-Series Trends:** Analyze monthly, quarterly, and annual sales and profit trends.
* **Visualization Variety:** Includes diverse visual elements such as a generated image and charts, allowing for clear data representation.

https://github.com/SaiKarun-28/FUTURE_DS_01/blob/main/Snapshot%20of%20the%20Dashboard.png

---

## 📊 Data Source

The dashboard utilizes the popular **Superstore** dataset, which was **downloaded from Kaggle**. This dataset contains sales transaction information across a large product catalog and customer base.
https://www.kaggle.com/datasets/karunimiddisetty/superstore-sales

The Power BI file likely contains the following tables (or similar):

* **`Orders`**: Contains details for each transaction, including Sales, Profit, Quantity, and Order Date.
* **`Returns`**: Records of returned items.
* **`People`**: Contains information about regional managers (if used in the dashboard).

**Note:** The `.pbix` file is self-contained and includes the imported data model. No external data connections or credentials are required to open and explore the dashboard.

---

## 🔑 Key Performance Indicators (KPIs)

The following primary measures are calculated and displayed throughout the dashboard:

| KPI (Measure) | Description |
| :--- | :--- |
| **Total Sales** | Sum of sales revenue across all orders is 2.30M. |
| **Total Profit** | Sum of profit generated across all orders 286.40K. |
| **Total Discount** | The Sum of Discount applied is 1.56K. |
| **Highest sales** | West region contributes the largest share of profit, accounting for 37.86% ($108.42K) of the total profit. |
| **Peak** | A major peak in sales, exceeding $100K, occurred in the latter half of 2014. |

---

## 🏷️ Primary Data Fields

The analysis relies heavily on the following dimensional fields for slicing and filtering:

* **Geographical:** Region, State, City, Country/Territory.
* **Product:** Category, Sub-Category, Product Name.
* **Customer:** Customer Name, Segment.
* **Time:** Order Date (used to derive Year, Quarter, Month).
* **Shipping:** Ship Mode.

---

## 💻 Requirements

To open and interact with this dashboard, you must have:

1.  **Power BI Desktop** installed on your system.

---

## Screenshots / Demo
Example: https://github.com/SaiKarun-28/FUTURE_DS_01/blob/main/Snapshot%20of%20the%20Dashboard.png

---
