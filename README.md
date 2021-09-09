# School District Analysis

## Overview

The purpose of this deliverable is to prepare all standardized test data in order to report on performance trends and patterns. This analysis will help make decisions at a district level. During this analysis the data will be aggregated to showcase trends. The end results will help the school board and superintendent make decision on the school budget and priorities. Because of the Thomas High School 9th grade evidence of academic dishonesty, a second analysis was completed to exclude Thomas High School 9th graders test grades. 

## Results

### How is the district summary affected?
When taking out the THS 9th grade test grades, the district summary has a slight downtick in reading, math, and overall test scores.  

#### District Summary including THS 9th graders
![THS_9th_Included](/Resources/PyCitySchools_District_Summary.PNG)

#### District Summary excluding THS 9th graders
![THS_9th_Excluded](/Resources/PyCitySchoolsChallenge_District_Summary.PNG)



### How is the school summary affected?
When taking out THS 9th grade test grades, THS has a slight downtick in reading, math, and overall passing percent. 


#### THS Summary including THS 9th graders
![THS_9th_Excluded](/Resources/PyCitySchools_THS_Summary.PNG)


#### THS Summary excluding THS 9th graders
![THS_9th_Excluded](/Resources/PyCitySchoolsChallenge_THS_Summary.PNG)


### How does replacing the ninth graders' math and reading scores affected Thomas High School's performance relative to the other schools?
Replacing THS 9th graders' math and reading scores didn't affected THS against other schools. THS ended up in the same rank prior to the recalculation.

### How does replacing the ninth-grade scores affect the following:
 - Math and reading scores by grade
   - Overall 9th grade schools district wide went down. All other grades remain unchanged.

 - Scores by school spending
   - The '% overall passing' for the bucket '$630-644' went down slightly. All other 'spending ranges(per student)' remain unchanged

 - Scores by school size
   - The '% overall passing' for the bucket 'Medium (1000-2000)' went down slightly. All other 'school sizes' remain unchanged
 
 - Scores by school type
   - The '% overall passing' for the bucket 'Charter' went down slightly. All other 'school types' remain unchanged

## Summary
 - Overall, there was very little change in the school district analysis when replacing THS 9th grade scores with NaNs. THS 9th graders had some of the highest math and reading scores out of the schools selected, but with the given sample size, there was little variance. Scores by school spending was relatively unaffected by the updated analysis. The third quartile became slightly worse, while keeping the same placement among spending categories. Scores by school size was also relatively unaffected. Medium sized schools remained the highest for "% Overall Passing". Scores by school type ranking remained unchanged. Charter schools remained ranking above district schools by a sizable margin.
