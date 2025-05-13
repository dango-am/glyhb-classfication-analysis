Linear Regression Analysis of Glycosylated Hemoglobin (GlyHb)

This project applies linear regression to predict Glycosylated Hemoglobin (GlyHb) levels using HBIostat diabetes dataset. 

Dataset

- Source: [HBIostat Diabetes Dataset](https://hbiostat.org/data/repo/diabetes.csv)
- Target variable: `glyhb` – Glycosylated Hemoglobin concentration (percentage)
- The dataset includes various features related to diabetes.

Objectives

- Predict the percentage of GlyHb using linear regression.
- Evaluate model performance and interpret regression results.

Steps

1. Data Preprocessing
   - Load dataset and inspect structure
   - Handle missing values
   - Separate features from the target variable

2. Train-Test Split
   - Split the dataset into training and testing sets

3. Feature Transformation
   - Standardization or normalization if required

4. Model Training
   - Apply linear regression to the training data
   - Evaluate model performance using RMSE, MAE, and R²

5. Result Interpretation
   - Analyze model coefficients
   - Identify key predictors of GlyHb

Tools & Libraries

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

