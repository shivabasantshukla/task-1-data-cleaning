Task 1: Data Cleaning and Preprocessing
🔧 Objective
To clean and prepare a raw dataset by handling missing values, removing duplicates, formatting columns, and standardizing data for future analysis.

🗂 Dataset Used
File Name: marketing_campaign.xlsx.csv
Original Size: 2,240 rows × 29 columns
Final Size After Cleaning: 2,215 rows × 29 columns

🧹 Cleaning Steps Performed
Removed Duplicate Rows

Used Excel’s Remove Duplicates feature across all columns.

Handled Missing Values

Deleted 24 rows with missing Income.

Deleted 1 row with missing Response.

Used filter in Excel to find blanks and manually removed them.

Formatted Date Column

Converted Dt_Customer into uniform dd-mm-yyyy format using Excel’s Custom Date format.

Standardized Column Headers

Renamed all headers to lowercase.

Replaced spaces and camelCase with underscores (e.g., Year_Birth → year_birth, Marital Status → marital_status).

Verified and Fixed Data Types

Ensured numeric fields like income, year_birth, etc. were formatted as numbers.

Ensured dt_customer was properly formatted as a date column.

(Optional) Categorical Standardization

To be done in future steps: unify categories like education, marital_status using Find & Replace.

🛠 Tools Used

Microsoft Excel
Manual cleanup techniques


