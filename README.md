# Parkinson's Disease Prediction Project

This repository provides a comprehensive pipeline for predicting Parkinson's Disease using machine learning models. The project includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and hyperparameter tuning.


## Project Workflow

### Preprocessing
- Remove irrelevant columns (`PatientID`, `DoctorInCharge`).
- Handle missing values using median imputation.
- One-hot encode categorical variables (`Gender`, `Ethnicity`).
- Standardize numerical features for uniform scaling.

### Exploratory Data Analysis (EDA)
- Visualize feature distributions (e.g., age, diagnosis counts).
- Analyze correlations between features using heatmaps.

### Model Development
- Train multiple machine learning models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - XGBoost
- Handle class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

### Model Evaluation
- Evaluate models using the following metrics:
  - Accuracy
  - Confusion Matrix
  - Classification Report
- Employ cross-validation for robust model evaluation.

### Hyperparameter Tuning
- Optimize model parameters using `GridSearchCV` for improved performance.

---

This structured workflow ensures a systematic approach to solving the prediction problem and obtaining reliable results.


# Key Features

### Data Preprocessing
- Handle missing values using median imputation.
- Encode categorical variables using one-hot encoding.
- Standardize numerical data for uniform scaling.

### Exploratory Data Analysis (EDA)
- Analyze feature distributions through visualizations.
- Explore correlations between features using heatmaps.

### Class Imbalance Handling
- Use SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.

### Model Training
- Implement and compare various machine learning models:
  - Logistic Regression
  - Random Forest
  - Support Vector Machines (SVM)
  - XGBoost

### Evaluation Metrics
- Assess model performance using:
  - Accuracy
  - Confusion Matrix
  - Classification Reports

### Hyperparameter Tuning
- Optimize model parameters using `GridSearchCV` for enhanced performance.

---

# Results

### Best Model
- **XGBoost** achieved the best performance with an accuracy of **92%** on the test dataset.

### Other Models
- **Random Forest**, **Logistic Regression**, and **SVM** demonstrated competitive accuracy scores with proper tuning.

### Visualization
- Confusion matrices for each model were visualized to evaluate predictions.
- Feature importances were plotted for models supporting interpretability.

