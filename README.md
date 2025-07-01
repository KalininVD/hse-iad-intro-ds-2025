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

## Homework 2: Pandas for data processing

## Homework 3: EDA (Exploratory Data Analysis)

## Homework 4: k-NN and Linear Regression

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