# Synthetix Explained Simply

[Synthetix](https://synthetix.io/) is a decentralized platform on Ethereum for trading synthetic assets, known as Synths.

> Synths are ERC-20 tokens representing cryptocurrencies, stocks, fiat currencies, precious metals, and other tradable assets.

These Synths are designed to mirror the price of the asset they represent, but without any of its other characteristics. 

For example, sBTC is a synthetic Bitcoin token that can be traded on Synthetix at the current Bitcoin price.

Similarly, an sMKR token has the same price as a real [MKR](../../token_guides/en/makerdao.md) token, but does not include voting rights.

- Owning synth tokens offers the same price exposure as owning the actual tokens they represent.
- Users can speculate on the price movements of various financial instruments without holding the actual asset.
- Synth assets can be transferred between users and traded on decentralized exchanges.

In summary, Synthetix enables the creation of Ethereum-based ERC-20 tokens that represent real-world assets.

> Any asset with a price feed can potentially be added to Synthetix as a synth asset.

Currently, available synth assets include cryptocurrencies, stocks, and precious metals. Synthetix aims to expand its offerings to include more assets commonly found in traditional markets, such as stocks.

## Supported Synths

The Synthetix platform currently supports around two dozen different synths, with potential for many more.

> Any asset with a market price can be added to Synthetix, as long as there is a price feed and community approval.

Currently, there are two types of synth assets:

1. **Standard Synths**

   These track the price of the asset they represent, suitable for those looking to go long on the assets.
   - sUSD: synthetic USD
   - sEUR: synthetic EUR
   - sAUD: synthetic AUSDollar
   - sBTC: synthetic Bitcoin
   - sETH: synthetic Ether
   - sMKR: synthetic Maker
   - sBNB: synthetic BNB
   - sXTZ: synthetic Tezos
   - sADA: synthetic Cardano
   - sXRP: synthetic Ripple
   - sLTC: synthetic Litecoin
   - sBCH: synthetic Bitcoin Cash
   - sXAU: synthetic Gold Ounce
   - sXAG: synthetic Silver Ounce
   - sDEFI: synthetic DEFI Index
   - sLINK: synthetic Chainlink

2. **Inverse Synths**

   These allow users to short the price of an asset, profiting inversely from price depreciation.
   - iBTC: inverse Bitcoin
   - iETH: inverse Ethereum
   - iBNB: inverse Binance
   - iXTZ: inverse Tezos
   - iADA: inverse Cardano
   - iXRP: inverse Ripple
   - iLTC: inverse Litecoin
   - iBCH: inverse Bitcoin Cash
   - iDEFI: inverse DEFI Index
   - iLINK: inverse Chainlink

Synths are traded 24/7 on the non-custodial [Synthetix.Exchange](https://synthetix.exchange), enabling anyone in the [Ethereum ecosystem](../../token_guides/en/ethereum.md) to go long or short on various assets.

## How Synths Are Created

To understand Synthetix, it's important to know how new synths are created and removed from circulation.

1. Synthetix allows users to create sUSD (synthetic USD) tokens by [locking](https://mintr.synthetix.io/) their SNX tokens into a smart contract at a 600% collateralization ratio.
2. To create 1000 sUSD tokens, a user must lock at least $6000 worth of SNX tokens. These tokens are returned when the user repays the borrowed amount.
3. Once created, sUSD tokens can be traded on the Synthetix exchange for other synth assets at current market prices.
4. Orders on the Synthetix exchange are instant and executed at market prices.
5. Traders always trade against the exchange, which destroys the asset received from the user and creates the asset bought by the user.
6. For instance, buying sBTC when Bitcoin is $10,000 involves destroying 10,000 sUSD and creating 1 sBTC.

This process ensures that every synth asset is backed by SNX tokens.

Speculators can also purchase existing sUSD or sETH on a [decentralized exchange](../../defi/en/3-decentralized-exchanges.md) like [Uniswap](../../token_guides/en/uniswap.md) using ETH.

## How Synths Are Traded

The Synthetix ecosystem includes its own decentralized exchange, [Synthetix.Exchange](https://synthetix.exchange), for trading synths.

- Unlike other decentralized exchanges, Synthetix.Exchange does not require liquidity matching mechanisms like order books or [liquidity pools](../../defi/en/3-decentralized-exchanges.md).
- All orders are guaranteed to execute at market prices within seconds.
- Trading fees range from 0.1% to 1% (typically 0.3%) and go to those who create sUSD tokens by locking their SNX tokens as collateral.

Trading on Synthetix.Exchange is often cheaper, especially for large orders, providing an economic incentive to use it over other decentralized exchanges like [Uniswap](../../token_guides/en/uniswap.md) or [Curve](../../token_guides/en/curve-finance.md).

## Why Create Synths?

Trading synths is cheaper and provides exposure to any tradable asset in the world, all on the Ethereum blockchain. This creates strong incentives for speculators to trade Synths rather than the actual assets.

The 600% collateralization ratio protects the stability of synth assets against SNX price fluctuations.

Those who lock their SNX into the platform to create new synths receive two types of rewards:
1. **SNX Staking Rewards**: Created through the inflationary monetary policy of SNX. Between March 2019 and August 2023, the total SNX supply will increase from 100 million to 260.3 million, with a weekly decay rate of 1.25%.
2. **Exchange Fees**: Fees from trading synths on [Synthetix.Exchange](https://synthetix.exchange/#/) go to a fee pool, available for SNX stakers to claim weekly.

SNX stakers create a debt position when they lock their tokens. This debt starts as the amount of sUSD minted and changes based on the price movements of all other synth assets.

- If all synths were sBTC and BTC halved in price, the total debt would halve, and each staker's debt would also halve.
- Conversely, if only 50% were sBTC and BTC doubled in price, each staker's debt would increase by one quarter.

In this way, SNX stakers act as a pooled counterparty to all synth exchanges, bearing the risk of the overall system debt.

## Synthetix Stats

For current stats on the Synthetix platform, including the amount of funds locked and the number of synths in circulation, visit the Synthetix overview on [DeFi Pulse](https://dashboard.synthetix.io).

As of September 9, 2020:
- Total Locked (in USD): $650.2M
- Total Locked (in ETH): 1.9M ETH
- Total Locked (in BTC): 63.3K BTC
- Total Locked (in SNX): 141M SNX
- % of SNX Supply Locked: 70.36%