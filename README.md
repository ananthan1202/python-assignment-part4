# python-assignment-part4
#Student Performance Analysis & Prediction

##Overview
This project analyzes a student performance dataset, creates meaningful visualizations, and builds a machine learning model to predict whether a student will pass or fail.

# Dataset
The dataset ('students.csv') contains information about 15 students, including:
- Subject scores: math, science, english, history, pe
- Attendance percentage
- Study hours per day
- Target variable: 'passed' (1 = Pass, 0 = Fail)

##Tasks Completed

##Task 1 — Data Exploration (Pandas)

- Loaded dataset using pandas
- Displayed first 5 rows
- Checked shape and data types
- Generated summary statistics
- Counted pass/fail students
- Computed average scores by group
- Identified top-performing student


##Task 2 — Data Visualization (Matplotlib)
Created and saved 5 plots:

1. Bar chart — average score per subject
2. Histogram — distribution of math scores
3. Scatter plot — study hours vs average score
4. Box plot — attendance (pass vs fail)
5. Line plot — math & science scores by student

##Task 3 — Data Visualization (Seaborn)

- Bar plots comparing math & science scores (pass vs fail)
- Scatter plot with regression lines (attendance vs avg score)
- Compared Seaborn vs Matplotlib in comments


##Task 4 — Machine Learning (scikit-learn)

- Split data into training and testing sets
- Scaled features using StandardScaler
- Trained Logistic Regression model
- Evaluated accuracy on test data
- Compared predicted vs actual results
- Analyzed feature importance
- Predicted outcome for a new student


#Outputs

- Multiple '.png' visualization files
- Model predictions and accuracy results
- Feature importance chart

##Key Insights

- Higher study hours and attendance generally lead to better performance
- Certain subjects contribute more to predicting pass/fail
- Model works despite small dataset (demonstration purpose)


#Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn


##How to Run
1. Open the notebook 'part4_visualization_ml.ipynb'
2. Run all cells.
