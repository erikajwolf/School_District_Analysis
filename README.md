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
After Maria's initial aggregation and analysis, it came to light that 9th grade students at Thomas High School had committed academic dishonesty, voiding their test scores. Because of this, Maria had to separate their data and recalculate all the analysis to exclude Thomas High Schools 9th graders.

## Results
Using bulleted lists and images of DataFrames as support, address the following questions.

- **How is the district summary affected?** 

- **How is the school summary affected?** 

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?** Thomas High School becomes the #1 performer after excluding 9th grade scores (at 97% overall passing). They were originally at 90.1% overall passing.
**How does replacing the ninth-grade scores affect the following:**
- **Math and reading scores by grade** Math and reading scores did not change for Grades 10, 11, and 12. The only change after the initial analysis is the ouput of the 9th grade scores. Originally 83.6 for math, 83.7 for reading. Now: NaN.
- **Scores by school spending** 
- **Scores by school size** Thomas High School is a medium sized school (1000-1999 students). It falls perfectly in the average % passing reading, but falls just short of the average percent passing math (THS is at 93.1%, Medium Schools is at 93.6%). Thomas High School far surpasses % Overall Passing at 97% (Medium Schools is at 91.8%). Before excluding 9th graders, THS fell just short of most averages: 93.9% (avg ), 97.3%, 90.9%
- **Scores by school type** Charter Schools had an average math and reading score of 83.5 and 83.9, respectively. Thomas High Schools scores are 83.4 and 83.9, pretty close to the average! Before 9th graders were excluded, THS was at 83.4 and 83.8. Excluding the 9th graders brought THS's scores up.

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
