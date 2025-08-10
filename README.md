🚀 Crypto Volatility & Correlation



📈 Analyze crypto markets with ease – fetch hourly price data, calculate annualized volatility, and visualize correlation heatmaps.
📊 Perfect for traders, analysts, and researchers.

📂 Project Structure
bash
Copy
Edit
crypto_analysis.py   # Main script
config.json          # Token list (editable)
.env                 # CoinGecko API key
README.md            # Documentation
🔧 Installation
bash
Copy
Edit
git clone https://github.com/yourusername/crypto-volatility-tool.git
cd crypto-volatility-tool
pip install requests pandas numpy matplotlib seaborn python-dotenv
⚙️ Setup
1️⃣ Get API Key
Sign up at CoinGecko Pro API and get your key.

2️⃣ Create .env
ini
Copy
Edit
GECKO_API=your_api_key_here
3️⃣ Configure Tokens (config.json)
json
Copy
Edit
{
    "tokens": ["bitcoin", "ethereum", "solana"]
}
Use CoinGecko token IDs, not tickers.

▶️ Usage
bash
Copy
Edit
python crypto_analysis.py
📊 Example Output
Annualized Volatility
nginx
Copy
Edit
solana     0.85
ethereum   0.65
bitcoin    0.40
Correlation Matrix
markdown
Copy
Edit
          bitcoin  ethereum  solana
bitcoin     1.00     0.92     0.88
ethereum    0.92     1.00     0.94
solana      0.88     0.94     1.00
🎨 Example Heatmap
(Optional: Insert saved heatmap.png here)

📝 Notes
Default period: 30 days (hourly resolution)

Volatility = StdDev(returns) × √(hours/year)

Handles missing data gracefully

Uses config.json for token list – no code editing needed

📜 License
MIT License. See LICENSE for details.