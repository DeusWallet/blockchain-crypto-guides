# Uniswap 简明解释

[Uniswap](https://uniswap.info/home) 是一个去中心化的点对点加密货币交易所，用于交易以太坊和基于以太坊的代币。

Uniswap 是以太坊上最早的 [去中心化交易所](../../defi/zh/3-decentralized-exchanges.md) 之一，具有几个关键功能：

- Uniswap 的智能合约以去中心化的方式自主管理数亿美元的加密货币。
- 它被认为是真正去中心化的交易所之一，这意味着运营商不能审查用户或关闭服务。
- 它在去中心化交易所中交易量最高，超过了许多中心化交易所。
- Uniswap 列出了众多加密货币交易对，并有一个免费的代币上市政策，允许任何人列出任何代币并提供流动性。
- 它使用一个简单的数学公式和流动性池中的可用代币来确定资产价格并执行交易。更多详细信息请参见 [此处](https://uniswap.org/docs/v2/protocol-overview/how-uniswap-works) 和 [此处](https://uniswap.org/docs/v2/core-concepts/swaps/)。
- 有两个版本，Uniswap V1 和较新的 Uniswap V2。遵循 DeFi 原则，Uniswap 的早期版本无法关闭。
- Uniswap V3 正在开发中，以进一步改进交易所的各个元素。

如今，Uniswap 是最大的 DEX 之一，24 小时交易量超过 1 亿美元。

## 在 Uniswap 上交易

您可以通过 [uniswap.org](https://app.uniswap.org/#/swap) 上的公共前端访问 Uniswap 的交易界面。

- 执行交易的服务费为 0.03%。
- 以太坊原生 ETH 货币与以太坊 ERC20 代币之间的交易通常比 ERC20 代币之间的交易更便宜。
- 与其他去中心化交易所相比，Uniswap 的智能合约设计允许更低的以太坊交易费用。
- 交易者在进行大额订单时可能会遇到明显的价格滑点（偏离市场价格）。
- 流动性更强的交易对将为大额订单提供比流动性更低的交易对更好的价格。
- 大型流动性池对于 Uniswap 的良好运作和允许大额交易至关重要。

您可以在 [此处](https://uniswap.info/pairs) 查看 Uniswap 上的所有交易对及其各自的流动性池。

## 流动性提供者

Uniswap 是首批通过流动性池引入自动做市的项目之一。

- Uniswap 上的每个交易对都有自己的流动性池，任何人都可以创建或加入。
- 要加入流动性池，用户必须存入交易对中涉及的两个代币。
- 流动性提供者必须根据当前市场价格存入等量的两种代币。
- 例如，[ETHUSDT](https://uniswap.info/pair/0x0d4a11d5eeaac28ec3f61d100daf4d40471f1852) 交易对需要存入 ETH 和 USDT 代币。
- 流动性提供者根据其存入资产的价值赚取一定比例的交易费。
- 提供者收到代表其在池中资产份额的池特定代币。
- 流动性提供者可以随时提取其资产和收益。

## 池盈利能力

虽然 Uniswap 流动性池似乎是通过将闲置的加密货币资产投入使用来赚取被动收入的保证方式，但存在风险：

> 尽管赚取了交易费，但存入资产的累计价值可能会下降。

要了解为什么流动性提供者的股份可能会减少，尽管有费用收入，请考虑管理 Uniswap 交易的公式。这个简单的公式在[此处](https://medium.com/@pintail/uniswap-a-good-deal-for-liquidity-providers-104c0b6816f2)中进行了解释，同时还介绍了评估流动性池时需要考虑的因素。

流动性提供者的一般经验法则：与仅持有原始资产相比，存入资产的任何价格变化都会降低权益的价值。

> 因此，涉及稳定资产（如稳定币）的流动性池可能会表现更好。

由于资产价格变化在利润计算中起着至关重要的作用，因此预测未来回报可能很复杂。

## Uniswap 代币

2020 年 9 月，Uniswap [推出](https://uniswap.org/blog/uni/) 其原生治理代币 UNI。

UNI 的主要用例是参与决策和其他治理方面，例如管理社区金库中的资金。