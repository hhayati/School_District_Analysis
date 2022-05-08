# School_District_Analysis
##Overview of the school district analysis
The goal for this challenge was to analyze the school district’s data to study the student’s passing percentage in math and reading exams and its relation to the school type, size and spending budget. In particular, it was investigated how exclusion of the scores from 9th grade students from one high school may affect the results.

## Data screening  
The district found strong evidence that math and reading scores  for 9th grade students at Thomas High School have been manipulated. As a result, the district decided to exclude those grades from the analysis. The screen shot below shows that the reading and math scores for those students were replaced by NaN. 

![image](https://user-images.githubusercontent.com/58461542/167281694-c1794f44-1dcd-4f1c-8ffc-8411afd1037e.png)


## School District Analysis
To assess the performance of the district and each school in the district, the following metrics are evaluated:
*The district summary (total budget, average math and reading scores, passing percentages)
*The school summary (total budget, average math and reading scores, passing percentages, top and bottom performing schools)
*The average math and reading scores by grades
*The average math and reading scores by school spending per student
*The average math and reading scores by school size
*The average math and reading scores by school typ

## District Summary
The school district summary is shown first for case (1) all students (2) after excluding 9th grade students from Thomas HS. 

##
The school district summary is shown first for case (1) all students (2) after excluding 9th grade students from Thomas HS. 
![image](https://user-images.githubusercontent.com/58461542/167281777-890cb995-cd95-4b58-9306-7c52b5890cc1.png)
![image](https://user-images.githubusercontent.com/58461542/167281780-263c748e-9778-475a-acea-5ee2298c913a.png)

It is noted eliminating the scores from the 9th graders of Thomas High School would reduce the average scores slightly but all together the effect is relatively insignificant. 

## School Summary
The school summary for two cases are provided below: case (1) all students (2) after excluding 9th grade students from Thomas HS. 

![image](https://user-images.githubusercontent.com/58461542/167281788-149168bc-482f-4c20-9743-9d90f5dcae96.png)

![image](https://user-images.githubusercontent.com/58461542/167281791-83bd36bf-1256-4ed0-8b41-9f3141c6745e.png)

The school   summary for all high schools is identical except for Thomas HS and it is noted that the average math and reading scores drops slightly by eliminating the date from 9th grade. 
## Thomas High School’s performance relative to the other schools
The top 5 schools with the highest performances are listed in tables below for two cases (1) All students (2) after excluding 9th grade students from Thomas HS. This ranking is based on the overall passing percentages. It is noted that the Thomas HS is the 2nd best school when including all students. It is also noted the Thomas HS remains in 2nd place even after the 9th graders are excluded. The total overall passing percentage drops from 90.94% to 90.63% but that’s not a big shift and as result Thomas HS retains their 2nd place.

![image](https://user-images.githubusercontent.com/58461542/167281797-a2b4cc7c-eaf6-4684-9c5d-c880fa85a0ed.png)
![image](https://user-images.githubusercontent.com/58461542/167281800-cd7b5da5-78df-4030-b71d-4944683057c5.png)

## Average math and reading scores by grade
For each school, the average math and reading scores by grade are shown below (math: left, reading: right). As expected, the average scores for 9th graders of Thomas High School have not been calculated. 
![image](https://user-images.githubusercontent.com/58461542/167281805-814cdfc7-2339-44ba-8a75-e08be3a767dd.png)
![image](https://user-images.githubusercontent.com/58461542/167281807-139d387e-c330-4ec1-b922-a70d54f05135.png)
![image](https://user-images.githubusercontent.com/58461542/167281808-40937b78-47ba-4e1b-9ccf-529d6b6ec5c1.png)
![image](https://user-images.githubusercontent.com/58461542/167281809-2f313bfa-efd5-4ada-9825-9b1e49efbe1a.png)

## Average math and reading scores by spending budgets
Table below shows the average scores and passing percentages based on the spending budget per student. It is noted that schools with lower budget have  better performance and as budget increases the overall passing percentage reduces. This pattern is against the expectations but might be explained by the fact that students with weaker academic background may be selected naturally by their parents to attend more expensive schools for better supervision. Parents of “high performer” students may not see the need to end their kids to more expensive schools. The average scores and passing percentages do not change much by excluding the scores for 9th graders of Thomas High School as that was only a small subset of data.

![image](https://user-images.githubusercontent.com/58461542/167281813-e32b65ea-2309-48a2-b5bb-166a08a20f56.png)

## Average math and reading scores by school size
The average scores and passing percentages based on the school size are presented below. It is noted that the small schools have higher performance.  Also noted that excluding the data from 9th grade of Thomas HS does not change the average scores and passing percentages as that was only a small subset of data.
![image](https://user-images.githubusercontent.com/58461542/167281816-c47e2b79-d8eb-4bd6-a41e-b9545d11d957.png)




##Average math and reading scores by school type
Table below shows the average scores and passing percentages based on the school type. Charter schools seem to have a better performance than District schools.  It is noted the average scores and passing percentages are not affected much by excluding the scores for 9th graders of Thomas High School.
![image](https://user-images.githubusercontent.com/58461542/167281827-5cfcb795-9387-489c-a26d-1e24719d7b39.png)

# Summary
The district school’s data including math and reading tests were analyzed to evaluate the student’s performance and its dependency on the school type, size, and spending budget. After eliminating the data from Thomas High School 9th grade, the average math and reading scores dropped slightly but the effects were minimal due to small size of students from 9th grade from Thomas high school . 




















