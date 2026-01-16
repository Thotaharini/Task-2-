Task 2: Data Cleaning & Missing Value Handling
 Internship: AI & ML Internship

Task Name: Data Cleaning & Missing Value Handling
Programming Language: Python

 Objective

The objective of this task is to perform data cleaning and missing value handling on a real-world dataset. This task helps in understanding how to identify missing data, handle it appropriately, and improve overall data quality before further analysis or machine learning.

 Dataset

Medical Appointment No Shows Dataset
(CSV format)

The dataset contains both numerical and categorical columns with missing values.

 Tools & Libraries Used

Python

Pandas

NumPy

Matplotlib

Google Colab

 Steps Performed
1️ Load Dataset

Uploaded the dataset using Google Colab

Loaded the CSV file into a Pandas DataFrame

2️ Identify Missing Values

Used .isnull().sum() to check missing values in each column

3️ Visualize Missing Data

Created a bar chart to visualize missing value distribution

4️ Handle Missing Values

Numerical columns: Filled missing values using median imputation

Categorical columns: Filled missing values using mode imputation

5️ Remove High Missing Columns

Removed columns having more than 40% missing values

6️ Validate Cleaned Data

Rechecked missing values after cleaning

Compared dataset shape before and after cleaning

7️ Save Cleaned Dataset

Exported the cleaned dataset as Cleaned_Dataset.csv

 Results

Missing values successfully handled

Dataset cleaned and ready for analysis or modeling

Improved data quality and consistency

 Project Structure
Task-2-Data-Cleaning/
│
├── README.md
├── Medical_Appointment_Dataset.csv
├── Cleaned_Dataset.csv
└── Task2_Data_Cleaning.ipynb

 Interview Questions Covered

Mean vs Median Imputation

When should rows or columns be dropped?

Why is missing data harmful?

What is data leakage?

What is data quality?

 Final Outcome

This task provided hands-on experience in data preprocessing, which is a crucial step in any AI/ML pipeline. It strengthened understanding of real-world data issues and best practices for handling missing data.
