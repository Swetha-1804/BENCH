
# DBT Weekly Assessment - Gym Management

## Project Overview
This project demonstrates data transformation using
dbt and Snowflake.

## Technologies Used
- Snowflake
- dbt Cloud
- GitHub
- SQL
- YAML

## Project Implementation

### 1. Source Ingestion
- Loaded CSV data using dbt seeds.
- Configured source definitions using YAML.

### 2. SCD Type 2 Implementation
- Implemented dbt snapshots.
- Used the check strategy on the STATUS column.
- Maintained historical records.

### 3. Intermediate Layer
- Created intermediate models.
- Generated surrogate keys using dbt_utils.
- Applied business transformations using macros.

### 4. Fact Table
- Created fact models.
- Implemented fee calculations.
- Configured materializations.

### 5. Data Testing
- Implemented generic tests.
- Implemented singular tests.
- Validated data quality.

## Author
Swetha

## Project Status
In Progress
