Task 2: Data Cleaning & Missing Value Handling
 AI & ML Internship

Task Name: Data Cleaning & Missing Value Handling
Language: Python
Libraries: Pandas, NumPy, Matplotlib

 Objective

The objective of this task is to perform data cleaning and missing value handling on a real-world dataset.
This task focuses on identifying missing values, visualizing missing data patterns, applying appropriate imputation techniques, and improving overall data quality before further analysis or machine learning.

 Dataset Used

House Prices Dataset
(Alternative dataset: Medical Appointment No Shows)

The dataset contains a mix of numerical and categorical features with missing values.

 Tools & Technologies

Python

Pandas

NumPy

Matplotlib

Google Colab

 Steps Performed
1️ Load Dataset

Uploaded the CSV dataset using Google Colab

Loaded data into a Pandas DataFrame

2️ Identify Missing Values

Used .isnull().sum() to detect missing values in each column

3️ Visualize Missing Data

Created bar charts to visualize missing value distribution across columns

4️ Handle Missing Values

Numerical columns: Missing values filled using median imputation

Categorical columns: Missing values filled using mode imputation

5️ Remove High Missing Columns

Dropped columns with more than 40% missing values

6️ Validate Cleaned Dataset
Verified that missing values were handled correctly

Compared dataset size before and after cleaning

7️ Save Cleaned Dataset

Exported the cleaned dataset as Cleaned_Dataset.csv

 Results

Missing values successfully handled

Improved data consistency and quality

Dataset prepared for further analysis or machine learning models

 Project Structure
Task-2-Data-Cleaning/
│
├── README.md
├── Dataset.csv
├── Cleaned_Dataset.csv
└── Task2_Data_Cleaning.ipynb

 Interview Questions Covered
Difference between mean vs median imputation

When should rows or columns be dropped?

Why is missing data harmful?

What is data leakage?

What is data quality?

 Final Outcome

This task provided practical experience in data preprocessing, a critical step in any AI/ML workflow.
It helped build a strong understanding of handling missing data in real-world datasets.# Task-2-
exploratory data analysis on houseprice dataset
