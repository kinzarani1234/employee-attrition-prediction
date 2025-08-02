# Employee Attrition Prediction

This project involves analyzing and predicting employee attrition using IBM HR Analytics data.

##  Problem Statement

The goal is to identify key factors behind employee attrition and build a machine learning model to predict whether an employee is likely to leave the company.

##  Dataset

Kaggle Link: [IBM HR Analytics Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

##  Tools Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

##  Part 1: Exploratory Data Analysis (EDA)

- Total employees vs attrition count
- Age comparison (left vs stayed)
- Attrition rate by department
- Distance from home vs attrition
- Overtime and attrition correlation
- Monthly income impact
- Missing values detection

##  Part 2: Visualizations

- Bar chart: Attrition count
- Boxplot: MonthlyIncome vs Attrition
- Histogram: Age vs Attrition
- Stacked bar chart: Department vs Attrition
- Countplot: JobSatisfaction vs Attrition
- Heatmap: Correlation matrix

##  Part 3: Machine Learning

- Preprocessing: Label Encoding, One-Hot Encoding
- Models used:
  - Logistic Regression
  - Decision Tree / Random Forest
- Model Evaluation:
  - Accuracy
  - Confusion Matrix
  - Classification Report
  - ROC Curve

##  Files Included

- `Employee_Attrition_Analysis.ipynb` (Jupyter Notebook)
- `requirements.txt` (Python dependencies)
- `README.md` (Project documentation)

##  How to Run

```bash
pip install -r requirements.txt
