# School_District_Analysis
School_District_Analysis
Overview
Specifically, this report analyzes school and district metrics before and after the math and reading scores for Thomas High School (THS) were omitted due to academic dishonesty. Was to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact,and then how how these changes affected the overall analysis.
Resources
•	schools_complete.csv
•	students_complete.csv
Development Environment
•	Python 3.7.10
o	Pandas library
o	Numpy library
•	Anaconda 4.10.3
•	Jupyter Notebook 6.1.4
Results
District Summary
Taking Thomas High School ninth graders out of the equation had the following effects on the district summary metrics:(FIG1 and FIG 2)
•	Average Math Score decreased by <1%
•	Average Reading Score remained unaffected
•	% Passing Math decreased by <1%
•	% Passing Reading decreased by <1%
•	% Overall Passing decreased by <1%
School Summary
Cleaning the data had affected theThomas High School's metrics in the following ways:
•	% Passing Math decreased from 93% to 67%
•	% Passing Reading decreased from 97% to 70%
•	% Overall Passing decreased from 91% to 65%
School Rankings
Before the the data cleanup, THS was ranked third in the district 
After cleaning the data, their ranking fell to eighth place.

Scores by School Spending
The scores in the $630-644 per student spending rage were affected as follows:
•	% Passing Math dropped from 73% to 67%
•	% Passing Reading dropped from 84% to 77%
•	% Overall Passing dropped from 63% to 56%
Scores by School Size
The scores for medium size schools were affected as follows:
•	% Passing Math dropped from 94% to 85%
•	% Passing Reading dropped from 97% to 91%
•	% Overall Passing dropped from 91% to 85%
Scores by School Type
Charter school scores were affected as follows:
•	% Passing Math dropped from 94% to 90%
•	% Passing Reading droppedd from 97% to 93%
•	% Overall Passing dropped from 90% to 87%
•	Summary
•	Removing 9th grade math and reading scores from Thomas High School negatively impacted its ranking among other schools and had a ripple effect on district score categories that THS fell into.

