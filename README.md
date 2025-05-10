# Cloudburst Prediction Project

## Project Overview

This project aims to develop a machine learning–based predictive model to identify potential cloudburst events in urban areas within a short (3–6 hour) time window. The work includes data preprocessing, feature engineering, model training, and performance evaluation, with a focus on addressing class imbalance and improving early warning capabilities.

## Repository Structure

### 📁 `Miami.ipynb`  
This notebook contains the **initial data processing and cleaning** steps. It focuses on loading and transforming NOAA weather station data from Miami, including:
- Removing duplicates and outliers  
- Handling missing values  
- Extracting and engineering features such as lagged precipitation, weather indicators, and temporal encodings  

### 📁 `Improving cloudburst prediction.ipynb`  
This notebook documents the **final machine learning modeling process**, including:
- Applying SMOTEENN for class balancing  
- Training multiple classifiers (Random Forest, Two-Stage Model)  
- Evaluating model performance using metrics such as precision, recall, F1 score, ROC-AUC, and PR-AUC  
- Final model selection based on predictive reliability and practicality  

### 📁 `final_report.pdf`  
A comprehensive **project summary and reflection**, including:
- Problem statement and goals  
- Literature review and methodology  
- Data and model performance analysis  
- Ethical considerations and future directions  
- Personal learning reflections  

## Getting Started

To reproduce this project:
1. Open `Miami.ipynb` to preprocess the dataset.  
2. Proceed to `Improving cloudburst prediction.ipynb` to train and evaluate the models.  
3. Refer to `final_report.pdf` for context and conclusions.  

## Requirements

- Python 3.8+  
- Scikit-learn  
- Pandas  
- NumPy  
- Imbalanced-learn  
- Matplotlib / Seaborn (for visualization)  
