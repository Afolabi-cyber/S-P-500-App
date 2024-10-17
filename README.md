# S&P 500 Explorer Web App

This is Day 5 of the **Data Science App Series**, where we explore S&P 500 companies and their stock closing prices (year-to-date) using a web app built with **Streamlit**.

## App Features
- **Filter Companies by Sector**: Select one or more sectors to display relevant companies from the S&P 500 index.
- **Download Data**: Easily export the filtered company data to a CSV file for further analysis.
- **Stock Price Visualization**: View stock closing prices for selected companies with interactive plots.
  
## Tech Stack
- **Libraries Used**:
  - `streamlit`
  - `pandas`
  - `base64`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `yfinance`
  
## Data Source
- The list of S&P 500 companies is retrieved from [Wikipedia](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies).
- Stock price data is fetched using the `yfinance` API.

## How to Run the App
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/sp500-explorer.git
