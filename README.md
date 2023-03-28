# Panda_Challenge
Education Data Analysis with Pandas and Jupyter Notebook
In this project, we will use Pandas and Jupyter Notebook to analyze education data. The data consists of information about schools, students, budgets, and academic performance. The goal is to create several DataFrames that summarize the key metrics about each school and the district as a whole.

Required Libraries
Before we start, make sure that you have the following libraries installed:

Pandas
Jupyter Notebook
Dataset
The dataset is provided in a CSV file named schools_complete.csv which contains information about schools and students.

Project Tasks
District Summary: Create a high-level snapshot of the district's key metrics in a DataFrame. Include the following:

Total number of unique schools
Total students
Total budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
School Summary: Create a DataFrame that summarizes key metrics about each school. Include the following:

School name
School type
Total students
Total school budget
Per student budget
Average math score
Average reading score
% passing math (the percentage of students who passed math)
% passing reading (the percentage of students who passed reading)
% overall passing (the percentage of students who passed math AND reading)
Highest-Performing Schools (by % Overall Passing): Sort the schools by % Overall Passing in descending order and display the top 5 rows. Save the results in a DataFrame called "top_schools".

Lowest-Performing Schools (by % Overall Passing): Sort the schools by % Overall Passing in ascending order and display the top 5 rows. Save the results in a DataFrame called "bottom_schools".

Math Scores by Grade: Create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Reading Scores by Grade: Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

Scores by School Spending: Create a table that breaks down school performance based on average spending ranges (per student). Use the code provided to create four bins with reasonable cutoff values to group school spending. Use pd.cut to categorize spending based on the bins. Use the scores to create a DataFrame called spending_summary.

Scores by School Size: Bin the per_school_summary by school size. Create a DataFrame called size_summary that breaks down school performance based on school size (small, medium, or large).

Scores by School Type: Use the per_school_summary DataFrame to create a new DataFrame called type_summary. This new DataFrame should show school performance based on the "School Type".

Conclusion
In conclusion, this project involves analyzing education data using Pandas and Jupyter Notebook. We will create several DataFrames that summarize key metrics about each school and the district as a whole. By completing this project, we will gain experience in data manipulation and analysis using Pandas and Jupyter Notebook.
