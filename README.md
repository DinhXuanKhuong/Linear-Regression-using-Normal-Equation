# Linear-Regression-using-Normal-Equation


## Overview

The goal of this project is to analyze and understand which factors significantly affect students' academic performance (Academic Student Performance Index). These factors may include the number of hours spent studying or doing research, participation in extracurricular activities, hours of sleep, and the number of practice tests completed, among others.

In this project, the dataset was preprocessed, including converting and encoding the data type for the `Extracurricular Activities` attribute.

After preprocessing, the dataset is randomly split into two subsets with a 9:1 ratio:
- 90% of the data is used for training.
- 10% of the data is used for testing the model.

### Provided Data

- `train.csv`: Contains 9000 samples used for training the model.
- `test.csv`: Contains 1000 samples used for testing/evaluating the model.

An example snippet of the code is included to display the first five samples in the `train.csv` file.

In this project, **Linear Regression using the Ordinary Least Squares (OLS)** method was implemented to model the relationship between input features and the student performance index.

---

## Objectives

- Understand how different factors influence academic performance using EDA.
- Build a regression model to predict student performance based on the given features.
- Evaluate model performance using appropriate metrics.
- Visualize and interpret the results.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib

---

## Model Used

- **OLS Linear Regression** (Ordinary Least Squares)
- Evaluation using **k-Fold Cross Validation** (typically k=5) to assess model stability and generalization

## Report

[My report](report.pdf) is written in Vietnamese.