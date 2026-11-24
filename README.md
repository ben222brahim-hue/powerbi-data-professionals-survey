# powerbi-data-professionals-survey
# Data Professionals Survey Dashboard (Power BI)

An interactive Power BI dashboard analysing a survey of **630 data professionals**: their roles, salaries, age, country, favourite programming language and job satisfaction.

![Dashboard preview](dashboard.png)

## Objective

Explore who works in data and how they feel about their jobs, and practise the full Power BI workflow: loading, cleaning, modelling and visualising data.

## Dataset

- 630 survey responses, 1 table.
- Main fields: job title, salary range, industry, favourite programming language, satisfaction scores (salary, work/life balance, coworkers, management, upward mobility, learning new things), difficulty of breaking into data, gender, age, country.
- Source: _add the source of the dataset here (link or "provided by my instructor")_.

## What I did

- Loaded and cleaned the data in Power Query.
- Created a calculated column **`average salary`** from the salary ranges (e.g. "86k-105k" becomes 95.5) so salaries could be aggregated.
- Built the report with:
  - KPI cards: number of respondents and average age
  - Bar chart: respondents by job title
  - Treemap: respondents by country
  - Donut chart: average salary by gender
  - Gauges: satisfaction scores (work/life balance, learning new things)
  - Column chart: favourite programming language by job title

## Key insights

_Add 2 or 3 findings from your dashboard, for example: which role is most common, which language is most popular, how satisfaction changes with salary._

## Files

| File | Description |
| --- | --- |
| `data_prof_survey_analyse.pbix` | Power BI report (open with Power BI Desktop) |
| `dashboard.png` | Screenshot of the dashboard |

## Tools

Power BI Desktop, Power Query, DAX

## Author

**Anis Benbrahim**, Business Computing student at ESEN
[LinkedIn](https://www.linkedin.com/in/anis-ben-brahim)
