# Features

**Feature 1：Share the same Pool**

All funds deposited by users will be placed in the same trading pair, and the smart contract records each user's share for profit distribution. From the perspective of Uniswap V3, all funds deposited in Crest are like the funds of a user. Participating in the liquidity mining of V3 POOL and dividends will be returned to Crest, and the Crest contract will distribute dividends to users proportionally.

**Feature 2：Share the income in proportion to the invested capital**

To ensure the sustainability and stability of income, rebalancing and reinvesting are necessary, but they both require users to pay high Gas fees. For ordinary users, the gas fee will blow away all the fee income carelessly.

**Feature 3：GP adjust range**

GP manages the funds of all LPs, and will follow the market uniformly, adjust the interval, and identify the transaction-intensive areas. Since the LP does not need to adjust the interval, the GAS cost is basically 0.

**Feature 4：Crest Robot**

Since the market price changes rapidly, Crest Robot can automatically detect the price change. If the price is about to jump out of the range, it can automatically set the range, avoiding manual operation. However, it is necessary to save enough fees to pay for the gas consumption of the adjustment range. The interval setting is small, and the income is high, but the price is easy to run out of the interval, and the number of adjustments is large, resulting in high GAS costs. The interval setting is large, the income is small, but the price is not easy to run out of the interval, the number of adjustments is small, and the gas fee will naturally decrease. Therefore, Crest Robot will find a balance between the two extremes, automatically identify the current market trend, and set the highest yield range.
