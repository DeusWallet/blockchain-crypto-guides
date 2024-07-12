# 简单介绍 Curve

[Curve Finance](https://curve.fi) 是一个类似于 Uniswap 的去中心化交易所，但它专注于交易稳定币。

随着 DeFi 的发展，对稳定币交易的需求不断增加，而 Curve 满足了这一需求。稳定币在 DeFi 生态系统中备受追捧，Curve 处理的交易量很大，通常超过 [5000 万美元](https://www.curve.fi/dailystats)。

## Curve 代币

Curve 旨在成为一个 DAO，并拥有一个治理代币 CRV，它为用户提供 [额外福利](https://guides.curve.fi/crv-launches-curve-dao-and-crv/)，包括对重要决策进行投票。

总供应量：约 30 亿 CRV

- 61% 给流动性提供者
- 31% 给股东
- 5% 给可销毁储备
- 3% 给员工

## 在 Curve 上交易

- Curve 的独特卖点是其交易算法，可为大型稳定币交易提供更优惠的价格。

- 与 [Uniswap](../../token_guides/zh/uniswap.md) 相比，Curve 收取的费用略高，为每笔交易 0.04%。

## 流动性提供者

Curve 的流动性池通常比 Uniswap 更有利可图，因为它们不仅收取交易费，还将闲置资金借给外部 [DeFi 借贷](../../defi/zh/4-lending-protocols.md) 服务，从而产生额外收入。

- 目前，7 个 Curve 流动性池中有 4 个通过交易费和向 [Compound](../../token_guides/zh/compound.md) 借贷池借贷获得收入。

- Curve 的池允许流动性提供者只存入一种稳定币，而不是池中的所有代币。

- 提供者可以存入单一资产来为多个池提供流动性。

- 一些池提供奖金以维持余额。存入低份额代币可获得奖金，提取主要代币也可获得奖金。

## 池盈利能力

- 存入池时，您的资金会根据池的代币分布自动分成多个代币。

- 例如，如果您将 4 DAI 存入一个包含 200 DAI（50%）、100 USDT（25%）和 100 USDC（25%）的池中，您的存款将分为 2 DAI、1 USDT 和 1 USDC。

- 提款通常会返回所有池代币，无论存款代币是什么。

- 由于池的存款机制多种多样，当以太坊网络繁忙时，添加资金的成本可能会很高。

## 风险

Curve Finance 比 Uniswap 更复杂，并集成了第三方 DeFi 服务，增加了其智能合约中未发现问题的可能性。

> Curve 的智能合约已由第三方服务 Trail Of Bits [审核](https://www.curve.fi/audits)。