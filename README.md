# Stock Analysis AI Chatbot

An interactive Streamlit application that provides AI-powered stock market analysis using real-time data.

## Features

- Real-time stock data visualisation with candlestick charts
- AI-powered analysis of stock performance
- Interactive chat interface for stock-related queries
- Support for multiple popular stock symbols
- Last 5 days of detailed stock metrics

## Setup

1. API key links: 
    - [Financial Modeling Prep](https://financialmodelingprep.com/)
    - [DeepSeek](https://deepseek.com/)

2. Clone the repository:
```bash
git clone https://github.com/cameronjoejones/DeepSeek-Stock-AI-Chatbot.git
cd DeepSeek-Stock-AI-Chatbot
```

3. Install dependencies:
```bash
pipenv install
```

4. Set up your API keys:
   - Copy `.streamlit/example_secrets.toml` to `.streamlit/secrets.toml`
   - Add your API keys in `secrets.toml`:
     ```toml
     deepseek_api_key = "your-deepseek-api-key"
     stock_api_key = "your-fmp-api-key"
     ```

5. Run the application:
```bash
streamlit run app.py
```

## Requirements

- Python 3.8+
- Pipenv
- DeepSeek API key
- Financial Modeling Prep API key

## Usage

1. Select a stock symbol from the sidebar
2. View the candlestick chart and key metrics
3. Ask questions about the stock using the chat interface
4. Try example prompts or ask your own questions
