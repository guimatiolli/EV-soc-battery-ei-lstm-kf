# EV-soc-battery-ei-lstm-kf

Code, trained models, and datasets associated with the paper  
**“State-of-Charge Estimation in Li-ion Batteries Using EI-LSTM and Kalman Filtering.”**

---

## Running the EI-LSTM + Kalman SOC Notebook in Google Colab

All experiments reported in the paper can be reproduced directly in Google Colab using the notebook below.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guimatiolli/EV-soc-battery-ei-lstm-kf/blob/main/code/code_soc_lstm_kf.ipynb)

This notebook is Colab-ready and automatically:
- clones the repository,
- loads the trained EI-LSTM model and scalers,
- applies the Kalman-based post-processing methods (KF_global, KF_adapt, and UKF),
- computes performance and computational metrics,
- and generates the figures and tables reported in the paper.

---

## Predictive Models Benchmark Notebook

The notebook below executes the benchmarking pipeline across multiple predictive models and highlights the LSTM as the selected model based on performance and computational criteria.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/guimatiolli/EV-soc-battery-ei-lstm-kf/blob/main/code/Models.ipynb)

This notebook allows:
- comparative evaluation of different predictive architectures,
- analysis of accuracy and robustness,
- and justification of the LSTM selection adopted in the proposed methodology.

---

## Repository Structure

