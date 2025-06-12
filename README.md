# HealthTech Analytics – Using SQL & Python for Data-Driven Healthcare Decisions
 
## Scenario:
HealthTech Analytics is a health data startup working with hospitals to analyze patient and treatment data for improving care and operational efficiency.
 
### They have provided your data science team access to a relational database with the following tables:
 
- patients(patient_id, name, gender, birth_date, city)
- visits(visit_id, patient_id, visit_date, doctor_id, diagnosis_code)
- doctors(doctor_id, name, department)
- treatments(treatment_id, visit_id, treatment_name, treatment_cost)
- diagnoses(diagnosis_code, diagnosis_description)
 
## Instructions:
Create a Jupyter Notebook to perform the following tasks using Python and SQL. Use sqlite3 to connect and query the data.
 

### 1. Data Setup & Exploration 
Connect to the database using Python.
Write a query to list the number of patients by city.
Display results using a bar chart (using matplotlib or seaborn).
 
### 2. Diagnosis Trends by Department 
Write a SQL query to calculate how many diagnoses are made per department.
Join the necessary tables (visits, doctors, and diagnoses) and present the results in a table.
Interpret the results briefly in Markdown.
 
### 3. Cost Analysis per Patient
Write a query to calculate the total cost of treatments per patient.
Identify the top 5 patients by total spending.
Display a horizontal bar chart of their names and spending.
 
### 4. Data Quality & Anomaly Detection 
Write a query to identify:
Duplicate patient records (same name, gender, and birth_date).
Treatments with zero or negative cost.
Provide Python-based suggestions for handling these anomalies.
 
### 5. Advanced Insight – Frequent Patients & Visit Patterns 
Identify patients with more than 5 visits in the last year.
Analyze visit frequency across months.
Create a line graph to show visit trends (monthly count).
