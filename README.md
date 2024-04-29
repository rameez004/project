# Financial Data Analysis and Visualization Dashboard

## Project Description
This project provides a comprehensive analysis and visualization tool for financial data, specifically focusing on stock market trends. The system uses Python for data fetching, analysis, and visualization, with the integration of libraries like `yfinance`, `matplotlib`, `numpy`, and `pandas`. It also features a web dashboard built with Bottle to display stock-related data and graphs dynamically.

## Features
- Fetch and display stock price data, dividends, and volatility.
- Analyze stock sentiment using Natural Language Processing.
- Generate and save various financial charts like candlestick plots, MACD, and moving averages.
- Real-time recommendation system based on analyzed data.
- Web-based interface for easy interaction and visualization.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
## Install the required dependencies:
pip install numpy pandas matplotlib yfinance newsapi-python beautifulsoup4 lxml newspaper3k gcsfs requests dash kaleido bottle torch nltk textblob transformers
## Run the Bottle server:
python <your-server-script>.py
## Usage
Navigate to http://localhost:9000 on your web browser to access the dashboard. Enter a stock symbol to fetch and visualize data like historical market data, income statements, and stock predictions.
