# pandas-challenge
> Module 4 Challenge - Pandas
This project will showcase coding using Pandas via Jupyter notebook


## PyCitySchools Instructions
Using Pandas and Jupyter Notebook:
* Create a report that includes the following data. 
* Your report must include a written description of at least two observable trends based on the data.

### District Summary
Create a high-level snapshot of the district's key metrics in a DataFrame, including the following:

* Total schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### School Summary
Create a DataFrame that summarizes key metrics about each school, including the following:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Highest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the top-5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Lowest-Performing Schools (by % Overall Passing)
Create a DataFrame that highlights the bottom-5 performing schools based on % Overall Passing. Include the following metrics:

* School name
* School type
* Total students
* Total school budget
* Per student budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Math Scores by Grade
Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

### Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student). Use your judgment to create four bins with reasonable cutoff values to group school spending. Include the following metrics in the table:

* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

### Scores by School Size
Create a table that breaks down school performance based on school size (small, medium, or large).

### Scores by School Type
Create a table that breaks down school performance based on school type (district or charter).

---


## PyCitySchools Code Theory
1. First, confirm the source data is placed in the proper "Resource" folder
2. Check for the data types for each column
3. Check the CSVs for inconsistancies: extra spaces in headers, empty rows/columns, incomplete rows, wrong datatypes, duplicate entries to be consolidated, (using `.head()`command).
4. Prep scripts to clean up the issues found in #2 above.
5. Merge the two data sets together and show a sample.
6. Do the calculations: note that some calculations will only need to use one dataset (ex: since the "budget" amounts are static for each school, only that dataset is used). Otherwise the math can be done from the joined dataset.
7. Format the output - currency, decimals, etc

The hardest thing I found was trying to test in a cell and then keeping track of the information as you have to continuously scroll back and forth.  In this assignment, my code is VERY messy.... xD

---
Assignments and other documentation sourced from the Georgia Tech Boot Camp, Summer/Fall 2022
