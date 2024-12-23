# GEMASTIK
This repository is owner's projects in GEMASTIK competition

## Deep Learning Performance Analysis for SPEI-Based Drought Prediction
This repository contains the implementation and analysis of various deep learning models (RNN, LSTM, GRU) to predict drought conditions using the Standard Precipitation-Evapotranspiration Index (SPEI) for the provinces of East Java and East Nusa Tenggara (NTT).

Project Overview
Drought is a critical environmental challenge with widespread impacts on agriculture, water resources, and ecosystems. This project compares the performance of deep learning models to predict drought indices, enabling better resource planning and mitigation strategies.

Key Features
1. Data Source: SPEI dataset from 1951–2023 for East Java and NTT, obtained from the SPEI Global Drought Monitor.

2. Models Evaluated:
* Recurrent Neural Network (RNN)
* Long Short-Term Memory (LSTM)
* Gated Recurrent Unit (GRU)
3. Evaluation Metrics:
* Root Mean Squared Error (RMSE)
* Mean Absolute Percentage Error (MAPE)
* Mean Absolute Error (MAE)
* R-Square (R²)

Results
* RNN performs best for SPEI-6 predictions.
* LSTM excels in SPEI-12 predictions for East Java.
* GRU delivers the best performance for SPEI-12 in NTT.

Technologies Used
* Python
* TensorFlow
* Google Colab (with GPU acceleration)
* Getting Started
* Clone the repository.
  
Insights
This study emphasizes the potential of deep learning models for time-series data analysis, contributing to adaptive water resource management and agricultural planning in drought-prone areas.
