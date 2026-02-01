# Manufacturing Log Anomaly Detection (Industry Grade)

## Overview
This project detects abnormal patterns in manufacturing tool logs using
unsupervised learning techniques commonly used in semiconductor fabs


## Techniques Used
- Isolation Forest
- One-Class SVM
- Autoencoder (Deep Learning)

## Why Unsupervised?
Manufacturing failures are rare and unlabeled.
Models learn normal behavior and flag deviations.

## Setup
```bash
python -m venv venv311
venv311\Scripts\activate
pip install tensorflow==2.15.0 scikit-learn pandas numpy
