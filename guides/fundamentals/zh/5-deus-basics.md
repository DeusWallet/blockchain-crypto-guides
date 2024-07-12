# Deus Wallet

本节将重点介绍使用非托管钱包应用时的实际方面和“需要了解的事项”。

从用户的角度来看，对任何非托管钱包应用的基本期望应该是：

1. **符合标准的密钥生成**：钱包应用应以符合标准的方式生成私钥，确保其安全性和与其他第三方钱包应用的兼容性。

2. **正确管理多种加密货币**：钱包应用应正确管理每种加密货币的支付地址，例如，确保用户的比特币地址与以太坊地址不同。

3. **安全私钥存储**：钱包应用应按照记录的准则存储私钥。iOS 和 Android 钱包应用都应利用其操作系统提供的安全存储机制来确保私钥的安全。

其他期望可能因目标用户而异。例如，寻求广泛隐私的人可能需要大多数钱包应用中没有的功能。

下面，我们将重点介绍使用非托管钱包应用时需要牢记的一些要点，并使用 Deus 钱包应用来说明这些方面。

### 1. 设置/恢复

每个非托管钱包都从设置新钱包或迁移现有钱包开始。

- **“创建钱包”** 按钮会生成一个新的私钥并将其显示为 12 个字，需要备份。

- **“恢复钱包”** 选项可恢复先前在 Deus 或其他符合标准的钱包中创建的现有钱包。

恢复非托管钱包可能需要几分钟到几个小时的时间。

### 2. 授权锁

非托管钱包应用应包括内置措施以防止未经授权的访问。移动钱包和硬件钱包都通过访问钱包所需的解锁代码来实现这一点。

即使有人获得了您钱包设备的物理访问权限，这项措施对于保证您的资金安全也至关重要。

### 3. 支持的加密货币

钱包可以处理的加密货币越多越好。在单个应用程序中管理多种加密货币比在多个应用程序之间切换更方便。

钱包应用程序还应显示当前的加密货币价格，以熟悉的货币（如美元或欧元）显示您的余额。这对于付款特别有用，因为它简化了计算。

### 4. 硬币概览

每种加密货币都是一个具有自身特点的独特项目。对于任何想要投资加密货币的人来说，了解这些细节都至关重要。

许多项目仍然晦涩难懂，即使对于那些具有技术背景的人来说也是如此。Deus 旨在以简单的术语提供各种加密货币的全面概述。

### 5. 图表和数据

选择显示代币历史市场汇率的钱包。

历史价格概述了加密货币的价格如何变化，并允许用户查看过去交易的历史汇率。

### 6. 多钱包

包括 Deus 在内的一些钱包允许在单个应用程序中创建无限数量的钱包。

此功能使用户能够轻松管理多个加密货币投资组合。

### 7. 隐私

非托管钱包中的隐私功能可能存在很大差异。

在评估钱包的隐私功能时，请考虑以下几点：

- **基本用户数据**：根据钱包的设计，提供商可能知道一些不可识别的数据，例如用户的 IP 地址和位置。如果这些数据存储在服务器上，则始终存在数据泄露的风险。

- **余额和交易**：一些钱包允许用户恢复或迁移现有钱包。钱包提供商可能会使用针对此任务优化的特殊服务器，这可能会泄露有关用户余额和过去交易的信息。

为了解决这个问题，像 Deus 这样的钱包支持直接从区块链网络本身恢复，确保提供商没有关于用户余额或交易的信息。

- **区块链隐私**：不同的区块链提供不同级别的隐私。比特币交易通常比以太坊交易更私密。一些非托管钱包包含增强特定区块链隐私的功能。例如，Deus 集成了功能，使将比特币交易链接到单个实体变得更加困难。

用户的最低隐私要求应该是钱包对其用户一无所知。

### 8. 抗审查

鉴于加密货币不断变化的法律环境，请寻找具有以下设计的钱包应用：

- 抗审查
- 在所有地区均可使用
- 始终可用于交易

真正的非托管钱包应该在任何地方工作，并且始终可用于交易。如果非托管钱包在您所在的地区被封锁，您应该能够将您的私钥迁移到另一个非托管钱包应用。