# 30-Day Hospital Readmission Prediction

A healthcare predictive analytics project that uses **Logistic Regression** to predict whether a patient will be readmitted to the hospital within 30 days of discharge.

### Objective

Identify patients at higher risk of readmission using demographic, clinical, comorbidity, utilization, discharge, and laboratory variables.

### Methodology

* Exploratory Data Analysis
* Missing-value handling
* Clinical feature engineering
* Stratified train/validation/test split
* Feature scaling
* Logistic Regression
* Class imbalance handling using **Class Weighting and SMOTE**
* 5-Fold Stratified Cross-Validation
* ROC-AUC and Precision-Recall analysis
* Threshold optimization
* Odds-ratio interpretation

### Tools

Python | Pandas | NumPy | Scikit-learn | Imbalanced-learn | Matplotlib | Seaborn | Jupyter Notebook

### Files

* `readmission_clinical_data.csv` — Clinical dataset
* `Readmission_Logistic_Regression.ipynb` — Analysis and model

### Healthcare Application

The model can support **risk stratification, discharge planning, follow-up prioritization, and transitional-care management**.
