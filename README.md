Classfication Analysis of Glycosylated Hemoglobin (GlyHb)

This project applies classfication machine learning algorithms to predict Glycosylated Hemoglobin (GlyHb) levels using HBIostat diabetes dataset. 

Dataset

- Source: [HBIostat Diabetes Dataset](https://hbiostat.org/data/repo/diabetes.csv)
- Target variable: `glyhb` – Glycosylated Hemoglobin concentration (percentage)
- The dataset includes various features related to diabetes.

Objectives

- Predict the diabetis patients using classfication.
- Evaluate model performance and interpret classfication results.

Steps

1. Data Understanding and Exploration
   - Load dataset 
   - initial data exploration
   - Check missing values by using visual and non visual steps
   - Understand each variables present

2. Data Cleaning
   - Handle missing values based on data types
   - Check for duplicate records

3. Feature Engineering
   - Data encoding 
   - Creating new features
   - creating binary classification from 'glyhb' called diabetis for prediction

4. Exploratory Data Analysis (EDA)
   - Visualizing different plots 
   - Visualizing distribution of target variable
   - Correlations detection between features and target
   - Distribution and outlier detection
   - Solving different problems identified during this process

5. Feature Selection
   - Selection of feature and target based on the corellation
   - Separation of feature and target
6. Data Preprocessing for Modeling
   - Split data into train/test set
   - handling class imbalance in the traning data set
   - Scale and normalize numerical features
7. Model Building and evaluation
   - Buling the needed classfication models
   - Evaluating the model performance and selcting the best performing model
   
Tools & Libraries

- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook
- imblearn
- scipy

