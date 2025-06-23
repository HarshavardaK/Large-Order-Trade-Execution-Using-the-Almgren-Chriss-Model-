# Large-Order-Trade-Execution-Using-the-Almgren-Chriss-Model-
# Optimising Trading Strategies: The Almgren-Chriss Model Explained

In the trading industry, large orders are rather complex to execute efficiently. Traders must minimise costs both from market impacts and volatility of prices while accomplishing the trades on time. The optimal execution model proposed by Robert Almgren and Neil Chriss in 2000 deals with this issue within a mathematical framework. It balances out the cost and risk of executing large trades over time, thereby providing traders with a means to reduce both explicit and implicit costs.

---

## Practical Overview

Suppose you are a portfolio manager and you have a large sell order for an enormous amount of shares. You cannot sell all the shares at once, since it would drastically drop the price level as a result of an imbalanced supply and demand. On the other hand, selling them out for an extended period risks you from market volatility that may further result in worse prices over some time. The Almgren-Chriss model gives a strategy to trade these shares in a manner that minimises both the immediate price impact of your trades and the risk from price fluctuations over the execution period.

---

## Key Components of the Almgren-Chriss Model

According to the basic idea of the Almgren-Chriss model, it determines the optimal execution strategy based on two factors:

1. **Market Impact Costs**: These would involve the costs associated with moving the market price as a result of your trading activity. The bigger the volume traded and the shorter the time frame, the bigger the effect on the price of the security and hence the hike in the transaction cost.

2. **Execution Risk Costs**: These arise from market volatility and the risk that, while attempting to execute, the price of the security may fluctuate unfavourably.

---

It is, therefore, the goal to minimise these two factors by finding an optimal balance that defines the best schedule for the execution of the trade.

## Market Impact Costs: Breaking Down Temporary and Permanent Effects

Market impact costs in the Almgren–Chriss model are split into two types: **temporary impact** and **permanent impact**.

### 1. Temporary Market Impact

This is the movement in price due to the trade that temporarily exists but decays when the source of the liquidity returns to its normal state.
Large trades executed quickly will have a disproportionately larger cost, incentivizing traders to execute smaller trades over time to reduce this cost.

---

### 2. Permanent Market Impact

In contrast to temporary impact, permanent market impact reflects the long-term price impact of the trade. After a large trade, market participants may reassess underlying security value and there may be a permanent price adjustment.
While the permanent impact grows linearly, the long-lasting effects mean that larger trades tend to shift the market’s baseline valuation of the security, making it crucial for traders to monitor total traded volume.

## Execution Risk Costs: Managing Volatility Exposure

Execution risk costs arise from price volatility during the trade execution period. The longer it takes to execute an order, the more exposed a trader is to unfavourable price movements.
