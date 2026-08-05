# Haberstock-et-al.-2026-Supplementary-Material
This repository contains the supplementary material of the study "Machine-Learning-Based Discharge Forecasting of the Ems River: A Model Comparison" from Haberstock et al. 2026.

## Contents

- `Google Colab Jupiter Notebooks/`: Google Colab notebooks used for data preprocessing,
  model training, and evaluation.
- `Input_Data_Stations/`: The seven rainfall measuring stations and the discharge gauge at Einen. All data sets were cropped to the same timespan (01.01.2007 - 01.01.2024).
- `ML_Input_Data/`: Data set with the combined data of the seven rainfall stations, discharge and DOY. This data set is used for running the ML models
- `predictions_with_doy/`: Saved .csv files of the ran LSTM model containing the observed and predicted values of the test data set.
- `rf_predictions_best_compromise/`: Saved predictions of the RF model for all five horizons. These files are loaded and used to skip the repeated running of the RF model.
- `trained_lstm_models/`: Saved data files of the ran LSTM model with the highest NSE values for all horizons. These files 
are loaded and used to skip the repeated running of the LSTM model.
- `supplementary_tables/`: Supplementary tables referenced in the manuscript.
- `supplementary_figures/`: Additional figures.
- `model_parameters/`: Hyperparameters of the LSTM and Random Forest models.

## Study overview

The repository contains the implementation of LSTM and Random Forest models
for hourly discharge forecasting at the gauging station Einen of the Ems River, Germany, at forecast
horizons of 3, 6, 12, 24, and 72 hours.

## Data availability

Discharge data for the study area were obtained as open-access records from OpenGeodata.NRW. The seven precipitation data sets were provided upon request by the State Office for Nature, Environment, and Climate of North Rhine-Westphalia (LANUK).

## Reproduction

Run the notebooks from the "Google Colab Jupiter Notebook" folder in the following order:

1. `01_Haberstock_Ems_Data_Processing.ipynb`
2. `02_Haberstock_Ems_RF.ipynb`
3. `03_Haberstock_Ems_LSTM.ipynb`
4. `04_Haberstock_Ems_Model_Comparison.ipynb`

## License

See LICENSE file

