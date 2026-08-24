# Student Performance Prediction using Machine Learning and Explainable AI

## Project Overview

This project predicts whether a student will **PASS or FAIL** based on factors such as:

* Gender
* Study Hours
* Attendance
* Assignment Marks

The system uses a **Random Forest Machine Learning model** along with **Explainable AI techniques like SHAP** to understand feature importance and prediction behavior.

The project also includes:

* Bias Analysis
* Feature Importance Visualization
* SHAP Explainability
* Pass vs Fail Graphs
* User Input Prediction


## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* SHAP


## Project Features

* Student Performance Prediction
* Data Preprocessing
* Random Forest Classification
* Accuracy Evaluation
* Feature Importance Analysis
* SHAP Explainability
* Bias Detection
* Graph Visualization
* User Prediction System


## Dataset Features

| Feature     | Description                        |
| ----------- | ---------------------------------- |
| Gender      | Male / Female                      |
| StudyHours  | Number of study hours              |
| Attendance  | Attendance percentage              |
| Assignments | Assignment marks                   |
| Pass        | Target output (0 = Fail, 1 = Pass) |


## Project Structure

text
Student_Bias/
│
├── analysis.py
├── student_data.csv
├── feature_importance.png
├── shap_plot.png
├── pass_fail_graph.png
└── README.md
