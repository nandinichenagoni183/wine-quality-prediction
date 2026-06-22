# 🍷 Wine Quality Prediction using Machine Learning

## Overview

This project is an end-to-end Machine Learning implementation for predicting wine quality using physicochemical properties of wine samples. The project covers the complete ML workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, pipeline creation, and hyperparameter tuning.

The original wine quality prediction problem was converted into a binary classification task:

* Good Wine (1) → Quality ≥ 7
* Bad Wine (0) → Quality < 7

---

## Dataset

**Dataset:** `winequality.csv`

The dataset contains chemical characteristics of wine such as:

* Fixed Acidity
* Volatile Acidity
* Citric Acid
* Residual Sugar
* Chlorides
* Free Sulfur Dioxide
* Total Sulfur Dioxide
* Density
* pH
* Sulphates
* Alcohol

**Target Variable:** Quality

---

## Project Workflow

### Task 1: Dataset Loading & Understanding

* Imported required libraries
* Loaded dataset using Pandas
* Viewed dataset using:

  * head()
  * tail()
  * sample()

### Task 2: Data Inspection

* Column analysis
* Dataset dimensions
* Data types
* Statistical summary using describe()

### Task 3: Missing Value Analysis

* Checked missing values using:

  * isnull()
  * isnull().sum()

### Task 4: Exploratory Data Analysis (EDA)

* Quality distribution analysis
* Countplot visualization
* Class distribution observations

### Task 5: Binary Classification Conversion

Created:

```python
quality_label = 1 if quality >= 7 else 0
```

### Task 6: Feature & Target Separation

* Features (X)
* Target (y)

### Task 7: Train-Test Split

* 80% Training Data
* 20% Testing Data
* random_state = 42

### Task 8: Feature Scaling

Implemented StandardScaler:

* Fit on training data
* Transform train and test data

### Task 9: Model Training

The following Machine Learning models were trained:

1. Logistic Regression
2. K-Nearest Neighbors (KNN)
3. Decision Tree Classifier
4. Random Forest Classifier
5. Support Vector Machine (SVM)

### Task 10: Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix
* Model Comparison Table

### Task 11: Pipeline & Hyperparameter Tuning

Implemented:

* Pipeline
* StandardScaler
* Support Vector Machine (SVM)
* GridSearchCV

Hyperparameters Tuned:

* C
* kernel

### Task 12: Final Conclusion

* Dataset understanding
* EDA findings
* Model comparison
* Best model identification
* Key learning outcomes

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Machine Learning Concepts Applied

* Data Preprocessing
* Feature Engineering
* Data Visualization
* Classification Algorithms
* Feature Scaling
* Model Evaluation
* Pipeline Creation
* Hyperparameter Tuning
* Cross Validation

---

## Learning Outcomes

Through this project, I gained practical experience in:

* Building an end-to-end Machine Learning pipeline
* Performing Exploratory Data Analysis (EDA)
* Training multiple classification models
* Comparing model performance
* Applying GridSearchCV for optimization
* Following industry-standard ML workflows

---

