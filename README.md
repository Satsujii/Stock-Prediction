# Stock Prediction App

This is a simple and interactive web application built with Streamlit that allows you to predict the future stock prices of selected companies, including Itissalat Al-Maghrib (IAM.PA), Apple (AAPL), Google (GOOG), Microsoft (MSFT), and GameStop (GME). The app uses historical data from Yahoo Finance and Facebook's Prophet model for time series forecasting.

## Features

- **Select from multiple stocks:** IAM.PA, AAPL, GOOG, MSFT, GME
- **Choose prediction horizon:** 1 to 4 years into the future
- **Visualize raw historical data:** Interactive Plotly chart of Open and Close prices
- **Forecast future prices:** See predicted trends and values using Prophet
- **Explore forecast components:** Visualize trend, seasonality, and more

## How to Run

1. **Clone the repository** (or copy the code to your local machine):

   ```bash
   git clone https://github.com/Satsujii/Stock-Prediction
   ```

2. **Install dependencies**  
   (You can use the provided `requirements.txt`):

   ```bash
   pip install -r requirements.txt
   ```

   > **Note:** Prophet may require additional system dependencies. If you have issues, see the [Prophet installation guide](https://facebook.github.io/prophet/docs/installation.html).

3. **Run the app:**

   ```bash
   streamlit run main.py
   ```

4. **Open your browser**  
   Go to the URL shown in your terminal (usually http://localhost:8501).

## Usage

1. **Select a stock** from the dropdown menu.
2. **Choose the number of years** to predict into the future using the slider.
3. **View the raw data** and interactive time series plot.
4. **See the forecasted data** and interactive forecast plot.
5. **Explore forecast components** (trend, seasonality, etc.).

## Example

- To predict the stock price for Itissalat Al-Maghrib (IAM.PA), select "IAM.PA" from the dropdown and choose your desired prediction period.

## Requirements

- Python 3.7+
- streamlit
- pandas
- yfinance
- prophet
- plotly

## Notes

- The predictions are for educational and demonstration purposes only and should not be used for financial decisions.
- The app fetches the latest data from Yahoo Finance each time you run it.

## License

MIT License 