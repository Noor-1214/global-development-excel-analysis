# Global Development Indicators Analysis

An Excel-based analysis of global development trends in **life expectancy, population, and GDP per capita** across five continents from **1952 to 2007**.

The project demonstrates an end-to-end Excel analysis workflow, including data cleaning, quality checks, calculated fields, PivotTable analysis, data visualisation, dashboard development, and interpretation of key findings.

## Dashboard

![Global Development Dashboard](images/Dashboard.png)


## Project Objectives

The aim of this project was to analyse long-term global development patterns and answer several key questions:

- How has average life expectancy changed across continents over time?
- Which continents experienced the greatest improvements in life expectancy?
- How does GDP per capita vary between continents and over time?
- How was the global population distributed across continents in 2007?
- Which continents recorded the highest life expectancy and GDP per capita by 2007?

## Dataset

The analysis uses Gapminder-style development data covering **1952–2007** across five continents:

- Africa
- Americas
- Asia
- Europe
- Oceania

Three main development indicators were analysed:

| Indicator | Description |
|---|---|
| `LIFE_EXP` | Life expectancy in years |
| `POP_TOTAL` | Total population |
| `GDP_PC` | GDP per capita |

The workbook preserves the original data separately from the cleaned analytical dataset, allowing the data preparation and analysis stages to remain clearly separated.


## Data Preparation & Excel Techniques

The raw data was preserved in a separate worksheet before creating a cleaned dataset for analysis. This allowed the original source data to remain unchanged while transformations and validation checks were performed separately.

Key preparation and analysis techniques included:

- **Data quality checks** to identify invalid, missing, or negative values.
- **IF, AND and ISNUMBER** logic to create validation flags.
- **FLOOR** to group observations into decades for time-based analysis.
- **Nested IF statements** to categorise life expectancy values into bands.
- **VLOOKUP** to map indicator codes to broader development dimensions.
- **COUNTIF** and **AVERAGEIF** for conditional aggregation.
- **PivotTables** to compare indicators across years and continents.
- **PivotCharts** to visualise long-term trends and continental differences.
- **Filtering and aggregation** to isolate specific indicators and analyse 2007 outcomes.
- **Dashboard design** to combine KPIs, charts and analytical insights into a single stakeholder-facing view.

## Workbook Structure

| Worksheet | Purpose |
|---|---|
| `raw_data` | Preserves the original source data |
| `cleaned_data` | Contains the cleaned dataset and derived analytical fields |
| `quality_checks` | Documents data validation and quality checks |
| `calculated_fields` | Contains formula-based calculations and headline metrics |
| `pivot_analysis` | Contains PivotTables used for aggregated analysis |
| `charts` | Contains the main analytical visualisations |
| `dashboard` | Presents KPIs, charts and key insights in one view |
| `Insights_Report` | Summarises the main analytical findings and conclusions |
