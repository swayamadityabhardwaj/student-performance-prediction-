 Student Performance Prediction Using Machine Learning

Project Overview

This project uses Machine Learning algorithms to predict students' final mathematics grades based on their academic and personal information.

The main objective is to analyse student data, identify important factors related to academic performance, and build predictive models using Python.

 Project Objectives

- Analyse student academic performance.
- Explore and visualise the dataset.
- Select important features for prediction.
- Train Machine Learning models.
- Compare model performance using evaluation metrics.
- Predict the final grade of a new student.

 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

 Dataset Information

The project uses the Student Performance dataset, specifically the `student-mat.csv` file.

- Total records: 395 students
- Total columns: 33
- Prediction target: G3 (Final Mathematics Grade)

 Features Selected

The following eight features were selected:

1. Age
2. Study Time
3. Previous Failures
4. Absences
5. Mother's Education
6. Father's Education
7. First Period Grade (G1)
8. Second Period Grade (G2)

 Machine Learning Algorithms

Two regression algorithms were implemented:

 1. Linear Regression

Used to predict final student grades by learning linear relationships between input features and the target variable.

 2. Random Forest Regressor

Used to predict final student grades by combining multiple decision trees.

 Model Evaluation Results

| Evaluation Metric | Linear Regression | Random Forest |
|---|---:|---:|
| MAE | 1.34 | 1.08 |
| RMSE | 2.13 | 1.76 |
| R² Score | 0.78 | 0.85 |

Random Forest performed better on the test dataset, achieving an R² score of 0.85.

 Conclusion

This project demonstrates how Machine Learning can be used to analyse and predict student academic performance.

Both Linear Regression and Random Forest were implemented and evaluated. Random Forest achieved better results on the selected test split.

This project helped develop practical knowledge of Python programming, data analysis, data visualisation, Machine Learning model training, and model evaluation.

 Limitations

- The dataset contains only 395 student records.
- The results are based on one train-test split.
- Predictions are estimates and are not guaranteed examination results.
- G1 and G2 are included as input features, so predictions assume earlier examination grades are already available.

 Project Author

Swayam Aditya Bhardwaj

Bachelor of Technology – Artificial Intelligence and Data Science
