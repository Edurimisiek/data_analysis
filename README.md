# data_analysis
EDA-SQL-drawio

# Employee Data Analysis and Flask API

This repository contains Python code for analyzing employee data and serving it through a Flask API.

## Steps Followed:
1. **Data Loading**:
   - Loaded employee data from a CSV file.
   - Displayed basic statistics and inspected the data.

2. **Data Analysis**:
   - Filtered and selected specific employees based on department, salary, and performance score.
   - Grouped the data by department and calculated average salary and experience.
   - Merged employee data with department-level information.

3. **Data Visualizations**:
   - Plotted various visualizations to understand the salary distribution, performance scores, and relationship between experience and salary.

4. **Flask API**:
   - Set up a Flask API to allow querying of employee data.
   - Endpoints for retrieving employee data, filtered employees, specific employees by ID, and aggregations by department.
   - API supports query parameter filtering and returning top performers based on performance score.

## How to Run the Code:
1. Install the necessary dependencies by running:
   ```bash
   pip install -r requirements.txt

