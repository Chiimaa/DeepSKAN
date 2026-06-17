# DeepSKAN: Anomaly Detection in Multivariate Time Series via Wavelet KAN and Geometric Boundary Learning

[![Framework: EasyTSAD](https://img.shields.io/badge/Framework-EasyTSAD-orange.svg)](https://github.com/yourusername/DeepSKAN)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python: 3.9+](https://img.shields.io/badge/Python-3.9+-green.svg)](https://python.org)

This repository contains the official implementation, training notebooks, and experimental evaluation tracking for **DeepSKAN**, a hybrid deep learning model for unsupervised anomaly detection in multivariate time series. 

DeepSKAN integrates a Sensor Self-Attention layer, a Kolmogorov-Arnold Network (KAN) forecasting branch leveraging localized wavelet functional bases, and a Deep Support Vector Data Description (DeepSVDD) geometric boundary head. All experiments, data preprocessing, and baselines are standardized using the open-source **EasyTSAD** pipeline to ensure a strictly fair and unified benchmark evaluation.

