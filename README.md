# MENA-GLPI Reproducibility Repository

This repository provides the data and code used in the study:

Global Logistics Performance Index (GLPI) for MENA Countries.

## Software Environment
Python 3.12

## Required Libraries
Install dependencies using:

pip install -r requirements.txt

## Repository Structure

data/
Raw datasets used in the study.

notebooks/
Jupyter notebooks used for analysis.

scripts/
Python scripts for GLPI calculation and forecasting.

outputs/
Generated results and figures.

## Reproduction Steps

1 Run notebooks/01_data_processing.ipynb  
2 Run notebooks/02_imputation.ipynb  
3 Run notebooks/03_GLPI_PCA.ipynb  
4 Run notebooks/04_ARIMA.ipynb  
5 Run notebooks/05_LSTM.ipynb  

All results reported in the manuscript can be reproduced using these steps.
