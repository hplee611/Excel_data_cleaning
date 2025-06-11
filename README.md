# Excel_data_cleaning & Dashboard Project
This project demonstrates Excel-based data cleaning, transformation, and basic dashboard creation. The raw dataset was manually processed, and a simple interative summary was generated using a Pivot Table and Dashboard layout.

---

## Files
- `Excel Project Dataset.xlsx`
  Contains all sheets:
  - `Working Sheet` - original + cleaned dataset
  - `Pivot Table Sheet` - summary view using pivot table
  - `Dashboard Sheet` - interavtive visualization panel
 
---

## Data Cleaning Steps

1. **Removed Duplicates**
   - Identified and removed any duplicate rows
     
2. **Standardized Categorical Data**
   - Replaced shorthand codes with meaningful values:
     - Gender: `M` -> `Male`, `F` -> `Female`
     - Marital Status: `M` -> `Married`, `S` -> `Single`

3. **Formatted Income Data**
   - Converted `Income` column to currency format
   - Removed decimal points for clarity

4. **Created Age Brackets**
   - Transformed numerical `Age` into categorical bins:
     - `Age < 32` -> `Young`
     - `Age 32-54` -> `Adult`
     - `Age > 54` -> `Old`

---

## Pivot Table Summary
- Used Excel's Pivot Table to create grouped summaries
- Analyzed data by categories such as Gender, Commute Distance, and Age Bracket

---

## Dashboard
- A basic dashboard was created on the `Dashboard` sheet
- Combines charts and pivot summaries for quick insight

---

## Purpose
This project showcases my ability to:
- Clean and preprocess raw Excel data manually
- Perform basic categorization and formatting
- Summarize findings with Pivot Tables
- Build a simple dashboard for stakeholders

---

## Tools Used
- Microsoft Excel
  - Replace Tool (`Ctrl + H`)
  - Format Cells
  - Pivot Tables
  - Dashboard Elements (Charts, Filters, Layout)
