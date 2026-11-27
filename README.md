# hr-attrition-analysis

## Project Overview

This project is using fictional employee data from Kaggle.

After presenting the overall employee attrition rate, I analyzed whether work environment satisfaction, job satisfaction, relationship satisfaction, work-life balance, and overtime differed between employees who left and those who stayed, focusing on employees with less than five years of tenure.


## Business Question

How do attrition rates vary by work environment satisfaction, job satisfaction, relationship satisfaction, work-life balance, and overtime among employees with less than five years of tenure?　

For detailed findings, see [Business Insights](reports/findings_and_recommendations.m).


## Key Metrics

- Overall Attrition Rate
- Under 1 Year Attrition Rate
- 1 to Under 5 Years Attrition Rate
- 5 Years or More Attrition Rate
- Under 5 Years Attrition Rate

KPI definitions and calculation methods are documented and validated in the [KPI and the Validation](reports/kpi_validation.csv).


## Tools Used

- Tableau Public — Data visualization and dashboard publishing
- CSV — Exported query results used as dashboard data sources
- GitHub — Version control and portfolio publication

## Dataset

- **Dataset:** 
- **Source:** [Northwind DemoDB](https://northwind.demodb.dev/downloads/)
- **License:** MIT License
- **Analysis Period:** July 4, 2016 – May 6, 2018

The first and last months contain partial-month data.

For additional information, see [Data Documentation](data/README.md) and [Data Quality Notes](analysis/data-quality-notes.md).

## Dashboard

[View Northwind Sales Dashboard on Tableau Public](https://public.tableau.com/app/profile/mikiko.tanaka/viz/NorthwindSalesAnalysis_17943008493170/Dashboard1)

### Dashboard Preview

![Northwind Sales Analysis](image/dashboard-preview.png)

## Key Insights

- Monthly net sales generally increased, reaching approximately 123.8K in April 2018.
- Beverages generated the highest net sales among product categories, at approximately 267.9K.
- The top three products accounted for approximately 23.1% of total net sales.
- The USA and Germany together contributed approximately 37.6% of total net sales.

For detailed findings and limitations, see [Business Insights](analysis/business-insights.md).

## Business Recommendations

1. Investigate the Drivers of Sales Growth
2. Monitor Revenue Concentration in Key Products
3. Evaluate Market-Specific Product Mix
4. Evaluate Performance in Major Markets
5. Assess Potential Expansion into New Markets

For supporting evidence and recommendations, see [Business Insights](analysis/business-insights.md).

## Repository Structure

```text
hr-attrition-analysis/
├── data/
│   └── README.md
├── references/
│   └── data_dictionary.csv
├── reports/
│   ├── figures/
│   │   └── dashboard.png
│   ├── data_quality_checks.csv
│   ├── data_quality_report.md
│   ├── kpi_validation.csv
│   └── findings_and_recommendations.md
├── .gitignore
└── README.md
```
