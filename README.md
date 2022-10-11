# PyCity Schools - Analysis of Standardized Testing in a School District Using Pandas
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
## Conclusion
The Py City School District has 15 high schools, with enrollment size ranging from 427 students to 4976 students, with a total of 39,170 students. Interestingly, spending per student has an inverse relationship with testing grades; schools with lower budgets per student have higher overall math and reading scores leading to higher percentages of students passing their standardized tests in one or both subjects. School size also has a negative impact on testing averages, with the largest schools (over 2000 students) having an average of only 58.3% students passing both math and reading. Charters schools also fared significantly better than district schools, with 90.4% of charter school students passing overall, compared to 53.7% of district school students. All five top schools are charter schools, with all except one under 2000 students. All five bottom schools are district schools, each with total students well above 2000.

