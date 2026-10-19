# ServiceNow - Import Data Using Transform Maps (Spreadsheet)

## 1. Introduction
This project demonstrates how to import spreadsheet data into ServiceNow using Import Sets and Transform Maps.

The imported data is validated, transformed, and transferred into a target table.

## 2. Objectives
- Import spreadsheet data into ServiceNow.
- Create an Import Set Table.
- Configure a Transform Map.
- Map source fields to target fields.
- Validate imported records.
- Prevent duplicate records using Coalesce.

## 3. Tools and Technologies
- ServiceNow Developer Instance
- Microsoft Excel / CSV
- Import Sets
- Transform Maps
- GitHub

## 4. Sample Spreadsheet Fields
The spreadsheet contains employee information, including:

- Employee ID
- Name
- Email
- Department
- Location

## 5. Project Workflow

### Step 1: Prepare the Spreadsheet
Create an Excel or CSV file containing employee records.

### Step 2: Load Data
Upload the spreadsheet using the ServiceNow Load Data feature.

### Step 3: Create an Import Set Table
Store the uploaded spreadsheet records in a temporary import table.

### Step 4: Create a Transform Map
Connect the source Import Set Table to the target table.

### Step 5: Configure Field Mapping
Map each source field to its corresponding target field.

### Step 6: Configure Coalesce
Use a unique field to identify existing records and avoid duplicates.

### Step 7: Transform Data
Run the transformation to insert or update records.

### Step 8: Validate Results
Verify that the records have been imported correctly.

## 6. Benefits
- Reduces manual data entry.
- Saves time during data migration.
- Improves data consistency.
- Supports automatic field mapping.
- Helps prevent duplicate records.

## 7. Expected Outcome
Spreadsheet records are imported into ServiceNow and transferred to the target table using a Transform Map.

## 8. Conclusion
This project demonstrates how Import Sets and Transform Maps simplify spreadsheet data migration in ServiceNow.
