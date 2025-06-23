Data Cleaning Process
The raw dataset (customer_personality_large_raw.xlsx - Sheet1.csv) contained several inconsistencies that were addressed to prepare the data for analysis. The final, cleaned dataset is customer_personality_large_raw.xlsx - Sheet2.csv.

The following data cleaning and transformation steps were performed:

1. Gender Column (Gender)
Standardized Values: The column contained multiple representations for the same gender (e.g., M, male, FEMALE, JEFEMALEFEMALErey male). These were standardized to a consistent format: Male and Female.

Corrected Errors: Obvious data entry errors were corrected to their appropriate gender categories.

2. Country Column (Country)
Standardized Naming: Inconsistent country names were unified. For example, usa and USA were both changed to United States.

Corrected Casing: Capitalization was made consistent across all country names (e.g., china was changed to China).

Handled Nulls: Null string values were removed and replaced with blank cells to represent missing data correctly.

3. Signup Date Column (Signup Date)
Unified Date Format: The column contained mixed date formats (e.g., mm/dd/yy and mm-dd-yyyy). All dates were parsed and converted into a single, consistent DD/MM/YYYY format. This ensures accurate chronological sorting and time-based analysis.

4. Age and Income Columns
Handled Nulls: Null string values in the Age and Income columns were replaced with blank cells, ensuring these columns are treated as numerical and that missing values are handled properly during analysis.

These cleaning steps ensure data quality, consistency, and reliability, forming a solid foundation for any subsequent exploratory data analysis, visualization, or modeling.
