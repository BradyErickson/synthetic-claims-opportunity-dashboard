# Synthetic Claims Opportunity Dashboard

An Excel portfolio project demonstrating data consolidation, formula-driven classification, dashboard reporting, linked record-level views, and reconciliation controls using entirely synthetic claims data.

## Project Overview

This project consolidates 560 synthetic claims across five opportunity indicators and 12 fictional claims-analyst views. The workbook includes three dashboard visualizations and independent audit controls for validating claim IDs, source-report totals, indicator distributions, and analyst-level coverage [1].

## Key Features

- Formula-driven opportunity classifications
- Text-search logic for claim-alert indicators
- Dashboard KPIs and charts
- Conditional formatting
- Linked analyst-level record views
- Blank-safe formulas for optional dates and amounts
- Reconciliation and audit controls
- 560 unique synthetic claim IDs with zero unexplained differences [1]

## Opportunity Indicators

The workbook evaluates five fictional opportunity indicators:

- Settlement Authorization
- Open Stipulation Without C&R
- Pending QME
- Automated Claim Alert
- Inactive Customer

## Signal-Level Methodology

Opportunity Signal Level is determined solely by the number of active indicators:

- 1 indicator: Single-Signal
- 2 indicators: Multi-Signal
- 3 indicators: Elevated Multi-Signal
- 4 indicators: High Multi-Signal
- 5 indicators: Maximum Multi-Signal

This classification is intended only to demonstrate Excel logic and dashboard design. It is not a predictive model or a real-world claims recommendation.

## Tools Demonstrated

- Microsoft Excel
- Excel formulas and text-search logic
- Conditional formatting
- KPI and chart design
- Linked worksheet views
- Data-quality and reconciliation controls

## Data Validation

The workbook’s controls confirm:

- 560 master records
- 560 unique synthetic claim IDs
- All records assigned to one signal-level group
- Complete analyst-view coverage
- Source-report totals reconciled with zero unexplained differences [1]

## Synthetic Data Statement

All names, organizations, claim identifiers, dates, monetary amounts, evaluator names, statuses, and alert text in this project are synthetic and fictional. The workbook was independently created for public portfolio use and contains no personal contact details, employer-specific system names, internal file paths, or original claim-level values [1].

The fictional reporting date is December 31, 2031. Time-dependent statuses and classifications should be interpreted relative to that date [1].

## Important Limitation

This project demonstrates spreadsheet engineering, reporting, and data-quality techniques. It does not provide legal, medical, financial, insurance, or claims-handling advice. The data and results should not be used for real-world decisions.

## File

- `synthetic-claims-opportunity-dashboard.xlsx` — complete Excel workbook
- `dashboard-preview.png` — preview of the main dashboard

## License

This project is available under the MIT License. See [LICENSE](LICENSE) for details.

## Author

Brady Erickson 
bradyerickson101@gmail.com
