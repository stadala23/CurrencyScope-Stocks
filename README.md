# Stock Market Dashboard

A Flask-based web application that provides real-time stock prices with currency conversion and trading recommendations.

## Features

- Real-time stock prices for top 10 companies
- Multi-currency support (USD, EUR, INR, GBP)
- Trading recommendations based on moving averages
- Company profiles and latest news
- Search functionality for any listed company

## Prerequisites

- Python 3.8 or higher
- Google Cloud SDK
- Docker
- Access to Google Cloud Platform (GCP)
- API Keys:
  - Finnhub API ([Get here](https://finnhub.io/))
  - Exchange Rate API V6 ([Get here](https://www.exchangerate-api.com/))

## Local Development Setup

1. Clone the repository:

```bash
git clone <repository-url>
cd stock-dashboard
```

2. Create and activate a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Create a `.env` file in the root directory:

