# Student Grade Prediction Model

## Authors:
- Samuel Nicklaus
- Jakob Kindle
- Lane Swartzendruber
- Alejandro Mirafuentes

# Introduction

In this project, our team focuses on predicting a student's academic performance based on various personal, academic, and social factors using **classification**. We aim to classify students into different grade categories based on inputs such as age, sex, high school type, participation in extracurricular activities, and more. Note that we originally attempted to categorize by every grade, but for a number of reasons this made the accuracy low (Quality of Data, Number of data entries, etc). If you want to run the code with different groupings you can edit the 'grade_mapping' variable in the Data Description code cell.

*Data Source*: [Here](https://www.kaggle.com/datasets/jacksondivakarr/student-classification-dataset?select=student.csv)

*Data Source Description (Via Kaggle):*

This dataset encompasses various aspects related to student performance. Each entry is uniquely identified by an 'Id'. The dataset includes demographic information such as 'Student_Age' and 'Sex'. 'High_School_Type' categorizes the type of high school attended, while 'Scholarship' indicates whether the student has a scholarship. Details about 'Additional_Work' and involvement in 'Sports_activity' provide insights into extracurricular commitments.

'Transportation' outlines the mode of commuting for each student. Academic aspects are captured through 'Weekly_Study_Hours', 'Attendance', and evaluations of 'Reading', 'Notes', and 'Listening_in_Class'. The culmination of these factors is reflected in the 'Grade' column, providing a comprehensive overview of student performance. This dataset serves as a valuable resource for exploring the multifaceted dynamics influencing academic outcomes.

# Data Description

- Student_Age: The age of the student.
- Sex: The gender of the student (e.g., Male, Female).
- High_School_Type: The type of high school the student attended (e.g., State, Private, Other).
- Scholarship: Whether the student has a scholarship (Yes/No).
- Additional_Work: Whether the student does additional work apart from regular studies (Yes/No).
- Sports_activity: Participation in sports activities (Yes/No).
- Transport: Mode of transportation used by the student (e.g., Car, Bike, Public Transport).
- Weekly_Study_Hours: Number of hours the student studies per week.
- Attendance: The attendance percentage of the student.
- Reading: A score evaluating the student’s reading habits.
- Notes: A score evaluating the quality of the student's notes.
- Listening_in_Class: A score evaluating how well the student listens in class.
- Grade: The final grade of the student (e.g., A, B, C, D, F).

# Methodology

### Data Preparation and Cleaning

- Loaded the dataset using Pandas.
- Checked for null values and handled them appropriately.
- Performed encoding of categorical variables.
- Split the dataset into training and testing sets.

### Model Selection

We used the following machine learning models for classification:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

### Model Evaluation

- Used cross-validation to evaluate the models.
- Selected the best model based on accuracy score.
- Tuned the hyperparameters to improve the model performance.

# Feature Selection

Selected features based on their importance and correlation with the target variable (Grade). The features used were:
- Student_Age
- High_School_Type
- Additional_Work
- Weekly_Study_Hours
- Attendance
- Reading
- Notes

# Results

The best model achieved an accuracy score of 0.6087 on the test set. The Random Forest model with 10 estimators was selected as the best model. The most important features identified were:
- High_School_Type_Private
- High_School_Type_State
- High_School_Type_Other
- Additional_Work
- Reading
- Notes
- Student_Age

# Conclusion

While the accuracy result was not as high as expected, it reflects the quality and nature of the dataset. Future improvements could involve using a more comprehensive dataset and applying more sophisticated feature engineering techniques. The project provided valuable experience in end-to-end machine learning model development.

# Disclosures

The use of ChatGPT was used to help make guided decisions, such as methods to clean the dataset, as well as methods to test many different feature combinations against one model (this was before we learned how to do it in lecture).
