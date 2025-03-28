# Bitcoin Price Chart

![Bitcoin Logo](https://bitcoin.org/img/icons/opengraph.png)

A sleek, interactive Bitcoin price chart with dark theme and mempool.space integration. Track Bitcoin's price across different time intervals with a responsive, canvas-based visualization.

## 🚀 Features

- **Live Bitcoin Price Chart**: Track BTC price with multiple time frames (1D, 7D, 1M, 1Y, ALL)
- **Interactive Timeline**: Zoom and pan through price history with the range selector
- **Mempool.space Integration**: Search for wallet addresses and transaction IDs directly
- **Responsive Design**: Works perfectly on desktop, tablet and mobile devices
- **Dark Theme**: Easy on the eyes with Bitcoin's signature orange accents
- **Zero Dependencies**: Built with vanilla JavaScript and HTML5 Canvas - no external libraries
- **Copy-to-Clipboard**: One-click copy for the tip jar Bitcoin address

## 📊 Demo

Check out the live demo: [https://saganaki22.github.io/BTC/](https://saganaki22.github.io/BTC/)

## 📱 Screenshots

![Bitcoin Chart Screenshot](https://i.ibb.co/placeholder-image/btc-chart-screenshot.png)

## 💻 Technologies

- HTML5 Canvas API
- Vanilla JavaScript
- CSS3 with responsive design

## 🔧 Installation

Clone this repository and open the HTML file in any modern browser:

```bash
git clone https://github.com/Saganaki22/BTC.git
cd BTC
```

Simply open `index.html` in your browser or serve it with any web server:

```bash
# Using Python's built-in server
python -m http.server 8000

# Using Node.js http-server if installed
npx http-server
```

## 🔍 Usage

### Price Chart
- Select from 5 time intervals: 1D, 7D, 1M, 1Y, or ALL
- Hover over the chart to see exact price, date, market cap, and volume
- Use the bottom timeline slider to zoom in on specific time periods

### Mempool Search
- Enter a Bitcoin wallet address (starting with bc1, 1, or 3) to view on mempool.space
- Enter a transaction ID to see transaction details on mempool.space
- All searches open in a new tab

## 🔄 Data Source

This chart uses real-time data from the CoinGecko API with the following endpoints:
- Historical price data: `/coins/bitcoin/market_chart`
- Current price data: `/simple/price?ids=bitcoin`

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Saganaki22/BTC/issues).

## 💰 Tip Jar

If you find this project useful, consider sending some sats to support development:

```
bc1qlp5urduycv8kaynym0z6cvgqwk7frxr8vk489a
```

## 📝 License

This project is [MIT](LICENSE) licensed.

## 📧 Contact

GitHub: [@Saganaki22](https://github.com/Saganaki22)

---

Made with ❤️ and ₿
