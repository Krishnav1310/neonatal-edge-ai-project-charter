# Machine Learning Model Implementation

## Overview

This module contains the first implementation of the neonatal health prediction model.

The workflow includes:

- Dataset loading
- Data preprocessing
- Feature selection
- Train-test split
- Random Forest model training
- Prediction
- Model evaluation

## Model

Random Forest Classifier

## Input Features

- Heart Rate
- SpO₂
- Respiratory Rate
- Temperature

## Output Classes

- Safe
- Warning
- Critical

## Evaluation Metrics

- Accuracy
- Classification Report
- Confusion Matrix

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Progress Completed

✔ Updated ML notebook

✔ Added threshold-based preprocessing

✔ Retrained Random Forest model

✔ Generated model.pkl

✔ Generated scaler.pkl

✔ Generated label encoder

✔ Prepared backend deployment files

## Files Included

- updated_model.ipynb
- model.pkl
- scaler.pkl
- highrisk_label_encoder.pkl
- threshold_configuration.md

Next Step:
Integrate the trained model with FastAPI and perform real-time predictions.

The trained model will later be integrated with the FastAPI backend for real-time neonatal monitoring.
