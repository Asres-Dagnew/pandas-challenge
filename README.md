# pandas-challenge
## Instructions
Using Pandas and Jupyter Notebook, create a report that includes the following data. Your report must include a written description of at least two observable trends based on the data.
Hint: Check out the sample solution called PyCitySchools_starter.ipynb located in the .zip file to review the desired format for this assignment.
## District Summary
Perform the necessary calculations and then create a high-level snapshot of the district's key metrics in a DataFrame.
Include the following:
* Total number of unique schools
* Total students
* Total budget
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)
## School Summary
Perform the necessary calculations and then create a DataFrame that summarizes key metrics about each school.
Include the following:
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
## Highest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in descending order and display the top 5 rows.
Save the results in a DataFrame called "top schools".
## Lowest-Performing Schools (by % Overall Passing)
Sort the schools by % Overall Passing in ascending order and display the top 5 rows.
Save the results in a DataFrame called "bottom schools".
## Math Scores by Grade
Perform the necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.
## Reading Scores by Grade
Create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.
## Scores by School Spending
Create a table that breaks down school performance based on average spending ranges (per student).
Use the code provided to create four bins with reasonable cutoff values to group school spending.
Use pd.cut to categorize spending based on the bins.
Use the code provided to then calculate mean scores per spending range.
Use the scores above to create a DataFrame called spending summary.
Include the following metrics in the table:
* Average math score
* Average reading score
* % passing math (the percentage of students who passed math)
* % passing reading (the percentage of students who passed reading)
* % overall passing (the percentage of students who passed math AND reading)

## Scores by School Size
Use the code provided to create three bins with reasonable cutoff values to group school size.
Use pd.cut to categorize school size based on the bins.
Use the provided code to then calculate mean scores per size range.
Create a DataFrame called size summary that breaks down school performance based on school size (small, medium, or large).
## Scores by School Type
Use the per_school_summary DataFrame to create a new DataFrame called type_summary.
This new DataFrame should show school performance based on the "School Type".

## Summary of the Analysis
The district summary data frame shows that there are 15 schools with a total enrollment of 39,170 students. It also reveals that the percentage of students passing reading is higher than those passing math, suggesting that students generally perform better in reading than in math.

The school summary data frame shows that of the 15 schools, 7 are district schools and 8 are charter schools. The per school summary data frame further provides the total budget allocated to each school. According to the analysis, Bailey High School allocated the highest budget, while Holden High School allocating the lowest. In terms of budget per student, Huang High School allocated the most per student ($655), whereas Wilson allocated the least ($578). The summary data frame also demonstrates that students in schools with higher budgets per student tend to perform better in both reading and math compared to those in schools with lower budgets per student. Regarding school types, charter schools allocated more budget per student than district schools. Conversely, district schools had a higher total student enrollment than charter schools.

The top/bottom school summary data frame reveals that charter schools dominated the highest performing schools in all metrics (average, percentage, and overall reading and math scores), while district schools dominated the lowest performing schools.

## Conclusions
1. The spending summary indicates that schools with higher spending per student typically have higher average math and reading scores as well as higher percentages of students passing reading and math. These schools also tend to have better academic performance. This implies that better academic performance may result from higher spending per student.
2. According to the school size summary, smaller schools—those with fewer than 1000 students—generally have higher passing rates and average math and reading scores than larger ones. This suggests that, perhaps because of things like smaller class sizes and more individualized attention for each student, smaller schools may offer a more favorable learning environment.
These findings can inform future policy makers by shedding light on the ways in which various elements, like school size and spending per student, can affect academic performance.

## References
Class Materials




