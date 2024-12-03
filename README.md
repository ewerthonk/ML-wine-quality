# Machine Learning - Wine Quality

*Supervised Machine Learning Modeling (Classification and Regression) for Wine Quality Prediction*

<div align="center">
<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
<img src="https://img.shields.io/badge/seaborn-add8e6?style=for-the-badge&logo=python&logoColor=333333">
</div>

## 📖 Project

### 👨🏻‍🏫 Introduction

Explore a dataset of 🍷 **Red Wines** 🍷 from Potuguese's "Vinho Verde" type. The [dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) indicates the **quality score** (0-10) given via sensorial to each wine.

### 🎯 Goal

Create two Machine Learning Models. One to **predict the quality score** and the other to **classify a wine to "good" or "bad"**. The Models to be used are from Linear and Logistic Regression.

### 📊 Results

- Regression:
  - R2: 0.4153
  - RMSE: 0.6182
  - MAE: 0.4970
  - MSE: 0.3821
- Classification:
  - Accuracy: 0.7469
  - Precision: 0.7917
  - Recall: 0.7430
  - F1: 0.7666
  - AUCROC: 0.8202

### Results visualizations

![Results](references/results.png)

## 🗄 Notebooks

- [1.0-eda-and-modeling.ipynb](notebooks/1.0-eda_and_modeling.ipynb)

## 📈 Features

| Column                 | Description                                                |
|:-----------------------|:-----------------------------------------------------------|
| fixed_acidity          | Fixed acidity level in the wine                            |
| volatile_acidity       | Volatile acidity level in the wine                         |
| citric_acid            | Citric acid content in the wine                            |
| residual_sugar         | Residual sugar content in the wine                         |
| chlorides              | Chloride concentration in the wine                         |
| free_sulfur_dioxide    | Free sulfur dioxide concentration in the wine              |
| total_sulfur_dioxide   | Total sulfur dioxide concentration in the wine             |
| density                | Density of the wine                                        |
| pH                     | pH level of the wine                                       |
| sulphates              | Sulfate concentration in the wine                          |

## 📦 Folder Structure

    ├── LICENSE
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data dump.
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         and a short `-` delimited description, e.g.
    │                         `1.0--creating-the-model.ipynb`.
    ├── references         <- images, reports, and other resources for the project