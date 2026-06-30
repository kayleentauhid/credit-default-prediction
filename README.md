# Credit Default Prediction

## Overview
This project predicts whether a credit card customer will default or not on their next payment using machine learning classification models. The project uses the UCI Default of Credit Card Clients dataset and it compares multiple models, including Logistic Regression, Random Forest, Support Vector Machine, and Gradient Boosting.

## My Contributions
This project was completed as part of CFRM 521 at the University of Washington in a four-person team.

My main contributions included:
- Data cleaning and preprocessing
- Feature engineering
- Exploratory data analysis (EDA)
- Logistic Regression model implementation
- Model tuning and evaluation

## Dataset
This project uses the Default of Credit Card Clients dataset from the UCI Machine Learning Repository.

The dataset contains 30,000 credit card clients and includes demographic information, credit limits, repayment history, billing amounts, payment amounts, and default status.

License: Creative Commons Attribution 4.0 International (CC BY 4.0)

Citation:
Yeh, I. C., & Lien, C. H. (2009). The comparisons of data mining techniques for the predictive accuracy of probability of default of credit card clients. Expert Systems with Applications, 36(2), 2473–2480.

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow
1. Loaded and cleaned the dataset
2. Handled outliers
3. Engineered features such as credit usage ratio, average bill amount, and repayment status
4. Performed exploratory data analysis
5. Split the data into training, validation, and test sets
6. Trained and tuned machine learning models
7. Evaluated models using Accuracy, Precision, Recall, F1 Score, and ROC AUC

## Model Results

| Model | Accuracy | Precision | Recall | F1 Score | ROC AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.7216 | 0.4182 | 0.6596 | 0.5119 | 0.7401 |
| Random Forest | 0.7870 | 0.5170 | 0.5620 | 0.5380 | 0.7760 |
| SVM | 0.7551 | 0.4612 | 0.6325 | 0.5334 | 0.7624 |
| Gradient Boosting | 0.7318 | 0.4282 | 0.6315 | 0.5103 | 0.7563 |

## Key Insights
- Repayment history was one of the strongest predictors of credit default.
- Customers with delayed past payments were more likely to default in the following month.
- Random Forest achieved the strongest overall performance based on F1 Score and ROC AUC.
- Accuracy alone was not enough because the dataset was imbalanced.

## How to Run
1. Clone this repository.
2. Open `credit_default_prediction.ipynb`.
3. Make sure `UCI_Credit_Card.csv` is in the project folder or `data/` folder.
4. Run all notebook cells.

## Project Note
This was a collaborative academic project. My individual work focused on preprocessing, exploratory data analysis, feature engineering, and Logistic Regression.
