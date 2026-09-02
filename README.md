# Cost accounting workbook

Standard-cost variance lab for a fictional plant (**Northline Components**, July 2026).

**Deliverable:** [`Northline_Cost_Accounting_Variances_Jul2026.xlsx`](Northline_Cost_Accounting_Variances_Jul2026.xlsx)

## Business question

Actual COGS is above standard. Who owns the miss — purchasing, the floor, or the production plan?

## How to review this file (8 minutes)

1. Open `05_Bridge` first. That tab is the meeting.
2. Scan `03_Variances` for price vs quantity vs volume.
3. Change one yellow cell on `02_Actuals` (price, quantity, or units).
4. Confirm only the matching bar on `05_Bridge` moves. Black font is formulas.

Convention: **positive variance = unfavorable**.

## Screen-share tests

- **Volume:** drop July production ~10% on `02_Actuals`, leave standards fixed. Fixed-overhead **volume** variance should widen. Price and rate lines should not move unless spend also changes.
- **Price:** raise actual material price 5% with quantity unchanged. Only the material price bar should jump.

## Who owns which line

| Variance | Typical owner | Conversation |
| --- | --- | --- |
| Material price | Purchasing | Freight, vendor mix, or a stale standard price |
| Material quantity | Operations / yield | Scrap, BOM vs actual usage |
| Labor rate | HR / scheduling | Temps vs full-time, overtime |
| Labor efficiency | Floor supervisor | Hours per unit vs routing |
| Variable OH spending / efficiency | Plant controller + ops | Consumables and runtime |
| Fixed OH budget / volume | Planning | Actual units vs denominator volume |

## Tabs

| Tab | Role |
| --- | --- |
| `00_Cover` | Purpose |
| `01_Standards` | Standard qty, price, hours, rates, volume |
| `02_Actuals` | July production and actual spend |
| `03_Variances` | Full variance stack |
| `04_By_SKU` | Two-SKU quantity lens |
| `05_Bridge` | Standard COGS → actual COGS |
| `06_Dictionary` | Terms |

Excel formulas only. No VBA, no live ERP, no employer data.

[Profile](https://github.com/saisiri-bandaru) · [Portfolio](https://saisiri-bandaru.github.io) · [LinkedIn](https://www.linkedin.com/in/bandarusaisiri) · [bandarusaisiri1207@gmail.com](mailto:bandarusaisiri1207@gmail.com)
