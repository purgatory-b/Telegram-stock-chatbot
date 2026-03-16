# Telegram Stock & Information Bot

A Python-based Telegram chatbot for stock lookup and daily information services.

This project integrates multiple functions into a single chatbot, including:

- Taiwan stock price lookup
- Candlestick chart generation
- News aggregation
- Weather query
- Oil price query
- Chat history storage in MySQL

## Overview

This project is built as a webhook-based chatbot service using Flask and Telegram Bot API.

It routes user requests by intent and provides different services such as stock information, chart visualization, news, weather, and fuel price updates.

## Features

- Telegram chatbot interface
- Flask webhook backend
- Taiwan stock query using TWSE data
- Candlestick chart generation with Plotly
- News scraping and aggregation
- Weather query service
- Oil price lookup
- MySQL-based chat log storage

## Tech Stack

### Backend
- Python
- Flask

### Bot / Integration
- Telegram Bot API
- Dialogflow webhook handling

### Data / Visualization
- Requests
- BeautifulSoup
- NumPy
- Plotly

### Database
- MySQL
- SQLAlchemy

## Project Structure

```bash
stock_bot/
├── main.py
├── stock.py
├── news.py
├── weather.py
├── price.py
├── services.py
├── chatdb.py
├── util.py
├── config.ini
└── README.md
