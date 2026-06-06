# ShagunGarg53

# Student Performance Prediction using Machine Learning
## Project Overview
This project predicts student exam scores using different Machine Learning Regression algorithms and compares their performance.
The dataset contains information related to student study habits, attendance, sleep patterns, internet usage, assignment completion, previous scores, etc.
The objective is to determine which regression model provides the best prediction accuracy.

## Dataset Features
Input Features:
- Study Hours
- Attendance
- Sleep Hours
- Internet Usage
- Assignments Completed
- Previous Score

Target Variable:
- Exam Score

Additional Column:
- Placement Status (not used for regression)

---

## Machine Learning Models Used

### 1. Multiple Linear Regression
Used to model linear relationships between independent variables and exam scores.

### 2. Polynomial Regression
Used to capture nonlinear relationships between features and exam scores.

### 3. Support Vector Regression (SVR)
Used to perform regression using Support Vector Machines.

### 4. Random Forest Regression
Used ensemble learning with multiple decision trees.

---

## Project Workflow:

### Step 1: Import Libraries
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Step 2: Load Dataset
Read CSV dataset using Pandas.

### Step 3: Data Preprocessing
- Handle missing values using SimpleImputer
- Split dataset into training and testing sets

### Step 4: Train Models
Train multiple regression algorithms.

### Step 5: Make Predictions
Generate predicted exam scores.

### Step 6: Evaluate Models
Compare model performances using R² Score.

### Step 7: Visualization
Visualize Actual vs Predicted values.

---

## Model Performance
| Model | R² Score |
|------|------|
| Support Vector Regression | 0.6164 |
| Multiple Linear Regression | 0.6646 |
| Polynomial Regression | 0.7326 |
| Random Forest Regression | 0.7067 |

### Best Performing Model:

**Polynomial Regression**
R² Score:
0.7326

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
---

## Future Improvements
- Hyperparameter tuning
- Cross Validation
- Feature Engineering
- Additional regression models

---

## Author
Shagun Garg
