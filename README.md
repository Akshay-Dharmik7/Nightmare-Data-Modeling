# 🌪️ Nightmare Data Model — Power BI Practice Project

A Power BI practice project focused on data modeling: transforming messy, denormalized source data into a clean **star schema** with Power Query ETL, DAX measures, and Row-Level Security.


## 📌 Overview

The raw data was intentionally messy — scattered across multiple sheets, missing surrogate keys, columns needing splits/unpivots, and junk rows to filter out. This project cleans and reshapes that data into a proper star schema in Power BI.

**Model structure:**
- **fact tables**: sales, sales targets, inventory, order process, campaign spend, promotion coverage
- **dimension tables**: customer, product, date, geography (role-playing: ship-to/bill-to), order flags, campaign, security
- **DAX measures** in a dedicated `_measures` table
- **Dynamic Row-Level Security** by region

## 🛠️ Tools Used
Power BI Desktop, Power Query (M), DAX, Excel (source data)

## 📁 Structure
```
├── Nightmare_Data_Model.pbix   # Main Power BI file
└── README.md
```

## 🚀 How to Use
1. Download `Nightmare_Data_Model.pbix`
2. Open in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Explore **Model view** for the schema/relationships and the `_measures` table for DAX

## 🎓 What I Practiced
Star schema design, Power Query transformations (merges, unpivots, surrogate keys), role-playing dimensions, Row-Level Security, and centralized DAX measures.
