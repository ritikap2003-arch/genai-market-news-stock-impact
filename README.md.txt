# GenAI Market News → Stock Impact Prediction

This project uses Financial NLP (FinBERT) + Market Data to predict whether a stock will go up / down / stay neutral after a news headline.

## Features
- News sentiment analysis using FinBERT
- Stock price data from NSE (via yfinance)
- Simple ML model for price movement prediction
- Streamlit UI for easy testing
- GenAI explanation for predictions

## Project Structure
/data        → stock & news datasets
/models      → trained models
/notebooks   → experiments
/src         → source code
app.py       → Streamlit UI

## Tech Stack
- Python
- Hugging Face Transformers
- FinBERT
- Streamlit
- Scikit-Learn
- yfinance
