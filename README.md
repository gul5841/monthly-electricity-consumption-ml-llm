# Monthly Electricity Consumption Prediction Using Machine Learning with LLM-Assisted Data Integration

## Description
This repository contains the source code and supporting materials for the study entitled  
**“Monthly Electricity Consumption Prediction Using Machine Learning with LLM-Assisted Data Integration.”**  

The study focuses on predicting monthly electricity consumption by subscriber type across 81 provinces in Turkey for the period 2020–2024. Multiple machine learning, ensemble learning, and deep learning models are evaluated and compared. Large Language Model (LLM)-assisted text processing techniques are used during the data integration phase to construct a comprehensive, multidimensional dataset from heterogeneous data sources.

---

## Dataset Information
The dataset was constructed by integrating demographic, geographic, environmental, and energy-related variables.  
Key data sources include official statistical documents and publicly available datasets in various formats (tables, reports, and text-based documents), which were processed using LLM-based text extraction and normalization techniques.

Main features include:
- Monthly electricity consumption by subscriber type
- Population and demographic indicators
- Geographic attributes (latitude, longitude, altitude)
- Environmental variables (sunrise–sunset times)
- Temporal features (year, month)

Due to data usage policies, raw datasets are not fully included in this repository. However, the data structure, preprocessing steps, and feature definitions are documented in the manuscript.

---

## Code Information
The `src/` directory contains scripts used for:
- Data preprocessing and feature engineering
- Model training and evaluation
- Performance comparison across models

The following models are implemented and evaluated:
- Multiple Linear Regression (MLR)
- Artificial Neural Networks (ANN)
- Long Short-Term Memory networks (LSTM)
- Random Forest
- Gradient Boosting–based models
- CatBoost

Model performance is assessed using:
- R²
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Mean Absolute Percentage Error (MAPE)

---

## Repository Structure
