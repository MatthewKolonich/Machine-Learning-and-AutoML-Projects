# Stroke Prediction Naive Bayes

## Project Overview
This project applies Gaussian Naive Bayes classification to predict stroke risk using demographic, medical, and lifestyle data. The goal was to evaluate how a probability-based classification model performs in identifying high-risk stroke patients.

## Dataset
The project uses the `healthcare_dataset_stroke_data.csv` dataset, which includes variables such as age, hypertension, heart disease, average glucose level, BMI, smoking status, marital status, residence type, work type, gender, and stroke outcome.

## Methods Used
- Exploratory data analysis
- Missing value imputation
- One-hot encoding
- Train-test split with stratification
- Gaussian Naive Bayes classification
- Parameter tuning (`var_smoothing`)
- Balanced priors
- Confusion matrix analysis
- ROC-AUC evaluation

## Key Results
The final model achieved extremely high stroke-case recall (0.98), correctly identifying 61 out of 62 stroke cases. The ROC-AUC score was approximately 0.796, showing meaningful predictive capability.

## Key Findings
- Average glucose level and age were the strongest predictors.
- Hypertension and heart disease also showed strong relationships with stroke risk.
- The model performed extremely well at identifying stroke cases.
- Precision remained low because of a high false positive rate.

## Files Included
- `stroke-prediction-naive-bayes-report.pdf`
- `stroke-prediction-naive-bayes-model.ipynb`

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Future Improvements
Future improvements could include testing Random Forest, XGBoost, Support Vector Machines, and neural networks. Additional balancing techniques such as SMOTE could also improve model precision while maintaining strong recall.
