# XGBoost Diabetes Classification 

A machine learning project using XGBoost to predict diabetes based on patient health metrics.

![Python](https://img.shields.io/badge/Python-3.13-blue)
![XGBoost](https://img.shields.io/badge/XGBoost-3.0.3-green)
![Docker](https://img.shields.io/badge/Docker-Enabled-2496ED)
![License](https://img.shields.io/badge/License-MIT-yellow)

##  Overview

This project implements a classification model to predict diabetes in patients using the Pima Indians Diabetes Database. The model uses XGBoost with hyperparameter tuning via GridSearchCV to achieve optimal performance.

**Key Metrics:**
- **Dataset Size:** 768 patients
- **Features:** 9 health indicators
- **Model Accuracy:** ~78%
- **Best Feature:** Glucose level (highest importance)

##  Features

- Comprehensive Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning (handling missing values)
- XGBoost classifier with GridSearchCV hyperparameter optimization
- Feature importance visualization
- Confusion matrix analysis
- Model performance evaluation (precision, recall, F1-score)
- Fully Dockerized for reproducibility
  
##  Quick Start

### Prerequisites
- Docker Desktop
- Docker Compose

### Run the Project
```bash
# Clone the repository
git clone https://github.com/milicaantic011/XGBboost-diabetes-docker.git
cd XGBboost-diabetes-docker

# Start the Jupyter notebook server
docker-compose up

# Copy the URL with token from terminal output and open in browser
# Example: http://127.0.0.1:8888/?token=abc123...

docker-compose up
