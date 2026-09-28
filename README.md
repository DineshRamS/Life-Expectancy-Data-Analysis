# Life Expectancy Data Analysis

## Project Overview

This project is an end-to-end data analysis capstone focused on historical life expectancy data.

The project covers:
- Data cleaning
- Exploratory Data Analysis (EDA)
- Statistical analysis
- Trend analysis
- Entity-level comparison
- Data visualization
- Actionable insights
- Reproducible notebook-based analysis

## Dataset

The original dataset contains:

- 21,565 records
- 4 columns
- 247 entities
- Years ranging from 1543 to 2023

After cleaning:

- 20,217 records
- Missing country/entity codes removed
- Duplicate records checked

## Key Findings

### Overall Statistics

- Mean life expectancy: 62.07 years
- Median life expectancy: 64.79 years
- Latest-year average (2023): 74.12 years

### Entity Comparison

Highest average life expectancy:

- Monaco: 78.05 years

Lowest average life expectancy:

- South Sudan: 37.84 years

The difference between the highest and lowest average is approximately 40.21 years.

## Visualizations

### 1. Average Life Expectancy Over Time

`average_life_expectancy_trend.png`

Shows the change in average life expectancy across the historical period.

### 2. Top 10 Entities by Average Life Expectancy

`top_10_average_life_expectancy.png`

Compares the entities with the highest average life expectancy.

## Actionable Insights

1. Long-term life expectancy trends should be monitored to identify periods of improvement and areas requiring additional health and social investment.

2. The large gap between high- and low-performing entities highlights areas where stronger healthcare, prevention and social-development interventions may be required.

3. Historical comparisons should consider changing data coverage because the number of represented entities varies across the dataset.

## Methodology

1. Loaded the original dataset.
2. Inspected the dataset structure.
3. Checked missing values.
4. Removed records without country/entity codes.
5. Checked duplicate records.
6. Calculated descriptive statistics.
7. Analyzed yearly average life expectancy.
8. Calculated entity-level statistics.
9. Filtered entities with at least 20 recorded years for comparison.
10. Created two visualizations.
11. Generated actionable insights.
12. Created a 1–2 page visual PDF report.

## Project Files

- `Life_Expectancy_Analysis_Report.pdf`
- `average_life_expectancy_trend.png`
- `top_10_average_life_expectancy.png`
- `life_expectancy_actionable_insights.csv`
- `life_expectancy_kpi_summary.csv`
- `Life_Expectancy_Data_Analysis.ipynb`

## Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter / Google Colab
- ReportLab

## Conclusion

The analysis demonstrates substantial variation in life expectancy across entities and historical periods. Combining data cleaning, trend analysis, entity-level comparison and visual reporting provides a reproducible approach for understanding the dataset.
