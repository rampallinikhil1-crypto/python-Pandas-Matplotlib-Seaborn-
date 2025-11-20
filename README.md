🚢 Titanic Survival Data Analysis

This project analyzes the Titanic Dataset to understand which factors affected passenger survival during the tragic shipwreck.
It includes data cleaning, exploratory data analysis (EDA), visualizations, and key insights that help explain survival patterns.

📂 Dataset

File: Titanic-Dataset.csv

Contains passenger details such as:

Name, Age, Sex

Ticket Class (Pclass)

Fare

Cabin

Embarked

Survival Status

🛠 Technologies & Libraries Used

Python

Pandas – data cleaning & manipulation

NumPy – numerical operations

Matplotlib, Seaborn – data visualization

Jupyter Notebook

(Optional) SQL for filtering and analysis queries

📊 Project Workflow
1️⃣ Data Cleaning

Handled missing values in:

Age

Embarked

Cabin (dropped or filled as needed)

Removed duplicates

Converted categorical variables (Sex, Embarked) to numeric

2️⃣ Exploratory Data Analysis (EDA)

Visual exploration to identify survival patterns:

Gender vs Survival

Class (Pclass) vs Survival

Age distribution

Fare distribution

Embarked port and survival

Visuals created:

Countplots (Survived vs Sex)

Barplots (Pclass and Fare)

Histograms

Survival rate charts

3️⃣ Key Insights

Females had a much higher survival rate than males.

1st class passengers survived the most, while 3rd class had the highest casualties.

Children (age < 15) survived more compared to adults.

Passengers with higher fare generally had higher survival chances.

Passengers embarked from Cherbourg (C) had better survival rates than others.
