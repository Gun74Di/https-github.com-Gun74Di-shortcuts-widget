# https-github.com-Gun74Di-shortcuts-widget
A lightweight DeFi dashboard &amp; DEX aggregator with one-click shortcuts for swap, liquidity, and staking.
# Shortcuts Widget – Zama FHE Edition

Shortcuts Widget is a lightweight DeFi dashboard and DEX aggregator built with Zama’s Fully Homomorphic Encryption (FHE) technology in mind.  
The project explores how FHE can bring **privacy-preserving DeFi interactions** to users while keeping the interface simple and efficient.

## 🚀 Features
- One-click DeFi actions (swap, add/remove liquidity, stake)
- Modular widget design for easy integration into dashboards
- **FHE-powered privacy**: transaction inputs and user balances can be encrypted while still enabling computations
- Dashboard view for quick asset management
- Supports multi-protocol integration

## 🔒 Why FHE (with Zama)?
Most DeFi dashboards require users to reveal wallet balances, transaction details, and even strategies.  
With Zama’s FHE:
- Sensitive data (like amounts, balances, preferences) can stay encrypted.
- Computations (e.g., swap rate calculation, portfolio stats) happen on encrypted data.
- Users gain better security and privacy without losing functionality.

This makes Shortcuts Widget not only fast and lightweight, but also **privacy-first**, aligning with the mission of Zama.

## 🛠️ Tech Stack
- React + Next.js
- TailwindCSS for UI
- Ethers.js / Web3.js for blockchain interactions
- Vercel for deployment
- [Zama FHE libraries](https://github.com/zama-ai) for encryption logic

## 🌐 Live Demo
[shortcuts-widget.vercel.app](https://shortcuts-widget.vercel.app/)

## 📦 Installation
```bash
git clone https://github.com/Gun74Di/shortcuts-widget
cd shortcuts-widget
npm install
npm run dev
