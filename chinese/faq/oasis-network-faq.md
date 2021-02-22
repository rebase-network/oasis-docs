---
description: >-
  我们将用这个页面来回答一些我们最常被问到的问题接收关于Oasis Network 的信息。本页将不断更新。
---

# Oasis Network 问答

## **概述**

### **为什么是 Oasis?**

Oasis Network 是为下一代区块链设计的，是第一个为开放式金融和负责任的数据经济提供隐私保护的区块链平台。
结合其高吞吐量和安全架构，Oasis 网络能够为隐私的、可扩展的 DeFi 提供动力，彻底改变了开放金融，并将其从交易者和早期采用者扩展到大众市场。其独特的隐私功能不仅可以重新定义 DeFi，还可以创建一种新型的数字资产，称为 token 化数据，该 token 可以使用户控制自己生成的数据，并通过对应用程序进行抵押获得报酬，从而创造了首个负责任的数据经济 。

**第一个启用隐私的区块链：** Oasis Network 是世界上第一个可扩展的、支持隐私的区块链。
Oasis Network 上的 ParaTimes 可以利用机密计算技术（例如安全区域）来保持数据机密性-解锁区块链的新用例和应用程序。

**可扩展的，隐私的 DeFi：** Oasis Network 的隐私优先设计可以将 DeFi 扩展到交易员和早期使用者之外，从而开拓新的主流市场。加上其创新的可扩展性设计，为 DeFi 交易带来了更快的速度和更高的吞吐量。

**率先启用数据代币化：** Oasis Network 可以**代币化数据**，为区块链解锁改变游戏规则的用例，以及网络上全新的应用和项目生态系统--为下一代隐私优先的应用提供动力。

**快速发展的社区：** Oasis Network 有一个繁荣的社区，有近千名节点运营商、开发者、企业合作伙伴、形象大使，近万名社区成员参与全球社交渠道。

**顶级团队：** Oasis 团队由来自世界各地的顶尖人才组成，这些人才来自苹果，谷歌，亚马逊，高盛，加州大学伯克利分校，卡内基·梅隆大学，斯坦福大学，哈佛大学等等，所有这些团队致力于发展和扩大 Oasis Network 的影响力。

**Oasis 协议基金会是否仍在接受建立新的 dApp 的项目的赠款申请？**

是的! 我们仍在接受拨款申请。 你可以随时在[这里]（https://medium.com/oasis-protocol-project/oasis-foundation-grant-wishlist-3ad73b723d7%20）申请。

### ** 主网何时启动？**

