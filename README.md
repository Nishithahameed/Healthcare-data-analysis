# Healthcare-data-analysis
Healthcare Data Analysis and Insights

Data cleaning:

Checked the number of missing values marked with '?' in each column of the “Medical
Examinations” Table and "Hospitalization Details" Table. and replaced it with appropriate values using find and replace
Filled the missing values of ‘month’ with Sep and ‘year’ with its average rounded to the
nearest integer.
Determined the most frequently occurring values in the ‘smoker’, 'Hospital tier' and 'City
tier' columns, and filled the missing values accordingly.
'State ID' values are missing, filled them with 'Unknown' values

Data Transformation:

Splitted the ‘names’ column in the “Customer Names” Table into 3 meaningful columns,
‘Title’, ‘First Name’, and ‘Last Name’ using text to columns
Converted the "NumberOfMajorSurgeries" column in the “Medical Examinations” Table to
numerical data by replacing non-numeric characters with zero
corrected inconsistencies in the 'Heart Issues' and 'smoker' column
Created a new column named “Weight Status” and  “Diabetes Status” that categorizes BMI and hba1c into different
categories using nested if function
Merged ‘year’, ‘month’ and ‘date’ columns in the “Hospitalization Details” Table into one
column named ‘Date of Birth’ and formatted it in ‘DD-MMM-YYYY’ custom format.
Calculated the ‘Age’ of each customer based on their ‘Date of Birth’ and the date of
collection of the dataset given.
Formatted ‘charges’ column as currency ($).

Data Exploration, Analysis & Visualization:

Created a new sheet named “Healthcare", combine all three tables into one, using
Customer ID as the common column, utilizing VLOOKUP.
Analysis using Pie/Donut Chart, Column/Bar Chart, Line/Scatter Plot all these done using pivot chart
Finally created a healthcare analysis dashboard
Added slicers for the fields “Weight Status” and “Diabetes Status” to enable filtering across
all visualizations, supporting comparison of health outcomes and charges based on body
weight and diabetes condition.




