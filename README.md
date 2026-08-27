# Cost accounting workbook

Standard-cost variance lab for a fictional plant (**Northline Components**, July 2026).

Portfolio: [saisiri-bandaru](https://github.com/saisiri-bandaru)

**Workbook:** `Northline_Cost_Accounting_Variances_Jul2026.xlsx` (upload the Excel file to this repo, or generate it with `python3 build_workbook.py` after `pip install openpyxl`).

All figures are invented. No real employer data.

## What this shows

- Bill of materials and routing (standards)
- July actual production, usage, and rates
- Material price and quantity variances
- Labor rate and efficiency variances
- Variable overhead spending and efficiency
- Fixed overhead budget and volume
- One-page bridge from standard COGS to actual COGS

## Interview talk track

Open `05_Bridge`. Price/rate sits with purchasing and HR. Quantity/efficiency sits with the floor. Volume sits with the production plan vs capacity. Change yellow cells on `02_Actuals` and the bridge moves.

Blue / yellow = inputs. Black = formulas. Positive variance = unfavorable.

## Tabs

| Tab | Role |
| --- | --- |
| `00_Cover` | Purpose |
| `01_Standards` | Standard qty, price, hours, rates, volume |
| `02_Actuals` | July production and actual spend |
| `03_Variances` | Full variance stack |
| `04_By_SKU` | Two-SKU quantity lens |
| `05_Bridge` | Standard COGS to actual COGS |
| `06_Dictionary` | Terms |
