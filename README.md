# Dashboard and Data Clearning for Professional Data Survey


## INTRODUCTION

This Desktop and Mobile Friendly dashboard helps understand Survey data taken from Professionals in the field of Data Science. 
The project extracts, cleans and presents relevant data for a Survey aimed to understand Professional Data of People in the field of Data Science. It aims to create a general overview of the data concentrating on the People, their age, salary, location, satisfcation and field and technical skills.

It helps understand what the general demographics of the survey takers is in relation to age and location. The dashboard presents the breakdown of the specific job role and corresponding salary. It also relates the satisfaction with work-life balance and salary. It also shows the general difficulty of breaking into the field of Data Science and the skill that is most common.

On a scale of 1-10 the survey takers rate their satisfaction with their salary at 4.27 and their work-life balance at 5.74.


### CONSTRUCTION

- Load data into Power BI Desktop, dataset is a csv file.
- Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- It was observed that in none of the columns errors & empty values were present.
- It was observed that the Other Category in several columns (Location, Languages, Job Title) was too diverse and for simplification the data was manipulated using the split column function.
- It was also observed in the salary section that occasionally ranges were given which could not be quantified as such so a new Average Salary Column was created by taking into account the averages of the ranges.
- The manipulated and cleaned data was saved and used now for report.
- In the report view, since the data is a survey the 'card' visualisation was used to denote the number of survey takers and the average age of the survey taker.
- A Treepmap visual filter was used to denote the location of the survey takers.
- A Stacked Bar Chart was used to denote the Average Salary given the Job Title.
![Average Salary By Job Title](https://github.com/YVandana/Professional-Data-Analysis/assets/80910772/84886fdc-7420-4d9c-a20d-b30661528d8a)
- A Stacked Column Chart was used to denote the Programming Language used given the Job Title.
- Two gauges were added to represent the average satisfaction of the survey taker with respect to their Salary and Work/Life-Balance.
![Satisfaction With Work Life Balance](https://github.com/YVandana/Professional-Data-Analysis/assets/80910772/d6479575-6b18-49b2-a437-8b417f6ba430)

![Satisfaction With Salary](https://github.com/YVandana/Professional-Data-Analysis/assets/80910772/9f4ef86b-b9bf-4f12-be68-c3254b4114f9)
- A donut chart was added to account for how easy the survey takers found breaking into the field of Data Science.
- The canvas was then adjusted to look appealing and the colours, font and visual details were adjusted to make the dashboard palatable to the eyes.
- A mobile canvas was created subsequently to adjust for a mobile view.
 
 
 # Report Snapshot (Power BI DESKTOP)

 
![Dashboard](https://github.com/YVandana/Professional-Data-Analysis/assets/80910772/47519ffa-8d03-47d7-8b8a-081c6ff06ba6)

 # Report Snapshot (Power BI MOBILE)

 
![Mobile View](https://github.com/YVandana/Professional-Data-Analysis/assets/80910772/cf14117c-5cc1-4b1e-94a8-88af696e7cc5)

# Insights

A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;

### [1] Survey Takers
Total Number of Survey Takers = 630
### [2] Age
Average Age of Survey Takers = 29.87
### [3] Salary
Satisfaction With Salary (Scale 1-10) = 4.27
### [3] Work/Life-Balance
Satisfaction With Work/Life Balance (Scale 1-10) = 5.74          
### [4] Breaking Into Data Science
Difficulty of Breaking Into Data
        Very Easy = 4.29%
        Easy = 21.27%
        Neither Easy Nor Hard = 42.7%
        Difficult = 24.76%
        Very Difficult = 6.98%
### [5] Country of Residence (Count)
        USA = 261
        India = 73
        UK = 40
        Canada = 32
        Other = 224
