# Smart Inventory Control

**Google Sheets Inventory Management & Replenishment Dashboard**

[**View the Live Google Sheets Demo**](https://docs.google.com/spreadsheets/d/1bTOh8ek2TDDCdaTAmOb_va159wGaf4sA3-b0MHiWLNU/edit)

A spreadsheet-based inventory tracking and replenishment prototype designed for small businesses. It demonstrates how connected tables, formulas and KPI reporting can support stock control and purchasing decisions.

## Project features

- Track stock balances using opening inventory and inbound/outbound movements.
- Flag items at or below their reorder thresholds.
- Calculate suggested reorder quantities based on target stock levels.
- Estimate replenishment cost using item unit costs.
- View stock KPIs and a monthly movement chart.

## Sample data

- 36 fictional products
- 180 synthetic inventory movements
- 4 fictional suppliers

## Workbook worksheets

| Worksheet | Description |
| --- | --- |
| `Suppliers` | Fictional supplier directory |
| `Inventory` | Product catalog, stock balances, alerts and suggested orders |
| `Movements` | Inbound and outbound stock transaction log |
| `Reorder Summary` | Estimated reorder quantities and purchasing costs |
| `Dashboard` | Inventory KPIs and monthly outbound movement chart |
| `Guide` | Instructions and limitations |

## Technology and skills

Google Sheets, spreadsheet modeling, inventory analysis, KPI reporting, data visualization, `IF`, `SUMIF`, `SUMIFS`, and cross-sheet formulas.

## How to use

1. Open the [live Google Sheets demo](https://docs.google.com/spreadsheets/d/1bTOh8ek2TDDCdaTAmOb_va159wGaf4sA3-b0MHiWLNU/edit).
2. Review the `Inventory`, `Movements`, and `Dashboard` worksheets.
3. Modify fictional stock records to test the automatic calculations.
4. Restore the original demo data after testing.

Alternatively, download `03_Smart_Inventory_Control.xlsx` and import it into Google Sheets.

## Limitations

All company, supplier and transaction data are synthetic and for demonstration only. This is a portfolio prototype rather than a production-ready inventory or procurement management platform. Suggested order quantities use a simple target-stock rule; demand forecasting, supplier lead times, purchase orders and transaction audits are outside the current scope. Check formula ranges before adding large datasets.

## Author

Enrico Raspa · [GitHub profile](https://github.com/enricoRSG)
