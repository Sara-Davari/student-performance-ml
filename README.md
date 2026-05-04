# Student Performance Predictor
This project uses machine learning to predict whether a student will pass or fail their test based on study hours, daily habits, previous test score, etc...

Input: gender, age, study_hours, attendance_rate, parent_education, internet_access, extracurricular_activities, previous_score, final_score. 

Model: SVM

Output: pass: 1 or fail: 0

How it works:
1. Load the dataset
2. Inspect the dataset
3. Using Label Encoder to turn all data to integers
4. Re-inspecting data after changes
5. Understand the relationship of columns
6. Split the data into training and testing sets
7. Train a classification model (SVM)
8. Evaluate the model's accuracy

Results:
The model achieved a 96% accuracy on the test data.

What I learned:
How to avoid overfitting.
How to use Label Encoder to turn strings to numbers in a dataset.
How to split data for train and test.

Future Improvements:
Use a larger dataset.
Try more models.
