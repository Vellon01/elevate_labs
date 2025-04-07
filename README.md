# elevate_labsData cleaning and preprocessing using python(Pandas)

Cleaning Steps
Loading the Data

Imported the dataset using pandas and loaded it into a DataFrame df.
Initial Data Exploration
Used .describe() to generate statistical summary.
Used .info() to check column types, non-null counts, and general structure.

Handling Missing Values
Checked for any missing (null) values across all columns with .isnull().sum().
No specific handling of missing values was shown, implying no missing data or need for imputation.
Removing Duplicates
Dropped duplicate rows using .drop_duplicates() to ensure unique records.

Standardizing Values
Gender column: Converted all gender values to uppercase and removed any leading/trailing whitespace.
Dates:Converted ScheduledDay and AppointmentDay columns to proper datetime format for easier time-based analysis.
Standardized column names:Stripped spaces.
Converted all names to lowercase. Replaced spaces with underscores for easier referencing in code.
Data Type Conversion
Age:Converted the age column to integer (Int64).
Neighbourhood:Converted the neighbourhood column to string type.