# Predicting Student Scores

## Overview
This project demonstrates a simple yet effective approach to predicting student scores based on the number of hours they study. The goal is to build a linear regression model that establishes the relationship between hours studied and scores achieved.

## Dataset
The dataset includes:
- `Hours`: Number of hours studied
- `Scores`: Scores obtained in an exam

## Methodology
1. **Data Exploration**: Checked for missing values and verified the structure of the dataset.
2. **Data Preprocessing**: Renamed columns for clarity and ensured data integrity.
3. **Model Training**:
   - Used **Linear Regression** as the predictive model.
   - Split the dataset into training (80%) and testing (20%) subsets.
4. **Evaluation**:
   - Assessed model performance using metrics like **Mean Squared Error (MSE)** and **R-squared (R²)**.
   - Visualized the regression line and actual scores for comparison.
5. **Prediction**: Predicted scores for new inputs, e.g., estimating a student's score for 8 hours of study.

## Results
- **Mean Squared Error (MSE)**: 
- **R-squared Score (R²)**: 

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, matplotlib, scikit-learn, joblib

## How to Run
1. Clone the repository and navigate to the project directory.
2. Ensure the dataset is named `student_scores.csv` and placed in the directory.
3. Run the Python script or Jupyter Notebook provided.
4. View predictions and visualizations.

## Usage
- Predict new scores: Modify the `hours` variable in the script.
- Save the model: The trained model is saved as `student_score_model.pkl` for reuse.

## Acknowledgments
This project is part of the **Future Interns Machine Learning Internship**, focusing on foundational machine learning concepts like regression analysis.

