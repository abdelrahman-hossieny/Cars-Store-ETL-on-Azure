# end-to-end-pipeline-on-azure


# Azure Data Transformation Project

This project utilizes a set of Azure tools to transform data and load it into Azure Data Lake Gen 2. The project includes the following components:

## Tools Used

1. **Azure Database**: To create the following database tables:
   - `dbo.cars`
   - `dbo.countries`
   - `dbo.movies`

2. **Azure Data Lake Gen 2**: To store raw data from the database and the final data after transformation.

3. **Azure Data Factory**: To create a pipeline for extracting data from the tables:
   - Utilized `Lookup Activity` to extract data.
   - Used `For Each Activity` within it with `Copy Activity` for copying operations.

4. **Azure Databricks**: To clean and transform the data using the following steps:
   - Handle Missing Values
   - Fill Missing Values with Default Values
   - Data Type Casting
   - Remove Duplicates
   - Column Renaming
   - Filter Data
   - Add New Columns
   - String Transformations
   - Join, Aggregate, and Group Data Tables


![Blue Gradient Technology Zoom Virtual Background](https://github.com/user-attachments/assets/6747ddbf-4bcc-4b7d-bf28-440d85a37c22)


![Screenshot 2024-09-22 033347](https://github.com/user-attachments/assets/80f0f50d-1321-4e7b-b34e-888304c49441)


