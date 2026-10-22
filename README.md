# US GDP Analysis (1987–1997) | Excel Portfolio Project

Exploratory analysis of US GDP by sector and industry from 1987 to 1997 using Microsoft Excel. This is an independent learning analysis based on Codecademy's *Explore GDP in Excel* project.

> **Completed workbook:** [GDP_Analysis_Completed.xlsx](GDP_Analysis_Completed.xlsx) — the saved Excel project, including worksheet calculations and the pivot-table analysis.

## Questions explored
- Which categories contributed most and least to GDP in 1987, 1992, and 1997?
- How did Finance, Manufacturing, and Education change as a share of overall GDP?
- How did computer-related industries rank when regrouped as their own category?

## Excel skills demonstrated
- Multi-level sorting (year and GDP contribution), filtering and comparative analysis
- Annual totals using `=SUM(C9:C24)`
- GDP shares with mixed references using `=C9/C$25`, filled down and across
- Reclassification of two computer-related industries into a new **Computers** category
- Pivot tables (rows: Category; columns: Year; values: SUM of GDP billions)
- Interpretation of trends and discussion of analysis limitations

## Selected findings

| Indicator | 1987 | 1997 | Interpretation |
|---|---:|---:|---|
| Total GDP (nominal USD billions) | 4,656.8 | 8,222.0 | Increased |
| Finance GDP share (rounded) | 18% | 20% | +2 percentage points |
| Manufacturing GDP share (rounded) | 19% | 17% | −2 percentage points |
| Education GDP share (rounded) | ~1% | ~1% | Approximately stable |
| Computers category rank | 12th | 10th | Improved by two positions |

Manufacturing led in the original 1987 grouping, while Finance led in 1992 and 1997. After computer-related industries were separated out, Finance led in 1987 as well. This is a **classification effect**, not an increase or decrease in aggregate GDP.

## Workbook and visual previews
Open or download [GDP_Analysis_Completed.xlsx](GDP_Analysis_Completed.xlsx) to examine the completed Excel exercise.

The following **recreated SVG table previews** summarize the workbook's results (they are not literal Excel screenshots):

**Percentage analysis**

![GDP percentage preview](screenshots/gdp_percentage_preview.svg)

**Pivot table analysis**

![GDP pivot preview](screenshots/gdp_pivot_preview.svg)

The original Excel screenshots can be uploaded separately if needed.

See [INSIGHTS.md](INSIGHTS.md) for interpretation and [data/summary_metrics.csv](data/summary_metrics.csv) for a compact metrics table.

## Limitations
- Figures are nominal and not inflation-adjusted.
- Years covered are limited to 1987–1997.
- The Computers category includes only two industries explicitly described as computer-related, not the economy-wide impact of IT.
- Percentages shown are rounded, and sector definitions affect rankings.
- Observed correlations and shifts do not demonstrate that computer adoption caused changes in GDP.

## Data source and attribution
Based on Codecademy's **Explore GDP in Excel** exercise within the *Exploring Data* course module. Original course dataset and instructions belong to their respective rights holders; the narrative, workflow, and insights document the learner's analysis. The official solution workbook is not distributed here.

## Reproducibility
The completed workbook is included in the repository root as [`GDP_Analysis_Completed.xlsx`](GDP_Analysis_Completed.xlsx). Open it in Microsoft Excel to review formulas, the percentage analysis, and pivot table. The source material is attributed to Codecademy above.
