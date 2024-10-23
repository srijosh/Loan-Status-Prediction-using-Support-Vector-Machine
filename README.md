# Loan Status Prediction using Support Vector Machine

This repository contains a project for predicting loan approval status using a Support Vector Machine (SVM) model. The project employs data preprocessing techniques and trains an SVM classifier to predict whether a loan will be approved or not.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)

## Introduction

Loan approval is a critical task in the banking and finance sector. Predicting whether a loan should be approved or not helps reduce risks for financial institutions. This project aims to build a machine learning model using SVM to predict loan approval status based on customer details and financial history.

## Dataset

The dataset used in this project is from Kaggle's Loan Prediction dataset. It contains information about loan applicants, including various attributes like gender, marital status, income, and more. The dataset is split into training and testing sets to evaluate the model's performance.

- [Loan Prediction Dataset on Kaggle](https://www.kaggle.com/datasets/ninzaami/loan-predication?resource=download)

## Installation

To run this project, you need to have Python installed on your machine. You can install the required dependencies using `pip`.

```
pip install numpy pandas nltk scikit-learn
```

Requirements
Python 3.x
NumPy
Pandas
NLTK
Scikit-learn

## Usage

1. Clone the repository to your local machine:

```
   git clone https://github.com/srijosh/Loan-Status-Prediction-using-Support-Vector-Machine.git
```

2. Navigate to the project directory:
   cd Loan-Status-Prediction-using-Support-Vector-Machine

3. Download the dataset from Kaggle and place it in the project folder

4. Open and run the Jupyter Notebook:
   jupyter notebook Loan_Status_Prediction.ipynb

## Model

The model used in this project is a Support Vector Machine (SVM) classifier. The dataset is split into training and testing sets, and the SVM model is trained to classify whether a loan should be approved or not based on the applicant's attributes.
