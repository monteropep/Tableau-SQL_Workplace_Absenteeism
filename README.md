# A study on Absenteeism with the Integration of Python, SQL & Tableau 2019.

This project is a part of the learning milestone of a Udemy course delivered by [365 Careers](https://www.udemy.com/course/python-sql-tableau-integrating-python-sql-and-tableau/).

   Author [Jose Montero](https://github.com/monteropep) [LinkedIn](https://www.linkedin.com/in/jose-montero-8a517b129/)

## Project Status: [Completed]  :nerd_face:

## Project Objective

A real-life example centered around the 'Absenteeism at Work' was introduced in this course. 
We are required to investigate and explore the problem of 'Absenteeism at Work' which involved:

 - Download the Dataset
 - Data Preprocessing and Cleaning
 - Applying a **Logistic Regression** Model
 - Train & Test the Model
 - Connect and Build a SQL Database
 - Data Visualization with Tableau

## Environment Prerequisites

`Jupyter Notebook` for Python scripting - `MySQL` for Database/Source - `Tableau 2019` for Data Visualization

## Instructions

  1. Downloaded the database
  2. Run and execute the [IPython file for Machine Learning Pipeline](Project_Absenteeism.ipynb). The following will be covered, and return a prediction.
  
    1. Import Dataset
    2. Data Preprocessing
        2.1 Remove Irrelevant Data
        2.2 Convert Variables to Dummies
            2.2.1 Group the Reasons for Absence
            2.2.2 Concatenate Column Values
        2.3 Convert Timestamp
            2.3.1 Extract the Month Value
            2.3.2 Extract the Day of the Week
        2.4 Convert Categorization Variable
    3. Load the Processed Data
        3.1 Create the Target
        3.2 Standardize the Data
        3.3 Train-Test Split
    4. Applying Logistic Regression
        4.1 Find Intercept and Coefficients
        4.2 Test the Model
    5. Save the Model
   
  3. Run and execute the [IPython file for integrating Python & MySQL](Absenteeism_Integration.ipynb).
    
    1. Import Modules
    2. Link to SQL Database
    3. Create the Insert Statement
    4. Execute

Screenshot of the MySQL Dataset: <img src="MySQL_Database.png">

  4. Extract the dataset from `MySQL`as [CSV](Absenteeism_predictions.csv).
  5. Import in `Tableau 2019`. Tableau workbook for this project can be viewd and downloaded from TableauPublic. 
  
Screenshot of the Dashboard: Relationship of Age and Absenteeism Probability: <img src="Tableau's worksheets/Age vs Probability.jpeg">

Screenshot of the Dashboard: Relationship of Transportation Expense and Absenteeism Probability: <img src="Tableau's worksheets/Transportation Expense vs Probability.jpeg">

Screenshot of the Dashboard: Relationship of Reasons for Absenteeism and Absenteeism Probability: <img src="Tableau's worksheets/Reasons vs Probability.jpeg">


  
