# Predicting Student Performance Based on Study Hours and Attendance

## Project Overview

This project aims to predict student performance based on two key factors: **study hours** and **attendance percentage**. By utilizing machine learning techniques, the goal is to build a model that helps educators identify students at risk of poor performance and take necessary actions to improve their outcomes. This project includes data collection, preprocessing, model training, evaluation, and visualizations to support the prediction of student exam scores.

## Objectives

- Predict student exam scores based on study hours and attendance.
- Evaluate the relationship between study habits, attendance, and academic performance.
- Provide a tool for educators to identify at-risk students and offer interventions.

## Dataset

The dataset used in this project includes information about **study hours**, **attendance percentage**, and the **exam score** for each student. The data is structured as follows:

| Student ID | Study Hours | Attendance (%) | Exam Score |
|------------|-------------|----------------|------------|
| 1          | 5           | 80             | 75         |
| 2          | 10          | 90             | 85         |
| 3          | 15          | 70             | 65         |
| 4          | 12          | 85             | 80         |
| 5          | 8           | 60             | 70         |

**Note**: The dataset contains 100 students' data and is used to train and evaluate the model.

## Methodology

### 1. **Data Collection**

The data for this project was collected from publicly available educational datasets, such as those found on platforms like Kaggle. The dataset consists of three columns: Student ID, Study Hours, and Exam Score.

### 2. **Data Preprocessing**

Data preprocessing steps include:
- Handling missing values: We ensure there are no missing or incomplete entries.
- Feature scaling: Normalizing the **Study Hours** and **Attendance (%)** to make the data suitable for machine learning models.
- Data splitting: Splitting the dataset into a **training set** and a **testing set** for model evaluation.

### 3. **Modeling**

A **Linear Regression** model was used to predict the **Exam Score** based on **Study Hours** and **Attendance (%).** This model was chosen due to its simplicity and effectiveness in predicting continuous values.

### 4. **Model Evaluation**

To assess the performance of the model, the following metrics were used:
- **Mean Absolute Error (MAE)**: Measures the average magnitude of the errors in predictions.
- **Mean Squared Error (MSE)**: Measures the average squared difference between the predicted and actual values.
- **R-squared (R²)**: Indicates the proportion of the variance in the dependent variable (Exam Score) that is predictable from the independent variables (Study Hours and Attendance).

## Results

### Descriptive Statistics

The following descriptive statistics summarize the dataset:

- **Study Hours**: Mean = 10.69 hours, Std = 3.28 hours
- **Attendance (%)**: Mean = 79.35%, Std = 9.72%
- **Exam Score**: Mean = 80.39, Std = 7.11

### Correlation Matrix

The correlation matrix shows the relationship between different features:

- **Study Hours and Attendance (%)**: 0.68 (moderate positive correlation)
- **Attendance (%) and Exam Score**: 0.91 (strong positive correlation)
- **Study Hours and Exam Score**: 0.76 (moderate positive correlation)

### Model Coefficients

The Linear Regression model gives the following coefficients:

- **Intercept**: 31.36
- **Study Hours Coefficient**: 0.47
- **Attendance Coefficient**: 0.56

This suggests that both study hours and attendance positively influence exam scores.

### Evaluation Metrics

- **Mean Absolute Error (MAE)**: 1.96
- **Mean Squared Error (MSE)**: 5.93
- **R-squared (R²)**: 0.89

The model performs well with an **R-squared value of 0.89**, indicating that it explains 89% of the variance in the exam scores.

## Setup Instructions

### Requirements (Tools)

- Python 3.x
- Required Python libraries: 
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `matplotlib`
  - `seaborn`


