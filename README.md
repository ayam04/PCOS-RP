# PCOS Prediction Project

This repository contains code for a project focused on predicting Polycystic Ovary Syndrome (PCOS) using machine learning. PCOS is a common hormonal disorder in women that can affect fertility and overall health. The goal of this project is to build a predictive model that can identify the presence of PCOS based on various health and medical factors.

## Table of Contents
1. [Introduction](#introduction)
2. [Getting Started](#getting-started)
3. [Data Preprocessing](#data-preprocessing)
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
5. [Model Building](#model-building)

### Introduction

PCOS is a complex condition that can have a wide range of symptoms and health implications. Early detection and diagnosis are crucial for effective management and treatment. Machine learning can provide a valuable tool for identifying patterns in data that may be indicative of PCOS.

### Getting Started

Before running the code, make sure you have the necessary libraries installed. The following Python libraries are used in this project:

- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn (sklearn)

You can install these libraries using pip if you haven't already:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Data Preprocessing

The project begins with importing necessary libraries and loading the datasets. Two datasets are used: one with PCOS patients and another without. The datasets are merged based on patient file numbers, and unnecessary columns are dropped.

The code also includes data preprocessing steps, such as handling missing values and converting object-type columns to numeric values.

### Exploratory Data Analysis (EDA)

Exploratory Data Analysis is a crucial step in understanding the data and identifying patterns or relationships between variables. This project includes various EDA visualizations using seaborn and matplotlib. Key insights and correlations are highlighted.

### Model Building

The main goal of this project is to build a machine learning model to predict PCOS based on the dataset's features. The code includes:

- Splitting the data into training and test sets.
- Building a Random Forest Classifier initially.
- Evaluating the model's accuracy.
- Using GridSearchCV to find the best hyperparameters for the model.
- Rebuilding the model with the optimized hyperparameters.
- Evaluating the final model's accuracy and generating a classification report and confusion matrix.

The final model achieved a high accuracy in predicting PCOS presence.

Feel free to explore the code and adapt it to your own PCOS prediction project or similar healthcare-related machine learning tasks.
