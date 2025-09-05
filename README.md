# Titanic-Survival-Prediction

📌 Overview
This project is based on the classic Titanic dataset, where the goal is to predict whether a passenger survived or not using machine learning.
It demonstrates the full data science workflow: data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

📂 Dataset
The dataset contains information about passengers such as:
PassengerId → Unique ID
Pclass → Ticket class (1st, 2nd, 3rd)
Name → Passenger name
Sex → Gender
Age → Age in years
SibSp → Number of siblings/spouses aboard
Parch → Number of parents/children aboard
Ticket → Ticket number
Fare → Ticket fare
Cabin → Cabin number
Embarked → Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Survived → Survival (0 = No, 1 = Yes)

⚙️ Steps Performed
1. Data Preprocessing
-Handled missing values (Age → median, Embarked → mode).
-Converted categorical data (Sex, Embarked) into numerical format.
-Feature engineering: created FamilySize and other useful features.

2. Exploratory Data Analysis (EDA)
-Visualized survival rates across gender, class, age groups, and family size.
-Used plots (bar charts, histograms, heatmaps) to understand feature relationships.

3. Model Building
-Algorithms tested: Logistic Regression, Random Forest, Decision Tree, KNN.
-Split dataset into training and testing sets.
-Evaluated models using accuracy, confusion matrix, and classification report.

4. Feature Importance
-Identified which features (e.g., Gender, Pclass, FamilySize, Age) had the most influence on survival prediction.

📊 Results
Best performing model: Random Forest Classifier.
Achieved accuracy of 0.821.
Key insights: Women and children had higher survival chances, higher-class passengers survived more.
