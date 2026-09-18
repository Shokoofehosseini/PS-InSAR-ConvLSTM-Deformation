# PS-InSAR-ConvLSTM-Deformation
 Spatiotemporal Ground Subsidence Forecasting in Tehran District 17 using PS-InSAR and ConvLSTM
# Spatiotemporal Ground Subsidence Forecasting Using PS-InSAR and ConvLSTM

This repository contains the core implementation of the hybrid PS-InSAR and Convolutional LSTM (ConvLSTM) architecture for ground deformation monitoring and forecasting in District 17 of Tehran, Iran.

## Overview
- **SAR Data:** Sentinel-1 (2021–2024), Track 28.
- **InSAR Processing:** SARPROZ (Star-graph, PS points with $\gamma > 0.8$).
- **Deep Learning Model:** ConvLSTM Network for spatiotemporal sequence modeling.
- **Validation:** Multi-seed reproducibility protocol ($N=5$) and spatial error mapping.

## File Description
- `convvv.ipynb`: Jupyter notebook containing data loading, multi-seed training loop, temporal forecasting, and performance metrics (MAE, RMSE).

## Requirements
- Python >= 3.9
- TensorFlow >= 2.10
- NumPy, Pandas, Matplotlib, Scikit-learn

## Citation
If you use this code or methodology in your research, please cite our corresponding paper:
> *[Author Names], "Spatiotemporal Ground Subsidence Monitoring and Forecasting in Tehran District 17 using PS-InSAR and ConvLSTM", [Journal Name], 2024.*
