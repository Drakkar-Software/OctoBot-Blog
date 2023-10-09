---
title: Crypto trading using artificial intelligence
subtitle: Learn how to automate your crypto trading with AI in 5 steps
slug: trading-with-ai-introduction
tags: ai, deep learning, trading, cryptocurrency, octobot
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1696882392556/RgxD6fE44.jpeg?auto=format
domain: blog.octobot.online
--- 

# How to automate crypto trading using AI

Dive into the future of cryptocurrency trading using the power of AI with OctoBot script! 
We'll walk you through 5 simple steps to automate your crypto trading using artificial intelligence. 
No matter your experience level, this guide is designed to provide a step-by-step process for setting up and executing your first automated cryptocurrency trade using AI.

## AI in Trading
Artificial intelligence (AI) has revolutionized how we trade. It helps in analyzing massive amounts of data, predicting market trends, and executing trades at lightning speed. To trade using AI, you need to choose a reliable AI trading software, set your trading parameters, and let the system do the rest.

![trading](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-with-ai-introduction/trading.jpg)

## Understanding reinforcement learning
Reinforcement Learning is a type of machine learning (itself a type of AI) where an agent learns to make decisions by taking actions in an environment to maximize some notion of cumulative reward. An 'agent' in this context refers to the algorithm or program that is making the decisions. It operates by interacting with its environment (in this case, the trading market), taking actions (such as buying or selling stocks), and receiving rewards or penalties based on the outcome. The goal of this agent is to learn over time which actions lead to the best outcomes, in this case, the most profitable trades.
In trading, we can use reinforcement learning to understand market dynamics, make accurate predictions, and execute profitable trades.

![brain](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-with-ai-introduction/brain.jpeg)

## OctoBot script

OctoBot script is engineered to provide traders with a framework for crafting and testing crypto trading strategies. 

It offers a suite of keywords (Python methods) which simplifies the process of creating trades and calculating TA indicators like RSI, thus facilitating users to design their unique trading strategies. 

OctoBot script also allows users to test their strategies using past data through the backtesting feature. With the generation of an advanced report at the end of each backtesting, users gain valuable insights into the performance of their strategies, enabling a comprehensive understanding of their effectiveness.

## How to use OctoBot script to trade with AI

- Install OctoBot script by following the get started guide at [pro.octobot.info](https://www.octobot.cloud/guides/scripting/getting-started)
- Install AI requirements with 
```
pip install -r requirements-ai.txt
```
- Install the necessary dependencies to be able to run the script on your GPU by following [this tutorial](https://gretel.ai/blog/install-tensorflow-with-cuda-cdnn-and-gpu-support-in-4-easy-steps) 
- Start to train your own model (model = the "brain" of your AI) on ETH/BTC using 
```
python3 ai-example.py -t -s ETH/BTC -e 10
```
- Once done your AI model will be saved in the weights folder. Find its name and add it in the end of the following command to run a backtesting using your new AI model 
```
python3 ai-example.py -p -s ETH/USDT -w weights/202310050722-final-dqn.h5
```
*202310050722-final-dqn.h5 is an example of weight, update it with your own*

- Here is an example of a backtesting using an AI model built using OctoBot script AI. There is no human action behind it, all the trades have been triggered by the AI.

![strategy-ouput](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-with-ai-introduction/strategy-output.png)

If you found this content helpful, please give us feedback in our community [Discord](https://discord.com/invite/vHkcb8W) and [Telegram](https://t.me/+UisN86uSzOMKtEwy)! Your support will encourage us to create a series of detailed guides exploring more strategies and insights into AI trading.
