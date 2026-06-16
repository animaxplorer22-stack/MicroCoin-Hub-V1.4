# ◈ MicroCore (MCX) - Decentralized Blockchain Network

**MicroCore** is a complete, production-ready blockchain network with built-in DEX, staking, liquidity pools, and multi-device mining support.

[![Version](https://img.shields.io/badge/version-1.4-blue.svg)](https://github.com/yourusername/microcore/releases)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.7%2B-blue.svg)](https://python.org)

---

## 📋 Table of Contents

- [Features](#-features)
- [Tokenomics](#-tokenomics)
- [Quick Start](#-quick-start)
- [Installation](#-installation)
- [Running a Node](#-running-a-node)
- [Mining](#-mining)
- [Web Wallet](#-web-wallet)
- [Block Explorer](#-block-explorer)
- [API Reference](#-api-reference)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🚀 Features

### Core Blockchain
- ✅ **10-level system** (1,000 MCX per level)
- ✅ **84M MCX hard cap** (with halving)
- ✅ **3 MCX block reward** (10 levels, each with own pool)
- ✅ **Block times**: 40s → 35s → 30s → 25s → 20s → 15s → 10s → 9s → 8s → 7s
- ✅ **10 validators** per block (2.5 second signing window)
- ✅ **Slashing** (10% stake loss on missed signatures)
- ✅ **Slashing redistribution** to signers
- ✅ **Temporary & Permanent Towers**
- ✅ **Level unlocking** (10 unique wallets needed)

### Decentralized Exchange (DEX)
- ✅ **Own pools**: MCX/USDC, MCX/BTC, MCX/ETH, MCX/SOL, MCX/BNB
- ✅ **0.3% swap fee** (paid in MCX)
- ✅ **LI.FI aggregator** integration
- ✅ **THORChain** integration
- ✅ **Add/remove liquidity** with LP shares

### Staking & Rewards
- ✅ **On-chain stake verification**
- ✅ **70% to validators** (0.21 MCX each per block)
- ✅ **8% to node operators**
- ✅ **5% to uptime pool** (miners by uptime)
- ✅ **5% to liquidity providers**
- ✅ **12% to buyer rewards** (top 10 monthly)

### Buyer Rewards (Monthly)
| Rank | Reward (MCX) |
|------|--------------|
| 🥇 1st | 5,000 |
| 🥈 2nd | 3,000 |
| 🥉 3rd | 2,000 |
| 4th-5th | 1,000 |
| 6th-10th | 500 |

### Mining Support
- ✅ **PC Miner** (Windows/Mac/Linux)
- ✅ **Phone Miner** (iPhone a-shell / Android Termux)
- ✅ **ESP32/ESP8266 Miner**
- ✅ **Raspberry Pi Pico W Miner**
- ✅ **Arduino Uno Miner** (with WiFi Bridge)

### Fiat On-Ramp
- ✅ **Stripe integration** (credit cards)
- ✅ **Bitcoin** payment support
- ✅ **Ethereum** payment support
- ✅ **USDC** payment support
- ✅ **DUCO** payment support (special handling)

### Web Wallet
- ✅ **Create/Login** with username/password
- ✅ **Web mining** (browser-based)
- ✅ **Send MCX** to username
- ✅ **Buy MCX** with credit card/crypto
- ✅ **Stake/Unstake** MCX
- ✅ **Swap tokens** (real DEX)
- ✅ **Provide liquidity** (real LP)
- ✅ **Miner management** (start/stop/restart)
- ✅ **Node management**
- ✅ **Transaction history**
- ✅ **Leaderboards** (top stakers/buyers)
- ✅ **Gossip discovery** (no DNS required)

---

## 📊 Tokenomics

### Supply Distribution

| Recipient | Percentage | MCX per Block (3 MCX total) |
|-----------|------------|-----------------------------|
| 10 Validators | 70% | 2.1 MCX total (0.21 each) |
| Node Operators | 8% | 0.24 MCX total |
| Uptime Pool | 5% | 0.15 MCX total |
| Liquidity Providers | 5% | 0.15 MCX total |
| Buyer Rewards | 12% | 0.36 MCX total |

### Level Caps (4-year halving periods)

| Level | Cap per 4 years | Total Cap (infinite halvings) |
|-------|-----------------|-------------------------------|
| 1 | 9,460,800 | 18,921,600 |
| 2 | 10,812,000 | 21,624,000 |
| 3 | 12,614,400 | 25,228,800 |
| 4 | 15,137,280 | 30,274,560 |
| 5 | 18,921,600 | 37,843,200 |
| 6 | 25,228,800 | 50,457,600 |
| 7 | 37,843,200 | 75,686,400 |
| 8 | 42,048,000 | 84,096,000 |
| 9 | 47,304,000 | 94,608,000 |
| 10 | 54,061,680 | 108,123,360 |
| **TOTAL** | **273,420,000** | **~546,840,000** |

---

## 📁 Repository Structure
