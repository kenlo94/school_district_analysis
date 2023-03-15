# Analyzing School Data using Jupyter Notebook & Pandas

## Resources
Data Source: schools_complete.csv, students_complete.csv
Software: Python 3.9.7; Jupyter Notebook 6.4.11; Pandas 1.3.5

## Project Overview
Use the school data provided to complete the analysis of a school district.

Tasks include:
1. Creating a table displaying the school district's key metrics
2. Creating a table displaying the key metrics for each individual school
3. Creating tables displaying the top 5 and bottom 5 schools based on % Overall Passing
4. Creating tables displaying the average math and reading scores received by students in each grade level at each school
5. Creating tables displaying the school performance based on the budget per student, school size, and type of school

## Results & Analysis
![Screenshot](Images/district.PNG)
- The table displays the school district's key metrics
- There are 15 total schools in the school district
- There are 39,170 total students in the school district
- The total budget for the school district is $24,649,428
- The average math and reading scores are 78.9% and 81.8% respectively
- The average % passing math and average % passing reading are 74.9% and 85.8% respectively
- The % overall passing is 65.1%

![Screenshot](Images/schools.PNG)
- The table displays the key metrics for each individual school
- Total students range from 427 to 4,976
- % Overall Passing ranges from 52.9% to 91.3%

![Screenshot](Images/top.PNG)
- The table displays the top 5 schools based on % Overall Passing
- The highest performer was Cabrera High School with 91.3%

![Screenshot](Images/bottom.PNG)
- The table displays the bottom 5 schools based on % Overall Passing
- The lowest performer was Rodriguez High School with 52.9%

![Screenshot](Images/math.PNG)
- The table displays the average math scores received by students in each grade level at each school
- The highest performers were the 10th graders from Griffin High School with 84.2
- The lowest performers were the 10th graders from Huang High School with 75.9

![Screenshot](Images/reading.PNG)
- The table displays the average reading scores received by students in each grade level at each school
- The highest performers were the 12th graders from Holden High School with 84.6
- The lowest performers were the 12th graders from Huang High School with 80.3

![Screenshot](Images/budget.PNG)
- The table displays the school performance based on the budget per students
- Schools who spent less than $585 per student received the highest % Overall Passing (90.3%)
- Schools who spent $645-680 per student received the lowest % Overall Passing (53.5%)

![Screenshot](Images/size.PNG)
- The table displays the school performance based on the size of the schools
- Schools who had less than 1000 students received the highest % Overall Passing (89.8%)
- Schools who had between 2000-5000 students received the lowest % Overall Passing (58.2%)

![Screenshot](Images/type.PNG)
- The table displays the school performance based on the type of the school
- Charter schools received the highest % Overall Passing (90.4%)
- District schools received the lowest % Overall Passing (53.6%)

## Drawing Insights

- As a whole, schools with higher budgets, did not yield better test results. By contrast, schools with higher spending $645-680 per student actually underperformed compared to schools with smaller budgets (<$585 per student).
- As a whole, smaller and medium sized schools dramatically out-performed large sized schools on passing math performances (89-91% passing vs 58%).
- As a whole, charter schools out-performed the public district schools across all metrics. However, more analysis will be required to glean if the effect is due to school practices or the fact that charter schools tend to serve smaller student populations per school. 