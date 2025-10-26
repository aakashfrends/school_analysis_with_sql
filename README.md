# school_analysis_with_sql
A structured SQL project demonstrating database design, data analysis, and query optimization using PostgreSQL for school record management.
## 📘 Overview
<br>
This SQL project analyzes student performance data from a school.  
<br>
The dataset includes 900 student records with marks across five subjects and demographic details.
<br>
This project contains SQL queries used to analyze student performance and demographic data 
<br>
stored in a school_records table. The data was imported from a CSV file (/tmp/school23.csv).
<br>
**Database Setup**
<br>
Create Database: create database school; 
<br>
Table Structure: The school_records table includes fields like roll_number,
<br>
name, admission_year, grade, subject marks (hindi_marks, english_marks, etc.)
<br>
and calculated fields like total_marks and percentage. 
<br>
Data Import: Data is loaded using a COPY command from /tmp/school23.csv.
<br>
**Key Analysis Queries**
<br>
The provided queries cover common educational data analysis tasks:
<br>
Analysis Topic,Example Query Result
<br>
Top Performers,Students with >70% and Top 5 students overall. 
<br>
Demographics,"Counts of students per city , by Category , and Male vs Female count. "
<br>
Performance Metrics,,Average marks per subject and Average percentage by standard. 
<br>
Specific Insights,,"City-wise toppers , Highest score per category , and Students failing English (<33 marks). "
<br>
Sub-Query Analysis,Students scoring above their standard's average percentage. 
<br>
**How to Use**
  <br>
Ensure a PostgreSQL environment is set up.
<br>
Execute the database and table creation script.
<br>
Ensure your data file (school23.csv) is correctly placed at /tmp/.
<br>
Execute the COPY command to load the data.
<br>
Run any of the analysis queries in the file.
