Machine Learning & Python Foundations — Weekly Progress
Overview

This repository contains my learning progress across multiple weeks covering:

Core Python (problem solving + OOP)
Data Analysis (NumPy, Pandas)
Data Visualization (Matplotlib)
Machine Learning (Regression + Intro to Classification)

I have completed Weeks 1–3 assignments and am currently studying Week 4 concepts (Classification & Logistic Regression).

Week 1 — Python Fundamentals & Problem Solving
Concepts Covered
1. Functions and logic building
2. String manipulation
3. Recursion
4. Stack-based problem solving
5. Object-Oriented Programming (OOP)
6. Classes & objects
7. Inheritance

Assignments Implemented
1. Caesar Cipher
  Encrypts and decrypts text using character shifting
  Handles:
    Uppercase & lowercase
    Wrap-around logic
    Non-alphabet characters unchanged

2. Balanced Brackets
Validates bracket expressions: () [] {}
Uses stack-based approach
Ensures proper nesting and ordering

3. Flatten Nested List
Converts deeply nested lists into a flat list
Implemented using recursion

4. Run-Length Encoding
Compression: "aaabb" → "3a2b"
Decompression implemented as well

5. Student Report Card (Class-Based)
Created a Student class with:
Grade storage
Average calculation
Top subject identification
Report generation

6. Shapes with Inheritance (Bonus)
Base class: Shape
Derived classes:
Circle
Rectangle
Demonstrates:
Method overriding
Polymorphism


Week 2 — Data Analysis & Visualization
Libraries Used
NumPy
Pandas
Matplotlib

1. NumPy (Numerical Computing)
Key Operations:
Array creation & manipulation
Statistical functions:
Mean, Std Dev
Matrix operations (transpose)

Student Marks Analysis
Performed:
Total & average marks per student
Subject-wise max/min
Broadcasting (adding grace marks)
Conditional filtering (marks < 70 → 0)
Topper identification

2. Pandas (Data Handling)
Dataset Operations:
CSV file loading
Data inspection:
.head(), .tail(), .info(), .describe()
Data filtering
Column creation:
Total Marks
Average Marks
Analysis:
High-performing students
Subject-wise averages
Gender distribution
Sorting & ranking

3. Matplotlib (Visualization)
Plots Created:
Line Plot (student performance)
Bar Chart (subject averages)
Histogram (marks distribution)
Pie Chart (grade distribution)
Scatter Plot (attendance vs marks)
Subplots (multiple visualizations)

4. Final CSV Project
Combined NumPy + Pandas + Matplotlib
Tasks included:
Data cleaning
Feature creation
Statistical analysis
Visualization dashboard


Week 3 — Regression Models (Machine Learning)
Concepts Covered
Supervised Learning
Regression Models
Model Evaluation

Dataset Used
California Housing Dataset (from sklearn)

Models Implemented
1. Linear Regression
Trained using different train-test splits:
80:20, 70:30, 60:40, 90:10
Observed:
Model coefficients
Intercept
Performance metrics

2. Ridge Regression
L2 Regularization
Tested multiple alpha values

3. Lasso Regression
L1 Regularization
Compared sparsity and performance

4. Evaluation Metrics:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score


Week 4 — Classification (Currently Studying)
Topics Covered
Classification Basics
Predict categories instead of continuous values

Examples:
Spam detection
Pass/Fail prediction

Why Not Linear Regression?
Outputs are not bounded (not in [0,1])
No probabilistic interpretation
Sensitive to outliers
Logistic Regression
Sigmoid Function

Maps any value → probability (0 to 1)
Log-Odds (Logit)
Linear relationship in log space

Classification Types
1. Binary Classification
Two classes (0/1)
2. Multiclass Classification
More than 2 classes
Approaches:
One-vs-All (OvA)
One-vs-One
Softmax Regression (direct method)

Decision Boundary
Defined by:
Linear separator (hyperplane)

Prediction Logic
Convert probability → class using threshold:
Default: 0.5
Threshold tuning:
Lower → fewer false negatives
Higher → fewer false positives

Current Status

Week 1 — Completed
Week 2 — Completed
Week 3 — Completed
Week 4 — In Progress

Data → Processing → Visualization → Model → Evaluation
Transitioning from Regression → Classification
