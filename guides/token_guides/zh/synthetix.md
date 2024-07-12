# Synthetix 简明解释

[Synthetix](https://synthetix.io/) 是以太坊上的一个去中心化平台，用于交易合成资产，即 Synths。

> Synths 是 ERC-20 代币，代表加密货币、股票、法定货币、贵金属和其他可交易资产。

这些 Synths 旨在反映其所代表资产的价格，但不具备其任何其他特征。

例如，sBTC 是一种合成比特币代币，可以按当前比特币价格在 Synthetix 上交易。

类似地，sMKR 代币的价格与真实 [MKR](../../token_guides/zh/makerdao.md) 代币相同，但不包括投票权。

- 拥有合成代币提供的价格风险与拥有其所代表的实际代币相同。

用户无需持有实际资产即可推测各种金融工具的价格走势。
- 合成资产可以在用户之间转移，并在去中心化交易所进行交易。

总之，Synthetix 支持创建基于以太坊的 ERC-20 代币，这些代币代表现实世界的资产。

> 任何具有价格信息流的资产都可能作为合成资产添加到 Synthetix。

目前，可用的合成资产包括加密货币、股票和贵金属。Synthetix 旨在扩大其产品范围，以涵盖更多传统市场中常见的资产，例如股票。

## 支持的合成资产

Synthetix 平台目前支持大约二十种不同的合成资产，并且可能支持更多。

> 只要有价格信息流和社区批准，任何具有市场价格的资产都可以添加到 Synthetix。

目前，合成资产有两种类型：

1. **标准合成资产​​*

这些合成资产跟踪它们所代表的资产的价格，适合那些希望做多资产的人。
- sUSD：合成美元
- sEUR：合成欧元
- sAUD：合成澳元
- sBTC：合成比特币
- sETH：合成以太币
- sMKR：合成 Maker
- sBNB：合成 BNB
- sXTZ：合成 Tezos
- sADA：合成卡尔达诺
- sXRP：合成瑞波币
- sLTC：合成莱特币
- sBCH：合成比特币现金
- sXAU：合成金盎司
- sXAG：合成银盎司
- sDEFI：合成 DEFI 指数
- sLINK：合成 Chainlink

2. **逆向合成**

这些允许用户做空资产价格，从价格贬值中反向获利。
- iBTC：反向比特币
- iETH：反向以太坊
- iBNB：反向币安
- iXTZ：反向 Tezos
- iADA：反向卡尔达诺
- iXRP：反向瑞波币
- iLTC：反向莱特币
- iBCH：反向比特币现金
- iDEFI：反向 DEFI 指数
- iLINK：反向 Chainlink

合成器在非托管 [Synthetix.Exchange](https://synthetix.exchange) 上全天候交易，使 [以太坊生态系统](../../token_guides/zh/ethereum.md) 中的任何人都可以对各种资产进行多头或空头交易。

## 合成器是如何创建的

要了解 Synthetix，重要的是要知道如何创建新的合成器并将其从流通中移除。

1. Synthetix 允许用户通过以 600% 的抵押率将他们的 SNX 代币锁定到智能合约中来创建 sUSD（合成 USD）代币。
2. 要创建 1000 个 sUSD 代币，用户必须锁定至少价值 6000 美元的 SNX 代币。当用户偿还借入金额时，这些代币将返还。
3. 创建后，sUSD 代币可以在 Synthetix 交易所以当前市场价格与其他合成资产进行交易。
4. Synthetix 交易所的订单是即时的，并以市场价格执行。
5. 交易者总是与交易所进行交易，交易所会销毁从用户那里收到的资产并创建用户购买的资产。
6. 例如，当比特币价格为 10,000 美元时购买 sBTC 需要销毁 10,000 个 sUSD 并创建 1 个 sBTC。

此过程可确保每项合成资产均由 SNX 代币支持。

投机者还可以使用 ETH 在 [Uniswap](../../token_guides/zh/uniswap.md) 等 [去中心化交易所](../../defi/zh/3-decentralized-exchanges.md) 上购买现有的 sUSD 或 sETH。

## 合成资产的交易方式

Synthetix 生态系统包括自己的去中心化交易所 [Synthetix.Exchange](https://synthetix.exchange)，用于交易合成资产。

- 与其他去中心化交易所不同，Synthetix.Exchange 不需要订单簿或 [流动性池](../../defi/zh/3-decentralized-exchanges.md) 等流动性匹配机制。
- 所有订单都保证在几秒钟内以市场价格执行。
- 交易费用从 0.1% 到 1%（通常为 0.3%）不等，并分配给那些通过锁定其 SNX 代币作为抵押品来创建 sUSD 代币的人。

在 Synthetix.Exchange 上交易通常更便宜，尤其是对于大订单，这为使用它提供了经济激励，而不是其他去中心化交易所，如 [Uniswap](../../token_guides/zh/uniswap.md) 或 [Curve](../../token_guides/zh/curve-finance.md)。

## 为什么要创建合成器？

交易合成器更便宜，并且可以在以太坊区块链上接触世界上任何可交易资产。这创造了强大的 g 激励投机者交易合成资产而不是实际资产。

600% 的抵押率保护合成资产的稳定性，免受 SNX 价格波动的影响。

那些将他们的 SNX 锁定在平台中以创建新合成资产的人会获得两种类型的奖励：
1. **SNX 质押奖励**：通过 SNX 的通胀货币政策创造。2019 年 3 月至 2023 年 8 月期间，SNX 的总供应量将从 1 亿增加到 2.603 亿，每周衰减率为 1.25%。
2. **交易所费用**：在 [Synthetix.Exchange](https://synthetix.exchange/#/) 上交易合成资产的费用将进入费用池，SNX 质押者可以每周领取。

SNX 质押者在锁定他们的代币时会创建一个债务头寸。这笔债务从铸造的 sUSD 数量开始，并根据所有其他合成资产的价格变动而变化。

- 如果所有合成资产都是 sBTC，且 BTC 价格减半，则总债务将减半，每个质押者的债务也将减半。
- 相反，如果只有 50% 是 sBTC，且 BTC 价格翻倍，则每个质押者的债务将增加四分之一。

这样，SNX 质押者充当所有合成资产交易所的集合交易对手，承担整个系统债务的风险。

## Synthetix 统计数据

有关 Synthetix 平台的当前统计数据，包括锁定的资金量和流通的合成资产数量，请访问 [DeFi Pulse](https://dashboard.synthetix.io) 上的 Synthetix 概览。

截至 2020 年 9 月 9 日：
- 总锁定量（美元）：6.502 亿美元
- 总锁定量（ETH）：190 万 ETH
- 总锁定量（BTC）：6.33 万 BTC
- 总锁定量（SNX）：1.41 亿 SNX
- 锁定的 SNX 供应量百分比：70.36%