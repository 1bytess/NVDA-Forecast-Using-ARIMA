# NVDA-Forecast-Using-ARIMA
Time series forecasting for NVDA stock prices using the ARIMA model.

## Project Overview
This project involves forecasting the future stock prices of NVIDIA (NVDA) using the ARIMA (AutoRegressive Integrated Moving Average) model. The analysis is performed in a Jupyter Notebook, utilizing historical stock price data provided in the `Data/NVDA.csv` file.

## Project Structure
NVDA-Forecast-Using-ARIMA/
├── Data/
│   └── NVDA.csv           # Historical stock price data for NVIDIA
├── NVDA_Forecasting.ipynb # Jupyter Notebook with ARIMA analysis
└── README.md              # Project overview and instructions

## Installation and Setup
To run the analysis, you need to have Python installed along with the necessary libraries. You can set up your environment by following these steps:

1. **Clone the repository**:
   git clone https://github.com/yourusername/NVDA-Forecast-Using-ARIMA.git
   cd NVDA-Forecast-Using-ARIMA

2. **Install required libraries**:
   You can install the necessary libraries by running:
   pip install pandas numpy matplotlib statsmodels jupyter

3. **Run the Jupyter Notebook**:
   Start the Jupyter Notebook by executing:
   jupyter notebook NVDA_Forecasting.ipynb

## Data Description
- **NVDA.csv**: Contains the historical stock prices of NVIDIA used in the analysis. The data includes columns such as `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, and `Adj Close`.

## Analysis Overview
In the Jupyter Notebook, the ARIMA model is implemented to forecast future stock prices of NVIDIA. The notebook includes:
- Data preprocessing and visualization.
- Stationarity checks using the Augmented Dickey-Fuller (ADF) test.
- Parameter selection for the ARIMA model using ACF and PACF plots.
- Model training and validation.
- Forecasting and evaluation of the results.

## Results
The forecast results are presented in both tabular and graphical formats, showing the predicted stock prices for a specified future period.

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
