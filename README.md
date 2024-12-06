
# Global Stock Market Analysis and Prediction

## Introduction
This project focuses on **technical analysis, visualization, and prediction** of global stock markets, specifically targeting major technology stocks like Apple (AAPL), Google (GOOGL), Amazon (AMZN), and Microsoft (MSFT). Using data retrieved from Yahoo Finance, the project explores historical stock performance, evaluates risk, and employs predictive techniques such as the Monte Carlo simulation.

## Objectives
This analysis addresses the following key questions:

1. What was the change in price of the stock over time?
2. What was the daily return of the stock on average?
3. What was the moving average of the various stocks?
4. What was the correlation between different stocks' closing prices?
5. What was the correlation between different stocks' daily returns?
6. How much value is at risk by investing in a particular stock?
7. How can we attempt to predict future stock behavior?

## Features
- **Data Retrieval**: Fetches stock data using Yahoo Finance API.
- **Visualization**: Utilizes Matplotlib and Seaborn for data visualization.
- **Risk Assessment**: Analyzes historical data for risk evaluation.
- **Prediction**: Implements Monte Carlo simulation to predict future stock trends.
- **Correlation Analysis**: Examines relationships between stock performances.

## Technologies Used
- **Python Libraries**:
  - `pandas` and `numpy` for data processing
  - `matplotlib` and `seaborn` for data visualization
  - `yfinance` and `pandas_datareader` for fetching stock data
- **Jupyter Notebook** for code execution and visualization.

## File Structure
- **Project Notebook**: Contains the code, analysis, and visualizations.
- **Dataset**: Stock market data retrieved dynamically through Yahoo Finance.

## Getting Started

### Prerequisites
Ensure you have Python installed, along with the following libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `yfinance`
- `pandas_datareader`

### Installation
1. Clone this repository.
   ```bash
   git clone <repository-url>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Project
1. Open the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the project file and execute the cells in sequence.

## Results
The analysis provides:
- Insights into historical stock trends and patterns.
- An evaluation of the risk associated with investments.
- Predictions of future stock prices using a probabilistic approach.

## Future Work
Potential enhancements include:
- Incorporating additional stocks or indices.
- Applying machine learning techniques for more advanced predictive analytics.
- Automating the workflow for real-time analysis.
