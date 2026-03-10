# Downscaling-and-Forecasting_RNN_LSTM_TRANSFORMERS-NAPS2025
Source code and experiments for the paper “Downscaling and Forecasting Solar Irradiance with RNN, LSTM, and Transformer Models,” presented at NAPS 2025. Includes model implementations, training scripts, and evaluation.


## Dataset
1. 5 min Solar Irradiance (Local Data) - https://ambientweather.net/
2. 15 min GHI (Global Data) - https://open-meteo.com/

## Prepocessing Dataset Methodology
A cubic spline interpolation is applied to the 15-minute global data to produce a corresponding 5-minute global time series for training

## Citation
If you reference this paper or use this code in your work, please cite our NAPS 2025 paper:

@inproceedings{peter2025downscaling,
  title={Downscaling and Forecasting Solar Irradiance with RNN, LSTM, and Transformer Models},
  author={Peter, Jesto and Hansen, Timothy M and Rekabdarkolaee, Hossein Moradi},
  booktitle={2025 57th North American Power Symposium (NAPS)},
  pages={1--6},
  year={2025},
  organization={IEEE}
}
