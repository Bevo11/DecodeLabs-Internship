# Data Cleaning & Preparation - DecodeLabs Project 1

## Project Overview
This repository contains the results of **Project 1: Data Cleaning & Preparation** from the Data Analytics Internship at DecodeLabs (Batch 2026). The primary goal of this project was to transform a raw, unstructured dataset into a "Gold Standard" clean dataset suitable for analytical modeling.

## Project Objectives
- **Data Integrity Audit**: Identifying and addressing missing values and null entries.
- **Deduplication**: Removing redundant records to ensure each `OrderID` represents a single, unique transaction.
- **Data Standardization**: Correcting formats for dates, pricing, and categorical variables to ensure consistency.

## Key Actions Taken
1. **Missing Value Handling**: Evaluated null patterns and applied appropriate imputation techniques (Mean/Median/Mode) based on data distribution.
2. **Elimination of Redundancy**: Used `GROUP BY` logic to filter and remove duplicate transaction entries, ensuring every `OrderID` is unique.
3. **Format Normalization**: Standardized column formats to ensure that date-time stamps and currency values are correctly recognized by analytical tools.

## Repository Contents
- `Dataset for Data Analytics.xlsx`: The original, raw data file.
- `Cleaned_Dataset.xlsx`: The final, processed dataset ready for EDA.
- `README.md`: Project documentation.

---
*Created by [Your Name] | Data Analytics Intern, DecodeLabs 2026*