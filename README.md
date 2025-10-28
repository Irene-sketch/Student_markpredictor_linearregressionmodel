STUDENT MARK PREDICTION USING LINEAR REGRESSION MODEL

This project predicts a student's marks based on the number of study hours using a **simple linear regression model** built in Python.  
It demonstrates basic **data cleaning, visualization, model training, and evaluation** using popular machine learning libraries.

---

# Features
- Handles missing and fake NaN values
- Splits dataset into training and testing sets
- Implements a **Linear Regression** model using `scikit-learn`
- Evaluates model performance using:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score
- Predicts marks for new input hours
- Visualizes regression line vs actual marks using `matplotlib`

---

# Libraries Used
- **pandas** → data manipulation
- **numpy** → numerical operations
- **matplotlib** → data visualization
- **scikit-learn (sklearn)** → ML model building and evaluation

---

# Dataset
The dataset used is `student_info.csv` containing two columns:
- `study_hours` – Number of hours a student studied  
- `student_marks` – Marks scored by the student  

Example:

| study_hours | student_marks |
|--------------|---------------|
| 6.5 | 75 |
| 7.0 | 80 |
| 8.0 | 85 |

---

# Regression Line Equation
After training the model, the regression equation is displayed as:
where:
- `m` → slope (coefficient)
- `c` → intercept

---

# Visualization
The model plots a regression line comparing actual vs predicted marks.

---

# How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/student-marks-prediction.git
   Install required libraries:

pip install pandas numpy matplotlib scikit-learn


2. Run the script:

python student_gradepredictor_lr.py

Output Example:
Regression Line Equation: y = 9.68x + 48.75
Mean Absolute Error: 2.43
Mean Squared Error: 8.17
R2 Score: 0.96
Predicted Marks for 7.5 study hours = 79.89



