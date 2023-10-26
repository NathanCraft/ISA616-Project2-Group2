## Project Overview

Annually, the FSB conducts a senior survey of graduates to learn of their employment status.  In addition, information is verified using LinkedIn and employer survey information.  The data you are provided ('FSB_BI_Survey_2019_2021.rds') contains data on graduates for 2019, 2020, and 2021.  The data are merged from two sources:  the senior survey and data from the Miami University database.  

The data are anonymized, however, it is possible that if you look hard enough, you can identify students.  You are bound, ethically, not to do so.  It is a strict ethical code that you will not discuss individual data points with ANYONE except for me and your team.  Failure to comply with this code of ethics will result in a failing grade in the course.  

## Project Statement
The goal of this project is for Nathan Craft and Elle Prusko to answer the question: "What are the macro placement and salary trends we have seen over the past three years?". To do so, we have identified potential pains for our audience. Such pains consist of 
- Lack of information to better guide students down the right career path 
- Finding students high-paying jobs that fit their major
- Deeper understanding of salary trends by industry
- Limited staffing to allocate sufficient time to each student’s needs

To eliminate these pains, we intend to pilot an FSB Placement Analysis where we will visualize and understand salary and placement trends. We will also do external research on salary trends in related industries and deliver a soundbite of key findings and data-driven recommendations.

## Deliverables

1. Graduate Placement Analysis (Graduate Placement Analysis Group 2.Rmd)
   - In this file we cleaned the data and prepared it for analysis and use in the dashboard files.
   - This is the file to open and run first in RStudio in order to get the cleaned data. You will need to get the starting data set from outside of our repository.
   - After you run this .Rmd file, the clean data set, "CleanedStudentSuccessData.csv", will show up in this repository.

2. Student Success Dashboard (StudentSuccessDashboard.html)
   - This improves guiding students to an optimal path using the placement rates and average salary by each major. This allows advisors to know which majors are doing well, which ones are falling off, and how stable they are in terms of their trends.
   - The dashboard provides insight into the salaries students could expect to make in each major, but also gives reasonable expectations of being able to find a job with that major after graduating.
   - The dashboard provides a comparison point for the Farmer School of Business administrators when comparing to the market through means such as the National Association of Colleges and Employers salary survey.
   - The dashboard serves as a tool to help advisors understand the landscape and give better recommendations to students more efficiently. Additionally, they could prioritize students in majors that might need more attention for job placement.
  
## Overview of the Repository

The purpose of this repository is to have all our files related to the ISA 616 Student Success Project in one easily accessible place. To better understand the repository contents, below is a guide to all files (from most important to least) and an overview of what each contains.

StudentSuccessDashboard.html
- A knitted dashboard with key insights and conclusions (page 1)
- Visualizations displaying salary and placement trends from 2019-2021 (pages 2, 3)

StudentSuccessDashboard.Rmd
- A compilation of our documented code in R Markdown that is used for creating the Student Success Dashboard

Graduate-Placement-Analysis-Group-2.html
- A knitted document that shows the data-cleaning process we used to achieve our final, tidy dataset

Graduate Placement Analysis Group 2.Rmd
- An R Markdown file that contains documented code used for data preprocessing, exploration, and cleaning

FSB Placement Insights BVP Slide 1
- An overview of our business value proposition consisting of our customer, client jobs, pains, and intended solution

FSB Placement Insights BVP Slide 2
- An overview of our business value proposition consisting of our pain killers, gains, and gain creators

Analysis Class Project from Client.docx
- Project scope and the primary questions we want to answer

Back End Files R Studio Uses:
- .DS_Store
- .RData
- .Rhistory
- .gitignore
- ISA616-CareerProj.Rproj


