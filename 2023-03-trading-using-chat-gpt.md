---
title: Trading using ChatGPT
subtitle: Use ChatGPT to predict market trends and trade accordingly
slug: trading-using-chat-gpt
tags: ChatGPT, AI, cryptocurrency, trading, strategy, exchange, blog, octobot cloud
cover: https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-using-chat-gpt/cover.png
domain: blog.octobot.online
--- 

# Ask ChatGPT about the future of the market
Wouldn't it be great to know what [ChatGPT](https://chat.openai.com/) thinks about a particular market direction ? 

![chatgpt-logo](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-using-chat-gpt/ChatGPT-Logo.png)


While ChatGPT can't directly answer question such as "Will BTC/USD go up tomorrow ?", it can answer many related questions including forecasting trends.

This is a great opportunity to take advantage of the extremely powerful AI that is ChatGPT (in version 3 or later) and integrate it directly in your trading strategies.


# ChatGPT in your OctoBot
In OctoBot 0.4.47, we added a new evaluator: the `GPTEvaluator`. This evaluator can be used like any other evaluator in the `DailyTradingMode`.

When enabled, it will automatically ask ChatGPT about is opinion on every traded pair, on each time frame.

The type of data given to ChatGPT can be configured: the value of the asset price or different kind of technical evaluator can be sent to ChatGPT for it to make its opinion.

Once enabled, `GPTEvaluator` behaves like any other technical evaluator, this means that it can combined with others, used to trade, to create trading signals or to notify you when the situation changes. 

You can therefore:
- Automatically trade based only on ChatGPT's predictions
- Trade combining ChatGPT's predictions with other evaluators
- Get ChatGPT's view on the market at anytime from the web interface and market status and get notified on any change

![telegram-chat](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-using-chat-gpt/telegram.png)

# How to use ChatGPT in your OctoBot
As ChatGPT's automated calls is a paid feature from [openai.com](https://openai.com/), there are 2 ways to use it in OctoBot.

## 1. ChatGPT with covered costs on Cloud OctoBots
When using Pro Cloud OctoBots, you will be using our subscription to [openai.com](https://openai.com/). This means that we will cover the costs of your requests to ChatGPT ourselves so that you don't need to worry about it. 

## 2. ChatGPT from your self hosted OctoBot
To use ChatGPT from your self hosted OctoBot (meaning OctoBots that are not running on the [OctoBot Cloud](https://octobot.cloud/)), you have to provide your how OpenAI API key and store it into your OctoBot configuration. The regular OpenAI pricing will then be applied.

More details on how to setup ChatGPT and how to estimate the cost of its requests on the [dedicated docs](https://www.octobot.info/interfaces/chatgpt-interface)
