# Sales Performance Dashboard (Excel)

**One-line:** Interactive Excel Sales Performance Dashboard using PivotTables, Slicers, conditional formatting and calculated fields to analyze 1,000+ sales transactions.

---

## Project Overview
This project demonstrates an end-to-end, job-ready Excel dashboard built from a synthetic sales dataset (1,000+ rows). It showcases practical data-cleaning, analysis and visualization skills commonly used in entry-level MIS / Reporting / Data Analyst roles.

---

## Key Features
- Clean, structured dataset using an Excel Table (`SalesData`)
- Calculated column: **Total Sales** (`Units Sold * Unit Price`)
- Conditional formatting:
  - Highlight Top 10 Total Sales
  - Row shading where `Region = "East"`
- PivotTables summarizing:
  - Sum of Total Sales by Salesperson and Region
  - Sum of Units Sold
- Interactive PivotChart (bar/column) for quick visualization
- Slicers for **Region** and **Product** (instant filtering)
- KPI card (Total Sales) that reacts to slicer selections
- Polished Dashboard sheet optimized for presentation and sharing

---

## Dataset
- File: `Sales_Performance_Data.xlsx`
- Rows: 1,000+ synthetic transactions
- Columns: `OrderID`, `Date`, `Region`, `Product`, `Salesperson`, `Units Sold`, `Unit Price`, `Total Sales`

(Generated for practice — no sensitive or real business data.)

---

## How to view / use
1. Download `Excel_Sales_Performance_Dashboard.xlsx`.
2. Open in Microsoft Excel (desktop recommended for full slicer/pivot functionality).
3. Go to the **Dashboard** sheet to explore visuals.
4. Use the **Region** and **Product** slicers to filter the charts and KPI.
5. To refresh data after edits: `Data → Refresh All` (or right-click a PivotTable → Refresh).

---

## What I built (technical steps)
1. Converted raw data into an Excel Table (`Ctrl+T`) and named it `SalesData`.
2. Added calculated column: `Total Sales = [Units Sold] * [Unit Price]`.
3. Applied conditional formatting for top sales and region-based row shading.
4. Created PivotTables (Salesperson rows, Region columns, values: Sum of Total Sales and Units Sold).
5. Inserted PivotChart and linked interactive Slicers (Region, Product).
6. Created a Dashboard sheet, added a title, KPI card and arranged visuals for readability.
7. Saved and prepared the file for sharing (Google Drive/GitHub).

---

## Skills demonstrated
- Excel: Tables, PivotTables, PivotCharts, Slicers, Conditional Formatting, Calculated Columns, Number Formatting
- Data storytelling: KPI design, clean layout, interactive filters
- Versioning & sharing: GitHub / Google Drive ready

---

## Resume / LinkedIn copy (paste-ready)
**Sales Performance Dashboard (Excel)** — Built an interactive Excel dashboard using PivotTables, PivotCharts and Slicers to analyze 1,000+ sales transactions. Implemented calculated columns, conditional formatting for insights (Top 10 sales, region highlights), and a KPI card for real-time summary. Tools: Microsoft Excel (Tables, PivotTables, Slicers).

---

## Possible extensions (next steps you can mention in interviews)
- Rebuild dashboard in Power BI for advanced visuals and scheduled refresh
- Add automated data import via Power Query from CSV/CSV dumps
- Create Python script to preprocess incoming sales files and append to the table
- Add monthly trend charts and YoY comparison metrics

---

## License
This repository contains synthetic data and example workbook for practice and portfolio use. Feel free to reuse and adapt for learning or interview demonstrations.

---

## Contact
If you want to see a walkthrough or need a tailored version for your resume or an interview task, reach me at: `eshantbagwe2000@gmail.com` 
