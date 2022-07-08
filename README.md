# School_District_Analysis
## Project Overview:
Analysis of school districts for State-Testing scores, including budgeting, and spending per student. 
Revising analysis to flag 9th grade Math and Reading scores from Thomas High School as NaN due to academic dishonesty, and rerun analysis for remaining schools in district.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Anaconda 4.13.10, Pandas 1.3.5

## Analysis Results

How is the district summary affected? The district as a whole held a strong average passing score and overall passing percentage in Math and Reading.  
How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
By removing the THS 9th grade scores for math and reading you see an honest display of testing scores. The scores reported lower without the inflated Thomas High School data.
![School Summary](https://user-images.githubusercontent.com/106544424/177901825-6839b515-d5fa-4422-b4a8-e6a5c95f82c5.png)

In replacing the tarnished 9th grade scores, I found the below results:
Math and reading scores by grade indicate math scores cluster mid-high 70's to low 80's percentile; while reading scores by grade cluster low-to-mid 80's percentile range.
For a 4-variable spread for spending per student: low (<$586) and mid ($586-630) returned similar testing results, both in averages and overall percentages. 
Spending in the mid-high ($631-645) range had a slight drop in scores, and in schools htat had a higher spending per student ($649-800) the scores and overall percentages took a large dip, with overall percentages dropping below passing. 
![Spending Range per student](https://user-images.githubusercontent.com/106544424/177901865-8afdfdbe-6e80-4629-b0ef-2634bc852cd9.png)


Analysis of scores by school size indicate that schools with medium student body size (between 1,000 and 1,999 students), performed slightly above small schools (<1,000 students), and well above larger school(>2,0000 students) sizes.
![Scores by School Size](https://user-images.githubusercontent.com/106544424/177901885-3bc45188-d2fb-42c0-9157-2cec2ca03877.png)

Results by school type indicate that Charter Schools have a higher average score for Math and Reading, as well as higher Passing Percentages. 
 ![Scores by School Type](https://user-images.githubusercontent.com/106544424/177901905-86178f1d-3782-4d9d-a72c-a68c9788d007.png)


## Summary
Summary: Four changes found in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:
Charter school have a greater success rate in testing. Mid-line budgeting and spending on students balanced out in positive tests results and passing percentages.
