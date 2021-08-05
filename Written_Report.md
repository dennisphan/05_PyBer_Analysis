# School_District_Analysis

## Overview of Project
This project summarized data from various schools and their students' results to produce meaningful measures. Moreover, the project also aimed to adjust the result and assessed the effects of academic dishonesty of 9th graders at Thomas High School. All results were to facilitate further decision-making. 
### Purpose
This project focuses on several metrics as valuable measurements:
 - **The District Summary** summarized general information about schools and students in the district.
 - **The School Summary** summarized general information about each school in the district. 
 - **Top 5 performing schools** based on the overall passing scores.
 - **Bottom 5 performing schools** based on the overal passing scores.
 - **The average math scores by grades** summarized math scores by grades. 
 - **The average reading scores by grades** summarized reading scores by grades.
 - **The math and reading scores by school spendings** indicated the relationship between spending ranges and scores
 - **The math and reading scores by school sizes** indicated the relationship between school sizes and scores
 - **The math and reading scores by school types** indicated the relationsihp between school types and scores
## Analysis and Challenges

### The district summary
The academic dishonesty had a slight effect in the district summary.

**The district summary before the changes at Thomas High School**
![The District Summary Before Changes at Thomas High School](Resources/Screenshots_Analysis_with_9th_THS/01_District_Summary.png)

**The district summary after the changes at Thomas High School**
![The District Summary After Changes at Thomas High School](Resources/Screenshots_Analysis_without_9th_THS/01_District_Summary.png)


### The school summary
The results of 9th graders at Thomas High School removed and replaced by "NaN". Only the result of Thomas High School was influenced. However, the difference was not significant. Details are expressed below:

**The school summary before the changes at Thomas High School**
![The School Summary Before Changes at Thomas High School](Resources/Screenshots_Analysis_with_9th_THS/02_School_Summary.png)

**The school summary after the changes at Thomas High School**
![The School Summary After Changes at Thomas High School](Resources/Screenshots_Analysis_without_9th_THS/02_School_Summary.png)

### Top 5 performing schools
The top 5 performing schools was not influenced by the academic dishonesty at Thomas High School. Details are expressed below:

**Top 5 performing schools**
![Top 5 schools](Resources/Screenshots_Analysis_without_9th_THS/03_Top_Schools.png)

### Top 5 bottom performing schools
The bottom 5 performing schools was not influenced by the academic dishonesty at Thomas High School. Details are expressed below:

**Bottom 5 performing schools**
![Bottom 5 schools](Resources/Screenshots_Analysis_without_9th_THS/03_Bottom_Schools.png)

### The average math scores by grades
Only the results of 9th graders at Thomas High School were influenced, removed, and replaced by "NaN". Details are expressed below:

**The average math scores by grades before academic dishonesty**
![The School Summary Before Changes at Thomas High School](Resources/Screenshots_Analysis_with_9th_THS/02_School_Summary.png)

**The average math scores by grades after academic dishonesty**
![The School Summary After Changes at Thomas High School](Resources/Screenshots_Analysis_without_9th_THS/02_School_Summary.png)

### The average reading scores by grades
Only the results of 9th graders at Thomas High School were influenced, removed, and replaced by "NaN". Details are expressed below:

**The average reading scores by grades before academic dishonesty**
![The School Summary Before Changes at Thomas High School](Resources/Screenshots_Analysis_with_9th_THS/02_School_Summary.png)

**The average reading scores by grades after academic dishonesty**
![The School Summary After Changes at Thomas High School](Resources/Screenshots_Analysis_without_9th_THS/02_School_Summary.png)

### The math and reading scores by school spendings
Based on the results, for schools with the spendings per student below $584, the number of students passed math, reading, and both was highest. As the spending ranges increased, the results were decreasing and reach bottom at the range from $645 to $675. The academic dishonesty didn't have any effect on these results. Details are expressed below: 

**The averages scores by school spendings**
![The Average Scores By School Spendings](Resources/Screenshots_Analysis_without_9th_THS/07_Scores_By_School_Spendings.png)

### The math and reading scores by school sizes
Based on the results, for schools with sizes below 2000 students, the results were very similar with unsignificant difference. However, when the sizess were more than 2000 and below 5000 students, the results dropped significantly. The differences in each measure were 5.7% in average math score, 2.6% in average reading score, 24% in math passing rate, 14% in reading passing rate, and up to 33% in overal passing rate. The academic dishonesty didn't have any effect on these results. Details are expressed below:

**The averages scores by school sizes**
![The Average Scores By School Sizes](Resources/Screenshots_Analysis_without_9th_THS/08_Scores_By_School_Sizes.png)


### The math and reading scores by school types
Based on the results, charter-typed schools had better results than district-typed. The differences were significant in math (27%) and overall passing rates (36%) but shrank on reading passing rate (16%). The academic dishonesty didn't have any effect on these results. Details are expressed below:

**The averages scores by school types**
![The Averages Scores By School Types](Resources/Screenshots_Analysis_without_9th_THS/09_Scores_By_School_Types.png)


## Results
- There was an inversed relationship between average spending per student and results. The higher the spending, the lower the result and vice versa. However, since the data only included a specific spending range from $550 to $675, the pattern might change in the ranges of higher than $675 and of lower than $550. 

- The sizes schools influenced their students's performance. In specific, schools that had 2000 students or less performed better than schools that had from 2000 to 5000 students. One of the possible reasons could be the insufficiency of staff and facilities. More data with higher level of details are needed to better assess the relationship of school sizes and students' performance such as total fixed assets or number of staff and educators in each school. 

- The influences of school types should be taken into account. Based on provided data, district-typed schools performed less effective than charter-typed schools. A more in-depth analysis should be conducted to figure out potential reasons as well as solutions. 

- Finally, to increase the reliability of this dataset, there should be an additional analysis to assess the influences of potential outliers which could mislead the above results. 
