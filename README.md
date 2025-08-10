🚀 Crypto Volatility & Correlation


📈 Analyze crypto markets with ease – fetch hourly price data, calculate annualized volatility, and visualize correlation heatmaps.


📊 Perfect for traders, analysts, and researchers.


📂 Project Structure

Token_Heatmap.ipynb   # Main script
config.json          # Token list (editable)
.env                 # CoinGecko API key
README.md            # Documentation


📝 Notes
Default period: 90 days (hourly resolution)

Volatility = StdDev(returns) × √(hours/year)

Handles missing data gracefully

Uses config.json for token list – no code editing needed



📜 License
MIT License. See LICENSE for details.