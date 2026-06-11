
# Data Quality Report

## Overview

Before starting the analysis, all available datasets were reviewed to understand their structure, quality, and completeness. The objective was to identify any issues that could affect the accuracy of the analysis and future modeling work.

## Missing Values

A review of the datasets showed that some columns contained missing values. The amount of missing data varied across datasets. These missing values were examined carefully to determine whether they represented data collection issues or valid business situations.

## Duplicate Records

The datasets were checked for duplicate and duplicate-like records. Customer identifiers and transaction records were reviewed to ensure that the same information was not counted more than once during the analysis.

## Outlier Analysis

Several numerical variables showed unusually high or low values compared to the rest of the data. These observations were investigated to determine whether they reflected genuine customer behavior or possible data-entry errors.

## Data Consistency Checks

Column formats and data types were reviewed to ensure consistency across datasets. Key fields used for joining tables were validated before combining the data for analysis.

## Join Validation
Customer, order, support ticket, and activity datasets were merged using the appropriate identifiers. Record counts were compared before and after the joins to identify any potential mismatches or missing links between datasets.

## Recommendations
-Introduce automated checks for missing values during data ingestion.
-Monitor duplicate records regularly.
-Review extreme values before using the data for business decisions.
-Validate customer identifiers before merging datasets.
-Establish routine data-quality monitoring to maintain reliability over time.

## Conclusion
Overall, the datasets were suitable for analysis after performing the required quality checks. The identified issues were documented and considered during the exploratory analysis phase.
