# Analysis of Standardized Testing in Schools Using Pandas
This project uses pandas to analyze standardized testing data across high schools in a school district. The results are calculated by district and at school level, with additional analyses of data stratified by spending per student, school size, and school type.
## Dependencies
* pandas
* reduce
## Environment
PythonData (Python 3.7.7)
## Data
Two datasets in CSV format are provided for analysis with the following fields:
* schools_complete.csv
  * School ID
  * school_name
  * type
  * size
  * budget
* students_complete.csv
  * Student ID
  * student_name
  * gender
  * grade
  * school_name
  * reading_score
  * math_score
## Analysis
Analyses are conducted to output the following information to dataframes:
* District Summary
  * Total number of schools
  * Total number of students
  * Total budget
  * Average math score
  * Average reading score
  * % of students with a passing math score (>=70)
  * % of students with a passing reading score (>=70)
  * % of students with a passing math AND reading score (>=70)
* School Summary
  * School name
  * School type (i.e. district, charter)
  * Total students
  * Total school budget
  * Per student budget
  * Average math score
  * Average reading score
  * % of students with a passing math score
  * % of students with a passing reading score (>=70)
  * % of students with a passing math AND reading score (>=70)
* Top Performing Schools (by overall % of students passing)
* Bottom Performing Schools (by overall % of students passing)
* Average math scores by grade per school
* Average reading scores by grade per school
* Average scores and % of students passing by ranges of school spending per student
* Average scores and % of students passing by school size
* Average scores and % of students passing by school type

