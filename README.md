# Student Pass/Fail Prediction

## About
This project predicts whether a student will Pass or Fail using Machine Learning.

The model uses:
- Gender
- Study Hours
- Attendance
- Assignment Marks

## Machine Learning

I used:
- Random Forest Classifier
- Scikit-learn
- Pandas
- SHAP
- Matplotlib
- Seaborn

## Results

The model achieved **100% accuracy on the test data**.
I also performed:
- Feature Importance
- SHAP Analysis
- Bias Analysis
- Student Prediction

## Example
Input:
- Gender: Male
- Study Hours: 5
- Attendance: 79%
- Assignment Marks: 57
Prediction:
**PASS**
Pass Probability: **61%**
## Files
- `student_pass_fail_prediction.ipynb` - Main notebook
- `student_data.csv` - Dataset
- `feature_importance.png` - Feature importance graph
- `shap_plot.png` - SHAP graph
- `bias_analysis.png` - Bias analysis graph
