# Compound 简明解释

[Compound](https://app.compound.finance) 是一个连接加密货币借贷双方的去中心化平台。

它的工作原理如下：

- **借贷**：加密货币所有者通过智能合约将其资产存入 Compound 的流动性池并赚取利息。

- **借贷**：借款人通过提供另一种加密货币的抵押品向 Compound 申请信贷。

普通用户和智能合约都可以进行借贷，从而允许 DeFi 工程师创建访问其他 DeFi 平台流动性的服务。

Compound 支持 8 种加密货币：

- [Wrapped BTC (WBTC)](https://compound.finance/markets/WBTC)
- [以太坊 (ETH)](https://compound.finance/markets/ETH)
- [USD Coin (USDC)](https://compound.finance/markets/USDC)
- [Tether (USDT)](https://compound.finance/markets/USDT)
- [Dai (DAI)](https://compound.finance/markets/DAI)
- [Augur (REP)](https://compound.finance/markets/REP)
- [0x (ZRX)](https://compound.finance/markets/ZRX)
- [Basic Attention Token (BAT)](https://compound.finance/markets/BAT)

每种加密货币都有特定的借贷要求，包括利率和抵押因素。

- **利率**：利率根据每种加密货币的市场供求而波动。

- **抵押因子**：确定借入所需的抵押品数量。例如，70% 的因子意味着用户可以借入其抵押品价值的 70%。

用户可以在 Compound 网站上查看总贷方、借方和可供借入的资产。

## 在 Compound 上借款

要借款，用户需要以另一种加密货币提供抵押品。他们可以借入的最大金额取决于该抵押品的准备金因子。

- **费用**：根据市场情况，借款会产生利息费用。

- **还款**：还款后，借款人可以提取抵押品。但是，如果借入余额超过允许金额，账户将破产并可能被清算。

## 在 Compound 上借款

贷方可以随时提取其资产（连同利息）。他们收到 cTokens 作为交换，这些 cTokens 代表他们的存款并随着时间的推移产生利息。

- **cTokens**：这些 ERC20 代币可以兑换为其基础资产。利息不断累积，随着时间的推移，cToken 的价值不断增加。

## Compound 治理

自 2020 年 5 月以来，Compound 使用其 COMP 代币采用社区治理。

- **提案和投票**：COMP 持有者可以对平台决策提出提案和投票，例如支持的抵押资产和利率。

- **代币分配**：COMP 代币分发给提供或借入加密货币的活跃用户，每个组分配 50%。

Compound 旨在将所有平台方面去中心化，用户通过参与治理决策赚取 COMP。

如需了解更多信息，请访问：

- [Compound 官方网站](https://compound.finance)
- [治理提案](https://compound.finance/governance/proposals)
- [Compound 所有者排行榜](https://compound.finance/governance/leaderboard)
- [项目文档](https://compound.finance/docs)