# XGBoost Diabetes Classification

A machine learning project using **XGBoost** to predict diabetes based on patient health metrics.

![Python](https://img.shields.io/badge/Python-3.13-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-3.0.3-green)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED)
![License](https://img.shields.io/badge/License-MIT-yellow)

## Overview

This project implements a classification model to predict diabetes in patients using the **Pima Indians Diabetes Database**. The model uses **XGBoost** with hyperparameter tuning via **GridSearchCV** to achieve optimal performance.

**Key Metrics:**
- **Dataset Size:** 768 patients
- **Features:** 9 health indicators  
- **Model Accuracy:** ~78%
- **Best Feature:** Glucose level (highest importance)

## Features

- **Comprehensive Exploratory Data Analysis (EDA)**
- **Data preprocessing and cleaning** (handling missing values)
- **XGBoost classifier** with GridSearchCV hyperparameter optimization
- **Feature importance visualization**
- **Confusion matrix analysis**
- **Model performance evaluation** (precision, recall, F1-score)
- **Fully Dockerized** for reproducibility

## Quick Start

### Prerequisites
- Docker Desktop
- Docker Compose

### Installation Steps

Clone the repository:
    git clone https://github.com/milicaantic011/XGBboost-diabetes-docker.git
    cd XGBboost-diabetes-docker

Start the Jupyter notebook server:
    docker-compose up

Copy the URL with token from terminal and paste in browser.

Stop the container when finished:
    docker-compose down

## Project Structure

    XGBboost-diabetes-docker/
    ├── Dockerfile
    ├── docker-compose.yml
    ├── requirements.txt
    ├── XGBoost Clasiffication.ipynb
    ├── diabetes.csv
    ├── .gitignore
    └── README.md

## Dataset

The **Pima Indians Diabetes Database** contains the following features:

| Feature | Description |
|---------|-------------|
| **Pregnancies** | Number of times pregnant |
| **Glucose** | Plasma glucose concentration |
| **BloodPressure** | Diastolic blood pressure (mm Hg) |
| **SkinThickness** | Triceps skin fold thickness (mm) |
| **Insulin** | 2-Hour serum insulin |
| **BMI** | Body mass index |
| **DiabetesPedigreeFunction** | Diabetes pedigree function |
| **Age** | Age in years |
| **Outcome** | 0 = No diabetes, 1 = Diabetes |

## Model Performance

- **Accuracy:** 78%
- **Precision (No Diabetes):** 80%
- **Recall (No Diabetes):** 86%
- **Precision (Diabetes):** 73%
- **Recall (Diabetes):** 64%

**Top 3 Most Important Features:**
1. **Glucose** (6.59 gain)
2. **BMI** (2.93 gain)  
3. **Age** (2.76 gain)

## Technologies Used

- **Python 3.13**
- **XGBoost 3.0.3**
- **Scikit-learn 1.7.1**
- **Pandas 2.3.1**
- **NumPy 1.26.4**
- **Matplotlib 3.10.0**
- **Seaborn 0.13.2**
- **Jupyter Notebook 7.4.4**
- **Docker**

## License

MIT License - Copyright (c) 2025 Milica Antic

## Author

**Milica Antic**
- GitHub: [@milicaantic011](https://github.com/milicaantic011)

---

If you find this project useful, please consider giving it a star!
