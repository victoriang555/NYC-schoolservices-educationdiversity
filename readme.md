# NYC School Services Distribution

## Description
Based on Kaggle project: https://www.kaggle.com/passnyc/data-science-for-good.

I shifted the goal based on my research. I found out that the Mayor of NYC has
proposed changing the specialized high school admission requirement by removing
the SHSAT and replacing it with acceptance based on being in the top 7 percent
of their middle school and top 25% citywide. This change could technically
be immediately applicable to 5 of the 8 specialized high schools since they were
not named in the 1971 state law mandating the enrollment process. The Mayor,
however, opposes making a change to these 5 schools separate, saying such actions
could invite a legal challenge. Instead, the Mayor would like to take his
proposal to the state legislature and have it apply to all 8 schools.

In addition, the Mayor already set aside 20% of specialized high school seats
for low-income students who score just below the cutoff. They would be able to
earn their spot through attending a summer session called the "Discovery"
program. The city recently updated the Discovery program to now target students
from high-povery schools instead, since they tend to have a higher proportion of
black or Hispanic students. The Mayor claims that his proposal would lead to
45% of students at the specialized high schools being black or Latino.

The original goal (based on the Kaggle project) was for PASSNYC to help make
more students do well on the SHSAT. This goal is aligned with NYC DOE's DREAM
program.

The updated goal is to help PASSNYC determine which Hispanic and Black students
are falling behind in their school compared to their peers. The hypothesis we
may prove or disprove is the Mayor's new proposal of using top 7% of each middle
school and top 25% of city as admissions standards for specialized high schools.

The data has been dedicated to the public domain.

## Project Planning
Agile Board: https://trello.com/b/nsdTRTwN/passnyc-education-diversity


## Further reading on topic
Below are interesting articles I found around the topic of educational diversity
in NYC schools.
1. "New York City's Flawed School Diversity Plan" http://www.centernyc.org/nyc-flawed-school-diversity-plan
NYC has the following "yardstick goals": Increase by 50,000 the number of
students at "racially representative" schools and reduce the number of
"economically stratified" schools by 10%. "Citywide, the number of students at
schools meeting the racially representative goal has increased by over 34,000
over the past five years, at an average growth rate of 2.4 percent per year.
This has happened in the absence of any citywide diversity policy, and it is
due primarily to an increase in the total number of white and Asian students
across the city and a decrease in the number of black students in the system
overall.""
2. "The Price of Specialized High Schools" https://radiopublic.com/miseducation-85nlgx/ep/s1!d9d66 There 8 Specialized High Schools, of the students, 55% are Asian and
27% are White. Yet, Asians and Whites each make up about 15% of students overall.
The admission test is the only way to get in and you get in if you score above
the cutoff. Seems like the questions on the SHSAT are algebra questions and not
topics that are taught in 8th grade at most schools. Therefore, it seems that
specialized test prep is required to pass the SHSAT.
3. "DeBlasio Proposes Changes to New York's Elite High Schools"
https://www.nytimes.com/2018/06/02/nyregion/de-blasio-new-york-schools.html
The proposal suggests replacing the SHSAT with admitting students based on their
class rank in their middle school
4. "What would happen if high-stakes exam was eliminated for NYC Specialized
High Schools?" https://brooklyneagle.com/articles/2019/02/01/what-would-happen-if-high-stakes-exam-was-eliminated-for-specialized-high-schools/
5. NYC DOE Specialized High Schools Information: https://www.schools.nyc.gov/enrollment/enroll-grade-by-grade/specialized-high-schools
6. NYC DOE DREAM program: https://www.schools.nyc.gov/about-us/programs/dream-program
7. "Carranza says the city could get rid of the SHSAT at 5 specialized schools on its own, contradicting de Blasio"https://www.chalkbeat.org/posts/ny/2018/10/09/carranza-breaks-with-de-blasio-on-specialized-high-schools/



## Installation
Download the repo
```bash
requirements.txt
```

## Problem Breakdown
1. Find which schools are most homogenous
2. Find which schools have the most diversity
3. Find which schools have the greatest population of each minority group
4. Find the lowest performing schools
5. Determine which group of minorities are left behind (big gap between school's overall performance and the student group's)
6. Determine which schools are racially representative schools
7. Determine which variables lead to poor performance
8. Which grades does performance start dropping off?
9. How much resources do they already have from their school?
10. Which schools have a higher percentage of students who qualify for the DREAM
program?

## Hypotheses
1. Community schools generally have lower Economic Need Index than non-community
schools
2. Community schools have larger concentrations of Black and Hispanic students
3. 

## Glossary
1. Economic Need Index - A measure that incorporates several factors, including
students living in temporary housing, eligibility for public assistance benefits
in student households, recent immigration status, and level of family poverty
in each students' home census tract.
2. Racially Representative School - One that has between 50 and 90 Percent
Black and Hispanic students
3. Specialized High School -  "The nine specialized high schools are one way
that New York City supports the educational needs of students who excel
academically and/or artistically, including English Language Learners and
students with an IEP or 504 Plan"
4. Economically Stratified School - If a school's Economic Need Index is 10 points
above or below the citywide average. In 2016-17, the average ENI for schools
citywide was 0.64
5. DREAM program - NYC DOE free specialized high school test prep program for
low income students
6. Discovery program - A summer session provided to low-income students who's
SHSAT score is just below the cutoff.
