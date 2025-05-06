## Decoder-only Foundation Model applications on Time Series Forecasting with Air Quality Datasets
(Project for ML703 - Probabilistic and Statistical Inference course at MBZUAI, 2025 Spring)

#### Abstract:
Time series forecasting is critical for air quality monitoring, enabling proactive public health measures. In this study, we adapt TimesFM, a novel decoder-only foundation model pre-trained on diverse time series data, for forecasting air quality metrics across three heterogeneous datasets from three urban areas in Asia and Europe: Beijing, Seoul, and Dublin. The experiments show a promising result of finetuning TimesFM with additional layers for air quality prediction tasks, however, the efficiency of this method is not too competitive with traditional statistical and deep learning models, raising the need for improvement to achieve both efficiency and accuracy and become the best choice in practice.

Please read the [Report](ML703_FinalProject.pdf) for more information.

#### About the repository:
The code includes these files: 
- `arima.ipynb`: ARIMA baseline, trained with Kaggle Notebook.
- `DL_baselines.ipynb`: Deep Learning-based baselines (RNN, LSTM, Transformer), trained with Google Colab.
- `timesfm_beijing.ipynb`: TimesFM finetuned for Beijing dataset, trained with Kaggle Notebook.
- `timesfm_dublin.ipynb`: TimesFM finetuned for Dublin dataset, trained with Google Colab.
- `timesfm_seoul.ipynb`: TimesFM finetuned for Seoul dataset, trained with RTX A6000.