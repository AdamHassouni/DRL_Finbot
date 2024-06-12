# Deep Reinforcement Learning Trading Bot

Welcome to the Deep Reinforcement Learning (DRL) Trading Bot repository. This project leverages the power of FinRL, a deep reinforcement learning library, to develop, train, and evaluate trading strategies using PPO, A2C, and DDPG policies. The model is trained on 10 years of historical financial data to make informed trading decisions.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This project aims to create a robust trading bot that can make profitable trades using deep reinforcement learning algorithms. The bot is trained on 10 years of historical financial data, using three different DRL policies: Proximal Policy Optimization (PPO), Advantage Actor-Critic (A2C), and Deep Deterministic Policy Gradient (DDPG).

## Features

- **Deep Reinforcement Learning**: Utilizes advanced DRL algorithms to learn and optimize trading strategies.
- **Multiple Policies**: Implements PPO, A2C, and DDPG policies for training and evaluation.
- **Historical Data**: Trained on a decade of historical financial data to ensure robustness and reliability.
- **FinRL Library**: Leverages the FinRL library for streamlined development and training of DRL models.

## Installation

To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/DRL_Trading_Bot.git
cd DRL_Trading_Bot
pip install -r requirements.txt
```
## Usage
To train and evaluate the trading bot, follow these steps:

1-Prepare Data: Ensure you have the historical data in the correct format. The data should cover at least 10 years of trading history.
2-Configure Settings: Modify the configuration files as needed to specify the data source, trading environment, and DRL policies.
3-Train the Model: Run the training script to train the model using the chosen DRL policies.

## Results
The results of the trained models, including performance metrics and visualizations, are documented here. The performance of the PPO, A2C, and DDPG models are compared to evaluate their effectiveness in trading.

Performance Metrics
-Total Return: Percentage return of the portfolio over the testing period.
-Sharpe Ratio: Measure of risk-adjusted return.
-Max Drawdown: Maximum observed loss from a peak to a trough.

## Happy Trading
