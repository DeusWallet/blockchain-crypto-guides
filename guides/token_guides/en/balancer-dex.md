# Balancer in Simple Terms

[Balancer](https://balancer.exchange/) is a decentralized exchange (DEX) that launched in March 2020. It began as a research project by [BlockScience](https://block.science/) in early 2018. The Balancer team developed a mathematical framework that enables any portfolio to self-rebalance continuously while generating fees, known as the Balancer protocol. The Ethereum token driving this protocol is BAL.

## Trading on Balancer

From a trader's perspective, Balancer is a platform to exchange Ethereum and ERC20 tokens in a decentralized manner.

- **Efficient Trading**: Balancer scans all available pools for the requested tokens and spreads orders across the most efficient pools to provide the best prices.
- **Variable Fees**: Trading fees differ between pools and depend on the tokens and liquidity pools involved.
- **Slippage**: Larger orders relative to available liquidity result in higher slippage.
- **Incentives**: Balancer encourages low fees by distributing BAL tokens to liquidity providers.

## Providing Liquidity

Like Uniswap and Curve, Balancer allows users to earn fees on their Ethereum-based idle assets. It offers more flexible opportunities through different types of liquidity pools.

- **Liquidity Pools**: Users can create a new pool or add assets to existing pools.
- **Pool Composition**: Each pool can contain 2-8 assets, maintaining a specific ratio between them.
- **Auto-Balancing**: Pools self-balance to maintain the required ratios.
- **Flexible Deposits**: Unlike Uniswap, Balancer allows deposits in any asset supported by the pool.
- **Pool Ownership Tokens**: Providers receive ERC-20 tokens representing their share of the pool, which can be used to withdraw liquidity.
- **Transaction Fees**: Each pool sets its own fees, with lower fees earning more BAL tokens.

## Pool Types

1. **Shared Pools**: 
   - Fixed tokens, weights, and fees set at creation.
   - No special privileges for the creator.
   - Anyone can add liquidity, and ownership is tracked with Balancer Pool Tokens (BPT).

2. **Private Pools**: 
   - Full control over parameters for the creator (e.g., accepted tokens, weights, fees).
   - Only the creator can provide liquidity.
   - Useful for managed index funds.

3. **Smart Pools**: 
   - Owned by a smart contract, not a person.
   - Accept liquidity from anyone with flexible parameter changes.
   - Ownership tracked by ERC-20 tokens.

## Index Funds

Balancer enables users to set up personal index funds without complex rebalancing.

- **Self-Balancing Pools**: Investors can group assets for long-term investment into auto-balancing pools, earning fees as others trade against their portfolio.
- **Custom Index Funds**: Users can create or invest in self-balancing index funds.
- **Nested Pools**: Pools can consist of other Balancer pools.
- **Permissionless**: Pools cannot be censored or altered once activated.

## Balancer Token

The BAL token, distributed to liquidity providers since June 1, 2020, also serves as the governance token for the protocol.

- **Total Supply**: 100 million BAL tokens.
- **Distribution**: 25 million to founders, devs, advisors, and investors; 75 million to liquidity providers.

Details on the governance model and token distribution can be found [here](https://balancer.finance/2020/05/15/proposing-balancer-liquidity-mining/).

## Useful Links

- [Project Whitepaper](https://balancer.finance/whitepaper/)
- [Official Blog](https://balancer.finance/blog-feed/)
- [Balancer Pool Management](https://pools.balancer.exchange/#/)