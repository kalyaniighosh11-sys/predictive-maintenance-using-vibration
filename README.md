# Predictive-Maintenance-Using-Vibration
This project implements a Machine Learning pipeline to detect and classify mechanical faults in industrial bearings using vibration sensor data. By transitioning from reactive to predictive maintenance, this system targets an annual reduction in downtime costs.

## Objective
To classify machinery condition as **Healthy vs Faulty** using vibration-derived features
and evaluate the potential business impact of predictive maintenance.

## Dataset
The dataset contains statistical features extracted from vibration signals:
- RMS
- Kurtosis
- Skewness
- Crest factor
- Standard deviation
- Max / Min values

## Methodology
- Exploratory Data Analysis
- Feature preprocessing and scaling
- Model building using:
  - Logistic Regression
  - Random Forest
- Hyperparameter tuning with GridSearchCV

## Key Results
- RMS and kurtosis emerged as strong fault indicators
- Random Forest outperformed baseline models
- Predictive maintenance could reduce unplanned downtime by ~40%

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Motivation
This project bridges mechanical engineering, data analytics, and business impact.
