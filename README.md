# Heart Disease Prediction

## Overview

A machine learning project that predicts whether a patient is at risk of heart disease based on clinical and demographic features. The goal is to assist healthcare professionals by providing a data-driven prediction model.

## Problem Statement

Heart disease is one of the leading causes of death worldwide. Early detection can improve treatment outcomes and reduce mortality rates. This project aims to build a predictive model capable of identifying patients at risk of heart disease.

## Dataset

### Source

* Dataset: https://www.kaggle.com/datasets/amirmahdiabbootalebi/heart-disease
* Number of samples: 918
* Number of features: 11

### Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak

### Target Variable

* 0 = No Heart Disease
* 1 = Heart Disease

## Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Model Development

### Models Tested

* Random Forest Classifier

### Hyperparameter Tuning

* Random Search


## Project Structure

```text
Heart Disease Classification/
├── heart.csv
├── main.ipynb
├── model.pkl
└── README.md
```

## Installation

```bash
git clone https://github.com/your-username/Heart-Disease-Prediction.git

cd Heart Disease Classification

pip install -r requirements.txt
```

## Usage

Run the notebook:

```bash
jupyter notebook
```

Open:

```text
main.ipynb
```

Follow the notebook cells sequentially.


## Author

Name: Stanley Tomoyo