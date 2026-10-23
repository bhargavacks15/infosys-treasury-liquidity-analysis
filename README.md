# Corporate Treasury & Liquidity Analysis: Infosys Limited

**An independent financial analysis project | FY2022–23 to FY2024–25 | Values in ₹ crore**

## Project Overview

This project examines Infosys Limited’s cash generation and liquidity position over three financial years using publicly available information from the company’s *Annual Report 2024–25 — Additional Information* extract.

The project brings together a formula-driven Excel workbook, a written report, supporting charts, and CSV datasets. It focuses on interpreting reported financial indicators, calculating selected measures, and clearly distinguishing reported figures from estimates derived from rounded ratios.

## Objectives

- Review the trend in cash and cash equivalents and investments.
- Examine operating cash flow relative to revenue.
- Compare capital expenditure with estimated free cash flow.
- Assess the movement in the company’s cash and investment pool.
- Document data limitations and make the calculations traceable to the source.

## Key Findings

| Indicator | FY2022–23 | FY2023–24 | FY2024–25 |
|---|---:|---:|---:|
| Operating cash flow / revenue (reported ratio) | 15.7% | 17.0% | 22.6% |
| Operating cash flow (derived estimate) | 23,042 | 26,124 | 36,836 |
| Capital expenditure | 2,579 | 2,201 | 2,237 |
| Free cash flow (derived estimate) | 20,463 | 23,923 | 34,599 |
| Cash and cash equivalents | 12,173 | 14,786 | 24,455 |
| Cash plus investments | 31,651 | 39,409 | 47,996 |
| Cash and investments / total assets (reported ratio) | 24.9% | 28.3% | 31.9% |
| Days of operating costs covered by cash plus investments (calculated) | 100 | 118 | 136 |
| Debt shown in the historical data table | Nil | Nil | Nil |

*All monetary figures are in ₹ crore. Figures labelled “derived” are estimates, not directly reported cash-flow amounts.*

### Interpretation

1. **Operating cash flow relative to revenue increased** from 15.7% to 22.6% over the period.
2. **Capital expenditure remained comparatively stable**, while the derived free cash flow estimate increased.
3. **Cash plus investments rose** from ₹31,651 crore in FY2022–23 to ₹47,996 crore in FY2024–25.
4. **The share held as cash and cash equivalents increased** in FY2024–25.
5. **The increase in cash and investments does not equal estimated free cash flow.** The source extract does not provide enough detail to identify all movements responsible for the difference.

## Project Files

```text
infosys-liquidity-analysis/
├── README.md
├── data/
│   ├── infosys_liquidity_dataset.csv
│   ├── infosys_liquidity_metrics.csv
│   └── source/
│       └── README.md
├── excel/
│   └── Infosys_Cash_Flow_Liquidity_Analysis.xlsx
├── charts/
│   ├── fig1_cash_and_investments.png
│   ├── fig2_ocf_capex_fcf_derived.png
│   ├── fig3_printed_ratios.png
│   ├── fig4_days_of_cover.png
│   └── fig5_fcf_vs_cash_build.png
└── report/
    ├── Infosys_Treasury_Liquidity_Report.pdf
    └── Infosys_Treasury_Liquidity_Report.docx
```

The filenames in the downloaded archive may include the prefix `last `; this does not affect the contents of the files.

## Methodology

- **Cash plus investments:** Cash and cash equivalents + investments (current and non-current).
- **Days of operating costs covered:** Cash plus investments divided by estimated daily operating costs, where estimated operating costs are revenue minus operating profit, divided by 365.
- **Operating cash flow (derived):** Reported operating-cash-flow-to-revenue ratio multiplied by revenue.
- **Free cash flow (derived):** Derived operating cash flow minus capital expenditure.
- **Capital intensity:** Capital expenditure divided by revenue.
- **Cash conversion (derived):** Derived operating cash flow divided by profit after tax.

The source prints the operating-cash-flow-to-revenue ratio to one decimal place. Therefore, the reconstructed rupee values are approximate and should not be treated as reported cash-flow statement figures.

## Data Source

**Primary source:** Infosys Limited, *Annual Report 2024–25 — Additional Information* (seven-page extract).

The project uses figures from pages 1, 3 and 4 of the extract. The extract is not included in this repository. Obtain the original document from the official Infosys investor-relations website and place it in `data/source/` if you want to retain a local copy for reference.

## Important Limitations

- The source extract does not include the full cash flow statement, total current assets, total current liabilities, or a detailed investment note.
- A current ratio, cash ratio, and operating-cash-flow ratio based on current liabilities cannot be calculated reliably from the available extract.
- Operating cash flow and free cash flow in rupees are **derived estimates** based on a rounded printed ratio.
- Cash plus investments includes non-current investments, so it should not be interpreted as a pure short-term liquidity measure.
- Three annual observations provide only a limited view of trends. The data do not show daily cash balances, bank-level positions, currency exposure, credit facilities, or cash-flow forecasts.

## How to Use the Deliverables

1. Start with the **Excel workbook** to review the input data, calculations, trends, dashboard, and audit checks.
2. Read the **PDF report** for the written interpretation and limitations.
3. Use the **CSV files** for further analysis in Excel or another spreadsheet/data tool.
4. Review the charts for a visual summary of the principal trends.

## Disclaimer

This project is for educational and analytical purposes only. It is not investment advice and does not describe Infosys Limited’s internal treasury policies or decision-making. Infosys is a trademark of Infosys Limited. This project is independent and is not affiliated with, endorsed by, or sponsored by Infosys Limited.

**Author:** Bhargava C  

