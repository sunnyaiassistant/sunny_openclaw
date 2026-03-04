# Trading Terminal Dashboard

A Bloomberg-style trading terminal with live data, interactive charts, and real-time news.

## Features
- 📡 Live crypto prices from Binance
- 📈 Interactive charts with Chart.js
- 📰 Live market news
- 🔍 Search any symbol
- 📊 Bloomberg terminal aesthetic

## Access

The dashboard is published at: **https://r3dr0cket.github.io/sunny_openclaw/**

## Local Development

```bash
# Start the proxy (for live data)
python3 proxy.py &

# Start the server
python3 -m http.server 8080
```

Then open http://localhost:8080

## Tech Stack
- Pure HTML/CSS/JS
- Chart.js for charts
- Binance API for crypto prices
