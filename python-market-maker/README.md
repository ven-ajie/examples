Sample market maker bot
===

Strategy
---

The bot maintains a exponential moving average of the mid price for each of the futures. It then centers a set bid and ask orders around this value. The spread between the bids and the asks depends on the volatility.

Set up
---

This bot requires python3 and the [Deribit api wrapper](https://pypi.org/project/deribit_api/).

To set up the bot, edit the `KEY` and `SECRET` variables in the code to your credentials. You can obtain those from the [Deribit account](https://www.deribit.com/main#/account?scrollTo=api).

To start the bot, run `python3 market_maker.py`.

Disclaimer
---

Different market conditions will produce different results. This code is for sample purposes only. It comes as is, with no warranty or guarantee or performance.