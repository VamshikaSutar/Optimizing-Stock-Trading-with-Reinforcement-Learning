# **FinSearch: Reinforcement Learning for Stock Trading**

FinSearch is a summer research project exploring how **Reinforcement Learning (RL)** can be applied to real-world financial markets.  
This project implements a **DDPG-based trading agent** capable of learning profitable strategies through continuous interaction with a custom-designed stock-trading environment.

---

## 🚀 Project Overview

The goal of FinSearch is to build an end-to-end RL pipeline that learns to buy, hold, or sell stocks based on historical market data and engineered state representations.  
The core of the project uses **Deep Deterministic Policy Gradient (DDPG)** — an Actor–Critic algorithm ideal for continuous action spaces in trading.

---

## 🧠 Key Features

### ✔ Custom RL Trading Environment
- Designed to simulate realistic market conditions.
- Models transaction costs, portfolio constraints, and risk exposure.
- Provides a continuous action space for fine-grained trading decisions.

### ✔ DDPG-Based Trading Agent
- Implements complete Actor and Critic networks.
- Target networks with soft updates for stable learning.
- Optimizes long-term return through policy gradients.

### ✔ Custom Action Space & Reward Engineering
- Tailored continuous action space for financial decisions.
- Reward function reflects real trading objectives — return, risk, drawdown, and stability.

---

## 📈 Results

The agent was evaluated on **ĜSPC2018 (S&P 500)** stock data and achieved:

> **💹 28% simulated return on a $500 virtual investment**

This demonstrates the potential of combining RL with careful environment and reward design for financial decision-making.

---

