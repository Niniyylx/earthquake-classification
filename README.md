# Earthquake Event Classification

This repository contains the code and data split configuration for my master's thesis on earthquake event classification. The study compares a baseline XGBoost model and a CNN–BiLSTM–Attention model using seismic waveform data.

## Contents
- `earthquake_models.ipynb`: Jupyter Notebook with data download, preprocessing, model training, and evaluation.  
- `frozen_splits.json`: Fixed data partitioning scheme used for reproducibility.  
- `LICENSE`: MIT open-source license.  

## Requirements
The main dependencies include:
- Python 3.9+  
- numpy, pandas, matplotlib  
- scikit-learn, xgboost  
- torch, torchvision  
- obspy, tqdm  

## How to Run
Open the notebook and run all cells in order:
jupyter notebook earthquake_models.ipynb

## Data
Seismic waveform data are obtained from the [IRIS](https://www.iris.edu/hq/) platform. Example preprocessing and download code are included in the notebook.  

## Citation
If you use this repository, please cite:  
> Two-Stage Deep Learning Framework for Earthquake Detection and Magnitude Classification Using Continuous Waveform Data in Northeast Japan, Master's Thesis, Durham University, 2025.
