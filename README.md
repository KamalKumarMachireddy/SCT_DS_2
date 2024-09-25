# Breast Cancer Dataset Analysis

## Overview

This project aims to analyze and model the Breast Cancer dataset using machine learning techniques. It includes data cleaning, exploratory data analysis (EDA), and building a Random Forest classifier to predict the type of breast cancer.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusions](#conclusions)
- [License](#license)

## Introduction

Breast cancer is one of the most common cancers worldwide. Early detection and classification of breast cancer types can significantly improve treatment outcomes. This project utilizes the Breast Cancer dataset to develop a predictive model for classifying breast cancer cases.

## Dataset

The dataset used in this project is the Breast Cancer Wisconsin dataset, which can be found at [UCI Machine Learning Repository](<https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)>). The dataset contains 569 instances and 30 features, which include measurements of various characteristics of cell nuclei present in breast cancer biopsies.

### Features

- `mean radius`
- `mean texture`
- `mean perimeter`
- `mean area`
- `mean smoothness`
- `mean compactness`
- `mean concavity`
- `mean concave points`
- `mean symmetry`
- `mean fractal dimension`
- (and others...)

### Target

- `target`: Class of cancer (Malignant or Benign)

## Installation

To run this project, you need to have Python and the following libraries installed:

```bash
pip install pandas matplotlib numpy scikit-learn
```
