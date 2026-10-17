# Data Cleaning Log

## 1. Whitespace
Problem: Extra spaces in text values.
Action: Removed leading and trailing spaces.
Alternative: Leave the spaces unchanged.

## 2. City Names
Problem: Inconsistent city spellings.
Action: Standardized known city names.
Alternative: Keep separate categories.

## 3. Numeric Values
Problem: Age and salary stored as text.
Action: Converted them into numeric values.
Alternative: Keep them as strings.

## 4. Missing Values
Problem: Missing ages and salaries.
Action: Kept missing values where information was unavailable.
Alternative: Replace missing salaries with zero.

## 5. Dates
Problem: Different date formats and invalid dates.
Action: Standardized valid dates and retained invalid dates as missing.
Alternative: Guess invalid dates.

## 6. Outliers
Problem: Implausible age and unusual salaries.
Action: Flagged suspicious values and investigated them.
Alternative: Delete every outlier automatically.

## 7. Duplicates
Problem: Potentially repeated employee records.
Action: Investigated similar records without automatically deleting them.
Alternative: Delete all repeated names.

## 8. Final Result
Exported the cleaned dataset to
cleaned_employee_dataset.csv.