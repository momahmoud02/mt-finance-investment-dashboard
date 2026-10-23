# MT Finance - Investment Preferences Dashboard

A Power BI dashboard that turns a 40-response investor survey into a clear view of what people invest in, why, for how long, and through which channel.

## Overview

| Item | Detail |
|---|---|
| Responses | 40 survey participants |
| Tooling | Power BI Desktop, DAX, HTML/CSS cards, native visuals |
| Filters | Four slicers covering the main survey dimensions |
| Focus | Investment avenues, objectives, duration, and channels |

## What the dashboard shows

- **Participants by investment type** - how the sample splits across mutual funds, equity, debentures, government bonds, fixed deposits, PPF, and gold.
- **Participants by objective** - capital appreciation, wealth creation, and related goals.
- **Participants by duration** - short, medium, and long holding preferences.
- **Investment channels distribution** - where participants place their money.
- **Survey detail table** - row-level responses for follow-up analysis.
- **HTML summary cards** - context and definitions kept visually consistent with the charts.

Four slicers let the viewer isolate a segment and have every visual respond at once.

## Dataset

`data/Finance_data.csv` contains 40 responses and 24 fields, including:

- Demographics: gender, age.
- Avenue ranking: mutual funds, equity market, debentures, government bonds, fixed deposits, PPF, gold.
- Behaviour: investment objective, purpose, preferred duration, monitoring frequency, expected return.
- Preferences: savings objective, reasons for each avenue, and information source.

`data/Original_data.csv` keeps the original column labels for traceability.

## Repository contents

```text
mt-finance-investment-dashboard/
|-- MT_Finance_Investment_Dashboard.pbix
|-- data/
|   |-- Finance_data.csv
|   `-- Original_data.csv
`-- README.md
```

## How to open

1. Open `MT_Finance_Investment_Dashboard.pbix` in Power BI Desktop.
2. If prompted, allow the HTML Content custom visual used by the summary cards.
3. Use the slicers to move from the full sample to a specific investor segment.

## Data notes

- The survey is a small illustrative sample and is not a statistically representative study.
- The project name is independent; it is not affiliated with any financial institution.
- No personally identifying information is included in the dataset.

## Author

**Mohamed Mahmoud Taha** - Financial Analyst | Data Analyst

GitHub: [momahmoud02](https://github.com/momahmoud02)
