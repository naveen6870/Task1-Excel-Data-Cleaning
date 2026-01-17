# Task 1 – Excel Data Cleaning & Formatting

## Objective
To clean and standardize a real-world dataset using Excel by identifying missing values, removing duplicates, correcting text inconsistencies, and validating data formats to prepare the data for analysis.

## Dataset
Netflix Movies and TV Shows dataset (CSV format).

## Tools Used
- Microsoft Excel

## Steps Performed
1. Imported raw CSV data and preserved original data in Raw_Data.xlsx
2. Created a separate working layer to avoid modifying raw data
3. Identified and analyzed missing values across key columns (director, cast, country, rating, date_added)
4. Documented data quality issues using a Data_Quality_Notes column
5. Checked for duplicates using show_id and title as primary keys
6. Standardized text columns using TRIM and PROPER functions
7. Validated date and numeric formats for consistency
8. Created a final Cleaned_Data sheet containing only cleaned values
9. Exported cleaned data in both Excel and CSV formats for further analysis

## Deliverables
- Raw_Data.xlsx
- Cleaned_dataset.xlsx
- cleaned_dataset.csv

## Key Learnings
- Real-world data often contains missing and inconsistent values
- Maintaining separate raw, working, and cleaned layers is a best practice
- Text standardization is essential for accurate analysis
- Documenting data quality issues improves transparency and reliability
