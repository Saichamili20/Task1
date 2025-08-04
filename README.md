Data Cleaning & Preprocessing — Task 1
This Jupyter Notebook focuses on data cleaning and preprocessing using Python's pandas library.

Dataset:
Initially, I used a dataset Medical Appointment No shows from Kaggle, but it didn’t require much cleaning.

So, with the help of ChatGPT, a custom messy dataset was created to practice common data cleaning tasks.

 Operations Performed:
Loaded the dataset using pandas

Handled missing values in:

Name

Email

Age

Gender

Join Date

Salary

Standardized gender values like:

M, F, Unknown, NaN → cleaned to Male or Female

Cleaned invalid emails and dates

Converted data types where needed

Used methods like:

.fillna(), .replace(), .dropna(), .astype(), and string operations

Tools Used:
Python

Jupyter Notebook

Pandas

 File:
Task 1.ipynb — Open this notebook to view the full code and transformations.
