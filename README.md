# 🐋 PumpTracker

> Real-time Pump.fun token scanner with price charts and whale tracking

[![Solana](https://img.shields.io/badge/Solana-Mainnet-9945FF?style=flat&logo=solana)](https://solana.com)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Live](https://img.shields.io/badge/Live-Demo-00d4ff?style=flat)](https://pump-tracker.vercel.app)

---

## 🌊 What is PumpTracker?

PumpTracker is a free, open-source token scanner for [Pump.fun](https://pump.fun) tokens on Solana. Paste any contract address and instantly see price data, market stats, a candlestick chart, and real on-chain whale activity — all in one place.

**No wallet connection required. No sign up. Just paste a CA and go.**

---

## ✨ Features

### 📈 Price Chart
- Candlestick chart with volume bars
- Timeframes: **5M · 15M · 1H · 4H · 1D**
- Powered by GeckoTerminal API
- Works for both bonding curve and graduated tokens

### 🐳 Whale Tracker
- Real on-chain transaction data via Helius
- Shows top 10 traders by SOL volume
- Buy pressure indicator
- 🐋 Whale · 🦈 Shark · 🐟 Fish icons by size
- Direct links to Solscan for each wallet

### 📊 Market Data
- Live price, market cap, volume, liquidity
- Price changes: 5m / 1h / 6h / 24h
- Bonding curve progress bar (% toward $69K graduation)
- Buys vs sells ratio (24h)

### 🔗 Quick Links
- One-click links to Solscan, DexScreener, Pump.fun
- Copy CA button
- Social links (Twitter, Telegram, Website)

---

## 🚀 Live Demo

**[pump-tracker.vercel.app](https://pump-tracker.vercel.app)**

Try it with any Pump.fun token CA.

---

## 🛠️ How It Works

```
User pastes CA
      ↓
DexScreener API → Price, volume, liquidity, pair info
      ↓
GeckoTerminal API → OHLCV candlestick data
      ↓
Helius RPC → Real on-chain transactions for whale tracking
      ↓
Rendered in browser — no backend needed
```

---

## 📡 APIs Used

| API | Purpose | Cost |
|---|---|---|
| [DexScreener](https://docs.dexscreener.com) | Price, volume, market data | Free |
| [GeckoTerminal](https://www.geckoterminal.com/api) | OHLCV chart data | Free |
| [Helius](https://helius.dev) | On-chain whale transactions | Free tier |

---

## 🖥️ Self-Host

Just open `index.html` in a browser — no build step needed.

Or deploy to Vercel in one click:

```bash
git clone https://github.com/vicentszr/pump-tracker
cd pump-tracker
# Open index.html or deploy to Vercel
```

---

## 📁 Structure

```
pump-tracker/
└── index.html    # Everything in one file — HTML, CSS, JS
```

---

## ⚠️ Disclaimer

This tool is for informational purposes only. Not financial advice. Always DYOR before trading any token.

---

## 📄 License

MIT — free to use, fork, and build on.

---

Built with ❤️ for the Solana community