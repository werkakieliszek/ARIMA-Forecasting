# ARIMA | Forecasting Inflation in Poland

## Overview

This project uses the ARIMA (AutoRegressive Integrated Moving Average) method to forecast inflation in Poland. The ARIMA model is chosen because it accounts for both autoregressive relationships (the relationship between current and previous inflation values) and moving average components (the impact of random disturbances). The data used for this project comes from the official website of the Central Statistical Office.

## Project Structure

- **ARIMA_Inflation_Forecast.ipynb**: The main Jupyter notebook containing the code and analysis for forecasting inflation using the ARIMA model.
- **ARIMA_Data.xlsx**: The dataset used for the analysis, which includes historical inflation data.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- statsmodels

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib statsmodels
```
## Usage
1. Load the Data: The dataset is loaded from an Excel file using pandas.
2. Data Preprocessing: The data is transformed using logarithmic transformation and differencing to obtain a stationary time series.
3. Model Fitting: The ARIMA model is fitted to the preprocessed data.
4. Forecasting: The model is used to forecast future inflation values.

## Results
The ARIMA model provides a forecast for the next 12 months based on the historical inflation data. The results are visualized using matplotlib.
## Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.
## Acknowledgements
The data used in this project is sourced from the official website of the Polish Central Statistical Office.
The ARIMA model implementation is based on the statsmodels library.
