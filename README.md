# 🛒 Blinkit Sales Analysis | Power BI Dashboard

An interactive Power BI dashboard that analyzes Blinkit grocery sales across outlets, locations, and product categories to uncover what drives sales and customer ratings.

---

## 📸 Dashboard Preview

![Blinkit Dashboard](Blinkit%20Dashboard.jpg)

---

## 🎯 Project Objective

To analyze Blinkit's grocery sales data and answer key business questions:

- What is the total sales, average sales, and average rating?
- Which item types generate the most sales?
- How do sales differ by fat content (Low Fat vs Regular)?
- Which outlet sizes, locations, and outlet types perform best?
- How have outlets performed by year of establishment?

---

## 📂 Dataset

**Source:** [BlinkIT Grocery Data (Google Drive)](https://docs.google.com/spreadsheets/d/1tdF_beuexr4n46cuZY8P-b8JCCYN-SNZ/edit?usp=sharing&ouid=110234731011492092452&rtpof=true&sd=true)

| Column | Description |
|---|---|
| Item Fat Content | Low Fat or Regular |
| Item Identifier | Unique product ID |
| Item Type | Product category (Dairy, Snack Foods, Frozen Foods, etc.) |
| Outlet Establishment Year | Year the outlet was established |
| Outlet Identifier | Unique outlet ID |
| Outlet Location Type | Tier 1, Tier 2, or Tier 3 city |
| Outlet Size | Small, Medium, or High |
| Outlet Type | Grocery Store or Supermarket Type1/2/3 |
| Item Visibility | Share of display area given to the item |
| Item Weight | Weight of the product |
| Sales | Sales amount |
| Rating | Customer rating |

---

## 🧹 Data Cleaning

- Standardized inconsistent **Item Fat Content** labels (`LF`, `low fat` → **Low Fat**; `reg` → **Regular**)
- Handled missing values in **Item Weight**
- Checked zero values in **Item Visibility**
- Verified data types for sales, rating, and year columns

---

## 📊 KPIs Tracked

| KPI | Description |
|---|---|
| **Total Sales** | Sum of all sales |
| **Average Sales** | Average sales per item |
| **Number of Items** | Total items sold |
| **Average Rating** | Mean customer rating |

---

## 🔍 Dashboard Analysis

- Total sales by **Item Fat Content**
- Total sales by **Item Type**
- Fat content vs item type performance
- Total sales by **Outlet Establishment Year**
- Sales by **Outlet Size** (percentage share)
- Sales by **Outlet Location Type**
- Metrics by **Outlet Type** (sales, average sales, items, rating, item visibility)

---

## 🛠️ Tools Used

- **Microsoft Power BI**: data modeling, DAX measures, and visualization
- **Microsoft Excel**: raw data and initial cleaning
- **DAX**: calculated KPIs

---

## 💡 Key Insights

> Add your own findings here after checking your dashboard, for example:

- Which item type has the highest sales: ____
- Which outlet size contributes the most sales: ____
- Which location tier performs best: ____
- Low Fat vs Regular sales split: ____

---

## 🚀 How to Use This Project

1. Download the dataset from the Google Drive link above.
2. Open the `.pbix` file in **Power BI Desktop** (or load the data into a new report).
3. Explore the dashboard using the slicers and filters.

---

## 👩‍💻 Author

**Trupti Rani Mohapatro**
GitHub: [truptiranimohapatro](https://github.com/truptiranimohapatro)

⭐ If you found this project useful, please star the repository!
