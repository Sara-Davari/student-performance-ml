# Student Performance Predictor
This project uses machine learning to predict whether a student will pass or fail their test based on study hours, daily habits, previous test score, etc...

Input: gender, age, study_hours, attendance_rate, parent_education, internet_access, extracurricular_activities, previous_score, final_score. 

Model: SVM (Support Vector Machine)

Output: pass: 1 or fail: 0

How it works:
1. Loading the dataset
2. Inspecting the dataset
3. Using Label Encoder to turn all data to integers
4. Re-inspecting the dataset after changes
5. Understanding the relationship of columns
6. Splitting the dataset into training and testing sets
7. Training a classification model (SVM)
8. Evaluate=ing the model's accuracy

Results:
The model achieved a 96% accuracy on the test data.

What I learned:
How to avoid overfitting.
How to use Label Encoder to turn strings to numbers in a dataset.
How to split data for train and test.

Future Improvements:
Use a larger dataset.
Try more models.
