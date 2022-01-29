# SCHOOL DISTRICT ANALYSIS
## **Purpose**
The school board has notified Maria and her supervisor that the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered. Although the school board does not know the full extent of the academic dishonesty, they want to uphold state-testing standards and have turned to Maria for help. She has asked me to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once I have replaced the math and reading scores, Maria would like me to repeat the school district analysis to see how these changes affected the overall analysis


## **Results**

## **1) How is the district summary affected?**

Original Analysis:
![district summary original](https://user-images.githubusercontent.com/96033163/151651036-85880fac-d924-4295-a784-bbf8d7fe8680.jpg)

Adjusted Analysis:
![district summary adjusted](https://user-images.githubusercontent.com/96033163/151651047-1189597a-f9d9-4f57-8d1f-cdfb0986c6ab.jpg)

After changing 9th graders to null in Thomas high school the district school summary was affected almost 1% overall.  

## **2) How is the school summary affected?**

Original Analysis:
![per school summary orginal](https://user-images.githubusercontent.com/96033163/151651228-de6a0eee-6a60-4cc2-8f41-5fc677562864.jpg)


Adjusted Analysis:
![per_school summary adjusted](https://user-images.githubusercontent.com/96033163/151651232-d4155da8-d10c-4008-9040-03221242e42d.jpg)


Having 91% overall passing rate raised the concerns for Thomas High School and that is the reason that we were asked to remove 9th grade students to have a look on impact and  after removing the 9th grade students from the data set have a big impact on overall passing rate that dropped from 91% to 65%. 

## **3) How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

Original Analysis:
![ranking original](https://user-images.githubusercontent.com/96033163/151652704-7c441659-a690-446b-bfd9-ea0ff6720e93.jpg)

Adjusted Analysis:
![ranking adjusted](https://user-images.githubusercontent.com/96033163/151652859-863b2397-149e-476f-9a96-f0ca9259eb00.jpg)

The ranking of the thomas school was not affected at all and it is still at second position 

## **3) How does replacing the ninth-grade scores affect the following:**

## *1) Adjusted Averages using the Math and Reading Scores*

Adjusted Average Math & Reading scores

![math score by grade adjusted](https://user-images.githubusercontent.com/96033163/151651994-fdae74f8-1e27-4aae-a456-945fa96dc56a.jpg) ![reading score by grade adjusted](https://user-images.githubusercontent.com/96033163/151651997-a3796a6e-6a19-414d-84ad-da4772d9fbbf.jpg)

9th grade is replaced by NaN in adjusted analysis

## *2) scores by school spending*


Original Analysis:
![score by schools spending original](https://user-images.githubusercontent.com/96033163/151652142-9678a171-44c3-43ad-aa2f-b8a715e2931b.jpg)

Adjusted Analysis:
![score by schools spending adjusted](https://user-images.githubusercontent.com/96033163/151652149-0486827c-1670-4bbe-b0a3-8ee547b46177.jpg)

Spending impact is very little by changing 9th grade

## *3) Scores by school size*

Original Analysis:
![score by schools size original](https://user-images.githubusercontent.com/96033163/151652154-c5fb89c0-5443-4953-b1c8-0a723285d91e.jpg)

Adjusted Analysis:
![score by schools size adjusted](https://user-images.githubusercontent.com/96033163/151652157-737b70a5-97f9-4e20-94ea-fd83926f9de6.jpg)

In this as well the impact is very minimal 

## *4) Scores by school type*

Original Analysis:
![score by school type original](https://user-images.githubusercontent.com/96033163/151652160-b4f589aa-0989-4f80-8872-4d4fafe3c069.jpg)

Adjusted Analysis:
![score by school type adjusted](https://user-images.githubusercontent.com/96033163/151652163-78165318-3101-44b1-831d-bce27ac4f13b.jpg)

In this also the impact is very little and the thomas high school is charter school type

## **Summary:**

- Passing rate dropped from 91% to 65% for Thomas High School

-  The change in ranking is only of less than 1% in ranking percentage.

- There was not a major impact in scores of school spendings, sizes, types after removing 9th grade  

- Math and reading averages and passing percentages all saw shifts.  

So overall average math, reading and overall scores at Thomas High School were impacted with the adjustment but these changes were not enough to change its overall ranking than other schools.
