🚢 Titanic Survival Prediction:
 This project aims to analyze the Titanic passenger dataset and build a machine learning model to predict whether a passenger survived or not based on various features like Age, Sex, Class, and Fare.

📌 Project Objectives:
 Perform Exploratory Data Analysis (EDA) to understand the data.

 Handle missing values and clean the dataset.

 Identify key factors that influenced survival rates.

 Build a Logistic Regression model for classification.

 Evaluate the model using performance metrics like a Confusion Matrix.

🛠️ Tech Stack:
 Language: Python

 Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

 Environment: Jupyter Notebook

🚀 Workflow:
Data Cleaning: Dropped unnecessary columns (PassengerId, Name, Ticket, Cabin) and handled missing values in the 'Age' column using the Mean strategy.

Outlier Handling: Used the Interquartile Range (IQR) method to handle outliers in the 'Fare' column.

Feature Encoding: Converted categorical features (Sex, Embarked) into numerical values.

Data Visualization: Created Bar charts and Boxplots to analyze survival probability by Gender and Passenger Class.

Model Building: Trained a Logistic Regression model to predict survival.

📊 Key Results:
 Gender Analysis: Female passengers showed a significantly higher survival rate than males.

 Class Analysis: Passengers in First Class had a better chance of survival compared to Second and Third classes.

 Model Accuracy: The model performed well with balanced predictions for both survived and non-survived classes, as shown in the Confusion Matrix.
