---
title: Following strategies in Astrolab
subtitle: You can now follow trading strategies of the community
slug: following-strategies-in-astrolab
tags: cryptocurrency, trading, strategy, exchange, blog, astrolab
cover: https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/cover.png
domain: blog.octobot.online
--- 


# Follow the best strategies
On Astrolab, you can subscribe to trading strategies. Subscribing to a strategy allows you to easily trade using a strategy made by someone else from the OctoBot community.

When subscribed to a strategy, you can use the strategy profile directly from your OctoBot. When you do so, your OctoBot will follow the strategy by coping any trade made by this strategy. Order amounts will be adapted to your current portfolio.

# How to use a followed strategy ?
1. Login on [Astrolab](https://www.astrolab.cloud/) and go to the desired strategy page 
2. Click `Subscribe`
![Following-strategies-pre-sub](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/pre-sub.png)
3. Now that you are subscribing to the strategy, click `Copy download url`
4. From your OctoBot, login to your Astrolab account
![Following-strategies-community](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/community.png)
5. Go to the `Profile` tab and click on the name of the current profile, click `Import a profile`
![Following-strategies-import](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/profile-sharing-in-astrolab/bot-import.jpg)
6. Paste the download url (that was copied from step 3) and click `Import`
![Following-strategies-imported](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/imported.png)
7. Use the imported profile and restart your OctoBot

# How does it work ?
When following a strategy, a user gets access to the trading signals of the strategy. Trading signals are emitted at each order created or cancelled by the followed strategy. This way followers of a strategy benefit from trades of the desired strategy in real time directly from their OctoBot. Strategies can be applied to any exchange as long as the strategy trading pairs are supported. You can follow a strategy with real or simulated trading.

Trading through strategy signals is achieved by using the RemoteTradingSignalsTradingMode configured to follow the strategy you selected. When importing a strategy profile, you are importing an already configured profile that enables this trading mode with the right strategy identifier and the strategy traded pairs and default exchange.

![Following-strategies-mode-config](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/mode-config.png)

As following a strategy is only possible through Astrolab, you need to login to your Astrolab account from your OctoBot to be able to follow a strategy.


# How to publish a strategy on Astrolab ?
Trading strategies are published on [Astrolab](https://www.astrolab.cloud/) by the OctoBot community. 
When a user wants to share a trading strategy, the only thing to do is to:
1. Create a strategy on [Astrolab](https://www.astrolab.cloud/) 
2. Setup the desired OctoBot trading mode to emit trading signals to this strategy
![Following-strategies-config](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/config.png)

Note: the identifier of the strategy to emit signal on can be found on the strategy page, by clicking on this button 
![Following-strategies-id-button](https://raw.githubusercontent.com/Drakkar-Software/OctoBot-Blog/master/resources/images/following-strategies-in-astrolab/id-button.png)

Please note that configuration and content of a published strategy is not uploaded to Astrolab and followers can't access the code or configuration of the strategy. They will only get trading signals when the OctoBot that is actually running the strategy will create or cancel orders.


# Join the beta

Following strategies will first be available on the [beta Astrolab](https://beta.astrolab.cloud/).
To join the OctoBot beta program, [have a look here](https://www.octobot.info/advanced&#95usage/beta-program)
