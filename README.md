# CA1 — Machine Learning for Business

**João Pedro Freire Moreira**
CCT College Dublin
Higher Diploma in Science in Data Analytics for Business

## Project: Traffic Volume Analysis

This project analyses traffic volume using Machine Learning techniques.

The main objective is to identify traffic patterns, compare clustering algorithms, and evaluate time series forecasting models.

## Dataset

**Metro Interstate Traffic Volume**

Source: UCI Machine Learning Repository.

The dataset contains traffic volume, weather conditions, holidays, and date information.

## Methods

### 1. Data Preparation

* Checked missing values and duplicate records.
* Created date and time features.
* Standardised numerical variables.
* Prepared daily traffic data for forecasting.

### 2. Clustering

Two algorithms were compared:

* K-Means
* Hierarchical Clustering

The models were evaluated using Silhouette Score and Davies-Bouldin Index.

### 3. Time Series Forecasting

The following models were evaluated:

* Baseline
* Seasonal Naive
* ARIMA
* SARIMA

Forecasting performance was measured using MAE and RMSE.

## Main Results

**Clustering:** Hierarchical Clustering achieved slightly better evaluation scores, but both algorithms showed limited cluster separation.

**Forecasting:** Seasonal Naive achieved the lowest forecasting errors:

* MAE: 194.73
* RMSE: 347.43

SARIMA performed best among the ARIMA and SARIMA models.

## Conclusion

The analysis identified a weekly pattern in traffic volume, with higher traffic during weekdays and lower traffic during weekends.

The results also showed that a simple forecasting model can perform better than more complex models for this dataset.

## Tools

Python, Jupyter Notebook, Pandas, Scikit-learn, Statsmodels, Matplotlib and GitHub.

## Academic Information

**Module:** Machine Learning for Business
**Lecturer:** Dr. Muhammad Iqbal
**Assessment:** CA1
**Institution:** CCT College Dublin
**Academic Year:** 2026
