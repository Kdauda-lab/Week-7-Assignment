# Week-7-Assignment
Analyzing Data with Pandas and Visualizing Results with Matplotlib
Absolutely—here’s a more natural, student-style version of the `README.md`, while still keeping it clean and informative:

---

## Introduction

This project focuses on analyzing the **Iris dataset** using Python. The dataset contains measurements of different species of Iris flowers. The goal of this assignment is to explore the dataset, perform basic analysis, and create several visualizations to better understand the data.

## What’s Included

* `Iris_Data_Analysis.ipynb`: Jupyter notebook with all the code, analysis, and charts.
* `README.md`: This file, explaining what the project is about.

## Dataset Info

The Iris dataset is a well-known dataset in data science and machine learning. It contains 150 rows and 5 columns:

* Sepal length (cm)
* Sepal width (cm)
* Petal length (cm)
* Petal width (cm)
* Target (species: Setosa, Versicolor, Virginica)

This dataset is available directly through `sklearn.datasets`.

## Objectives

* Load and inspect a dataset using pandas
* Handle missing data (if any)
* Perform basic statistical analysis
* Group data by species and compare measurements
* Create clear and informative plots using matplotlib and seaborn

## Tasks Completed

### 1. Data Loading and Exploration

* Loaded the dataset using `sklearn.datasets.load_iris()`
* Displayed the first few rows to get a sense of the data
* Checked data types and missing values (there were none)

### 2. Data Analysis

* Used `.describe()` to summarize numerical features
* Grouped the data by species and calculated average values
* Noticed that Setosa has smaller petal measurements compared to other species

### 3. Data Visualization

Created the following plots:

* **Line Plot**: Showed sepal and petal length across sample indices
* **Bar Chart**: Compared average petal length between species
* **Histogram**: Visualized the distribution of sepal width
* **Scatter Plot**: Compared sepal length to petal length, colored by species

## Observations

* Petal measurements are more helpful than sepal measurements for distinguishing between species.
* Setosa stands out clearly due to its smaller petals.
* No missing or incorrect data was found in the dataset.

## Tools Used

* Python 3
* pandas
* matplotlib
* seaborn
* scikit-learn
* Jupyter Notebook

## How to Run

1. Open the Jupyter notebook `Iris_Data_Analysis.ipynb`
2. Run each cell in order to see the analysis and visualizations

---
