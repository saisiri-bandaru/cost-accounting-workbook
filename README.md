# Cost accounting workbook

Standard-cost variance lab for a fictional plant (**Northline Components**, July 2026).

**Open this file:** [`Northline_Cost_Accounting_Variances_Jul2026.xlsx`](Northline_Cost_Accounting_Variances_Jul2026.xlsx)

All figures are invented. No employer data.

## Business question

Actual COGS is above standard. Who owns the miss — purchasing, the floor, or the production plan?

Open `05_Bridge` first. That tab is the meeting.

## Who owns which line

| Variance | Typical owner | What a good conversation sounds like |
| --- | --- | --- |
| Material price | Purchasing | Freight, vendor mix, or a stale standard price |
| Material quantity | Operations / yield | Scrap, BOM vs actual usage |
| Labor rate | HR / scheduling | Mix of temps vs full-time, overtime |
| Labor efficiency | Floor supervisor | Hours per unit vs routing |
| Variable OH spending / efficiency | Plant controller + ops | Consumables and runtime |
| Fixed OH budget / volume | Planning | Actual units vs denominator volume |

Convention in this file: **positive variance = unfavorable**.

## What to change in a screen-share

Yellow cells live on `01_Standards` and `02_Actuals`.

**Volume shock to try:** drop July production ~10% on `02_Actuals` and leave standards fixed. Fixed-overhead **volume** variance should widen. Price and rate lines should not move unless you also change spend.

**Price shock to try:** raise actual material price 5% with quantity unchanged. Only the material price bar on the bridge should jump.

Blue / yellow = inputs. Black = formulas.

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

[Profile](https://github.com/saisiri-bandaru) · [Portfolio](https://saisiri-bandaru.github.io) · [saisiri.bandaru12@gmail.com](mailto:saisiri.bandaru12@gmail.com)
