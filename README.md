Titanic Dataset: Data Cleaning & Preprocessing (Task 1)
1. Problem Statement
The objective of this task is to clean and prepare the raw Titanic dataset for further analysis. The dataset contained missing values, inconsistent data types, and unoptimized column names that needed to be fixed to ensure accurate results.  

2. Dataset Details
Source: Titanic Dataset (Kaggle).  

Key Columns: Survived, Pclass, Age, Sex, Embarked, Cabin, SibSp, Parch.

3. Approach
Handling Missing Values: Used Mean imputation for 'Age' and Mode for 'Embarked'. Dropped the 'Cabin' column due to more than 70% missing data.  

Removing Duplicates: Verified the dataset for any redundant rows.  

Data Type Conversion: Converted the 'Age' column to Integer for better calculation.  

Renaming Columns: Changed technical headers like 'Pclass' and 'Fare' to 'Ticket_Class' and 'Ticket_Price' for better readability.  

4. Results
A fully cleaned dataset with zero null values.  

Optimized data types and user-friendly column names ready for Exploratory Data Analysis (EDA).
