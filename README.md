# School_District_Analysis

# Overview of PyCityShcools Challenge
The goal of this challenge was to analyize the standardized testing results from a large number of schools state-wide. The test results covered both Math and Reading from 9th to 12th grade and the purpose of this analysis was to see how removing test results from Thomas High School's 9th grade class affect the overall results.

# Deliverable 1: Replace Ninth-Grade Reading and Math Scores
![image](https://user-images.githubusercontent.com/53358476/188975602-8b64c030-11bb-43ea-923b-a0bf2f35c065.png)

# Deliverable 2: Repeat the School District Analysis
Repeat the school district analysis you did in this module, and recreate the following metrics:

- The district summary

- The school summary

- The top 5 and bottom 5 performing schools, based on the overall passing rate

- The average math score for each grade level from each school

- The average reading score for each grade level from each school

- The scores by school spending per student, by school size, and by school type

# District Summary
![image](https://user-images.githubusercontent.com/53358476/188982988-6aabe3b5-a3fa-42de-9ac9-0400b7dd0e35.png)
![image](https://user-images.githubusercontent.com/53358476/188983136-a1bd08e9-04d8-4029-a9e9-7e062e525337.png)
![image](https://user-images.githubusercontent.com/53358476/188983263-c1b4f845-94ac-464d-906f-2249c437f068.png)

# The school summary
![image](https://user-images.githubusercontent.com/53358476/188985002-8ae0321d-a351-45ff-9130-676f3b700b9c.png)

# The top 5 and bottom 5 performing schools, based on the overall passing rate
To find the top 5 and bottom 5 perfoming schools, I recalucated the passing math percentage, passing reading percentage and overall passing percentage of Thomas High School and entered the new data into the school summary data frame. as shown in the frames below
- Total number of students in 10th - 12th grade: 1174
- Passing reading: 1094
- Passing math: 1139
![image](https://user-images.githubusercontent.com/53358476/188985708-799a2e6b-3e01-4d2c-a98f-4f569d456b76.png)

# The average math score for each grade level from each school
![image](https://user-images.githubusercontent.com/53358476/188986703-6a3f5eba-0af8-498d-a17a-d559c02eaafc.png)
![image](https://user-images.githubusercontent.com/53358476/188986813-b0869e0b-3b50-4311-a113-7a004df34a89.png)

# The average reading score for each grade level from each school
![image](https://user-images.githubusercontent.com/53358476/188987035-309a662b-f363-41e8-b308-d2613b0fc5b2.png)

# The scores by school spending per student, by school size, and by school type
![image](https://user-images.githubusercontent.com/53358476/188987560-d6451a60-e568-4d96-864c-a13368ea9403.png)

# Results
- Original Data to After data clean up: Average Math Score 79.0 to 78.9, Average Reading Score stayed the same, percent passing Math went from 75 to 74, percent passing reading went from 86 to 85, Overall percent Passing scores 64 to 65 How is the school summary affected?
- Thomas High School overall passing percent went from 90.95% down to 65.08% after removing 9th grades testing results. Going from placing 2nd to 8th How does replacing the ninth graders math and reading scores affect Thomas High Schools performance relative to the other schools?
- Scores by school spending: Thomas High school was in the $630 to $644 spending range and was one of four high schools in that range, their percent passing math was higher then the average prior to omitting the 9th grade test results and so reduced the averages for schools in that range when the test results dropped from 90.95% down to 65.08%

# Summary
replacing all of Thomas High Schools 9th grade math and reading test results with NaN has negatively affected a number of data points.
Thomas High Schools rankings for the overall percentage of passing students dropped from 2nd best to 8th worst.
