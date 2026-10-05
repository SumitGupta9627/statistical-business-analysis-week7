# Statistical Business Analysis — Week 7

## Project Overview
This internship project applies statistical techniques to business sales data to identify patterns, test business assumptions, measure relationships, estimate uncertainty, and build a regression model.

## Objectives
- Descriptive statistics: mean, median, mode, standard deviation.
- Distribution analysis using histogram and density plot.
- Pearson correlation and correlation heatmap.
- Three hypothesis tests: one-sample t-test, independent t-test, and one-way ANOVA.
- 95% confidence interval and margin of error.
- Linear regression with R-squared and RMSE.
- Business interpretation and recommendations.

## Dataset
`business_data.csv` contains 100 business observations and 5 columns:
- Date
- Region
- Sales
- Marketing_Spend
- Customers

## Setup
1. Install Python 3.13 or later.
2. Open the project folder in VS Code.
3. Create a virtual environment:
   `py -3.13 -m venv .venv`
4. Activate it:
   `.venv\Scripts\Activate.ps1`
5. Install packages:
   `py -3.13 -m pip install -r requirements.txt`
6. Start Jupyter:
   `jupyter notebook`
7. Open `statistical_analysis.ipynb` and run all cells.

## Code Structure
- `statistical_analysis.ipynb` — complete analysis and visualizations.
- `business_data.csv` — business dataset.
- `statistical_report.pdf` — submission documentation and results.
- `hypothesis_tests_results.txt` — hypothesis-test results.
- `requirements.txt` — required Python packages.
- `screenshots/` — visual and testing evidence.

## Technical Requirement Compliance
| Requirement | Status |
|---|---|
| Descriptive statistics | Completed |
| At least 3 hypothesis tests | Completed |
| Correlation analysis | Completed |
| Confidence intervals | Completed |
| Regression analysis | Completed |
| R-squared | Completed |
| Histograms / density plots | Completed |
| Business insights | Completed |

## Key Results
Average Sales: $55,257.63

95% Confidence Interval: $53,871.09 to $56,644.17

Margin of Error: ±$1,386.54

Sales-Marketing Correlation: 0.805

Regression R-squared: 0.647

## Testing Evidence
The project validates row/column counts, missing values, duplicate records, statistical calculations, hypothesis tests, confidence intervals, correlation, and regression.

See `screenshots/04_testing_evidence.txt`.
