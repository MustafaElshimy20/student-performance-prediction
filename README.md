


# Predicting Student Performance Based on Study Hours and Attendance

## Project Overview

This project predicts student exam scores based on two key factors: **study hours** and **attendance percentage**. By using machine learning, we aim to help educators identify at-risk students and provide interventions to improve their outcomes.

## Tools Used

- **Python Libraries**:
  - `pandas`: Data manipulation and analysis.
  - `numpy`: Mathematical operations and array handling.
  - `scikit-learn`: Machine learning library for model building.
  - `matplotlib`: Plotting and visualization.
  - `seaborn`: Data visualization (for statistical plots).

## Dataset

The dataset consists of the following columns:

| Student ID | Study Hours | Attendance (%) | Exam Score |
|------------|-------------|----------------|------------|
| 1          | 5           | 80             | 75         |
| 2          | 10          | 90             | 85         |
| 3          | 15          | 70             | 65         |
| 4          | 12          | 85             | 80         |
| 5          | 8           | 60             | 70         |

**Note**: The dataset contains data for 100 students.

## Methodology

1. **Data Preprocessing**: The data was cleaned, normalized, and split into training and test sets.
2. **Modeling**: A **Linear Regression** model was used to predict **Exam Score** based on **Study Hours** and **Attendance (%)**.
3. **Evaluation**: Model performance was evaluated using metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R-squared (R²)**.

## Results

- **R-squared (R²)**: 0.89, meaning the model explains 89% of the variance in the exam scores.
- **Mean Absolute Error (MAE)**: 1.96, indicating an average deviation of 1.96 points from the actual scores.
- **Mean Squared Error (MSE)**: 5.93, representing the average squared difference between predicted and actual scores.

## Setup Instructions

### Requirements

- Python 3.x
- Install the required libraries:
  ```bash
  pip install pandas numpy scikit-learn matplotlib seaborn
  ```

### Running the Code

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/student-performance-prediction.git
   ```
2. **Navigate to the project folder**:
   ```bash
   cd student-performance-prediction
   ```
3. **Run the script to train and evaluate the model**:
   - To train and evaluate the model, simply run:
   ```bash
   python train_and_evaluate.py
   ```
4. **Generate visualizations**:
   - To generate and view plots, run:
   ```bash
   python visualize.py
   ```

## Contributing

1. Fork the repository by clicking on the **Fork** button at the top-right of this page.
2. Create a new branch:
   ```bash
   git checkout -b new-feature
   ```
3. Commit your changes:
   ```bash
   git commit -m 'Add a new feature'
   ```
4. Push the changes to your fork:
   ```bash
   git push origin new-feature
   ```
5. Open a pull request from your fork to the main repository.




