# Wetland CO2 Flux Prediction using Satellite Data

## Project Overview
This project focuses on predicting CO2 fluxes in wetland ecosystems using high-resolution Sentinel-2 satellite data. It is part of the *Advanced Computational Learning and Data Analysis* [course](https://shnaton.huji.ac.il/index.php/NewSyl/52025/1/2024/) by Dr. Yuval Benjamini. The study involved developing and comparing Artificial Neural Network (ANN) and Long Short-Term Memory (LSTM) models to capture the dynamics of CO2 fluxes in the Agamon Hula wetland, Israel.


## Repository Contents
- `Satellite_Data.csv`: Preprocessed Sentinel-2 satellite data for the study area
- `CO2_Flux_Data.csv`: Daily CO2 flux measurements from the eddy covariance tower
- `CO2_Flux_Prediction_Model.ipynb`: Jupyter notebook containing the data preprocessing, model development, and evaluation code
- `Report_Yehuda_52025.pdf`: Detailed summary report of the project, including introduction, methodology, results, and discussion

## Data Description
- `Satellite_Data.csv`: Contains Sentinel-2 spectral bands with a 5-day temporal resolution
- `CO2_Flux_Data.csv`: 30-min CO2 flux measurements in g C m⁻² day⁻¹

## Methodology
1. Data preprocessing and merging of satellite and CO2 flux data
2. Implementation of ANN and LSTM models using PyTorch
3. Model training, validation, and testing
4. Performance evaluation using R², RMSE, and MAE metrics

## Results
The LSTM model outperformed the ANN model, demonstrating better capability in capturing temporal dependencies in CO2 flux predictions. Both models showed improved performance compared to previous studies in similar ecosystems.

