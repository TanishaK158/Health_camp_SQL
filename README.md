# Health_camp_SQL
Data Analysis on the dataset of a health checkup camp 

BASIC LEVEL QUERIES
what is the count of the pateint in the age group of 0-20,20-40,40-60 and 60 above? .
Write a query to count the number of records in the Health_Camp_Detail table.
Write a query to group patients by gender and count the number of patients in each group from the Patient_Profile table.
Write a query to select all patients and order them by age in descending order from the Patient_Profile table.


INTERMEDIATE LEVEL QUERIES
Write a query to retrieve the Patient_ID, Patient_Name, and Camp_Name for all patients, including those who have not attended any health camp.
Write a query to select the Patient_ID, Patient_Name, and the name of the camp they attended using a subquery in the SELECT clause.
Write a query to create a CTE that counts the number of patients for each camp and then use it to select the Camp_Name and Total_Patients.
Write a query to assign a rank to each patient based on their age in descending order using the RANK() window function.

ADVANCED LEVEL QUERIES
Write a query to retrieve the Patient_ID, Patient_Name, and Camp_Name for all patients and camps, including those with no matches
Write a query to count the number of patients in each camp, including subtotals for each camp and gender using ROLLUP.
Write a stored procedure to retrieve all patients who attended a specific camp based on the Camp_ID paramete
Write a transaction to update the age of a specific patient and ensure the transaction is rolled back if any error occurs.
