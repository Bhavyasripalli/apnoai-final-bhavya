# ApnoMart — The Insight Board

**Analyst:** Bhavya Sri  
**Tool:** Python (Pandas, Matplotlib, Plotly) and Excel  
**Dataset:** ApnoMart sales CSV — 1,200 records

## Project overview
Executive sales dashboard with KPI cards, category/region/customer/payment analysis, monthly trend, a discount-profit view, and interactive Region and Category filters.

## Headline KPIs
- Total Sales: ₹16,261,998.30
- Total Profit: ₹4,419,736.17
- Total Orders: 1,200
- Weighted Profit Margin: 27.18%

## Three data-backed insights
1. **Revenue:** Furniture is the largest category at 21.6% of sales. Electronics has the lowest weighted margin (18.9%); Office Supplies leads at 34.8%.
2. **Profitability:** Central contributes the highest regional profit (21.4% of total). North has the lowest sales share (18.3%).
3. **Customer behavior:** Corporate is the largest segment (26.5% of sales), but segment sales are broadly distributed. Cash accounts for 21.5% of orders.

## Strategic recommendation
Pilot a lower-discount Electronics offer in selected cohorts, compare against a matched control, and scale only if weighted profit margin improves without an unacceptable sales decline. Use Central as a benchmark when reviewing North.

## Files
- `dashboard.png` — high-resolution static dashboard screenshot
- `interactive_dashboard.html` — interactive dashboard (Region and Category filters; internet connection required for Plotly library)
- `insights.pdf` — executive insights report
- `analysis.xlsx` — source data and summary tables, including calculated profit margin

## Important data-period note
The supplied CSV spans **May–October 2026**, not Q2 alone. The analysis therefore uses the complete supplied period and does not claim that these figures are Q2-only. The task's requested title is preserved in the report.

## Metric definition
Weighted Profit Margin = `SUM(Profit) / SUM(Sales)`. This is used for aggregate, category and regional margin comparisons.
