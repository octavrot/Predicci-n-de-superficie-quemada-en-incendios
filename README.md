# Wildfire Burned Area Prediction

This repository contains the code and documentation for the prediction of burned area in wildfires using neural networks. 
This work was developed as part of the MSc in Data Processing in collaboration with the Complutense University of Madrid and the Polytechnic University of Madrid.

## Project Overview

Wildfires are one of the most significant environmental and socio-economic threats worldwide, with increasing frequency and intensity due to climate change. 
This study applies neural networks to model and predict the burned area based on various environmental and operational factors.

We developed a Multilayer Perceptron (MLP) regression model, optimizing its architecture through hyperparameter tuning and cross-validation.

We include the Jupyter Notebook (incendios-2.ipynb) corresponding to our work.


## Methodology

The study follows these steps:

1. **Data preprocessing**:
   - Exploratory data analysis and visualization.
   - Feature selection using Random Forest.
   - Data transformations and normalization.

2. **Model training**:
   - Splitting data into training and test sets (80%-20%).
   - Encoding categorical variables and normalizing numerical ones.
   - Hyperparameter tuning using **GridSearchCV** and cross-validation.

3. **Model evaluation**:
   - Performance metrics: **MSE** (Mean Squared Error) and **R²** (Coefficient of Determination).
   - Error visualization and prediction analysis.

## 📊 Results

- The model achieved an **R² = 0.58**, meaning it explains **58% of the variance** in the data.
- Key factors influencing wildfire spread include:
  - Economic losses.
  - Number of firefighting personnel deployed.
  - Fire extinguishing time.
- A direct relationship between **extinguishing time and burned area** was observed.


We include the link to the Google Sites (https://sites.google.com/ucm.es/rnae-pred-incendios/inicio) where we post two interactives maps: 
1. **1983**: This page shows all wildfires registered in Spain in 1983.
2. **Diferencias en predicciones**: This page shows all the predicted wildfires with a difference of 20 Ha or more in comparison to the real wildfires through all the years.
