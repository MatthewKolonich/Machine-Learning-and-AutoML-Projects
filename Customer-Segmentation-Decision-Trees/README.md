# Customer Segmentation Decision Trees

## Project Overview
This project uses Decision Tree Classification to predict customer categories in a telecommunications dataset. The goal was to identify patterns in customer demographics and behavior that could improve segmentation, retention strategies, and targeted marketing.

## Dataset
The project uses the `Telecust1(2).csv` dataset, which includes customer variables such as region, tenure, age, income, marital status, education level, employment history, retirement status, gender, and residential information.

## Methods Used
- Exploratory data analysis
- Distribution analysis
- Correlation analysis
- Decision Tree Classification
- Hyperparameter tuning with GridSearchCV
- Confusion matrix evaluation
- Classification report analysis
- Feature importance visualization

## Key Results
The final tuned Decision Tree model improved accuracy from 28.0% to 38.8% after hyperparameter tuning. More importantly, the final model successfully classified all four customer segments, improving overall business usefulness.

## Key Findings
- Education level was the strongest predictor of customer category.
- Customer tenure was the second strongest predictor.
- Address duration and residential area contributed smaller but meaningful predictive value.
- Model interpretability made it easier to understand customer behavior patterns.

## Files Included
- `customer-segmentation-decision-tree-report.pdf`
- `customer-segmentation-decision-tree-model.ipynb`
- `Telecust1(2).csv`

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Future Improvements
Future improvements could include Random Forest, Gradient Boosting, XGBoost, or clustering-based customer segmentation models to improve predictive performance and uncover hidden customer groupings.
