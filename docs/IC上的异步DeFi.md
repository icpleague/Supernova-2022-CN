# IC 上的异步 DeFi

不同容器智能合约的功能在单调用堆栈上运行。 重入（re-entrancy），迄今为止区块链上最大的黑客攻击来源之一，导致它们非常不安全。 另一个问题是交易必须按顺序运行，这给交易吞吐量设置了一个严格的上限。 在互联网计算机区块链上，智能合约调用并行运行，因为智能合约是“软件参与者”。 这消除了一个关键的安全漏洞，并为区块链计算提供了无限的、有效的扩展。

你可以为 NFT 创建一个 100% 链上并且可扩展的拍卖行，或为代币创建一个去中心化交易所；或者是一个软件库，可以帮助其他人使用一种新的方法编写 DeFi ；或者是与其他区块链交互的代码。

**更多的灵感和出发点：**

- **链上或混合多重签名钱包**不仅可以在 IC 上，并且可以在使用[阈值 ECDSA 签名](https://dfinity.org/howitworks/threshold-ecdsa-signing)和[比特币集成](https://dfinity.org/howitworks/direct-integration-with-bitcoin)的其他平台上控制资产

- 基于订单簿或自动化市场制造商 (AMM) 的**去中心化交易所**

  - [InfinitySwap](https://infinityswap.one/)
  - [ICPSwap](https://icpswap.com/)
  - [Sonic](https://sonic.ooo/)

- 从同步平台**移植您最喜欢的 DeFi 项目**并探索差异

  - Lending: [Compound](https://compound.finance/), [Aave](https://aave.com/)
  - Stablecoins: [MakerDAO’s Dai](https://makerdao.com/en/)

  点击 https://dappradar.com/defi 以查看 web3 生态系统中最常用的 DeFi 应用程序列表

- 利用集体智慧**预测市场**

**帮助您起步的链接：**

- 带有示例代码的视频教程: [基础 DEX 示例](https://beta.smartcontracts.org/samples#basic-dex), [ICP 转移](https://beta.smartcontracts.org/samples#token-transfer)
- 代币标准: [分类账容器](https://beta.smartcontracts.org/docs/current/references/ledger), [DIP20](https://github.com/Psychedelic/DIP20), [EXT](https://github.com/Toniq-Labs/extendable-token/), [IS20](https://github.com/infinity-swap/IS20), [DFT](https://github.com/Deland-Labs/fungible-token-standard), [DRC](https://github.com/iclighthouse/DRC_standards/tree/main/DRC20)
- 交易历史和资产来源: [CAP](https://cap.ooo/)
- 比特币集成: [工作原理](https://dfinity.org/howitworks/direct-integration-with-bitcoin), [Wiki](https://wiki.internetcomputer.org/wiki/Bitcoin_integration)
- [容器中 ECDSA 签名的模拟实现](https://github.com/ninegua/ecdsa_example)
- [用于 DeFi 的世界计算机和真实世界计算机](https://forum.dfinity.org/t/we-need-a-defi-subnet/11388/32#world-computers-and-real-world-computers-for-defi-1)上的Dieter Sommer 的帖子
- 更多教程: [ICP分类账的介绍](https://www.youtube.com/watch?v=CeqnBC1twc4), [处理ICP支付 (Rust)](https://www.youtube.com/watch?v=FSeFWmI2-fE)