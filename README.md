# BMW-Group-Financial-Analysis-
Project Overview

This project analyzes the financial performance of BMW Group from 2021 to 2025 using Python.

The goal is to transform raw financial statement data into meaningful financial indicators and visualizations that help assess the company's growth, profitability, efficiency, and cash-flow performance.

The project demonstrates practical skills in financial analysis, data manipulation, financial ratio calculation, and data visualization.

Data

The dataset contains BMW Group financial data for the period 2021–2025.

All monetary values are expressed in € million.

The raw dataset includes:

Revenue
EBIT
Net Profit
Total Assets
Equity
Operating Cash Flow
Cash and Cash Equivalents

The data was collected from BMW Group financial reports and consolidated financial statements.

Financial Metrics Calculated

The analysis calculates several key financial indicators using Python and pandas.

Revenue Growth

Measures the year-over-year change in revenue.

Revenue Growth = (Revenue_t / Revenue_t-1 - 1) × 100
EBIT Margin

Measures operating profitability relative to revenue.

EBIT Margin = EBIT / Revenue × 100
Net Profit Margin

Measures how much net profit is generated for every euro of revenue.

Net Margin = Net Profit / Revenue × 100
Return on Assets

Measures profitability relative to the company's total asset base.

ROA = Net Profit / Total Assets × 100
Return on Equity

Measures profitability relative to shareholders' equity.

ROE = Net Profit / Equity × 100
Operating Cash Flow Margin

Measures operating cash generation relative to revenue.

OCF Margin = Operating Cash Flow / Revenue × 100
Visualizations
Revenue Development




Profitability




ROA vs ROE




Operating Cash Flow Margin




Key Findings

The analysis highlights several important developments in BMW Group's financial performance over the 2021–2025 period.

Revenue increased strongly between 2021 and 2023, with the highest level recorded in 2023.
Revenue declined in both 2024 and 2025.
EBIT margin weakened considerably after 2023, indicating lower operating profitability.
Net profit and net profit margin also declined following the stronger performance observed earlier in the period.
ROE declined as profitability weakened while BMW's equity base remained relatively strong.
Operating cash flow showed substantial variation across the period, highlighting the importance of analyzing cash generation alongside accounting profitability.

Overall, the results suggest that BMW experienced strong revenue growth and profitability earlier in the period, followed by weaker financial performance in 2024 and 2025.

Tools Used
Python
pandas
matplotlib
Jupyter Notebook
GitHub
Project Structure
BMW-Group-Financial-Analysis/
│
├── README.md
│
├── data/
│   └── bmw_financials.csv
│
├── notebooks/
│   └── bmw_financial_analysis.ipynb
│
└── outputs/
    ├── revenue.png
    ├── profitability.png
    ├── roa_roe.png
    └── ocf_margin.png
How to Run
Clone or download the repository.
Open the Jupyter Notebook located in the notebooks folder.
Install the required libraries if necessary:
pip install pandas matplotlib jupyter
Run the notebook cells from top to bottom.
Skills Demonstrated

This project demonstrates practical experience with:

Financial statement analysis
Financial ratio calculation
Data cleaning and manipulation with pandas
Data visualization with matplotlib
Trend analysis
Financial performance interpretation
Jupyter Notebook workflows
Structuring a reproducible financial analysis project
