# Task1_datacleaning-and-preprocessing
📌 Project Overview
This project focuses on analyzing the Titanic dataset to understand the characteristics that influenced survival during the disaster. The goal is to explore and visualize data, Import the dataset,handle missing values,onehotencoding, Visualize outliers and generate insights through statistical techniques and plots.

📊 Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook

📁 Dataset
The dataset used is the famous Titanic passenger dataset from Kaggle, containing features like:

Name, Age, Sex, Pclass (Passenger Class)
Fare, Cabin, Embarked
Survived (Target column)

🛠️ Data Cleaning & Preprocessing
Removed the Cabin column due to many missing values.

Filled missing values in:
Age column with the mean age
Embarked column with the most frequent value ('S')
Dropped any rows with remaining missing values.

📈 Exploratory Data Analysis (EDA)
Distribution plots of Age, Fare, and survival status.

Comparison of survival based on:
Gender
Passenger class (Pclass)
Embarkation port
Used updated histplot() instead of deprecated distplot() for KDE visualizations.

🔍 Key Insights
Females had a higher chance of survival compared to males.
Higher class passengers (Pclass 1) had better survival rates.
Younger passengers also showed slightly better survival chances.



