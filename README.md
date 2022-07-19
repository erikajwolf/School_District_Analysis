# School District Analysis
maria is chief data scientist ny city school district
tasked with prepping standardized test data
insights used to inform discussed and decisions at schhool district level
task: aggregate data and show trends in performance
![Voting_Summary](Voting_Summary.png)
## Overview
### Maria & The District Data
Maria, the Chief Data Scientist at a New York City school district, has been tasked with aggregating and analyzing standardized test score data for all the high school students in this district. She takes a look at grades 9-12 at various high schools in the district, and has analyzed the data to identify trends in school performance. This information will help the school board and Superintendent make informed decisions regarding the school budgets and priorities. 

### Academic Dishonesty
After Maria's initial aggregation and analysis, it came to light that 9th grade students at Thomas High School had committed academic dishonesty, voiding their test scores. Because of this, Maria had to separate their data and recalculate all the analysis to exclude Thomas High School's 9th graders.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions.

- **How is the district summary affected?** 

- **How is the school summary affected?** 

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?** Thomas High School becomes the #1 performer after excluding 9th grade scores (at 97% overall passing). They were originally at 90.1% overall passing.
**How does replacing the ninth-grade scores affect the following:**
- **Math and reading scores by grade** Math and reading scores did not change for Grades 10, 11, and 12. The only change after the initial analysis is the ouput of the 9th grade scores. Originally 83.6 for math, 83.7 for reading. Now: NaN.
- **Scores by school spending** Thomas High School, after excluding 9th graders' scores, currently exceeds the average math and reading scores at 83.4 and 83.9 respectively. the $631-$645 spending bucket's scores are 78.5 and 81.6. Before excluding the 9th graders, THS's scores were 83.4 and 83.9, still exceeding the spending bucket's average at 78.5 and 81.6.
- **Scores by school size** Thomas High School is a medium sized school (1000-1999 students). After excluding the 9th graders, it falls perfectly in the average reading scores and just a hair short of the average math score--THS is at 84, Medium Schools is at 83.9 for reading, 83.3 and 83.4 for math, respectively). The scores were just about the same, compared to the average, before the 9th graders were excluded.
- **Scores by school type** Charter Schools had an average math and reading score of 83.5 and 83.9, respectively. Thomas High Schools scores are 83.4 and 83.9, pretty close to the average! Before 9th graders were excluded, THS was at 83.4 and 83.8. Excluding the 9th graders brought THS's scores up.

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
