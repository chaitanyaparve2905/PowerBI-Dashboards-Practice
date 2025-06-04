# 📦 boAt Regional Sales Performance Dashboard (Power BI)

## 📊 Project Overview

This Power BI dashboard provides a detailed regional analysis of boAt’s sales and profit metrics. The visual report is built to help decision-makers monitor key business indicators such as total sales, profit, delivery times, and performance across regions, categories, segments, and payment modes.

Key insights include:
- 💰 Total Sales: 1.56M | Total Profit: 175K
- ⏱️ Average Delivery Time: 4 Days
- 📦 Total Quantity Sold: 22K
- 🗺️ Geographical and temporal trends across North America, Europe, Asia, and more
- 📊 Monthly performance trends for 2019 and 2020

---

## 🛠️ Installation
### Requirements
- Power BI Desktop– Download: [https://powerbi.microsoft.com/desktop](https://powerbi.microsoft.com/desktop)
- Sales Dataset – [Boat.xlsx](https://github.com/user-attachments/files/20591340/Boat.xlsx)

---

## 🧭 Usage
Navigate through the dashboard for deep insights:

- Region Filters: Toggle between Central, East, South, and West to compare KPIs.

- Top KPIs: Track real-time Total Sales, Total Profit, Delivery Time, and Quantity.

- Sales by Category: Technology leads with 0.92M in sales.

- Segment Analysis: Consumer segment contributes nearly half (48.12%) of total sales.

- City Map: Interactive map shows regional distribution of sales and profit.

- Sales by Payment Mode: COD (42.65%) is the most used payment method.

- Monthly Trends: Compare monthly profit and sales across 2019 and 2020.

- Sub-Category Deep Dive: Phones, Chairs, and Storage lead in sales volume.
---

## Sample Dashboard Preview

![Image](https://github.com/user-attachments/assets/68072687-5b51-48a4-a558-61629a077c2d)
---
## 🧮 DAX Formulas and Additional Information
DAX Formula:

- Avg Delivery Time = DATEDIFF('Sheet1'[Order Date], 'Sheet1'[Ship Date], DAY)
Additional Details:

- Data was cleaned and structured using Power BI's Transform Data.
- Handled null values, standardized date formats, and normalized categorical fields.
---
## 📬 Contact Information

Have questions or suggestions? Feel free to reach out:

Maintainer: Chaitanya Parve

LinkedIn: www.linkedin.com/in/chaitanyaparve29

GitHub: https://github.com/chaitanyaparve2905
