# XGBoost Diabetes Classification

Machine learning project using XGBoost to predict diabetes based on patient health metrics.

## Overview
- Dataset: 768 patients with 9 health features
- Model: XGBoost Classifier with GridSearchCV hyperparameter tuning
- Accuracy: ~78%

## Features
- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Hyperparameter tuning
- Feature importance visualization
- Confusion matrix analysis

## Run with Docker
```bash
docker-compose up

cat > README.md << 'EOF'
# XGBoost Diabetes Classification

Machine learning project using XGBoost to predict diabetes based on patient health metrics.

## Overview
- Dataset: 768 patients with 9 health features
- Model: XGBoost Classifier with GridSearchCV hyperparameter tuning
- Accuracy: ~78%

## Features
- Exploratory Data Analysis (EDA)
- Data preprocessing and cleaning
- Hyperparameter tuning
- Feature importance visualization
- Confusion matrix analysis

## Run with Docker

Run: docker-compose up

Then copy the Jupyter URL from the terminal and open it in your browser.

## Requirements
- Docker
- Docker Compose

## Project Structure
- XGBoost Clasiffication.ipynb - Main notebook
- diabetes.csv - Dataset
- Dockerfile - Docker configuration
- docker-compose.yml - Docker Compose setup
- requirements.txt - Python dependencies
