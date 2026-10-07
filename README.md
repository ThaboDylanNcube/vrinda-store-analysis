# Vrinda Store 2022 Order Analysis (Excel)

An Excel portfolio project analysing order value, fulfilment status, sales channels and customer demographics. The workbook contains **31,047 order-line records** from 2022.

## Key Findings

- Total listed amount across all records: **₹21,176,377**  
  (includes cancelled, returned and refunded rows — **not** net revenue).
- **Delivered** records: ₹19,710,544 and 28,641 rows (**92.3%** of all rows).
- Women account for **₹13,562,773 (64.0%)** of the listed amount vs men ₹7,613,604.
- Channel share of order-lines:
  - Amazon → **35.5%**
  - Myntra → **23.4%**
  - Flipkart → **21.6%**

## Questions Explored

- Monthly trend of order amount and order-line count
- Top states and channels by amount / volume
- Differences by gender and age group
- Fulfilment status breakdown (Delivered / Cancelled / Returned / Refunded)

## Method Notes

- Age groups used: 18–29, Adult (30–49), Senior (50+).
- PivotTables use `Count of Order ID` (row count). Because the same Order ID can appear on multiple rows, these are **not** distinct order or customer counts.
- The dashboard shows all statuses unless filtered by the user.

## Workbook Structure

| Sheet | Contents |
|-------|----------|
| `Vrinda Store Report 2022` | Main interactive dashboard |
| Other sheets | Supporting PivotTables, charts and source data |

## Tools

Microsoft Excel (formulas, PivotTables, charts, slicers)

## How to Use

1. Download the `.xlsx` file.
2. Open it in **desktop Excel**.
3. Start on the `Vrinda Store Report 2022` tab and use the slicers.
