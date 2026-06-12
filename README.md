# Machine Learning and Deep Learning Training

This repository contains an introductory notebook for intermediate Python learners who are beginning machine learning and deep learning.

**Author:** Kayode Adebayo

## Overview

The main notebook, `Introduction.ipynb`, walks through a complete supervised classification workflow using the Iris dataset. It starts with exploratory data analysis, moves into classical machine learning models, and ends with a simple artificial neural network built in PyTorch.

## What You Will Learn

- How to load and inspect a tabular dataset.
- How to perform basic exploratory data analysis with pandas, seaborn, and matplotlib.
- How to prepare features and target labels for classification.
- How to train and evaluate an XGBoost classifier.
- How to compare machine learning models with grid search.
- How to build a simple artificial neural network with PyTorch.
- How to evaluate model performance using accuracy, classification reports, and confusion matrices.

## Notebook Sections

1. Setup
2. Dataset
3. Exploratory Data Analysis
4. Data Preparation
5. Evaluation Helper
6. Machine Learning Section
7. Deep Learning Section
8. Assignment

## Repository Structure

```text
.
|-- Introduction.ipynb
`-- README.md
```

## Requirements

The notebook uses the following Python packages:

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

Open `Introduction.ipynb` in Jupyter Notebook, JupyterLab, VS Code, or Google Colab. Work through the notebook section by section while reading the markdown notes before each code block.

The assignment at the end of the notebook gives learners extra practice with model tuning, result presentation, and reproducibility.

## Dataset

The notebook uses the Iris dataset loaded directly from seaborn, so no separate dataset download is required.
