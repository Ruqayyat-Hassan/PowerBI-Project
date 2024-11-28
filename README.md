# PowerBIProject- Analysis of Mental Health Status amongst College Students
![image alt](https://github.com/Ruqayyat-Hassan/PowerBI-Project/blob/75839d699bad4cf8ac80c3b63883edbe65148250/Analyis%20of%20Mental%20health%20status.png)

## Introduction and Objectives

As college students navigate the challenges of academic pressures, social dynamics, and personal development, their mental health can significantly impact their well-being and academic performance. In this analysis, I delved into three critical areas of mental health: **depression, anxiety, and panic attack**. Understanding these conditions is essential not only for fostering a supportive environment but also for implementing effective solutions that will improve student mental health and overall success.

**Objective**: To study the effect of mental health conditions on student academic performance and derive recommendations that will help college management create an healthier academic environment.

**Below is the report created in Power BI**
![image alt](

[Link to report on PowerBI service](https://app.powerbi.com/links/CzZFMYasjm?ctid=b3894c53-b435-4a79-bf3c-7185006c5f69&pbi_source=linkShare)

## Data collection process
**Data on Student Mental health was extracted from kaggle.com**
About Dataset- This Data set was collected by a survey conducted via Google forms from 101 University students in order to examine their current academic situation and mental health.
All the data was based on Malaysia and collected from IIUM (International Icamil University Malaysia)

Here's the data set

## Data cleaning & transformation process
- Renamed some columns (the former were written in query format)
- Replaced words in ‘marital status’ column (‘Yes’ was replaced with ‘Married’ and ‘No’ was replaced with ‘Not Married’)
- Checked for duplicates
- Creation of 3 additional columns ’Depression’, ‘Anxiety’ and ‘Panic Attack’) to score mental health conditions. 1 being ‘Yes’ and 0 being ‘No’ using the IF function in Power BI
  
**Tools used: Excel and Power BI**

## Data modelling process
- Schema: Flat
- Measures created using DAX: Depression, Anxiety, Panic attack, Total Number of student 
- Creation of DAX Measures to calculate percentage (Depression, anxiety and Panic attack)

## Questions
1. What student course had the highest record of depression, panic attack and anxiety?
2. How does mental health status affect students’ CGPA?
3. How is student mental health affected in respect to year of study?
4. Has specialist treatment played a significant role in improving students’ mental health? 
5. How has student marital status affected their mental health?
6. What gender suffers more from mental health conditions?

## Results derived from analysis…
1. - **Depression**: students studying Engineering had the highest record with a total number of 7
   - **Panic attack:** students studying BCS and Engineering had the highest record with a total number of 5 each
   - **Anxiety:** students studying BIT had the highest record with a total number of 8

2. Students with higher CGPA range (3.50-4.00 and 3.00-3.49) were found to suffer more from mental health conditions.
In terms of severity, 32 were found to be normal, 34 mild, 16 moderate and 9 were severe
The lesser CGPA ranges recorded lower number of students.

*Normal: has none of the conditions, Mild: only 1, Moderate: only 2 Severe:all 3 conditions*

3. Yes, student who seek specialist treatment although few in number **(5.94%)** suffer less from mental health conditions with only one record of severe.
Those who did not **(94.06%)**, had the following record. Depression: 29, Panic Attack: 29, Anxiety: 31

4. There were higher record of mental health conditions amongst year 1 students compared to students of the higher years with year 4 being the lowest.
- Year 1: D= 14, PA= 14, A= 14
- Year 2: D= 10, PA= 8 A= 10
- Year 3: D= 10, PA= 10, A= 8
- Year 4: D= 1, PA= 1, A= 2
*D: Depression, PA: Panic attack, A: Anxiety*

5. Married students had lower records of mental health conditions in comparison to their ‘Not Married’ counterparts. Although they also show a concerning amount with 0 records of Normal, 4 Mild, 7 Moderate and 5 Severe.
Not Married: 37 Normal, 32 Mild, 11 Moderate and 5 Severe.

6. Female students were found to suffer more from mental health conditions than their male counterparts. With records of Normal: 27 Mild: 27, Moderate: 12 and Severe: 9
Males: Normal: 10 Mild: 9, Moderate: 6 and Severe: 1

## Key Insights
- BCS and BIT courses are mentally demanding.
- High academic performance is directly linked to mental health conditions
- Students’ mental health status improve as they progress in college, probably due to adaptation or school-social life balance.
- Specialist treatment is helpful in managing academic stress
- Married student experience less mental health conditions which could be due to emotional support from spouses
- Females with mental health conditions are mostly those studying BCS, BIT or engineering
- One mental health condition is likely to be followed by another if not managed/treated well

## Recommendations
- Review of academic calendar for mentally challenging courses to include more breaks or stress relieving activities
- Assigning campus guide or mentors to Year 1 and Year 2 students to help them navigate and adapt to the new environment
- Encourage student participation in extracurricular activities
- Assigning Specialists (Counsellors or therapists) to every department
- Further research should be done on cause of increased mental health conditions amongst females













