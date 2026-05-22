# Canadian Household Credit Risk Monitoring Dashboard

## Project Overview

This project builds a Canada-level household credit risk monitoring dashboard using public Canadian macro-financial and insolvency datasets. The dashboard tracks household debt service burden, debt-to-income pressure, consumer insolvency growth, interest pressure, income pressure, and early-warning alert signals.

The final output is a Power BI dashboard designed for risk analytics, portfolio monitoring, and stakeholder reporting.

---

## Business Problem

Canadian financial institutions need to monitor whether households are becoming more financially stressed. Rising debt payments, high household leverage, increasing insolvencies, higher borrowing costs, and weak income growth can all signal higher household credit risk.

This project answers the question:

Are Canadian households becoming more financially stressed, and which indicators should risk teams monitor?

---

## Business Questions

The dashboard is designed to answer:

1. How has household debt service changed over time?
2. Is household leverage improving or worsening?
3. Are consumer insolvencies accelerating?
4. Which indicators are creating early-warning risk signals?
5. What risk level should a risk manager monitor?
6. What action should a risk team take based on the current trend?

---

## Data Sources

The project uses public Canadian datasets, including:

- Statistics Canada household debt service indicators
- Statistics Canada household financial indicators
- Statistics Canada household income and interest-related indicators
- Monthly insolvency statistics from Canada’s Open Government Portal

The final dashboard focuses on Canada-level quarterly monitoring because the selected household credit and debt-service datasets provide the strongest consistent national-level coverage.

---

## Tools Used

- Python
- Pandas
- NumPy
- Power BI
- Excel
- Statistics Canada data
- Open Government insolvency data

---

## Technical Workflow

```text
Raw data sources
→ Python ingestion and cleaning
→ Indicator filtering and transformation
→ Quarterly aggregation
→ Risk scoring logic
→ Dashboard-ready dataset
→ Power BI dashboard
→ Executive risk reporting
