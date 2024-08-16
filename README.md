# Data Analysis and Reporting

## Overview

This repository includes two data analysis exercises that focus on comparing datasets, identifying discrepancies, and analyzing various trends and patterns. The exercises utilize Python's `pandas` library for data manipulation and `openpyxl` for Excel file operations. Insights from these analyses are visualized using various plotting techniques, and results are summarized in reports.

## Exercise #1: Data Comparison and Reporting Missing Data

### Objective
Compare two datasets to identify discrepancies and missing records. The analysis involves filtering data, comparing columns for mismatches, and generating an Excel report.

### Files and Data
- `../data/Exercise #1A.xlsx`: Internal dataset.
- `../data/Exercise #1B.xlsx`: Acacia dataset.
- `../output/acacia-data-discrepancies.xlsx`: Output file containing discrepancies and missing records.

### Key Operations
- Load data from Excel files.
- Filter records based on specified criteria.
- Identify missing records and data mismatches.
- Generate an Excel report with discrepancy details and an email template for reporting findings.

## Exercise #2: Analysis Insights

### Objective
Analyze various aspects of application outcomes, client demographics, and processing times to uncover trends and correlations. The analysis includes visualizing data with box plots, scatter plots, heatmaps, and histograms.


### Files and Data
- `../data/Exercise #2.xlsx`: Subpractice dataset.

### Key Operations
- **Processing Time Analysis**: Analyze processing times by outcome using box plots.
- **Client Age Analysis**: Explore correlations between client age and application outcomes using scatter plots.
- **Geographic and Demographic Influences**: Assess the impact of court location and country of origin on application outcomes using heatmaps.
- **Processing Times Over Time**: Investigate trends in processing times and case numbers using heatmaps and line charts.
- **Pending Cases Analysis**: Examine the distribution of processing times for pending and resolved cases using histograms.
- **Application Types**: Analyze denial rates by application type using bar charts.
