# 📈 Volatility Trading Strategies & Quantitative Microstructure

[![Python 100%](https://img.shields.io/badge/Language-Python-blue.svg)](https://www.python.org/)

Welcome to **Volatility-Trading-Strategies**, a rigorous, production-grade quantitative repository dedicated to advanced options pricing, volatility surface modeling, market-maker microstructure, and automated trading strategies. 

This repository bridges classical derivative pricing theory (Black-Scholes, local and stochastic volatility models) with modern order-book dynamics, high-frequency data processing, dealer inventory mechanics (GEX, VEX), and machine learning-driven forecasting.

---

## 🏗️ Repository Architecture & Module Directory

The codebase is structured into modular research units mirroring institutional quantitative trading desks:

```text
Volatility-Trading-Strategies/
│
├── Module 1 - What Volatility Really is/             # Foundations: RV vs IV, volatility clustering
├── Module 2 - Implied Volatility & Option Pricing/   # BSM framework, forward pricing, put-call parity
├── Module 3 - Greeks as Risk Exposures/              # Delta, Gamma, Vega, Theta risk matrix
├── Module 4 - Volatility Surface & Skew Trading/     # Smile construction, arbitrage bounds, skew metrics
├── Module 5 - Realized vs Implied Volatility Trading/# VRP harvesting and statistical arbitrage
├── Module 6 - Delta Neutral Traing & Gamma Scalping/ # Dynamic hedging, transaction costs, and rebalancing bands
├── Module 7 - Volatility Trading Structures/         # Calendar spreads, straddles, iron condors, ratios
├── Module 8 - Variance Swap & Volatility Derivatives/# Variance swaps, gamma replication, VIX futures
├── Module 9 - Volatiltiy Surface Modelling/          # SVI parametrization, local vol (Dupire), stochastic vol (Heston)
├── Module 10 - Volaility of Volatility/              # Volga, Vomma, and higher-order risk factors
├── Module 11 - Dispersion Trading/                   # Index vs single-stock variance and correlation risk
├── Module 12 - Event Volaility Trading/              # Earnings IV crush, macro data releases, post-event drift
├── Module 13 - Volatility Market Microstructure/     # GEX, VEX, 0DTE dynamics, order flow, gamma squeezes
└── Results/                                          # Generated backtest outputs, figures, and logs
