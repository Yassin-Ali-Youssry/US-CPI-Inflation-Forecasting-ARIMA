# Forecasting US CPI Growth Using Inflation Data & ARIMA

This project applies time series forecasting techniques to analyze and predict U.S. Consumer Price Index (CPI) growth using monthly inflation data. The ARIMA model was selected for its robustness in handling univariate time series and its ability to model trends and seasonality with differencing.

## Project Goals

- Forecast monthly and annual CPI growth trends
- Compare MoM and YoY forecasts
- Evaluate ARIMA model performance using visual diagnostics
- Create a structured, replicable data science workflow

## Tools and Technologies

- Python (pandas, numpy, matplotlib, pmdarima)
- ARIMA modeling (`auto_arima`)
- Google Colab for interactive development
- GitHub for version control and project hosting

## Repository Structure

| File Name | Description |
|-----------|-------------|
| `Forecasting_US_CPI_Growth_Using_Inflation_&_ARIMA.ipynb` | Full forecasting pipeline with visuals |
| `Forecasting_US_CPI_Growth_Using_Inflation_&_ARIMA_Clean.ipynb` | Clean portfolio version (no line-by-line comments) |
| `Forecasting_US_CPI_Growth_Using_Inflation_&_ARIMA_Guide.ipynb` | Educational walkthrough with detailed explanations |
| `LICENSE` | MIT License |
| `README.md` | Project overview and repo documentation |

## Key Concepts Covered

- Time series decomposition
- ARIMA model selection with AIC optimization
- Rolling forecasting vs. fixed-horizon prediction
- Avoiding differencing on CPI to preserve level-based insights
- Forecast visualization and interpretation

## Project Outcome

The ARIMA-based forecasts provide reasonable estimates for future CPI growth and highlight the differences in volatility and trend between MoM and YoY data. The clean and well-documented code offers a reusable framework for similar forecasting problems in economics or finance.

## Get Started

You can open the notebooks directly in Google Colab or Jupyter. To replicate this project:
1. Clone the repo
2. Open any `.ipynb` file in Colab
3. Run cells from top to bottom

## License

This project is licensed under the MIT License. See the LICENSE file for details.
