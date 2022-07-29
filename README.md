# -School_District_Analysis.-
## Overview of the school district analysis:
The school board has informed Maria about the CSv file showing the possibility for academic dishonesty. Particularly in the reading and math grades of the 9th graders at Thomas High School. The purpose of this analysis is to perform a new School District Analysis after replacing the reading and math scores for ninth-graders for Thomas High School and write a report how this has impacted the overall analysis.

For this analysis we used the Pandas library in Python. Data from separate CSV files are read into Pandas and merged to create multiple different dataframes and analyzed.


## Results:
Deliverable 1: we replaced Ninth-Grade Reading and Math Scores.First we selected the ninth-grade reading and math scores for Thomas High School using the Pandas loc method with conditional statements and comparison and logical operators. Then, the reading and math scores were replaced to NaN using the Pandas NumPy module.

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/deliverable%201%20.png?raw=true




Deliverable 2:
we preformed a new analysis the following metrics after replacing the 9th-graders scores from Thomas High School:

##### The District summary


How is the district summary affected?

After re analysis the district summary showed slight effect as seen in image.Average Math Score , % Passing Math , % Passing Reading , % Overall Passing decreased by <1%
https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/deliverable%202.png?raw=true



##### The school summary


https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/school%20summer%20analysis.png?raw=true

How is the school summary affected?

The school summary had an impact in % Passing Math from 93% to 67%, % Passing Reading from 97% to 70%, % Overall Passing from 91% to 65% after re-analysis


##### The top 5 and bottom 5 performing schools, based on the overall passing rate


https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/top%20and%20bottom%20schools.png?raw=true

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the ninth graders’ math and reading scores at Thomas High School showed reduced performance compared to the other schools

##### The average reading score for each grade level from each school

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/reading%20score%20grade%20level.png?raw=true



##### The average math score for each grade level from each school

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/each%20grade%20level%20math%20scores.png?raw=true

Math and reading scores by grade: Math and reading scores by grade were higher after removing 9th Grader scores from Thomas High School

##### The scores by school spending per student, by school size and by school type
##### scores by school spending per student

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/scores%20by%20spending%20summary.png?raw=true

Scores by school spending : The scores by school spending  has impacted for the $630 - $644 category only



##### scores by school size

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/scores%20by%20size.png?raw=true

Scores by school size:The medium size school scores were effetced after re-analysing the data.


##### scores by type

https://github.com/AshleshaV/School_District_Analysis/blob/main/Resources/scores%20by%20type.png?raw=true

Scores by school type:charter schools score by type was changed after the data change.


## Summary:



After removing of Thomas High Schools ninth grade math and reading scores and re-Analysing, the schools metrics were impacted.
The school's ranking changed among the other schools in the district.
There is an Improvement in Thomas High School overall reading and math scores.
we can notice the Change in Medium-sized school pass rates and Charter School pass rates.
There is also a change in  $630-644 school's budget catogery pass rates.
