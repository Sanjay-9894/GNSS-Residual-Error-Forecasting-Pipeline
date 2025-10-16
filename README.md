# GNSS Residual Error Forecasting Pipeline

Project Overview
This repository demonstrates an AIML-driven approach to predict time-varying GNSS (Global Navigation Satellite System) errors in satellite clock and ephemeris values. Developed for Smart India Hackathon 2025, the goal is to reliably forecast x, y, z, and clock residual errors over short to medium time frames, greatly enhancing correction capabilities for navigation satellites.​

Problem Statement
GNSS positioning accuracy is significantly affected by residual errors, resulting from discrepancies in satellite clock and ephemeris modeling. Accurate, timely forecasts of these residuals increase reliability and enable robust position corrections, improving end-user navigation performance.

Proposed Solution

Key Features:
Reliable Data Transformation: Irregular GNSS error data is converted into smooth, uniform time series.
Intelligent Pattern Detection: ML models automatically recognize trends, shifts, and volatile regimes in error time series.
Advanced Prediction Engines: Uses ensemble learning (XGBoost, CatBoost, LightGBM) for multi-dimensional error prediction.
Flexible, Future-Proof Architecture: Easily integrates new features, learning strategies, and continuous model improvement

Core Objective
The main objective is to forecast GNSS-residual error components (x, y, z, clock) with high temporal accuracy and transform raw, erratic observations into predictable, nearly white-noise sequences—enabling robust error correction up to 24 hours ahead

Model Architecture

Data Pipeline
Data Ingestion & Preparation: Collect and preprocess satellite error data.
Temporal Regularization: Convert erratic series into uniformly spaced samples using interpolation.
Cleaning & Normalization: Remove missing values, apply scaling to stabilize training.

