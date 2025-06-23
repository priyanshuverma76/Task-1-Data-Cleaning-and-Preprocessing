# Pharma monthly Sales Data Cleaning (Excel)

This project demonstrates basic **data cleaning and preprocessing** using Microsoft Excel on a dataset named `salesmonthly.csv`.
##  Cleaning Tasks Performed

1. **Handled Missing Values**
   - Used Excel filters to identify blank cells
   - Filled missing data where possible in this no missing are values are there 

2. **Removed Duplicates**
   - Used Excel’s "Remove Duplicates" under Data tab as there no duplicate values are present
    
3. **Standardized Text Values**
   - Standardized gender values (e.g., "Male", "Female") as here medicines names are there 
   - Removed extra spaces using `TRIM()` is this data set no extra spaces values are there but if any other data set if values have extra space then we use trim formula
   - Applied consistent casing using `PROPER()`
  
4. **Date Format Consistency**
   - Converted all date columns to `dd-mm-yyyy` format
  
5. **Cleaned Column Names**
   - Renamed headers to lowercase and replaced spaces with underscores (in this data set are data is in number )

   ## Tools Used

- Microsoft Excel (Data tab, functions: `TRIM`, `PROPER`, `TEXT`, `INT`)
- Basic file handling

     
