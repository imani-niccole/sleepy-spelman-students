# Sleepy Spelman Students

## Overview

How are sleep habits, academic workload, and stress related among college students?

*Sleepy Spelman Students* is an exploratory data analysis examining sleep,
academic workload, bedtime habits, and stress among 18 surveyed Spelman College
students.

The project uses Python for data exploration and Tableau for visualization to
identify patterns in student sleep behavior and examine how sleep relates to
academic and personal factors.

## Tools

- Python
- pandas
- Jupyter Notebook
- Tableau Public

# Dataset

The dataset contains survey responses from **18 Spelman College students**.

Variables examined include:

- Sleep hours
- Stress level
- Course load
- Bedtime routine
- Reasons for sleep loss
- Sleep prioritization

A student number was added as a unique identifier to distinguish individual
responses during visualization.

## Key Questions

This analysis explored several questions: 

1. How much sleep are students getting?
2. Is sleep duration related to reported stress?
3. Does average sleep differ across course-load groups?
4. What are the most common reasons students lose sleep?
5. Do students with a consistent bedtime routine report different sleep patterns?

## Analysis Process

1. Imported and explored survey data in Python.
2. Reviewed the dataset for structure and data quality.
3. Calculated descriptive stats for student sleep hours.
4. Examined the relationship between sleep hours and stress level.
5. Compared sleep patterns across academic and behavioral categories.
6. Added a unique student identifier for observation-level visualization.
7. Built an interactive Tableau dashboard to communicate the results.

## Key Findings

Across the 18 surveyed students average sleep duration was **6.22 hours**.

- Median: **6 hours**
- Mode: **6 hours**
- Minimum: **4 hours**
- Maximum: **9 hours**

### More sleep was associated with lower reported stress

Sleep hours and stress level had a **moderate negative correlation (r = -0.39)**.

Within this sample, students with more sleep tended to report lower
stress levels. This relationship is correlational and does not establish
that sleep duration causes changes in stress.

### Sleep differed across course-load groups

Average sleep by course load:

- **12-16 credit hours:** 7.3 hours
- **17-19 credit hours:** 5.3 hours
- **20+ credit hours:** 6.2 hours

The 17-19 credit-hour group reported the lowest average sleep.

### Studying and homework were the primary reasons for sleep loss

Academic responsibilities, specifically **studying and homework**, were
the most frequently reported reasons students lost sleep.

### Bedtime routines show differences in sleep patterns

Students reporting a bedtime routine showed somewhat higher sleep duration.

## Dashboard
<img width="400" height="200" alt="Screenshot 2026-09-12 at 10 50 52 PM" src="https://github.com/user-attachments/assets/ba3a7fd5-bb71-4474-a2b0-2dcec3db1cba" />

[Spelman Students Sleep Analysis Dashboard](https://public.tableau.com/views/SpelmanStudentsSleep/SleepySpelman?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)


## Repository Structure
- notebook = further analysis & processing data
- data = raw data, cleaned data, and outputted CSV file
- visuals = PDF of sleep analysis dashboard

## Author

Imani Candler

[Portfolio](https://imaniniccole.my.canva.site/portfolio)  

[LinkedIn](http://www.linkedin.com/in/imanicandler)

September 12, 2026
