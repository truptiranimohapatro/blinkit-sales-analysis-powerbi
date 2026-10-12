<h1 align="center">🛒 Blinkit Sales Analysis Dashboard</h1>

<p align="center">
  An interactive Microsoft Power BI dashboard that explores Blinkit grocery sales across outlets, locations, and product categories.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Domain-Retail%20%26%20Grocery-0C831F?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Data%20Visualization-orange?style=for-the-badge" />
</p>

---

## 🎯 Project Overview

This project analyzes Blinkit grocery sales data in a single, filter-driven Power BI dashboard. Users can slice the data by outlet size, location type, outlet type, item fat content, and item type to understand what drives sales and customer ratings.

---

## 🖼️ Dashboard Preview

<p align="center">
  <img src="Blinkit%20Dashboard.jpg" alt="Blinkit Sales Analysis Dashboard" width="100%">
</p>

---

## 📌 Key Performance Indicators

| KPI | Value |
|---|---|
| 💰 Total Sales | 1.20M |
| 📊 Average Sales | 141 |
| 🔢 Number of Items | 8,523 |
| ⭐ Average Rating | 3.9 |

---

## 📈 Dashboard Features

- 🎛️ **Interactive filter panel:** Outlet Size, Outlet Location Type, Outlet Type, Item Fat Content, Item Type
- 🥛 **Fat content analysis:** Total sales by Low Fat vs Regular
- 🛍️ **Item type analysis:** Total sales by product category
- 📅 **Establishment year trend:** Sales by outlet establishment year
- 🏪 **Outlet size share:** Percentage of sales by Small, Medium, and High outlets
- 🗺️ **Location view:** Sales by Tier 1, Tier 2, and Tier 3 cities
- 🏬 **Outlet type comparison:** Sales, average sales, items, rating, and item visibility by outlet type

---

## 🔍 Key Insights

**Overall**
- The dashboard covers **8,523 items** with total sales of about **1.20M**, an average of about **141 per item**.
- The average customer rating is about **3.9 out of 5**.

**Item Fat Content**
- **Low Fat items drive roughly 65% of sales**, while Regular items contribute about 35%.

**Item Type**
- **Fruits and Vegetables and Snack Foods** are the top-selling categories.
- Everyday essentials like Household, Frozen Foods, and Dairy also contribute strongly.
- Categories such as Breakfast and Seafood sit at the bottom.

**Outlets**
- **Medium-sized outlets** generate the largest share of sales (about 42%).
- **Tier 3 cities** lead in sales, followed by Tier 2 and Tier 1.
- **Supermarket Type1** is the best-performing outlet type by total sales.
- Grocery Stores contribute the least.

---

## 🧹 Data Cleaning

- Standardized inconsistent **Item Fat Content** labels (`LF`, `low fat` → **Low Fat**; `reg` → **Regular**)
- Handled missing values in **Item Weight**
- Checked zero values in **Item Visibility**
- Verified data types for sales, rating, and year columns

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard building and visualization |
| DAX | Calculating KPIs and measures |
| Microsoft Excel | Raw data and initial cleaning |
| Slicers | Interactive filtering |

---

## 📂 Dataset

[⬇️ View Blinkit Raw Data (Google Drive)](https://docs.google.com/spreadsheets/d/1tdF_beuexr4n46cuZY8P-b8JCCYN-SNZ/edit?usp=sharing&ouid=110234731011492092452&rtpof=true&sd=true)

**Columns:** Item Fat Content, Item Identifier, Item Type, Outlet Establishment Year, Outlet Identifier, Outlet Location Type, Outlet Size, Outlet Type, Item Visibility, Item Weight, Sales, Rating

---

## 👩‍💻 Author

**Trupti Rani Mohapatro**

🔗 [LinkedIn](https://www.linkedin.com/in/trupti-rani-mohapatro-99545a36a/) | 💻 [GitHub](https://github.com/truptiranimohapatro)

⭐ If you found this project useful, consider giving it a star!
