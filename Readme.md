# Credit Card Fraud Detection Using Machine Learning

## Project Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Due to the highly imbalanced nature of fraud datasets, the project emphasizes data preprocessing, exploratory data analysis, class balancing, model training, and performance evaluation.

## Objective
To build a predictive model capable of identifying potentially fraudulent transactions and supporting financial institutions in reducing monetary losses.

## Dataset
The dataset contains historical credit card transaction records with features representing transaction behavior and a target variable:

- 0 = Legitimate Transaction
- 1 = Fraudulent Transaction

## Project Workflow

### 1. Data Collection
- Load transaction dataset.
- Understand dataset dimensions and feature structure.

### 2. Data Preprocessing
- Check for missing values.
- Analyze class distribution.
- Handle class imbalance through sampling techniques.

### 3. Exploratory Data Analysis
- Fraud vs Non-Fraud transaction distribution.
- Statistical summaries.
- Correlation analysis.

### 4. Data Preparation
- Feature-target separation.
- Train-test split.
- Feature scaling where required.

### 5. Model Training
- Logistic Regression classifier.
- Fraud prediction on unseen transactions.

### 6. Model Evaluation
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Results
The model successfully classifies fraudulent and non-fraudulent transactions while highlighting the challenges associated with imbalanced datasets.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Repository Structure

credit-card-fraud-detection/
├── data/
├── notebooks/
├── results/
├── README.md
└── requirements.txt

## Future Improvements
- Random Forest
- XGBoost
- SMOTE Oversampling
- Hyperparameter Tuning
- Real-Time Fraud Detection Dashboard


