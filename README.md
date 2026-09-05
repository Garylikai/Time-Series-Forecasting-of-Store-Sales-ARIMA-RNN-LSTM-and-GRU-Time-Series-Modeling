# Time-Series Forecasting of Store Sales

A Spring 2022 AMS 580 group project comparing ARIMA, simple recurrent neural networks, long short-term memory networks, and gated recurrent units for aggregate grocery-store sales forecasting.

## Data and task

The project uses the [Store Sales — Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting) competition data from Corporación Favorita. Item- and store-level transactions are aggregated to one total-sales value per day:

- training period: January 1, 2013–August 15, 2017;
- 1,684 aggregate daily observations; and
- forecast horizon: August 16–31, 2017.

The comparison includes an ARIMA model and three 200-unit neural sequence models trained for 50 epochs with a fixed random seed. On the project's held-out window, the reported RMSE values were approximately 89,214 for RNN, 95,041 for LSTM, and 101,220 for GRU, making the simple RNN best among the three neural models in that experiment.

These values reflect a particular aggregate target, split, preprocessing pipeline, and 2022 software environment. They are not current Kaggle benchmarks.

## Repository contents

- `AMS 580 Project_Time Series.Rmd` — full R analysis and modeling code
- `AMS-580-Project_Time-Series.pdf` — rendered analysis
- `presentation.pdf` — final group presentation

Competition data are not included.

## Contributors

Shuo Li, Kai Li, and Jun Hyuk Suh.
