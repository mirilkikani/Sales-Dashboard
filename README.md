# 🛒 Flink Grocery Sales Dashboard — Power BI

> **"Fast Groceries. Faster Insights."**  
> An interactive Power BI dashboard analyzing sales performance across Flink grocery outlets in Europe (2011–2022).

---

## 📊 Dashboard Preview

![Flink Grocery Dashboard](https://github.com/mirilkikani/Sales-Dashboard/blob/main/Screenshot%202026-05-21%20013606.png)

---

## 📁 Project Structure

```
flink-grocery-powerbi/
│
├── Flink_Grocery.pbix           # Power BI report file
├── FLINK_Grocery_Data.xlsx      # Source dataset
├── Screenshot_2026-05-21_013606.png  # Dashboard preview
└── README.md
```

---

## 🧾 Dataset Overview

| Attribute | Details |
|---|---|
| **Source** | FLINK_Grocery_Data.xlsx |
| **Rows** | 8,523 |
| **Columns** | 12 |
| **Time Period** | 2011 – 2022 |

### Columns

| Column | Description |
|---|---|
| `Item Identifier` | Unique product code |
| `Item Type` | Product category (16 types, e.g. Fruits & Vegetables, Dairy, Snack Foods) |
| `Item Fat Content` | Low Fat / Regular |
| `Item Weight` | Weight of the product |
| `Item Visibility` | Shelf visibility score (0–1) |
| `Outlet Identifier` | Unique outlet code |
| `Outlet Type` | Grocery Store / Supermarket Type 1/2/3 |
| `Outlet Size` | Small / Medium / High |
| `Outlet Location Type` | Tier 1 / Tier 2 / Tier 3 |
| `Outlet Establishment Year` | Year outlet was established |
| `Sales` | Item sales in EUR |
| `Rating` | Customer rating |

---

## 📌 Key KPIs

| Metric | Value |
|---|---|
| 💰 Total Sales | **€ 1.20M** |
| 📦 Total Items | **8,523** |
| 📈 Average Sales | **€ 141** |
| ⭐ Average Rating | **3.9** |

---

## 🔍 Key Insights

- **Supermarket Type 1** dominates with **€ 0.79M** in total sales across 5,577 items — by far the highest-performing outlet type.
- **Fruits & Vegetables** and **Snack Foods** are the top-selling item categories, each contributing **~€ 0.18M**.
- **Tier 3** locations lead outlet sales with **€ 472K**, followed by Tier 2 (€ 393K) and Tier 1 (€ 336K).
- **High-size outlets** generate the most revenue among outlet size segments (**€ 677K**).
- Sales peaked around **2018** (€ 205K) based on outlet establishment year trends, with a dip before recovering toward 2022.
- **Regular fat content** products account for **€ 776K** vs **€ 425K** for Low Fat items.

---

## 🎛️ Dashboard Features

- **Quick Filters** — Slice by Outlet Location Type, Outlet Size, and Item Type
- **KPI Cards** — Total Sales, Avg Sales, No. of Items, Avg Rating
- **Fat Content Donut Chart** — Low Fat vs Regular split
- **Item Type Bar Chart** — Sales breakdown across all 16 product categories
- **Fat by Outlet Tier Chart** — Grouped bar showing fat content distribution across Tier 1/2/3
- **Outlet Establishment Area Chart** — Sales trend by year of outlet establishment (2011–2022)
- **Outlet Size Donut Chart** — Revenue share by Small / Medium / High outlets
- **Outlet Location Bar Chart** — Tier-wise total sales comparison
- **Outlet Type Summary Table** — Total Sales, Item Count, Avg Sales, Avg Rating, Item Visibility per outlet type

---

## 🛠️ Tools & Technologies

| Tool | Usage |
|---|---|
| **Microsoft Power BI Desktop** | Dashboard development & DAX measures |
| **Microsoft Excel** | Source data (.xlsx) |
| **Power Query** | Data cleaning & transformation |

---

## 🚀 How to Use

1. Clone or download this repository.
2. Open `[Flink_Grocery.pbix](https://github.com/mirilkikani/Sales-Dashboard/blob/main/FLINK%20Grocery%20Data.xlsx)` in **Power BI Desktop**.
3. If prompted, update the data source path to point to `FLINK_Grocery_Data.xlsx`.
4. Explore the dashboard using the Quick Filters on the left panel.


---


## 📄 License

This project is for educational and portfolio purposes.  
Dataset is used for academic/non-commercial analysis only.
