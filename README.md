# Real World Data Storytelling: Student Performance Factors

**Group Members:**
* Eric Fidalgo - ef22r
* Thomas Hoppel - tah22a

## Context and Description
This project analyzes real-world data regarding various factors that influence student performance in exams. By examining study habits, attendance, parental involvement, and socioeconomic indicators, we aim to uncover actionable insights for educators and policymakers to better understand what drives student success.

## Dataset Information
* **Source:** `StudentPerformanceFactors.csv` from [Kaggle](https://www.kaggle.com/datasets/lainguyn123/student-performance-factors)
* **Justification:** This dataset fits the project constraints as it is a CSV file containing 6,607 rows. It includes well over 4 numeric columns such as `Hours_Studied`, `Attendance`, `Previous_Scores`, and `Exam_Score`, along with more than 2 categorical columns such as `Parental_Education_Level`, `Gender`, and `Access_to_Resources`.

## Repo Structure
* `analysis.ipynb` - main notebook with loading, cleaning, EDA, visualizations, and summary
* `data/raw/` - original dataset
* `data/processed/` - cleaned dataset exported during analysis
* `figures/` - saved graphs used in the project

## Research Questions
1. Do historical academic scores reliably predict current exam success?
2. How does parental education level impact a student's exam performance across different genders?
3. Is there a strong correlation between the number of hours studied per week and the final exam score?
4. How do different levels of access to resources affect average exam outcomes?
