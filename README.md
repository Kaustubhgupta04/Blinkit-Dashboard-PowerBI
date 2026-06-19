# 🛒 Blinkit Sales & Operations Dashboard — Power BI

---

## 📌 Project Overview

This project presents an **end-to-end Power BI dashboard** analyzing Blinkit's sales performance, customer satisfaction, and inventory distribution across different outlet types, sizes, and locations. The goal is to uncover actionable insights and optimization opportunities using interactive KPIs and visualizations.

> **Blinkit** (formerly Grofers) is India's leading last-minute grocery delivery app.

---

## 🎯 Business Objective

> To conduct a comprehensive analysis of Blinkit's sales performance, customer satisfaction, and inventory distribution to identify key insights and opportunities for optimization using various KPIs and visualizations in Power BI.

---

## 📊 Key KPIs

| KPI | Value |
|-----|-------|
| 💰 Total Sales | $1.20M |
| 📈 Average Sales | $141 |
| 📦 Number of Items | 8,523 |
| ⭐ Average Rating | 3.9 |

---

## 📋 Dataset Details

**File:** `BlinkIT_Grocery_Data.xlsx`

| Column | Description |
|--------|-------------|
| Item Fat Content | Whether item is Low Fat or Regular |
| Item Identifier | Unique product ID |
| Item Type | Category of the product |
| Outlet Establishment Year | Year the outlet was opened |
| Outlet Identifier | Unique outlet ID |
| Outlet Location Type | Tier 1, Tier 2, or Tier 3 city |
| Outlet Size | Small, Medium, or High |
| Outlet Type | Grocery Store or Supermarket Type |
| Item Visibility | % shelf visibility of the item |
| Item Weight | Weight of the item |
| Sales | Revenue generated |
| Rating | Customer rating |

---

## 📈 Dashboard Visualizations

1. **Fat Content Analysis (Donut Chart)** — Total sales split between Low Fat ($776.32K) and Regular ($425.36K) products
2. **Item Type Performance (Bar Chart)** — Sales breakdown across 16 product categories; Fruits & Vegetables and Snack Foods lead at $0.18M each
3. **Fat by Outlet Tier (Stacked Bar)** — Compares Low Fat vs Regular sales across Tier 1, 2, and 3 outlets
4. **Outlet Establishment Trend (Line Chart)** — Sales trend by outlet opening year; peak at $205K (2018)
5. **Outlet Size (Donut Chart)** — Medium outlets dominate at $507.90K (42.3%)
6. **Outlet Location (Bar Chart)** — Tier 3 cities lead with $472.13K in sales
7. **Outlet Type Matrix Table** — Full breakdown of Total Sales, No. of Items, Avg Sales, Avg Rating, and Item Visibility across all outlet types

---

## 💡 Key Insights

- **Low-fat products outsell regular** ones ($776K vs $425K), reflecting health-conscious buying habits among Blinkit customers.
- **Fruits, Vegetables & Snack Foods** are the top-selling categories ($0.18M each), suggesting demand for fresh and convenience items.
- **Tier 3 cities generate the highest revenue ($472K)**, outperforming Tier 1 ($336K) — indicating strong small-city market penetration.
- **Medium-sized outlets** contribute the most to total sales ($507K), making them the most profitable outlet size.
- **Supermarket Type 1** dominates outlet type sales with $787.55K across 5,577 items.
- **Outlet sales peaked in 2018** (~$205K) and have since stabilized, suggesting market maturity.
- **Average rating is consistent at 4** across all outlet types, indicating stable customer satisfaction.

---

## 🔧 Tools Used

- **Power BI Desktop** — Dashboard creation and data visualization
- **Microsoft Excel** — Raw data source (`BlinkIT_Grocery_Data.xlsx`)
- **DAX** — Calculated measures and KPIs
