# Risks

## Automated Market Maker Risks

Crest currently uses a mining revenue strategy with liquidity pool exposure.

Impermanent loss (also known as Non-permanent Loss) is the risk of capital loss caused by the automatic balance of assets under the AMM (Automated Market Maker) mechanism.

Impermanent loss is related to the provision of assets to the liquidity pool, which Uniswap to create trading markets and enable traders to trade the assets backed by the pool.

If you deposit funds that have been already used to provide liquidity in the AMM, you may lose part of the deposited value when the relative value of the assets in the AMM changes.

Further reading on impermanent loss and AMM risks:

[Beginner’s Guide to (Getting Rekt by) Impermanent Loss](https://blog.bancor.network/beginners-guide-to-getting-rekt-by-impermanent-loss-7c9510cb2f22)

[Uniswap: a good deal for liquidity providers?](https://medium.com/@pintail/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2)

[Calculating Value, Impermanent Loss and Slippage for Balancer Pools](https://medium.com/balancer-protocol/calculating-value-impermanent-loss-and-slippage-for-balancer-pools-4371a21f1a86)

[What Is IMPERMANENT LOSS? DEFI Explained - Uniswap, Curve, Balancer, Bancor](https://www.youtube.com/watch?v=8XJ1MSTEuU0)



**Safety Buffers：**

Impermanent loss are not exclusive to Crest, and they are prevalent in all liquidity mining and AMM projects.

As a user, you can choose pools closely connected to the token, e.g., WETH-WBTC (coming soon)

Crest will continuously upgrade and optimize its strategy to minimize impermanent loss.

## Liquidity and Market Risk

### **Risk**

The liquidity of many new Defi projects is extremely underperformed, and it may cause you significant loss under the influence of marketing changes when buying and selling. When prices change dramatically, liquidity could disappear, and you may be trapped in a position and unable to trade your assets.

Market impact (also known as price impact) occurs when trading volume is high enough to change the price of an asset traded on an exchange. Market impact increases when liquidity decreases during the time of severe volatility.

If you try to create a relatively large position with including an automatic swap of assets, your trade may face a large price slippage.

**Example:** The total amount of liquidity pool is $100 million. If you are taking approximately $1 million token trading (which accounts for 1% of the total amount of  liquidity pool), the price slippage you will face is roughly 4%  when you exchang your tokens.

If you are not familiar with the price exchange mechanism of AMMs, please read [how xy = k AMMs work.](https://medium.com/finnexus/understanding-the-xyk-model-of-pooled-liquidity-7340fdc20d9c)

**Safety Buffers：**

Avoid creating and closing positions in a short time.

Create multiple relatively small positions, or create a small position first and then add margin to that position after waiting some time. You can only avoid the impact of price slippage after the arbitrageur brings the price back to normal levels.

When you try to close a huge position, please choose a minimized trading strategy to reduce the price slippage and gas fees caused by the exchange.
