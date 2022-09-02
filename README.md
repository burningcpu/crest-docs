# Introduction

You can access Crest Protocol through the official [Web App](https://www.crest.money).

Welcome to the Crest Protocol document site.

## **Background**

The trading volume of Uniswap has surpassed that of mainstream exchanges and has become the decentralized trading platform with the largest trading volume, and its market share will gradually increase. The liquidity provision of Uniswap V2 is simple to operate, but free losses discourage users. The mechanics of Uniswap V3 give expert traders enormous scope to reap rewards by identifying and setting the current market’s trade-intensive range. The same funds, different interval settings, the benefits obtained are worlds apart.&#x20;

As shown in the figure below, the benefits obtained in different intervals are completely different, and the capital utilization rate will be highest only in the transaction-intensive area.

<figure><img src=".gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Let's illustrate with an example:

Alice and Bob both want to provide liquidity in an ETH/DAI pool on Uniswap v3. They each have \\$1m. The current price of ETH is 1,500 DAI.

Alice decides to deploy her capital across the entire price range (as she would have in Uniswap v2). She deposits 500,000 DAI and 333.33 ETH (worth a total of \\$1m).

Bob instead creates a concentrated position, depositing only within the price range from 1,000 to 2,250. He deposits 91,751 DAI and 61.17 ETH, worth a total of about $183,500. He keeps the other $816,500 himself, investing it however he prefers.

While Alice has put down 5.44x as much capital as Bob, _they earn the same amount of fees_, as long as the ETH/DAI price stays within the 1,000 to 2,250 range.

Liquidity providers need to follow the market price, constantly adjust the range, and set the range in the current trading intensive area to obtain the maximum return. However, the interval adjustment is frequent, and the gas consumption is also a huge overhead, and a balance needs to be found here. Obviously, this is very demanding on liquidity providers.

Is it possible to provide an agreement? Let LP entrust funds to GP for management. LP does not need to manage the interval, does not need to pay attention to the transaction-intensive area, and does not need to consume GAS. It only needs to deposit money, withdraw money, and obtain income. The GP can obtain the operation authority of the LP's funds, but cannot withdraw funds. It can only set the interval, so as to ensure the absolute security of the LP's funds. The GP helps the LP to earn a proportional share of the fees.

Crest Protocol was born in this context.

## What is Crest Protocol?

Crest Protocol is a liquidity management platform based on quantitative strategies on Uniswap V3. After the liquidity provider provides liquidity through the Crest smart contract, there is no need to adjust the range, and it is all managed by Crest Protocol and the GPs who join the platform. Help liquidity providers save gas fees, lower the threshold for participating in Uniswap V3, and improve the efficiency of revenue and capital use.

## The role of Crest Protocol

* LP: Liquidity providers, LPs can officially provide liquidity on Uniswap, but they need to follow the market to continuously adjust the range in order to obtain the maximum return, and LPs often suffer losses due to lack of experience.
* GP: Expert traders, who can sensitively identify the intensive trading area, set the interval within a reasonable range, and ensure the maximization of returns. GPs can deploy V3 POOL in Crest Protocol to attract LP funds with high APR.
* Protocol: The protocol provider is a set of smart contracts officially provided by Crest to ensure the security of funds and coordinate the relationship between GP and LP.

**Why Choose** Crest Protocol**?**
----------------------------------

**High return:** the true return rate of ETH-USD LP in Crest is the highest in the past few months.&#x20;

**Stable income:** after extreme market tests, our users can still enjoy low retracement and high Sharpe ratio and continuously earn fee income.&#x20;

**Low cost:** users do not need to pay the expensive gas fees for rebalancing and reinvesting.&#x20;

**Simple:** automatic balancing, automatic reinvesting, automatic income tracking, etc.

##
