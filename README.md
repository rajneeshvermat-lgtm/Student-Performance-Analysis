# Student Performance Analysis and Prediction

## AICTE | IBM SkillsBuild Data Analytics with AI Academic Internship 2026

**Student:** Rajneesh Verma  
**Branch:** B.Tech - Computer Science and Engineering  
**Institution:** Uttar Pradesh Textile Technology Institute, Kanpur

## Project Description

This project demonstrates a complete data analytics and machine-learning workflow for analyzing student academic performance. It covers data preparation, exploratory data analysis, visualization, feature analysis, prediction and model evaluation.

The submitted notebook generates a synthetic educational dataset with 500 records so the project can run without exposing private student information.

## Objectives

- Inspect student-performance data.
- Perform data-quality checks and preprocessing.
- Explore relationships among academic and behavioral variables.
- Create informative visualizations.
- Predict final score using Random Forest Regression.
- Evaluate the model using MAE, RMSE and R².
- Communicate findings, limitations and future improvements.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Dataset

The primary dataset is generated reproducibly inside the notebook using a fixed random seed.

For extension, the public UCI Student Performance Dataset can be used:

https://archive.ics.uci.edu/dataset/320/student+performance

## Project Structure

```text
RajneeshVerma_StudentPerformanceAnalysis/
├── RajneeshVerma_StudentPerformanceAnalysis.ipynb
├── requirements.txt
├── RajneeshVerma_ProjectReport.docx
└── README.md
```

## Setup and Run

1. Install Python 3.9 or newer.
2. Optional: create a virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Start Jupyter:

```bash
jupyter notebook
```

5. Open `RajneeshVerma_StudentPerformanceAnalysis.ipynb`.
6. Run all cells from top to bottom.

## Machine Learning

A `RandomForestRegressor` is used to predict `final_score`.

Evaluation metrics:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Because the primary dataset is synthetic, model performance is for educational demonstration only.

## Key Variables

- Study hours
- Attendance percentage
- Previous score
- Assignment completion percentage
- Sleep hours
- Internet access
- Extracurricular participation

## Limitations

The synthetic dataset is not representative of any particular institution or population. The model must not be used for grading, admissions, disciplinary action or other high-stakes decisions. A real deployment would require privacy protection, representative data, fairness testing, validation and human oversight.

## Future Scope

- Use a larger public dataset.
- Compare several ML algorithms.
- Add cross-validation and hyperparameter tuning.
- Build a Streamlit dashboard.
- Add explainable-AI methods such as SHAP.

## Author

**Rajneesh Verma**  
B.Tech - Computer Science and Engineering  
Uttar Pradesh Textile Technology Institute, Kanpur
