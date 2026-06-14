# Machine Learning and Deep Learning Training

This repository contains class notebooks for intermediate Python learners who are beginning machine learning and deep learning.

**Author:** Kayode Adebayo

## Overview

The notebooks walk through supervised learning workflows using tabular datasets. `Class_1_Introduction.ipynb` introduces exploratory data analysis, classical machine learning, and a simple PyTorch neural network with the Iris dataset. `Class_2_FFN.ipynb` builds a feed-forward neural network for binary heart disease classification using the Cleveland heart disease dataset.

## What You Will Learn

- How to load and inspect tabular datasets.
- How to perform exploratory data analysis with pandas, seaborn, and matplotlib.
- How to clean missing values and prepare numeric features.
- How to prepare features and target labels for classification.
- How to train and evaluate classical machine learning models.
- How to build feed-forward neural networks with PyTorch.
- How to evaluate model performance using accuracy, classification reports, confusion matrices, loss curves, and accuracy curves.
- How to recognize underfitting and overfitting from training and test performance.

## Notebooks

### `Class_1_Introduction.ipynb`

An introductory supervised learning workflow using the Iris dataset.

Main sections:

1. Setup
2. Dataset
3. Exploratory Data Analysis
4. Data Preparation
5. Evaluation Helper
6. Machine Learning Section
7. Deep Learning Section
8. Assignment

### `Class_2_FFN.ipynb`

A feed-forward neural network workflow using the Cleveland heart disease dataset.

Main sections:

1. Setup
2. Dataset
3. Initial Data Inspection
4. Data Cleaning
5. Exploratory Data Analysis
6. Feature Preparation
7. Convert Data to PyTorch Tensors
8. Train-Test Split and DataLoaders
9. Build the Feed-Forward Neural Network
10. Model Setup
11. Sanity Check the Model Output
12. Train and Evaluate the Network
13. Training Curves
14. Assignment

## Repository Structure

```text
.
|-- Class_1_Introduction.ipynb
|-- Class_2_FFN.ipynb
`-- README.md
```

## Requirements

The notebooks use the following Python packages:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- xgboost
- torch

Install the required packages with:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn xgboost torch
```

## How to Use

Open the notebooks in Jupyter Notebook, JupyterLab, VS Code, or Google Colab. Work through each notebook section by section while reading the markdown notes before each code block.

The assignments at the end of the notebooks give learners extra practice with model tuning, result presentation, reproducibility, and diagnosing overfitting.

## Datasets

`Class_1_Introduction.ipynb` uses the Iris dataset loaded directly from seaborn, so no separate dataset download is required.

`Class_2_FFN.ipynb` loads the Cleveland heart disease dataset directly from the UCI Machine Learning Repository.
