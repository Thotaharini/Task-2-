Task 2: Data Cleaning & Missing Value Handling
Internship: AI & ML Internship

Task Name: Data Cleaning & Missing Value Handling
Tools Used: Python (Pandas, NumPy, Matplotlib)

 Objective

The objective of this task is to perform data cleaning and missing value handling on a real-world dataset. This task helps in understanding how to identify, analyze, and handle missing data effectively before applying any machine learning models.

 Dataset Used

House Prices Dataset
(Alternative dataset: Medical Appointment No Shows)

The dataset contains both numerical and categorical features with missing values.

 Tools & Libraries

Python

Pandas

NumPy

Matplotlib

Google Colab (for execution)

 Steps Performed
1️ Load Dataset

Uploaded the dataset using Google Colab file upload

Loaded the CSV file into a Pandas DataFrame

2️ Identify Missing Values

Used .isnull().sum() to detect missing values in each column

3️ Visualize Missing Data

Plotted a bar chart to visualize missing values per column

4️ Handle Missing Values

Numerical Columns: Filled missing values using median imputation

Categorical Columns: Filled missing values using mode imputation

5️ Remove High-Missing Columns

Dropped columns having more than 40% missing values

6️ Validate Cleaned Dataset

Rechecked missing values after cleaning

Compared dataset shape before vs after cleaning
7️ Save Cleaned Dataset

Exported the cleaned dataset as Cleaned_Dataset.csv

 Results

Successfully cleaned the dataset

Removed inconsistencies caused by missing values

Improved data quality for further analysis or modeling

 Repository Structure
 Task-2-Data-Cleaning
  README.md
  Task2_Data_Cleaning.ipynb
  Day3_House_Price_data.csv
  Cleaned_Dataset.csv

 Interview Questions Covered

Difference between mean vs median imputation

When should rows or columns be dropped?

Why missing data is harmful?

What is data leakage?

What is data quality?

 Final Outcome

This task provided hands-on experience in data preprocessing, which is a crucial step in any AI/ML pipeline. It strengthened understanding of data quality and real-world dataset challenges.

 Submission

The GitHub repository link was submitted through the provided internship submission form.

 Author

Name: Your Name Here
Internship Role: AI & ML Intern