# Student Performance Analysis

## Project Overview

This project analyzes student performance data to understand the factors that influence academic scores and identify students who may be at risk of poor performance.

The analysis was completed as part of the Pluto Academy Data Analytics Internship Program.

## Objectives

- Explore and clean student performance data
- Analyze factors affecting student scores
- Compare performance across gender and test preparation groups
- Study relationships between mathematics, reading, and writing scores
- Identify at-risk students
- Provide actionable recommendations for improving student outcomes

## Dataset

The dataset contains performance information for 1,000 students, including:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## Analysis Performed

### Factor Analysis

The project answers five major questions:

1. Does parental education level affect scores?
2. Do students who complete test preparation score higher?
3. What is the correlation between reading, writing, and mathematics scores?
4. Which gender performs better in each subject?
5. What is the distribution of total scores?

### At-Risk Student Segmentation

A student is classified as at-risk if they score below 50 in at least one subject.

The analysis identified:

- Total students: 1,000
- At-risk students: 188
- At-risk percentage: 18.8%

## Visualizations

The project includes visualizations for:

- Scores by parental education
- Test preparation comparison
- Score correlation
- Gender vs subject performance
- Total score distribution
- Reading vs mathematics scores
- At-risk student groups

## Key Finding

Students who completed the test preparation course achieved higher average scores than students who did not complete it. Reading and mathematics scores also showed a strong positive correlation of approximately 0.82.

## Recommendations

1. Provide targeted academic support to at-risk students.
2. Strengthen test preparation and revision programs.
3. Monitor student performance regularly to identify students needing early intervention.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Project Structure

```text
Student_Performance_Analysis/
│
├── data/
├── charts/
├── Student_Performance_Analysis.ipynb
├── README.md
├── requirements.txt
└── .gitignore