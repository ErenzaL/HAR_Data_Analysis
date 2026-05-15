# Human Activity Recognition (HAR) Data Analysis

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

> 🎓 Class Project for the **Unstructured Data Analysis Course (Soonchunhyang University)**
> 
> 📅 March 3, 2026 – April 17, 2026

This project focuses on **Human Activity Recognition (HAR)** using motion sensor data collected from smart devices. The analysis explores statistical patterns from accelerometer and gyroscope signals through exploratory data analysis (EDA), feature engineering, and machine learning classification models.

The project aims to understand how sensor-based motion data can be used to classify human activities and improve prediction performance using statistical and frequency-based analysis techniques.

---

# 📌 Project Objectives

- Analyze human activity patterns from sensor data
- Perform statistical and signal-based feature engineering
- Explore motion behavior through data visualization
- Compare multiple machine learning models
- Improve classification performance using ensemble learning

---

# 📊 Dataset

The dataset contains motion sensor information including:

- Accelerometer signals
- Gyroscope signals
- Rotation rate
- User acceleration
- Magnitude-based motion features

These sensor readings are processed into statistical and frequency-based features for activity classification.

---

# 🔍 Exploratory Data Analysis (EDA)

The project includes:

- Correlation analysis
- Distribution analysis
- Sensor signal visualization
- Statistical summaries
- Peak analysis
- Frequency analysis
- Motion variability analysis

---

# ⚙️ Feature Engineering

Several custom features were engineered during the project:

```python
acc_rot_ratio
acc_rot_diff
acc_std_rot_std_ratio
acc_max_rot_max_ratio
acc_range
rot_range
```

Additional techniques:
- Magnitude-based features
- Signal ratio analysis
- Peak extraction
- Statistical aggregation
- Frequency-domain analysis

---

# Machine Learning Models

Implemented models:

- Random Forest (RF)
- XGBoost (XGB)
- LightGBM (LGBM)
- Voting Classifier Ensemble

Validation methods:
- Train/Test Split
- K-Fold Cross Validation
- Group-based validation

---

# 📈 Final Model Performance

| Category | Details |
|---|---|
| Model | Soft Voting Ensemble |
| Techniques Used | Feature Engineering + Feature Selection + Ensemble |
| Features Used | Statistical Analysis + Peak Analysis + Change Point Analysis + Interaction Features |
| Number of Features | 26 |
| Base Models | Random Forest, XGBoost, LightGBM |
| Ensemble Method | Soft Voting |
| Cross Validation | Group K-Fold |
| Train Accuracy | 1.000 |
| K-Fold Accuracy | 0.911 ± 0.026 |
| Test Accuracy | **0.920** |
