<div align="center">

# Supplement Sales Data Analysis Dashboard

<img src="Dashboard/Supplement Sales Dashboard.png" alt="Dashboard Preview" />

[![Power BI](https://img.shields.io/badge/Power%20BI-Desktop-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![Task](https://img.shields.io/badge/Future%20Interns-Task%201-2dc572?style=for-the-badge)](https://futureinterns.com/data-science-analytics-task-1-2026/)
[![GitHub](https://img.shields.io/badge/GitHub-ranjeet22-181717?style=for-the-badge&logo=github)](https://github.com/ranjeet22/FUTURE_DS_01)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

**An end-to-end Power BI dashboard for Ecovital - a natural food supplement brand.**  
Analysing $22.91M in revenue, 658K units sold, across 3 platforms and 3 global markets.

[🔗 View Dashboard PDF](Dashboard/Supplement%20Sales%20Dashboard.pdf) · [📋 Task Details](https://futureinterns.com/data-science-analytics-task-1-2026/) · [⭐ Star this Repo](https://github.com/ranjeet22/FUTURE_DS_01)

</div>

---

## 🏆 Key Metrics Achieved

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | **$22.91M** |
| 📦 Units Sold | **658,000+** |
| 💵 Average Price | **$34.78** |
| 🔄 Return Rate | **1.02%** (only 6,714 units returned) |
| 🥇 Best-Selling Product | **Biotin** - 41,533 units |
| 🛒 Top Platform | **iHerb** - $7.86M (34.28%) |

---

## 📸 Dashboard Preview

> **Open [`Dashboard/Supplement Sales Dashboard.pdf`](Dashboard/Supplement%20Sales%20Dashboard.pdf) for the full interactive export.**

The dashboard features a clean Ecovital brand theme with the following visuals:

```
┌─────────────────────────────────────────────────────────────────┐
│  KPI Row  │  Total Revenue · Avg Price · Units Sold · Return %  │
├───────────────────────────┬─────────────────────────────────────┤
│  Donut Chart              │  Sankey Diagram                     │
│  Revenue by Platform      │  Revenue by Location × Product      │
├───────────────────────────┼─────────────────────────────────────┤
│  Combo Chart              │  Bing Map                           │
│  Revenue + Avg Price      │  Geographic Revenue Bubbles         │
│  by Category              │                                     │
├───────────────────────────┴─────────────────────────────────────┤
│  Slicers: Category · Location · Platform · Product Name         │
└─────────────────────────────────────────────────────────────────┘
```

---

## 📈 Visuals Built

| # | Visual | Description |
|---|--------|-------------|
| 1 | **KPI Cards** | Total Revenue, Average Price, Units Sold, Units Returned, Return % |
| 2 | **Donut Chart** | Revenue split by Platform (iHerb / Amazon / Walmart) |
| 3 | **Combo Chart** | Total Revenue (bar) + Average Price (line) by Category |
| 4 | **Sankey Diagram** | Revenue flow from Location → Product Name |
| 5 | **Bing Map** | Bubble map of revenue by geographic location |
| 6 | **Dynamic Slicers** | Cross-filtered by Category, Location, Platform, Product |

---

## 💡 Key Insights

> **🟢 Balanced Platform Distribution**  
> Revenue is nearly equal across all three platforms — iHerb (34.28%), Amazon (33.47%), Walmart (32.25%) - demonstrating strong multi-channel performance with no over-reliance on any single platform.

> **🟢 Biotin is the Star Product**  
> With 41,533 units sold, Biotin outperforms every other SKU. This indicates strong consumer demand in the Vitamin category and could guide future inventory and marketing strategy.

> **🟢 Exceptional Product Quality**  
> A return rate of just 1.02% across 658K+ units sold is significantly below industry averages, reflecting high product satisfaction and reliable quality control.

> **🟡 Premium Pricing Opportunity**  
> Fat Burner and Sleep Aid products carry the highest average prices (~$36), while Hydration and Protein sit lower. There is room to test pricing elasticity in high-demand, lower-priced categories.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **Power BI Desktop** | Dashboard development and publishing |
| **DAX** | Custom KPI measures (Return %, Avg Price, etc.) |
| **Power Query (M)** | Data cleaning and transformation |
| **CSV (Flat File)** | Source dataset |
| **Bing Maps** | Geographic visualisation |
| **Sankey Chart** | Custom AppSource visual |
| **GitHub** | Version control & portfolio showcase |

---

## 📁 Repository Structure

```
FUTURE_DS_01/
│
├── 📁 Dashboard/
│   ├── Supplement Sales Dashboard.pbix    ← Power BI source file
│   └── Supplement Sales Dashboard.pdf    ← Exported dashboard
│
├── 📁 Data/
│   └── Supplement_Sales_Weekly_Expanded.csv   ← Raw dataset
│
└── README.md
```

---

## 🚀 How to Open

1. **Clone the repo**
   ```bash
   git clone https://github.com/ranjeet22/FUTURE_DS_01.git
   ```

2. **Open the dashboard**
   - Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
   - Open `Dashboard/Supplement Sales Dashboard.pbix`

3. **Explore the data**
   - Use the slicers to filter by Category, Location, Platform, or Product
   - All visuals are cross-filtered and interactive

---

## 📊 Dataset Overview

- **Source:** `Supplement_Sales_Weekly_Expanded.csv`
- **Fields:** Date, Product Name, Category, Units Sold, Price, Revenue, Discount, Units Returned, Location, Platform
- **Categories:** Vitamin, Mineral, Performance, Protein, Amino Acid, Omega, Fat Burner, Hydration, Herbal, Sleep Aid
- **Platforms:** Amazon, iHerb, Walmart
- **Locations:** Canada, UK, USA
- **Granularity:** Weekly records

---

## 🔗 Links

| | |
|--|--|
| 📌 **Internship Programme** | [Future Interns - Data Science Task 1](https://futureinterns.com/data-science-analytics-task-1-2026/) |
| 💼 **GitHub Profile** | [github.com/ranjeet22](https://github.com/ranjeet22) |
| 📄 **Dashboard PDF** | [View Here](Dashboard/Supplement%20Sales%20Dashboard.pdf) |

---

<div align="center">

**Built with ❤️ by Ranjeet · Future Interns Data Science & Analytics Internship · 2026**

*If you found this useful, please ⭐ star the repository!*

</div>
