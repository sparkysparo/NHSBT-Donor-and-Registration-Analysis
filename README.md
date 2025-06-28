# NHSBT Donor and Registration Analysis

This Power BI project explores NHS Blood and Transplant (NHSBT) donor and registration trends from 2020 to 2024. It provides in-depth insights into variations across ethnicity, region, and year. The goal is to support data-driven strategies to improve inclusivity and regional outreach.

## Key Insights

- Donor numbers dropped slightly in 2021, likely due to the COVID-19 pandemic.
- A recovery followed in 2022, with London and the South East showing the highest donor volumes.
- The White ethnic group makes up 76.31% of all registrations — highlighting a disparity in representation among minority groups.
- The South West showed a slower recovery in both donor and registration figures.
- A steady, if modest, drop in total donors between 2022 and 2024 suggests engagement could be waning post-pandemic.
- There is a growing divergence between registration and actual donor participation in some regions.

## Data Preparation Steps

### 1. Data Loading
- Loaded multiple datasets covering donors, registrations, ethnicity, region, and year into Power BI.
- Used CSV and Excel source files provided by NHSBT.

### 2. Data Cleaning
- Removed blank or null values and unnecessary rows.
- Standardized column names and formats.
- Converted data types for accuracy (e.g., dates, numbers).

### 3. Data Transformation
- Combined annual datasets using append queries for consistency.
- Standardized naming for regions and ethnic groups.

### 4. Unpivoting
- Unpivoted year-based columns to create a normalized structure for time-series analysis.
- Enabled comparative analysis across years.

### 5. Relationships and Measures
- Created relationships between year, ethnicity, and region tables.
- Developed custom DAX measures for:
  - Total Donors
  - Total Registrations
  - Donor to Registration Ratio
  - Year-over-Year Trends

### 6. Visualization
- Built a dynamic dashboard using slicers for year, region, and ethnicity.
- Included bar charts, line graphs, and KPI cards to highlight trends.

## Project Files

- `NHSBT Donor and Registration Analysis.pdf`: Visual summary of insights from the Power BI dashboard.

## Author

Paschal Uzoegwu  
Data Scientist |Data Analyst | Power BI Developer    
LinkedIn: [(https://www.linkedin.com/in/uzoegwu-paschal/)]

## Objectives

- Highlight trends in blood donor participation.
- Identify registration gaps in underrepresented communities.
- Support targeted outreach and awareness strategies through data insights.

---

Feel free to fork this repository, suggest improvements, or reach out for feedback and collaboration.
