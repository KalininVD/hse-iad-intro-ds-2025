<!-- omit in toc -->
# All homeworks for the 1st semester of Machine Learning course ([HSE iad-intro-ds 2025](https://github.com/hse-ds/iad-intro-ds/tree/master/2025))

![Python Version](https://img.shields.io/badge/python-3.12-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-completed-brightgreen.svg)

This repository contains all the homeworks for the 1st semester of the Machine Learning course at HSE University, 2025. All homeworks are completed in Jupyter notebooks and are designed to be run in a Python environment. **All 8 homeworks** were graded by the course staff and **received full marks** (**including all bonus points** for the 5th and 7th homeworks).

<!-- omit in toc -->
## Table of Contents

- [Homework 1: NumPy basics](#homework-1-numpy-basics)
- [Homework 2: Pandas for data processing](#homework-2-pandas-for-data-processing)
- [Homework 3: EDA (Exploratory Data Analysis)](#homework-3-eda-exploratory-data-analysis)
- [Homework 4: k-NN and Linear Regression](#homework-4-k-nn-and-linear-regression)
- [Homework 5: Gradient Descent (with bonus: simulating annealing implementation)](#homework-5-gradient-descent-with-bonus-simulating-annealing-implementation)
- [Homework 6: Working with Texts](#homework-6-working-with-texts)
- [Homework 7: Decision Trees (with bonuses: no for loops, missing values handling and feature importance calculation)](#homework-7-decision-trees-with-bonuses-no-for-loops-missing-values-handling-and-feature-importance-calculation)
- [Homework 8: Boosting and Clustering](#homework-8-boosting-and-clustering)
- [How to reproduce locally](#how-to-reproduce-locally)

## Homework 1: NumPy basics

* **Notebook:** [`hw01-numpy/hw01-numpy.ipynb`](./hw01-numpy/hw01-numpy.ipynb)
* **Score:** `5 / 5`
* **Description:** This assignment is an introduction to the NumPy library, with a strong emphasis on **vectorized computations**. A core requirement was to solve all problems **without using Python loops (`for`, `while`) or `if` statements**, forcing a "NumPy-native" approach. The tasks cover a range of fundamental operations: creating and manipulating arrays, applying mathematical functions, using advanced indexing (boolean, slicing with steps), sorting a 2D array by a specific column, and implementing a Min-Max scaler for data normalization.
* **Key skills:** `NumPy`, `Vectorization`, `Boolean Indexing`, `Array Slicing & Manipulation`, `Data Normalization`.

## Homework 2: Pandas for data processing

* **Notebook:** [`hw02-pandas/hw02_pandas.ipynb`](./hw02-pandas/hw02_pandas.ipynb)
* **Score:** `5 / 5`
* **Description:** This assignment delves into advanced data manipulation techniques using the Pandas library on a dataset of social media account metrics. Key tasks included: feature engineering (discretizing a continuous variable with `qcut`), data reshaping (transforming data from wide to long format with `melt` and creating summary tables with `pivot_table`), and performing complex group-wise operations (such as solving the "top-N-per-group" problem). A notable part of the homework was a practical demonstration of the performance benefits of vectorized operations in Pandas compared to standard Python loops for data processing.
* **Key skills:** `Pandas`, `Grouping & Aggregation`, `Data Reshaping`, `Feature Engineering`, `Pivot Tables`, `Vectorization`.

## Homework 3: EDA (Exploratory Data Analysis)

* **Notebook:** [`hw03-eda/hw-03.ipynb`](./hw03-eda/hw-03.ipynb)
* **Score:** `10 / 10`
* **Description:** This project provides a deep dive into Exploratory Data Analysis (EDA) on a human activity recognition dataset from smartphone sensors. After thorough data preprocessing and class balance analysis, the core of the work involved uncovering data patterns through correlation analysis and building visualizations with `matplotlib` and `seaborn`. The insights gained from the EDA were directly used to develop a `predict` method based on simple feature comparisons, which achieved a **71% accuracy** on the test set.
* **Key skills:** `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Exploratory Data Analysis (EDA)`, `Data Preprocessing`, `Feature Engineering`, `Hypothesis Testing`.

## Homework 4: k-NN and Linear Regression

* **Notebook:** [`hw04-knn-linreg/hw04_knn_linreg.ipynb`](./hw04-knn-linreg/hw04_knn_linreg.ipynb)
* **Score:** `10 / 10`
* **Description:** This comprehensive assignment covers two fundamental machine learning algorithms.
  * **k-Nearest Neighbors (k-NN):** The first part focuses on k-NN for classification, starting with building and visualizing decision boundaries using `mlxtend` to understand the impact of the `k` parameter. A key task was to implement the k-NN algorithm from scratch, demonstrating an understanding of its core mechanics.
  * **Linear Regression:** The second part explores linear regression for predicting diamond prices. This included preprocessing categorical features with one-hot encoding and scaling numerical features. The assignment also delved into handling multicollinearity by applying and comparing **Lasso (L1)** and **Ridge (L2)** regularization, including finding the optimal alpha for Lasso using `LassoCV`.
* **Key skills:** `k-NN`, `Linear Regression`, `Lasso (L1)`, `Ridge (L2)`, `scikit-learn`, `mlxtend`, `Feature Engineering`, `Regularization`, `Model Evaluation`.

## Homework 5: Gradient Descent (with bonus: simulating annealing implementation)

## Homework 6: Working with Texts

## Homework 7: Decision Trees (with bonuses: no for loops, missing values handling and feature importance calculation)

## Homework 8: Boosting and Clustering

## How to reproduce locally

First, clone the repository:

```bash
git clone https://github.com/KalininVD/hse-iad-intro-ds-2025 homeworks
cd homeworks
```

Then, create a virtual environment and activate it:

```bash
python -m venv venv
venv\scripts\activate  # `source venv/bin/activate` on Linux or macOS
```

Next, install the required packages (listed in `requirements.txt`):

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

> [!Note] 
> `requirements.txt` includes all necessary packages with corresponding versions tested with Python 3.12 on Windows 11. In case of problems with future versions of packages or other Python versions, you can try manually installing other versions of the packages listed in the file.

Finally, you can open any Jupyter notebook (`.ipynb` file) in preferred IDE and run all the cells (choose the kernel corresponding to the created virtual environment).

Alternatively, you can start Jupyter Notebook server directly from the command line:

```bash
jupyter notebook
```

Then you can open the notebooks in your web browser (usually the `localhost` link opens automatically in your default browser).