---
keywords: Trading,Options and Derivatives Trading,Options and Derivatives
title: Binomial Option Pricing Model
description: A binomial option pricing model is an options valuation method that utilizes an iterative technique and considers the node determination in a set period.
---

# Binomial Option Pricing Model
## What Is the Binomial Option Pricing Model?

The binomial option pricing model is an options [valuation](/valuation) method developed in 1979. The binomial option pricing model purposes an iterative method, considering the determination of nodes, or points in time, during the time frame between the valuation date and the option's [expiration date](/expiration-date).

The model reduces prospects of price changes and eliminates the possibility for [arbitrage](/arbitrage). A simplified illustration of a [binomial tree](/binomial_tree) could look something like this:
<!--87C9D3D79FF63D08201E6E848035602D-->
## Nuts and bolts of the Binomial Option Pricing Model

With binomial option price models, the suspicions are that there are two potential outcomes — consequently, the binomial part of the model. With a pricing model, the two outcomes are a move up, or a drop down. The major advantage of a binomial option pricing model is that they're mathematically simple. Yet these models can become complex in a multi-period model.

Rather than the [Black-Scholes model](/blackscholes), which gives a mathematical outcome in light of data sources, the binomial model considers the calculation of the asset and the option for different periods alongside the scope of potential outcomes for every period (see below).

The advantage of this multi-period view is that the client can envision the change in asset price from one period to another and assess the option in light of decisions made at various points in time. For a U.S-based [option](/americanoption), which can be exercised whenever before the [expiration date](/expirationdate), the binomial model can give knowledge concerning while practicing the option might be prudent and when it ought to be held for longer periods.

By taking a gander at the [binomial tree](/binomial_tree) of values, a trader can decide in advance when a decision on a [exercise](/exercise) may happen. On the off chance that the option has a positive value, there is the possibility of exercise though, assuming the option has a value under zero, it ought to be held for longer periods.

## Working out Price with the Binomial Model

The fundamental method of working out the binomial option model is to involve a similar likelihood every period for progress and disappointment until the option lapses. Nonetheless, a trader can incorporate various probabilities for every period in light of new data got over the long haul.

A binomial tree is a helpful device while pricing [American options](/americanoption) and [embedded options](/embeddedoption). Its simplicity is its advantage and disadvantage simultaneously. The tree is not difficult to model out mechanically, yet the problem lies in the potential values the underlying asset can take in one period of time. In a binomial tree model, the underlying asset must be worth precisely one of two potential values, which isn't practical, as assets can be worth quite a few values inside some random reach.

For instance, there might be a 50/50 chance that the underlying asset price can increase or diminish by 30 percent in one period. For the subsequent period, in any case, the likelihood that the underlying asset price will increase might develop to 70/30.

For instance, assuming an investor is assessing a [oil well](/exploratory-well), that investor doesn't know what the value of that oil well is, yet there is a 50/50 chance that the price will go up. Assuming oil prices go up in Period 1 making the oil well more important and the market [fundamentals](/fundamentals) presently point to proceeded with increases in oil prices, the likelihood of additional appreciation in price may now be 70 percent. The binomial model takes into account this adaptability; the Black-Scholes model doesn't.
<!--94DBA31F9D3220C6052579D485B8A416-->
## Genuine Example of Binomial Option Pricing Model

A simplified illustration of a [binomial tree](/binomial_tree) has just a single step. Expect there is a stock that is priced at $100 per share. In one month, the price of this stock will go up by $10 or go down by $10, causing this situation:

- **Stock price** = $100
- **Stock price in one month (up state)** = $110
- **Stock price in one month (down state)** = $90

Then, expect there is a call option accessible on this stock that terminates in one month and has a strike price of $100. In the up state, this call option is worth $10, and in the down state, it is worth $0. The binomial model can compute what the price of the call option ought to be today.

For disentanglement purposes, expect that an investor purchases one-half share of stock and composes or sells one call option. The total investment today is the price of half a share less the price of the option, and the potential payoffs toward the month's end are:

- **Cost today** = $50 - option price
- **Portfolio value** (up state) = $55 - max ($110 - $100, 0) = $45
- **Portfolio value** (down state) = $45 - max($90 - $100, 0) = $45

The portfolio payoff is equivalent regardless of how the stock price moves. Given this outcome, expecting no arbitrage opportunities, an investor ought to earn the risk-free rate throughout the span of the month. The cost today must be equivalent to the payoff discounted at the risk-free rate for one month. The equation to address is in this way:

- **Option price** = $50 - $45 x e ^ (- risk-free rate x T), where e is the mathematical steady 2.7183.

Expecting the risk-free rate is 3% each year, and T equals 0.0833 (one separated by 12), then the price of the call option today is $5.11.

The binomial option pricing model presents two advantages for option merchants over the Black-Scholes model. The first is its simplicity, which considers less errors in the commercial application. The second is its iterative operation, which changes prices on time to reduce the opportunity for purchasers to execute arbitrage strategies.

For instance, since it gives a surge of valuations to a [derivative](/derivative) for every node in a span of time, it is helpful for esteeming derivatives like American options — which can be executed whenever between the purchase date and expiration date. It is additionally a lot simpler than other pricing models, for example, the Black-Scholes model.

## Features
- The model is natural and is utilized more much of the time in practice than the notable Black-Scholes model.
- With the model, there are two potential outcomes with every cycle — a move up or a drop down that follow a binomial tree.
- The binomial option pricing model values options utilizing an iterative approach using various periods to value American options.
