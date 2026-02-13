# Hospital & Pharmacy Data Analysis – Power BI Project

<img width="881" height="501" alt="image" src="https://github.com/user-attachments/assets/f08cdbda-baf0-4005-8787-decf7c183333" />


## Assignment Overview

This project was completed as part of a Power BI data analysis assignment focused on a county referral hospital. The goal was to **clean**, **model**, **analyze**, and **visualize** messy healthcare data from multiple departments to support hospital management decision-making.
As a Junior Data Analyst, the objective was to transform raw hospital and pharmacy data into meaningful insights through a structured Power BI workflow.

## Project Objectives

The hospital management sought answers to the following key questions:

- Which diseases are most common across counties?

- Does a higher number of patient visits always lead to higher pharmacy revenue?

- Which departments generate the highest pharmacy costs?

- Are there age groups that consume more medication than others?

- Are some diagnoses associated with longer hospital stays but lower pharmacy spending?

## Data Preparation & Modeling

The provided data was messy and sourced from multiple departments. The following steps were performed:

Data cleaning in Power Query:
- Removed duplicates and null values
- Standardized column names
- Corrected data types (dates, numeric fields, categorical fields)
- Created relationships between tables (Visits, Pharmacy, Departments, Counties)

Built calculated measures using DAX:

- Total Visits
- Total Pharmacy Revenue
- Average Length of Stay
- Total Cost by Drug Category

The final data model followed a structured relational design to support accurate reporting and filtering.

## Dashboard Features

The final Power BI dashboard includes:

### KPI Cards

- Total Visits
- Total Pharmacy Revenue
- Average Length of Stay

### Visualizations

- Disease trends over time
- Pharmacy cost breakdown by drug category
- County comparison analysis
- Department-level performance
- Relationship between patient visits and revenue

### Interactive Slicers

- County
- Diagnosis
- Visit Date

These interactive elements allow management to dynamically filter and explore performance metrics.

## Key Insights Summary

1. Revenue is strongly influenced by patient visit volume.
2. Certain diseases (e.g., malaria and chronic conditions) drive higher pharmacy costs.
3. Disease patterns show seasonal variation.
4. Some departments contribute disproportionately to total pharmacy spending.
5. County-level differences highlight potential resource allocation opportunities.
6. Short average length of stay (1.41 days) indicates efficient patient turnover.

## Deliverables

This project includes:

- Cleaned and modeled Power BI report
- One-page executive dashboard
- Written insights report (400–600 words)

## Tools Used

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling Techniques

## Project Outcome

This analysis demonstrates how structured data cleaning, proper modeling, and thoughtful visualization can transform raw hospital data into actionable insights that support operational efficiency, cost management, and strategic planning.
