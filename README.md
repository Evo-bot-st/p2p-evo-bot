# p2p-evo-bot
Hello!

For sale: a bot for purchasing P2P orders on the Bybit exchange at a low rate.
The essence of the bot is to auto buy orders at a rate lower than the market on Bybit's P2P platform. Our project is currently the fastest, successfully capturing 95% of orders with a reduced rate. 

The remaining 5% is due to short-term load spikes on CloudFront servers, during which the bot may send purchase requests with increased delay (this is rare and is partially resolved by node rebalancing).
The bot does not violate Bybit's rules, and account blocking does not occur. Testing was conducted over 6 months, and all bugs were fixed.

## Technical specifications of the bot:
#### •	The project is written in C++ using CMake.
#### •	Configuration is set via a YAML file; tokens need to be updated and the master restarted every 3 days.
#### •	Metrics are exported through Prometheus to Grafana (see screenshots).
#### •	Supports purchases from multiple accounts, with the ability to set a list of banks and purchase limits for each.
#### •	Built-in filters for minimum and maximum differences between orders.
#### •	A node rebalancing mechanism is implemented, which can be enabled and disabled. Nodes reconnect to other CloudFront servers at specified intervals.
#### •	Purchase notifications are implemented through a Telegram bot (see screenshots).

## Who can benefit from this bot:
#### •	Arbitrageurs who want to catch orders from 30 kopecks or have many drops and are not worried about card blocking. Purchases are possible with a difference of up to 20-30 rubles (Bybit has a limit of up to 30%).
#### •	For processing: teams can buy at favorable rates and increase profit.

## Reason for sale: 
The project was our first and was initially developed for commercial implementation. We do not engage in P2P arbitrage and card, drop searching as this is not our main business.

## What we provide to the buyer:
#### •	Source code of the project.
#### •	Full setup of the bot on your servers (if required).
#### •	Additional instructions for working with the bot.
#### •	Support for 14 days (additional questions during usage are possible).

## To ensure the quality of the project, we will connect you to the bot and conduct joint testing.
Contact us for more information and purchase details.

### Telegram: @trade_rus

![1](https://github.com/Evo-bot-st/p2p-evo-bot/assets/171810664/d0db8be1-cd5e-4a3f-83b5-58183895a2a7)
![2](https://github.com/Evo-bot-st/p2p-evo-bot/assets/171810664/e7d83354-7db9-4233-9e33-7e30d2fe2d64)
![3](https://github.com/Evo-bot-st/p2p-evo-bot/assets/171810664/b6057f40-8ff5-4c1c-b468-21a0c44d6100)
![4](https://github.com/Evo-bot-st/p2p-evo-bot/assets/171810664/7731ee03-dcb6-410d-ba77-5e631b4667c7)





