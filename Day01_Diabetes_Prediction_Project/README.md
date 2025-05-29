# Day 1 – Diabetes Prediction using Logistic Regression

## Objective:
Predict whether a person has diabetes using health features like glucose, BMI, insulin, age etc.

## Tools Used:
- pandas
- seaborn
- matplotlib (Old-school chart artist)
- scikit-learn

## Dataset:
- Pima Indians Diabetes Dataset from Kaggle
- Target column: Outcome (1 = diabetic, 0 = not)

## Model:
- Logistic Regression

## Model Performance:
- Accuracy: 74.6%
- Precision, Recall, and F1 for Class 1 (diabetic): around 0.65
- Model handled non-diabetic cases well, but needs improvement in identifying diabetic ones

## Files:
- Day01_Diabetes_Prediction_Project.ipynb (the notebook)
- diabetes.csv (dataset)
- README.md (this file)

## Next Steps:
- Try Random Forest or XGBoost
- Use SMOTE to handle class imbalance
- Build a basic Streamlit interface for demo
