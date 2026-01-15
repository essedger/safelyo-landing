# Safelyo — #1 Offline Net Worth Tracker & Wealth Manager (AI-Powered)

> "Know Your Net Worth. Master Your Wealth."

## 📋 Project Summary

**Safelyo** is an offline-first wealth tracking application designed for privacy-conscious investors. It allows users to consolidate all assets—cryptocurrency (including cold wallets), stocks, real estate, and cash—into a single dashboard without ever sending sensitive financial data to the cloud.

All data is stored locally on the user's device. The app uses AI (Gemini, OpenAI, Perplexity) responsibly to provide real-time asset valuations and insights, with strict data anonymization protocols.

## ✨ Core Value Proposition

- **🔒 Offline-First**: Zero cloud storage dependence. Your ledger lives on your phone.
- **🛡 Privacy-Centric**: Financial data is encrypted locally. No "plaid-like" bank connections that spy on transactions.
- **🤖 AI-Powered**: Smart valuation for illiquid assets (Real Estate, Cars) and portfolio analytics.

## 🚀 Key Features

- **AI Real Estate Valuation**: Automatic estimation of property value based on market comps.
- **Double-Entry Ledger**: Accountant-grade precision with zero discrepancies.
- **Cold Storage Tracking**: Support for Ledger, Trezor, and Paper Wallets (manual or public address watch-only).
- **Freedom Score™**: A specialized metric tracking passive income vs. living expenses.
- **Wealth Velocity**: True Compound Annual Growth Rate (CAGR) tracking.
- **Privacy Vault**: Biometric (FaceID) protection for specific "hidden" assets.

## 🛠 Technical & Privacy Details

- **Data Storage**: Local SQLite database (App).
- **AI Processing**: Anonymized prompts. Personal Identifiable Information (PII) is stripped before any AI request.
- **Connectivity**: Works 100% offline (except for optional AI features and price fetch updates).

### Landing Page Tech Stack
This repository contains the static landing page for Safelyo.
- **HTML5**
- **CSS3** (Vanilla with Variables)
- **Zero Dependencies** (Pure static site)

## 💻 Local Development

To run this landing page locally:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd safelyo-landing
   ```

2. Open `index.html` directly in your browser, or start a local static server:
   ```bash
   # Python 3
   python3 -m http.server
   
   # Node.js (http-server)
   npx http-server .
   ```

3. Visit `http://localhost:8000` (or the port shown by your server).

## 🔗 Important Links

- **Official Website**: [https://safelyo.app/](https://safelyo.app/)
- **Privacy Policy**: [https://safelyo.app/privacy.html](https://safelyo.app/privacy.html)
- **Terms of Service**: [https://safelyo.app/terms.html](https://safelyo.app/terms.html)
