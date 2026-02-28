💳 Credit Card Fraud Detection:
 This project focuses on building a machine learning model to identify fraudulent credit card transactions. Given the highly imbalanced nature of fraud data, the project emphasizes data preprocessing and model evaluation to ensure high precision and recall.

📌 Project Objectives:
 Perform Exploratory Data Analysis (EDA) to understand transaction patterns.

 Handle imbalanced datasets to improve fraud detection accuracy.

 Build a classification model using Logistic Regression.

 Evaluate the model using performance metrics like Accuracy, Precision, Recall, and F1-score.

🛠️ Tech Stack:
 Language: Python

 Libraries: Pandas, NumPy, Scikit-learn

 Model: Logistic Regression

 Environment: Jupyter Notebook

🚀 Workflow:
 Data Loading: Importing the transaction dataset containing 31 features (Time, V1-V28, Amount, and Class).

 Data Cleaning: Checking for missing values and inspecting data types.

 Handling Imbalance: Analyzing the distribution of "Normal" vs. "Fraud" transactions to prepare the data for training.

 Feature Selection: Dropping irrelevant columns and splitting data into features (X) and targets (y).

 Model Training: Training a Logistic Regression model with a maximum of 2000 iterations.

 Evaluation: Generating a Classification Report to analyze the model's ability to catch fraud.

📊 Key Results:
 Imbalanced Class Handling: Successfully addressed the data skewness where fraud cases are much rarer than legitimate ones.

 Model Performance: The model achieved high accuracy and balanced precision/recall scores for the training data.
