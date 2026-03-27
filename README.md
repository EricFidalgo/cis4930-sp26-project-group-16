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
1. Is there a strong relationship between hours studied and exam score?
2. Is attendance associated with better exam performance?
3. How do different levels of access to resources affect average exam outcomes?
4. Which numeric factors are most strongly correlated with exam score?
