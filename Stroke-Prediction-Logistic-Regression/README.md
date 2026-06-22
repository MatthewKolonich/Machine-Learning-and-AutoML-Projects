# Stroke Prediction Logistic Regression

## Project Overview
This project uses logistic regression to predict stroke risk from a healthcare dataset containing demographic, medical, and lifestyle variables. The goal was to build an interpretable classification model that could identify patients who may be at higher risk of stroke.

## Dataset
The project uses the `healthcare_dataset_stroke_data.csv` dataset, which includes variables such as age, hypertension, heart disease, average glucose level, BMI, smoking status, work type, residence type, gender, and stroke outcome.

## Methods Used
- Exploratory data analysis
- Missing value handling
- One-hot encoding
- Feature scaling
- Logistic regression
- Class imbalance handling
- Confusion matrix evaluation
- Precision, recall, F1-score, and accuracy analysis

## Key Results
The final balanced logistic regression model achieved approximately 72.85% accuracy. More importantly, stroke-case recall improved significantly, helping the model identify a larger share of actual stroke cases.

## Key Findings
- Age was the strongest predictor of stroke risk.
- Average glucose level, hypertension, smoking status, and work type also contributed to predictions.
- Accuracy alone was not enough because the dataset was highly imbalanced.
- Recall was especially important because missing a potential stroke case could have serious healthcare consequences.

## Files Included
- `stroke-prediction-logistic-regression-report.pdf`
- `stroke-prediction-model.ipynb`
- `healthcare_dataset_stroke_data.csv`

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Future Improvements
Future work could compare logistic regression with Random Forest, Gradient Boosting, XGBoost, or neural network models. Additional improvements could include SMOTE, more advanced imputation methods, and additional healthcare variables.
