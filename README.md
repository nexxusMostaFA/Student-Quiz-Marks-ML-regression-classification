# Student-Quiz-Marks
📊 Student Performance Data Analysis & Cleaning
This project is a complete data analysis and preprocessing pipeline built with Python (Pandas, NumPy, Matplotlib, Seaborn) for exploring and cleaning a real-world dataset of student quiz scores and attendance. It involves data cleaning, visualization, feature engineering, and correlation analysis to prepare the dataset for further modeling or evaluation.

📁 Dataset
File: marks_final.csv

Context: Contains quiz results (Q1–Q12), attendance indicators, and final marks for students.

Objective: Clean malformed entries, impute missing values, create meaningful features like attendance, and uncover patterns between quiz participation and performance.

🚀 Project Workflow
1. 🔧 Data Cleaning & Preparation
Imported raw data and checked for missing values, duplicates, and non-numeric entries like "AB" and "O AB".

Created a utility function to clean all quizzes by replacing invalid entries with NaN, then filled them with 0.

Generated a new column "Attendance" to quantify how many quizzes each student attended.

Converted quiz scores to numeric format for proper analysis.

2. 📊 Exploratory Data Analysis (EDA)
Visualized attendance distributions, quiz-by-quiz performance, and correlation heatmaps.

Identified redundant features and removed them to reduce duplication.

Analyzed the impact of attendance on final performance using scatter plots and regression visuals.

Focused on the relationship between quiz consistency and final grades.

3. 🧠 Feature Engineering
Created clean datasets (final_num_data and combined versions) ready for modeling or statistical tests.

Prepared inputs that reflect student behavior: attendance, quiz averages, and total performance.

📈 Sample Visualizations
Heatmap of Correlations

Attendance vs. Final Grade scatter

Quiz-wise Score Distribution

All visualizations are built using matplotlib and seaborn with attention to interpretability.

🧰 Tech Stack
Tool	Purpose
Pandas	Data manipulation & cleaning
NumPy	Numerical operations
Matplotlib	Basic plotting
Seaborn	Statistical visualizations
CSV	Dataset format

📦 Folder Structure
bash
Copy
Edit
.
├── ddefeb7d-1f1f-4909-90b2-71578dbb889a.ipynb   # Main notebook
├── marks_final.csv                             # Dataset
├── README.md                                   # This file
✅ Outcomes
Cleaned dataset with reliable numerical values

Quantitative measure of attendance added

Clear insights on how student effort (attendance + quiz performance) impacts final grades

Ready-to-use features for future predictive modeling

