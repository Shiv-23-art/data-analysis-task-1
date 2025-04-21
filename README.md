## data-analysis-task-1
Internship Task 1: Data Cleaning and Preprocessing using Excel

## Objective:
Clean and preprocess a raw sales dataset using **Microsoft Excel** by handling missing values, duplicates, and inconsistent formats.

## Tools Used:
- Microsoft Excel

## Data Cleaning Steps Performed:
1. **Standardized column headers** – Converted to lowercase and replaced spaces with underscores.
2. **Handled missing values** – Replaced or removed blank/missing postal codes, rplaced blank cells with "Unknown" and had some difficulties in handling postal codes.
3. **Removed duplicates** – Used Excel’s "Remove Duplicates" feature to ensure unique rows.
4. **Filtered invalid records** – Removed entries with zero or negative quantity or sales values.
5. **Formatted columns** – Ensured date columns were in proper date format (`dd-mm-yyyy`).
6. **Created new columns:**
   - `total_cost` = `quantity_ordered` × `price_each`
7. **Added a new derived column** – `region` based on the country (e.g., Europe, North America, Asia).

## Files Included:
- `cleaned_enhanced_sales_data.xlsx` – Final cleaned and enriched dataset using Excel

## Notes:
This task was completed as part of a Data Analyst Internship to demonstrate hands-on data cleaning skills using Excel without any code. All transformations were performed manually using Excel formulas and tools.
