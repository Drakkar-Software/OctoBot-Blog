---
title: Trading using TradingView
subtitle: Automate your trades using any TradingView indicator 
slug: trading-using-tradingview
tags: tradingview, pinescript, webhook, cryptocurrency, trading, strategy, exchange, blog, octobot cloud
cover: https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-using-tradingview/cover.png
domain: blog.octobot.online
--- 

# Trading using your favorite TradingView strategies

You love using TradingView indicators and strategies ? With OctoBot, you can take it to the next level and trade using TradingView strategies and indicators directly the exchange you want.

This means that you can use all the OctoBot features according to your TradingView tools, this includes:
- Trading on your favorite exchange(s) using your TradingView strategy
- Test your TradingView strategy in real time with simulated funds
- Get real time notifications when your TradingView strategy sends a buy or sell signal

# TradingView strategies in your OctoBot

When following a TradingView strategy, your OctoBot will listen for TradingView signals and when signals are received, it will react instantly by creating the associated alert and order(s), which can be simulated or real, on any supported exchange.

![plan-display](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/trading-using-tradingview/telegram.png)

You can send details on the order to create directly from the TradingView signal such as the type of order, the take profit and stop loss prices and much more. View the full details of orders signals on [the OctoBot docs](https://www.octobot.info/webhooks/tradingview-webhook#create-an-alert).


# How to bind your TradingView account to your OctoBot

## Using a Cloud OctoBot

When using [OctoBot Cloud](https://www.octobot.cloud/), all you need to do is to [create TradingView alerts](https://www.octobot.info/webhooks/tradingview-webhook#create-an-alert) on any event, directly from pinescript or from a custom alert. 

Cloud OctoBots' webhook configuration is done automatically and does not require any work.

## Using a self hosted OctoBot
When using a self hosted OctoBot, you will have to configure a way to make your OctoBot reachable from a webhook. This is required for TradingView to send signals to your OctoBot and might require an external paid software.

Please have a look at the [webhook manual configuration](https://www.octobot.info/webhooks/using-a-webhook-with-octobot).

Once your webhook setup, you can [create TradingView alerts](https://www.octobot.info/webhooks/tradingview-webhook#create-an-alert) on any event, directly from pinescript or from a custom alert.
