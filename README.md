# Crashscope-Traffic-Accident-Severity-Rate
Machine Learning model for predicting traffic accident severity using real-world accident, vehicle, and person data.
# Traffic Accident Severity Prediction

## Project Overview

This project focuses on predicting the severity of traffic accidents using machine learning techniques. The target variable is divided into three severity classes:

* Minor: No apparent injury or possible injury
* Moderate: Suspected minor or serious injury
* Severe: Fatal or highly severe injury cases

The project includes exploratory data analysis, feature engineering, model development, and model evaluation.

## Dataset

The dataset is not included in this repository because of its large size.

To run the notebook, the required dataset files should be obtained separately and placed in the appropriate directory. The notebook may need to be updated with the correct file paths depending on where the data is stored.

## Project Workflow

### 1. Exploratory Data Analysis

The dataset was explored to better understand the relationship between accident severity and different features. The analysis included examining the data, identifying missing values, understanding feature distributions, and exploring factors related to accident severity.

### 2. Feature Engineering

Feature engineering was performed to prepare the data for machine learning models. This included processing and transforming features, handling missing values, creating new features where necessary, and preparing the final dataset for modeling.

### 3. Model Development

Multiple machine learning models were developed and tested to predict traffic accident severity. Different modeling approaches and preprocessing techniques were explored to improve performance.

### 4. Model Evaluation

The developed models were evaluated and compared using appropriate performance metrics. The evaluation focused on measuring how well each model performed in predicting the different accident severity classes.

## Technologies and Libraries

The project was developed using Python and includes libraries such as:

* pandas
* numpy
* matplotlib
* scikit-learn
* imbalanced-learn
* xgboost
* catboost

## Team Contributions

### Sama

* Performed exploratory data analysis (EDA)
* Contributed to feature engineering

### Judy

* Part of the feature engineering process
* Data splitting and preprocessing
* Machine learning model development
* Handling class imbalance
* Hyperparameter tuning

### Jana

* Performed model evaluation
* Compared and analyzed model performance
* UI

## Repository Structure

```text
├── Traffic_Severity_rate.ipynb
└── README.md
```

Note: The dataset files are not included in this repository because of their size.

## How to Run

1. Clone or download this repository.

2. Install the required libraries:

```bash
pip install pandas numpy matplotlib scikit-learn imbalanced-learn xgboost catboost
```

3. Obtain the required dataset files separately.

4. Update the file paths in the notebook if necessary.

5. Open the notebook using Jupyter Notebook or JupyterLab and run the cells in order.

## Project Goal

The goal of this project is to build machine learning models that can classify traffic accidents based on their severity. The project demonstrates a complete machine learning workflow, including exploratory data analysis, feature engineering, model development, and model evaluation.

## Contributors

## Contributors

- [@samaelbahrawyy](https://github.com/samaelbahrawyy) - Exploratory Data Analysis (EDA) and Feature Engineering
- [@judyelmawardy](https://github.com/judyelmawardy) - Feature Engineering and Model Development
- [@janaaamr06](https://github.com/janaaamr06) - Model Evaluation and UI
