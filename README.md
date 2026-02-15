# 💹 Basel Professional Forex Analytics
**Live USD/ILS Intelligence & Algorithmic Strategy Dashboard**

## 🚀 Overview
This project is a high-reliability Fintech dashboard designed to track the USD/ILS exchange rate. Unlike simple trackers, this system uses a multi-source API architecture (including the **Bank of Israel**) and implements a **Moving Average Crossover (7/14)** trading strategy.

## 🛠️ Technical Features
- **Multi-Source Data Ingestion:** Primary fetch from Bank of Israel (XML) with fallback to ExchangeRate.host and Open-API.
- **Resilient Architecture:** Implements local JSON caching to ensure 100% uptime even during API rate-limiting or network instability.
- **Algorithmic Analysis:** Automated "Buy/Sell" signals based on short-term vs. long-term trend convergence.
- **Backtesting Suite:** Includes a 30-day simulation engine calculating ROI, win rate, and portfolio drawdown.

## 📦 Installation & Usage
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `python main.py`

## 🧠 Strategic Decision: Why Mean Reversion/MA Crossover?
I chose the MA Crossover strategy for this MVP because it demonstrates the ability to handle **Time-Series Data** and **Rolling Window Calculations**—core requirements for any Backend or Data Engineering role in the Israeli Fintech sector.
