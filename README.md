# Task1_datacleaning-and-preprocessing
📌 Project Overview: 
I have completed  my first task of AI & ML INTERNSHIP of Elevate Lab.In this project focuses on analyzing the Titanic dataset to understand the characteristics that influenced survival during the disaster. The goal is to explore and visualize data, Import the dataset,handle missing values,onehotencoding, Visualize outliers and generate insights through statistical techniques and plots.


📊 Technologies Used
1.Python
2.Pandas
3.NumPy
4.Matplotlib
5.Seaborn
6.Jupyter Notebook 


📁 Dataset
The dataset used is the famous Titanic passenger dataset from Kaggle, containing features like:
1.Name, Age, Sex, Pclass (Passenger Class)
2.Fare, Cabin, Embarked
3.Survived (Target column)



🛠️ Data Cleaning & Preprocessing
Removed the Cabin column due to many missing values.


🛠️Filled missing values in:
1.Age column with the mean age
2.Embarked column with the most frequent value ('S')
3.Dropped any rows with remaining missing values.


📈 Exploratory Data Analysis (EDA)
Distribution plots of Age, Fare, and survival status.



🛠️Comparison of survival based on:
Gender
Passenger class (Pclass)
Embarkation port
Used updated histplot() instead of deprecated distplot() for KDE visualizations.



🔍 Key Insights
Females had a higher chance of survival compared to males.
Higher class passengers (Pclass 1) had better survival rates.
Younger passengers also showed slightly better survival chances..



