# E-commerce Order MIS Dashboard (Excel)

An MIS reporting workbook that turns raw order data into daily, weekly and monthly reports plus a KPI dashboard, like the reports an MIS Analyst prepares for an E-commerce / D2C team.

> Data is **simulated** (1,200 orders, 01 Jul - 30 Sep 2026) for practice.

![Dashboard](screenshots/dashboard.png)

## What is inside
| Sheet | Contents |
|-------|----------|
| Dashboard | 10 KPIs, category / city / payment-mode analysis, 4 charts |
| Daily MIS | Orders, revenue, delivered, returned, cancelled, RTO, delivery % and return % for each of 92 days |
| Weekly MIS | Same metrics for 14 weeks |
| Monthly MIS | Same metrics for Jul, Aug, Sep, plus AOV and COD share |
| Data | Raw order data |
| About | Definitions and how to use |

## KPIs tracked
Total orders, gross and net delivered revenue, average order value, average delivery days, delivery rate, return rate, cancellation rate, RTO rate, COD share.

## Key insights from the data
- Delivery rate is 82.2%; return rate is 7.4%.
- **COD orders have a 15.3% RTO rate vs 0.8% for prepaid orders**, so pushing prepaid payment would cut RTO losses.
- Skincare is the biggest category by revenue.
- Orders grew from July (363) to August (421) and stayed high in September (416).

## Excel skills used
`COUNTIFS`, `SUMIFS`, `AVERAGE`, `IFERROR`, `EOMONTH`, cross-sheet formulas, charts, formatted tables. All report numbers are formulas, nothing is hardcoded.

## How to use
Open `Ecommerce_Order_MIS_Dashboard.xlsx`. To use your own data, paste rows into the **Data** sheet and extend the formula ranges.
