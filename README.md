# Student Performance Predictor
This project uses machine learning to predict whether a student will pass or fail their test based on study hours and daily habits.
Input: gender, age, study_hours, attendance_rate, parent_education, internet_access, extracurricular_activities, previous_score, final_score. 
Model: SVM
Output: pass: 1 or fail: 0

How it works:
1. Load the dataset
2. Understand the relationship of columns
3. Split the data into training and testing sets
4. Train a classification model (SVM)
5. Evaluate the model's accuracy

Results:
The model achieved a 96% accuracy on the test data.

What I learned:
How to avoid overfitting.
How to use Label Encoder to turn strings to numbers in a dataset.
How to split data for train and test.

Future Improvements:
Use a larger dataset.
Try more models.
