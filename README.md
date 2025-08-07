# Excel-data-cleaning-project
Cleaned and organized customer transaction data using Excel for analysis readiness

# Microsoft Excel Data Cleaning Project

## Project Overview
The objective of this project was to clean and organize a raw dataset using Microsoft Excel to make it analysis-ready. This involved correcting formatting issues, removing duplicates, handling missing values, and ensuring consistency for accurate future analysis.

## Tools Used
- Microsoft Excel

## Dataset Description
The dataset consisted of customer transaction records with the following columns:
- Date
- ID
- Name
- Region
- Rating
- Product
- Quantity
- Price per Unit

##  Data Cleaning Steps

1. Trimmed Extra Spaces
   - Used the TRIM() function to remove unnecessary spaces in the “Names” column.

2. Corrected Inconsistent Formatting
   - Unified inconsistent spacing and capitalization.
   - Adjusted numerical formatting for currency and date fields.

3. Removed Duplicates
   - Applied Excel’s “Remove Duplicates” tool across selected columns to eliminate redundant records.

4. Handled Missing or Invalid Values
   - Replaced blank and placeholder values like inf with N/A or 0 using Find and Replace (Ctrl + H) in the “Region” and “Price Per Unit” columns.

## ✅ Final Outcome
- The dataset was successfully cleaned and is now consistent and ready for analysis in tools like Power BI or Python.

## 🔗 Link to Cleaned Dataset
[Google Sheets Link](https://docs.google.com/spreadsheets/d/1VTao2g8sMZ-waix7vGFqcxKdYK1SZR6R/edit?usp=drive_link&ouid=103402040859827038183&rtpof=true&sd=true)
