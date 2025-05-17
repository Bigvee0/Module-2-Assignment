# Salary Data Processing Assignment

## Overview
This Jupyter Notebook processes salary data, retrieves employee details, exports them to a CSV, and zips the output. It also includes an R script to unzip and display the data.

## Requirements
- Python 3.x with `pandas`, `csv`, `os`, and `zipfile` libraries.
- R with `readr` and `utils` packages.
- Jupyter Notebook with R kernel configured.
- `salary_data.csv` in the same directory as the notebook.

## Instructions
1. Place `salary_data.csv` in the same directory as the notebook.
2. Open `Updated_Salary_Data_Assignment.ipynb` in Jupyter Notebook.
3. Run the cells in order to:
   - Import the salary data.
   - Create a dictionary of employee details.
   - Use `get_employee_details("Employee Name")` to fetch details.
   - Use `export_employee_to_zip("Employee Name")` to export and zip a profile.
   - Run the R cell to unzip and display the data (ensure R is configured).
4. The output will be a zipped file (`Employee_Profile.zip`) containing the employee’s CSV profile.

## Notes
- Ensure R is installed and configured in your Jupyter environment for the R cell to work.
- Replace `John_Doe_profile.csv` in the R script with the actual employee’s CSV filename.
