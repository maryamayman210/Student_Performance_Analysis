# Student Performance Analysis

A comprehensive Data Analysis project exploring factors affecting student academic success. 
This project demonstrates mastery of the full data analysis workflow using Python, Pandas, NumPy, Matplotlib, and Seaborn.

## Project Overview
- Collected and cleaned student data (handling missing values, duplicates, and outliers)
- Conducted Exploratory Data Analysis (EDA) with histograms, boxplots, and correlation heatmaps
- Performed Feature Engineering:
  - Created pass/fail labels based on final grades
  - Calculated average subject scores
  - Categorized attendance levels and study hours
- Encoded categorical variables into numeric features for analysis
- Visualized key insights and trends across students' scores, study habits, and attendance
- Identified at-risk students based on low attendance or low average score

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn (LabelEncoder, OrdinalEncoder)

## Key Insights
- Most students study around 4 hours daily
- Students with higher attendance generally have better overall scores
- Small percentage of students are at risk due to low attendance or scores
- Data cleaning revealed inconsistencies in categorical values (e.g., 'Postgraduate' vs 'Post Graduate', 'Notes' vs 'Notesss')
- Outliers were handled carefully to maintain meaningful extreme cases (like 0 scores)

## Learning Outcomes
- Data wrangling and preprocessing real-world datasets
- Univariate and multivariate analyses
- Feature engineering and encoding
- Statistical analysis and visualization for actionable insights
- Working with ordinal and categorical data

## Project Files
- `student_data_uncleaned.csv` : Original raw dataset
- `Student_Performance_Analysis.ipynb` : Jupyter Notebook with full analysis pipeline
- Visualizations and insights embedded in the Notebook
