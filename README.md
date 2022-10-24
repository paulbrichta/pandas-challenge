# pandas-challenge

A script that analyzes student and school data and calculates:

District Summary
- The total number of unique schools
- The total number of students
- The total budget
- The average (mean) math score
- The average (mean) reading score
- The percentage of students who passed math
- The percentage of students who passed reading
- The percentage of students that passed both math and reading
- Creates a new DataFrame for the above calculations called district_summary


School Summary
- The school type
- The total student count
- The per capita spending
- The average test scores
- The number of schools with math scores of 70 or higher
- The number of schools with reading scores of 70 or higher
- The schools that passed both math and reading with scores of 70 or higher
- The passing rates
- Creates a new DataFrame for the above calculations called per_school_summary


Highest-Performing Schools by Percentage of Overall Passing
- Sorts the schools by % Overall Passing in descending order
- Saves the results to a DataFrame called top_schools
- Displays the first 5 rows


Lowest-Performing Schools by Percentage of Overall Passing
- Sorts the schools by % Overall Passing in ascending order
- Saves the results to a DataFrame called bottom_schools
- Displays the first 5 rows


Math Scores by Grade
- Separates the data by grade
- Groups by "school_name" and take the mean of each
- Selects only the math_score
- Combines each of the scores above into single DataFrame called math_scores_by_grade


Reading Scores by Grade
- Separates the data by grade
- Groups by "school_name" and take the mean of each
- Selects only the reading_score
- Combines each of the scores above into single DataFrame called reading_scores_by_grade


Scores by School Spending
- Uses pd.cut to bin the data by the spending ranges
- Calculates the averages
- Creates the spending_summary DataFrame using the binned and averaged spending data


Scores by School Size
- Uses pd.cut to bin the data by the school sizes
- Calculates the averages
- Creates the size_summary DataFrame using the binned and averaged size data


Scores by School Type
- Groups the per_school_summary DataFrame by "School Type" and averages the results
- Selects the new column data
- Creates a new DataFrame called type_summary that uses the new column data


Written Report
A cohesive written report that:
- Summarizes the analysis
- Draws two correct conclusions or comparisons from the calculations
