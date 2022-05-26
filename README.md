# Crest.money

## **1. What is** Crest?

Crest is an active liquidity management platform of Uniswap V3 based on risk ranking and quantitative strategies.

Official website : https://www.crest.money/

## 2. Crest VS Yearn

Yearn Finance (YFI) is a benchmark of liquidity management. There are some key differences between Crest and Yearn. ‌

Crest **= Yearn + Uniswap V3 ‌**

Crest is built for Uniswap V3 while Yearn focuses on Curve Finance.

Crest **= Yearn + Risk Grading ‌**

The products of Crest can meet different demands of users who have different risk appetites. ‌

Crest **= Yearn + Quantitative Strategy** ‌

Crest maximizes the return of LP through quantitative strategies. ‌

Crest **= Yearn + Leverage Trading** ‌

Users can open long/short LP positions earning both trading profit and LP profit.

## 3. Products

With a series of products, Crest can meet the needs of LPs who have different risk appetites.

* Uniswap V3 Backtesting Platform
* Uniswap V3 Active LP Quantitative Management Strategy
* Uniswap V3 Smart Vault
* Uniswap V3 Private Vault
* Uniswap V3 Hedging Vault (Developing)
* Uniswap V3 Leveraged Vault (Designing)

## **4. The Challenges on Uniswap V3**

The most significant improvement of Uniswap V3 is its ability to gather liquidity in a specified range, and in this way, it can generate earnings several times more than V2. Although it produces high yields, it also causes many challenges to LPs:

**Challenge 1：High risk**

While centralized liquidity can enlarge the income by increasing the capital efficiency, it also amplifies the impact of impermanent loss, especially when the price is out of range. Once it happens, the impermanent loss may continue to increase while the income goes to zero.

**Challenge 2: High cost**

To ensure the sustainability and stability of income, rebalancing and reinvesting are necessary, but they both require users to pay high Gas fees. For ordinary users, the gas fee will blow away all the fee income carelessly.

**Challenge 3: Rebalancing**

How to dynamically set the optimal price range to earn the optimal fee income? When the price deviates, it may face the risk of abnormality if it is not balanced, and it may also face the risk of loss of net value after the price returns. The timing and parameters of rebalancing are two complex quantitative matters.

**Challenge 4: Reinvestment**

Compared with automatic reinvestment on V2, V3 requires manual reinvestment of the fee income. How to resume investment continuously and stably? How much influence does the gas fee of reinvestment have on the returns? These problems are extremely challenging for most LPs.

**Challenge 5: Hedging**

Uniswap LP needs to provide dual currency investment (e.g., ETH-USDC). How do U-based users with low-risk preferences offset the price fluctuation of risky assets (such as ETH)? Furthermore, how to hedge the risk of LPs' impermanence loss?

## **5. Who do we serve?**

Crest serves different types of users in the Uniswap ecosystem.

### **Risk-averse users**

#### Example 1: U-based users or arbitrageurs with the lower risk appetite

**Need:** cutting-edge hedging strategies and tools that allow users to earn low-risk arbitrage returns.

**Challenge:** lack of efficient LP hedging strategies and useful LP hedging tools.

#### Example 2: High-net-worth users and institutions

**Need:** fund security+secured smart contracts.

**Challenge:** smart contracts are between Scylla and Charybdis at the moment.

### **Risk-neutral user**

#### Example: currency-based users or ordinary liquidity miners.

**Need:** looking for higher and more stable LP income

**Challenge:** currently, the income of mining is comparatively low and unstable.

### **Risk-seeking user**

#### Example: transactional users with higher risk preference.

**Need:** looking for high-risk and high-yield trading opportunities and earn stable mining income

**Challenge:** lack of appropriate products in the market that can earn mining and trading income at the same time

## 6. **Our approaches to the Challenges**

Crest solves these problems and meets the needs through a series of combinable products.

### 6.1 Crest backtesting Platform

Crest Backtesting is the first LP revenue backtesting system on Uniswap V3 with accurate on-chain data, granularity of block-level backtesting, flexible self-defined parameters, and robust strategy analysis indicators. It can help users understand the benefits and the risks of Uniswap V3 LP easier and customize the LP strategies.

### 6.2 Crest Active LP Management Quantitative Strategy

The active LP management quantitative strategies solve many problems on Uniswap V3 LP: high risk, high cost, rebalancing problem, extreme market situations, high loss value, etc.

Based on the underlying principle of Uniswap V3, we established a multifactor quantitative financial model. We finally created a strategy model with stable income through a large amount of data backtesting and optimizing. According to the backtesting data in the previous two months, the annualized earning of fee APY of the smart vault reaches 150%+. The net annualized income is up to 50%\~70%. These two items are outperforming all revenue products on the market.

### 6.3 Crest Smart Vault

**Target users:** currency-based users or ordinary LP users (risk-neutral users)

**Product Description:** A specific intelligent quantitative strategy supports each smart vault. Under the instruction of the strategy signal, the strategy contract dynamically rebalances the liquidity position of LPs, and helps users earn fee income.

### 6.4 Crest Private Vault

**Target users:** high-net-worth individuals and institutions (risk-averse users).

**Product Description:** the Crest private vaults is the intelligent vault with high-level security for high-net-worth individuals and institutions. Comparatively, the private vaults have improved their security through multiple technical solutions. And from a service perspective, the private vaults adopt a flexible deployment scheme to meet the user’s security needs fully.

### 6.5 Crest Hedge vault

**Target users:** USDT-based users or arbitrage users (risk avoidance type).

**Product Description:** With the hedging vault, users can borrow money to create market-neutral hedging LP positions, generating more fee income and offsetting the price risk of risky assets in the positions.

### 6.6 Crest Leveraged Vault

**Target users:** transactional users (risk-seeking users).

**Product Description:** by depositing in the leveraged vault, users can create long or short trading LP positions to earn trading income based on market evaluation and earn high mining income. However, trading LP positions would face higher liquidation risks.

## 7. **Why Choose Universe Finance?**

**High return:** the true return rate of ETH-USD LP in Universe Finance is the highest in the past few months.

**Stable income:** after extreme market tests, our users can still enjoy low retracement and high Sharpe ratio and continuously earn fee income.

**Low cost:** users do not need to pay the expensive gas fees for rebalancing and reinvesting.

**Risk grading:** risk is the foundation of finance. The risk grading management systems can meet the needs of different LPs.

**Simple:** automatic balancing, automatic reinvesting, automatic income tracking, etc.

## 8. Universe product roadmap

**2021 Q2**

* Backtesting system: Completed
* Active LP quantitative management strategy: Completed
* Smart Vault: Completed

**2021 Q3**

* Private Vault: Completed
* Hedge Vault: Developing
* L2 Support : Developing

**2021 Q4**

* Leveraged Vault: Designing
* Token economic model (staking dividends, burning, etc.): To be determined
* Liquidity mining: To be determined

## 9.Why Uniswap?

* Uniswap V3 is currently the best DEX with the most excellent depth and the lowest slippage.
* Uniswap V3 is currently the DEX with the most significant transaction volume. The market share continues to increase.
* We believe professional and active LP management will be a hot trend to develop in DEX with a promising future and tremendous market potential.
* We can migrate some of our products and technologies to other public chains and DEX (Sushiswap, PancakeSwap, Mdex, etc.). However, we will focus on Ethereum and Uniswap in the short and medium-term.

## 10.Universe Finance's vision

Maximize the liquidity income on Uniswap; build a one-stop yield platform with the highest and most stable real rate of return across the whole Defi market.
