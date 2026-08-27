# Excel-Superstore-dashboard
Interactive Excel dashboard analyzing Superstore sales &amp; Profitability
  Superstore Sales & Profitability Dashboard (Excel)

## Objective
Analyzed the Sample Superstore dataset to identify which regions, categories, discount levels, and customer segments drive — or drain — profitability, and presented findings in an interactive Excel dashboard.

## Business Questions
1. Which regions and categories drive the most sales and profit — are any losing money?
2. Which sub-categories have high sales but low or negative profit margins?
3. How does discount level affect profit? At what point does profit turn negative?
4. Which customer segment is most profitable?
5. Which Ship Mode is most/least profitable, and does it relate to discount levels?

## Tools & Skills Used
- Power Query — data cleaning
- PivotTables & PivotCharts — Region, Category, Sub-Category, Segment, Ship Mode breakdowns
- Calculated columns — Profit Margin % (Profit ÷ Sales)
- Charts — column, bar, and scatter charts with secondary axes
- Conditional Formatting & Data Validation
- Slicers — interactive filtering connected across multiple PivotTables
- Dashboard design — single-sheet layout with KPIs, charts, and filters

## Key Insights
1. The West region consistently outperforms other regions across Furniture, Office Supplies, and Technology, while the South region shows the weakest sales performance — a possible regional demand or marketing gap.
2. High-revenue sub-categories aren't always the most efficient earners: Phones and Chairs generate the highest sales (~$330K, ~$328K) but comparatively thin margins (~9–11%), while smaller sub-categories like Fasteners achieve stronger margins (~16%).
3. Discounting above 30–40% consistently erodes profitability — profit turns negative beyond that threshold, with losses deepening sharply past 50% (some transactions losing over $6,000). A discount cap policy could help.
4. Consumer segment drives the most total profit ($134K) vs. Corporate ($92K) and Home Office ($60K), despite similar discount rates (~14.7–15.8%) across all three — suggesting the gap is driven by order volume, not discounting.
5. Standard Class shipping generates the highest total profit ($163,864), while Same Day contributes the least ($15,872), likely reflecting lower order volume for that shipping option.

## Dashboard Preview
*(insert screenshot here)*

## Files
- `Superstore_Dashboard.xlsx` — full workbook with cleaned data, PivotTables, and dashboard
