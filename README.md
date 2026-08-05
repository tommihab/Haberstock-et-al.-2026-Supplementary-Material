# Haberstock-et-al.-2026-Supplementary-Material
This repository contains the supplementary material of the study "Machine-Learning-Based Discharge Forecasting of the Ems River: A Model Comparison" from Haberstock et al. 2026.

## Contents

- `code/`: Python and Google Colab notebooks used for data preprocessing,
  model training, and evaluation.
- `supplementary_tables/`: Supplementary tables referenced in the manuscript.
- `supplementary_figures/`: Additional figures.
- `model_parameters/`: Hyperparameters of the LSTM and Random Forest models.
- `environment/`: Software dependencies.

## Study overview

The repository contains the implementation of LSTM and Random Forest models
for hourly discharge forecasting of the Ems River, Germany, at forecast
horizons of 3, 6, 12, 24, and 72 hours.

## Data availability

Meteorological data were obtained from the German Weather Service (DWD).
Discharge data were obtained from [name of provider].

Due to licensing restrictions, the original input data are not redistributed
in this repository. The README provides the information required to retrieve
the data from the original providers.

## Software requirements

The analyses were conducted using Python. Required packages are listed in
`environment/requirements.txt`.

## Reproduction

Run the notebooks in the following order:

1. `01_preprocessing.ipynb`
2. `02_lstm_training.ipynb`
3. `03_random_forest_training.ipynb`
4. `04_model_evaluation.ipynb`

## License

Code: MIT License  
Figures, tables, and documentation: CC BY 4.0

## Citation

Please cite the archived Zenodo version of this repository.
