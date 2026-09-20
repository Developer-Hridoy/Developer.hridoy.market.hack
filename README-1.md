# QX Pro Ultra Premium

A self-contained, GitHub Pages-ready market analysis dashboard.

## Features
- Live public Binance market data for supported crypto symbols
- Multi-timeframe selector
- EMA 9/21, RSI 14, MACD, ATR
- Support/resistance and invalidation levels
- Transparent rule-based AI-style confluence analysis
- Bullish / Bearish / Wait bias with confidence
- Market regime and volatility state
- Local signal history using browser LocalStorage
- Responsive mobile/desktop UI
- No API key required for the public market feed
- No synthetic/fake prices

## GitHub Pages deployment
1. Upload `index.html` to the root of your repository.
2. Commit the file.
3. Open **Settings → Pages**.
4. Under Build and deployment choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`.
6. Save and open the generated Pages URL.

## Important
The dashboard is an analytical tool, not financial advice and not a guarantee of future price movement. The AI panel is a transparent technical confluence engine, not a claim of predictive certainty.

## Data
The app uses Binance's public REST market endpoint from the browser. Availability can vary by region/network and by symbol. If the feed fails, the app does not invent market prices.
