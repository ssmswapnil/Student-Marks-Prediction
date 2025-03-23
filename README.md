Student Marks Prediction

Project Overview

This project predicts a student's expected marks based on the number of hours studied and attendance percentage using a Linear Regression Model. The model is trained on a dataset of 1000 student records and evaluates performance using R² score.

Tech Stack

Programming Language: Python

Libraries Used: NumPy, Pandas, Matplotlib, Scikit-Learn

Dataset

The dataset consists of three key features:

Hours Studied: Number of hours a student studied.

Attendance Percentage: Percentage of classes attended by the student.

Marks Obtained: The final marks scored by the student.

Model Implementation

Data Preprocessing:

Loaded and cleaned the dataset using Pandas.

Normalized the feature values to improve model performance.

Training the Model:

Implemented Linear Regression to find the relationship between study hours, attendance, and marks.

Used Gradient Descent to optimize the cost function and update model parameters.

Evaluation:

Measured model accuracy using R² score.

Plotted cost function vs iterations to visualize convergence.

How to Run

Install required libraries:

pip install numpy pandas matplotlib scikit-learn

Run the Python script to train and test the model:

python student_marks_prediction.py

Results

The model successfully predicts student marks based on study hours and attendance.

Achieved a high R² score indicating strong correlation between inputs and target variable.

Future Improvements

Use additional features such as previous test scores and study patterns.

Experiment with advanced regression techniques like Polynomial Regression or Neural Networks.
