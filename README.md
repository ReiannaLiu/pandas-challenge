# pandas-challenge

## District Summary
This section of the Pandas Challenge involves performing necessary calculations and creating a high-level snapshot of the district's key metrics in a DataFrame. The following metrics will be included in the summary:

- Total number of unique schools
- Total number of students
- Total budget
- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Percentage of students overall passing (passing both math and reading)


## School Summary
In this part of the challenge, we will create a DataFrame that summarizes key metrics about each school. The following metrics will be included in the summary for each school:

- School name
- School type
- Total number of students
- Total school budget
- Per student budget
- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Percentage of students overall passing (passing both math and reading)


## Highest-Performing Schools (by % Overall Passing)
In this section, we will sort the schools by % overall passing in descending order and display the top 5 rows. The results will be saved in a DataFrame called "top_schools."

## Lowest-Performing Schools (by % Overall Passing)
In this part of the challenge, we will sort the schools by % overall passing in ascending order and display the top 5 rows. The results will be saved in a DataFrame called "bottom_schools."

## Math Scores by Grade
We will perform necessary calculations to create a DataFrame that lists the average math score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Reading Scores by Grade
In this section, we will create a DataFrame that lists the average reading score for students of each grade level (9th, 10th, 11th, 12th) at each school.

## Scores by School Spending
We will create a table that breaks down school performance based on average spending ranges (per student). We will use the provided code to create four bins with reasonable cutoff values to group school spending. The metrics to be included in the table are:

- Average math score
- Average reading score
- Percentage of students passing math
- Percentage of students passing reading
- Percentage of students overall passing (passing both math and reading)

## Scores by School Size
In this section, we will use the provided code to bin the per_school_summary based on school size (small, medium, or large) and create a DataFrame called "size_summary" that breaks down school performance based on school size.

## Scores by School Type
Finally, we will use the per_school_summary DataFrame to create a new DataFrame called "type_summary" that shows school performance based on the "School Type." The metrics included in this table are the same as those mentioned in the previous sections.