Oasis Network 目前正在运行 主网 的一个初始版本--[Amber Network](https://medium.com/oasis-protocol-project/introducing-the-amber-network-a-release-candidate-for-mainnet-7fe9c8d6a5c5)。下一个版本的主网即将推出!

![](../.gitbook/assets/image%20%283%29.png)

## **架构**

### \*\*Oasis Network 是个怎样的区块链？它使用侧链么？

Oasis Network 是一个使用 BFT、Pos 运行在第 1 层区块链上的协议。Oasis 创新的 ParaTime 架构使我们能够在不使用侧链的情况下进行扩展。 有关更多信息，请参考我们的[白皮书]((https://docsend.com/view/aq86q2pckrut2yvq)。

### ** Oasis Network 的架构是怎样的？**

Oasis Network 是 1 个运行在第 1 层的，基于 PoS 的去中心区块链网络。 它主要有 2 部分组成，共识层和 ParaTime 层。

1. **共识层**是一个可扩展的、高吞吐量的、安全的、由一组验证者节点分散运行的 PoS 共识。

2. ** ParaTime 层**托管许多并行运行时 \(ParaTimes\)，每个运行时代表具有共享状态的复制计算环境。

![](../.gitbook/assets/image%20%281%29.png)

### ** ParaTime 与平行链有什么不同？**

与平行链不同的是，ParaTime 本身不需要做共识，这使得它们的开发更加简单，更容易融入到整个网络中。
ParaTimes 负责计算，差异检测用于确保执行的正确性和完整性，从而使 ParaTimes 比平行链和其他依赖分片的链设计更有效率。

### **谁会运行所有这些 ParaTime？ 任何人都可以运行 ParaTime 吗？**

网络在这方面是不可知的。任何人都可以运行一个 ParaTime。完全由开发人员和用户来决定哪一个能提供他们所需要的功能。

开发中的 ParaTimes 的例子包括 Oasis Labs 数据主权 ParaTime 和[Second State 的虚拟机](https://medium.com/oasis-protocol-project/ethereum-support-on-the-oasis-blockchain-3add9e13556)，一个 EVM 兼容的 Runtime。

### \*\*Oasis Network 运行的什么共识机制？是 BFT 吗？

Oasis Network 使用 Tendermint 作为其 BFT 共识协议。
由于共识层使用的是 BFT 协议，Oasis Network 提供了即时的确定性，也就是说，一旦一个区块被最终确定，它就不能被还原（至少对于全节点而言）。一个 ParaTime 承诺会确定一个区块，因此 ParaTime 的状态也会被最终确定，一旦区块被最终确定，就无法还原。

### 为什么 Oasis Network 不进行分片？这是不是说它很慢？

Oasis 网络不使用分片。取而代之的是，Oasis 利用差异检测模型来进行 roothash 更新，从而为网络提供了与分片相同的可伸缩性优势，但又带来了在实践中易于实现的设计带来的附加优势。分片在理论上是一个很好的想法，但却伴随着很多复杂的问题和成本，因此很难在实践中实现。从安全的角度来看，分片的复杂性也使其更难审计，而且本质上更容易受到安全漏洞的影响。Oasis Network 基于差异检测的方法通过更清洁、更简单、更高效的实施，提供了与分片相同的优势。最终，Oasis Network 独特的可扩展性机制确保了该网络不仅速度快\(就像 sharding 网络所宣称的那样\)，而且具有足够的通用性和安全性，以支持各种实际工作负载。

### **Oasis Network 上的存储是如何工作的？是否使用 IPFS？**

Oasis Network 上的存储由每个 ParaTime 决定。共识层和运行时层之间存在明确的关注点分离。组成运行时层的 ParaTime 在选择存储管理方式方面具有很大的灵活性。 例如，Oasis Labs 正在开发的 ParaTime 可以支持 IPFS 作为其存储解决方案。其他 ParaTime 开发者可以根据自己独特的存储需求，选择实现不同的存储机制。

## **开放金融 与 DeFi**

### ** Oasis Network 对 DeFi 有愿景么？ 与 DeFi 的主流观点有区别吗？**

第一代 DeFi dApps 为市场提供了大量协议和原语，这些协议和原语是新金融系统特定组件的基础。尽管目前关注的是短期回报，但 Oasis 认为，DeFi 应用程序的目标应该是通过利用可编程参数（而不是地位，财富和地理位置）来建立一种新的金融系统，以消除主观性，偏见和低效率。Oasis 旨在通过提供比其他 1 层网络更好的隐私和可扩展性功能来支持下一波 DeFi 应用。

### **Oasis 同时使用了“开放式金融”和“ DeFi”这两个术语，有什么不同？**

“开放金融” 和 “DeFi” 这两个词是可以互换的。但我们认为，“开放金融” 更能代表这样一种理念，即新的金融体系应该让每一个在特定的可编程参数范围内操作的人都能使用，无论他们的地位、财富或地理位置如何。

### ** Oasis 是否会提供用于 DeFi 应用的 Oracle 解决方案**？

Oasis 最近宣布与[Chainlink](https://medium.com/oasis-protocol-project/oasis-network-chainlink-integrating-secure-and-reliable-oracles-for-access-to-off-chain-data-5d31e6e4591c)合作，成为 Oasis 的首选 oracle 提供者。这一整合正在进行中。

### \*\*DeFi 哪些方面需要隐私？Oasis 对隐私的关注如何帮助 DeFi 应用？

在这一代 DeFi 中，一些矿工和交易员利用 Ethereum 的低效率来叠加挖矿费用和利率，同时阻止更多的人参与到这个行业中来。隐私可以发挥强大的作用，使网络正常运行，减少这些低效率。在应用层面，隐私是一个推动因素。例如，强有力的隐私保障可以鼓励成熟的机构参与到系统中来，因为这些机构将能够保护自己的利益和关系。
此外，隐私功能还可以作为信誉系统的基础，从而充分释放低抵押贷款的潜力。我们一直听说隐私是 DeFi 的下一个大事件，我们期待着赋予开发者构建下一代 DeFi 应用的能力。

### **隐私如何助力打造开放金融新体系？**。

现有的财务系统和数据系统根本不开放。 只有少数几个人可以访问它们。 隐私具有广泛意义，而不仅仅是将某些事情保密。得益于隐私保护计算，用户可以保留其信息的所有权，并授予他人对其数据进行计算的权限，而不会实际泄露 \(或转移\) 其数据。这将使用户通过在区块链上押注自己的数据，从本质上累积数据收益率，释放出广泛的新金融机会。
开放金融指的是，地位、财富和地域不会阻挡你获得某种金融产品。遵守一套可编程的参数将决定某人是否可以参与，使新的金融机会向全世界更多的人开放。例如，贷款协议等服务可以根据该用户的历史提供不同的利率。对金融世界来说，改变游戏规则的是，公司将不必依赖 FICO 这样的中心化评分--他们将能够建立自己的模型。

### \*\*为什么有人会选择在 Oasis 上建立一个 DeFi 项目而不是在 Ethereum 上？

Oasis 提供最先进的可扩展功能可解决 DeFi 的阻塞，解决目前困扰其他第 1 层网络的高交易费和低吞吐量。结合了 Oasis 提供可扩展的私有 DeFi 的独特能力，有望使其成为释放下一代 DeFi 市场和用例的领先平台。

## **Token**

### \*\* Oasis Network 启动后，网络中如何使用 Oasis Network 的 token？

ROSE 将用于共识层的交易费，抵押和委托。

## **隐私**

### ** Oasis Network 是如何实现隐私和保密的？是通过同态加密吗**？

有很多方法可以实现保密性。使用可信的执行环境（TEEs）是一种方法。 我们使用的就是这种方式。
实际上，我们为交易提供了端到端的加密，在这些交易中，状态和有效负载在静止、动态，以及更重要的是在计算中都进行了加密。同态加密是另一种保密技术。目前，任何人都可以在 Oasis Network 上构建一个使用同态加密来提供保密性的 ParaTime。我们并不规定开发者应该采取什么方法。值得注意的是，隐私和机密性不相等。 隐私意味着保密，但并非相反。 对于隐私，可以采用诸如差异隐私之类的技术。

## **互操作性**

### \*\*能在 Oasis Network 上运行 Ethereum 智能合约吗？或者说，如果不能直接运行智能合约，能否在 Ethereum ERC20 资产和 Oasis 之间建立链接？

简而言之，能！ Oasis Network 支持与 EVM 兼容的 ParaTime，它将支持非常多的应用。