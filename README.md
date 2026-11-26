# Superstore Sales Analysis | Excel Dashboard
 
An end-to-end sales analysis of 9,994 retail orders (2014-2017), built in Excel with PivotTables, formulas, and a dashboard. The goal was to find what drives revenue and profit, and where the business is losing money.
 
<img width="773" height="740" alt="Screenshot 2026-11-26 214340" src="https://github.com/user-attachments/assets/f47dca25-7ee2-4f8d-9143-5c12ce16f674" />


[View the full-quality PDF](Dashboard.pdf)
 
## Key Findings
 
| Metric | Value |
|---|---|
| Total Sales | $2.30M |
| Total Profit | $286K |
| Profit Margin | 12.47% |
| Orders analyzed | 9,994 |
 
1. **Heavy discounts turn orders into losses.** Orders with no discount average **+$66.90** profit, while orders discounted 21-40% average **-$77.86** and orders above 40% average **-$106.71**.
2. **Three sub-categories lose money.** Tables (-$17.7K), Bookcases (-$3.5K), and Supplies (-$1.2K) are unprofitable despite healthy sales. Copiers, Phones, and Accessories are the top profit drivers.
3. **Sales are strongly seasonal.** Revenue peaks every September and November-December, and dips in January-February.
4. **Central region has the weakest margin** at 7.9%, against 11.9%-14.9% in the other regions.
5. **Revenue is not concentrated.** The top 10 customers account for only about 6.7% of total sales.
## Recommendations
 
- Cap discounts at 20% on low-margin products.
- Review pricing and discounting for Tables, Bookcases, and Supplies.
- Time inventory and marketing campaigns around September and Q4.
- Investigate why the Central region earns lower margins.
## What's in the Workbook
 
| Sheet | Purpose |
|---|---|
| `Dashboard` | Final dashboard: KPI cards, 6 charts, and key insights |
| `tblSales` | Cleaned data stored as an Excel Table (`tblSales`) |
| `Analysis` | Formula-based region summary, customer lookup, and order counts |
| `Pivot_*` sheets | PivotTables behind each chart (sales by year, sub-category profit, discount bands, top customers, monthly trend) |
 
## Methods and Excel Skills Used
 
- **Data preparation:** converted data to an Excel Table, checked for duplicate records on Row ID, and fixed date formatting
- **Helper columns:** `Year`, `YearMonth`, `Profit Margin`, `Loss Flag`, and `Discount Band` (nested `IF`, `IFERROR`, `YEAR`, `TEXT`)
- **Formulas:** `SUMIFS`, `COUNTIFS`, and `XLOOKUP`
- **PivotTables:** multi-field summaries, Top 10 value filters, and sorting
- **Visualization:** line, bar, and column charts with consistent colors (red reserved for losses)
- **Dashboard design:** KPI cards, grid layout, and insight-driven chart titles
## Dataset
 
[Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) on Kaggle: 9,994 orders with sales, quantity, discount, and profit across regions, segments, and product categories.
 
## Files
 
- `Superstore_Dashboard.xlsx`: the full workbook
- `Dashboard.pdf`: PDF version of the dashboard

 
 
