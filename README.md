@'
# CodeAlpha_DataVisualization — Interactive Power BI Books Catalog Dashboard

## 📌 Project Overview
This project transforms the cleaned books dataset (`books_data.csv`) into an interactive business intelligence dashboard using **Power BI Desktop**, **Power Query**, and **DAX**. Stakeholders can filter across star ratings and pricing tiers to inspect catalog distribution, pricing consistency, and high-rated inventory share.

## 🛠️ Technologies & Features Used
- **Power Query Editor:** Data type enforcement (`Decimal Number`, `Whole Number`, `Text`), duplicate title deduplication (`1,000` -> `999` unique titles), and conditional columns (`Price Tier`, `Rating Label`).
- **DAX (Data Analysis Expressions):** Dynamic measures (`Total Books`, `Average Price`, `Total Catalog Value`, `High Rated Share`) that recalculate automatically under slicer filters.
- **Power BI Desktop Visuals:** Executive KPI cards, interactive slicers, Clustered Column Chart, Clustered Bar Chart, and Donut Chart.

## 📂 Folder Structure
```text
CodeAlpha_DataVisualization/
├── data/
│   └── books_data.csv              # Input dataset
├── screenshots/
│   └── dashboard_overview.png      # Final Power BI dashboard screenshot
├── Books_Analytics_Dashboard.pbix  # Interactive Power BI report file
└── README.md                       # Project documentation