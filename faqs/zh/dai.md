# 什么是Dai?
Dai是一种由资产足额抵押担保的稳定币，通过一系列金融激励措施保证其价值与美元保持1:1稳定。

Dai完全基于区块链存在，其稳定性不受地域影响，其偿付能力也不依赖于任何需要信任的对手方。所有流通的Dai背后都有超额的抵押品支撑，这些抵押品托管在可审计且可公开查看的以太坊智能合约中。

Dai一旦生成，就可以像其它加密货币一样使用：它可以被自由地发送给其他人，用来购买商品或服务，或者作为对冲市场波动性的工具而持有。

# 为什么要使用Dai?
作为一种价格可预测，波动性较低的记账单位，Dai 可以运用在各种受市场投机和不稳定性影响无法进行的金融活动。

去中心化数字经济需要稳定性才能运行。稳定币 Dai 从根本上解决了这个问题，使其适用于广泛的金融市场。

**对冲**: 在市场剧烈波动时，Dai 为投资者提供了存储价值的避风港，使得投资者无需离开加密货币市场。对于持有大量加密资产的对冲基金、基金会以及刚刚完成融资的项目，可以将其资产转换成 Dai这种不受波动性影响的货币。

**去中心化交易所**: 去中心化交易所往往不支持法币和加密货币的交易，而数字资产持有者可以将手中的其他数字资产换成与美元锚定、价格具有低波动性的 Dai。

**交易对**:币币交易是一个复杂的过程。当用户在交易时，基础交易对的涨涨跌跌加剧了追踪收益的难度。当引入了 Dai 的低波动交易对后，用户就有一个稳定的计价货币，提高交易效率。

**金融市场**: Dai可以作为稳定且可靠的抵押品用于各种衍生品智能合约，或创建杠杆的保证金。

**商业发票、跨境交易和汇款**: 通过消除外汇的波动和第三方的参与，Dai可以显著降低跨国交易成本。

**预测市场和博彩行业**: 如果用户无法预测其投注资产在未来会达到的价值，则长期投注也变得不可行。Dai 这样的稳定货币可以成为预测市场的自然选择。

# 1个Dai总是价值1美元吗?
不是。Dai并不是硬锚定的货币。因此，它可能不会完完全全与现有法定货币价值保持一致。当然，与其它加密货币相比，Dai 维持了一种低波动性的软挂钩。值得注意的是，在紧急清算情况下，Dai可以依据紧急清算时预言机的价格赎回价值正好等于1美元的抵押品。

# Dai如何产生?
所有的 Dai 都是通过链上抵押数字资产创建的。

假设你有一些加密数字资产，比如以太坊。你需要一笔流动性现金，但是不希望卖掉以太坊，就可以抵押以太坊生成 Dai，使用 Dai 作为流动资金的同时保留以太坊的收益权。

当CDP所有者锁定抵押品借出 Dai 时，新的 Dai 就生成了。CDP持有者想要拿回他们的抵押品必须在公开市场上购买 Dai，归还到抵押债仓，相当于销毁Dai。这种生成和销毁机制确保了所有流通的Dai都有充足的抵押品支撑。

举个例子，

* 你将150美元的以太坊锁入CDP智能合约之中，作为担保物。
* 根据该担保物的风险参数 (2/3的折扣)，可生成100个 Dai，即100美元 。
* 用 Dai 换成美元或投资其他的资产。
* 当需要取回担保物以太坊时，偿还 100 个Dai 和利息，拿回以太并保留获取的收益(来自以太的上涨或用Dai投资的收益)。

一套专门为应对市场压力而设计的自主智能合约体系持续保证资产的基本稳定性。没有人可以修改Dai的核心机制，让 Dai 成为一种可靠可预测的货币形式。

值得注意的是，普通使用 Dai 的用户并不需要了解系统的详细机制，只需要查看公开市场的信息，以 1 美元的价格购买或出售 Dai。

# 除了我，还有谁控制 Dai？
没有，你拥有绝对的控制权。

Dai是一个完全价值同质的ERC20代币，可以保存在任何标准的以太坊钱包中。可以自由兑换，无需触及复杂的高级功能。

Dai的所有权归其持有人所有，不受任何第三方控制。

# Dai的价格怎样保持稳定?
Dai并不是一种硬锚定货币，因此，它无需与当前法定货币价值保持一致。相反，它维持了一种自由软锚定，与其他加密货币相比，这种锚定波动性更低。

它通过外部市场力量、互补的内部经济激励和政策工具的组合来实现这种稳定。许多不同的市场参与者为了自身的利益而行动，同时又协同合作，这有助于市场的稳定。这些参与者包括MKR持有者、套利者、CDP所有者和普通做市商。

如果Dai的需求持续超过供给，这就是MKR持有者需要调整[稳定费](./stability-fee.md)的信号，反之亦然。稳定费的增加导致CDP用户借贷成本增加，通过降低使用CDP的吸引力，从而抑制了Dai的供应。相反，稳定费(借贷成本)的降低将刺激Dai的额外生成，作为调整供应增长的政策工具。

套利者通过利用各种Dai市场的机会也有助于Dai的短期锚定。

当需求刺激推动Dai的价格高于汇率时，CDP持有者能够利用机会参与维持汇率稳定。这允许CDP用户发行Dai，用于购买具有额外可变购买力的资产。相反，当Dai的价格低于1美元，CDP用户可以更便宜的价格出售Dai，以可变折扣偿还他们的CDP债务。

最后，第三方网络参与者，也就是看护机帮助维持Dai的价格。看护机是人或自动程序通过利用套利机会帮助Dai维持锚定。

# 我可以怎样生成Dai?
你可以通过在[CDP面板](https://cdp-cn.makerdao.com/)锁定抵押品创造DAI。

# 我可以在哪里购买Dai?
你可以在传统或者去中心化[交易所](https://coinmarketcap.com/currencies/dai/#markets)购买 DAI。也可以在内置交易所的钱包，如 imToken 里购买 Dai。如果你希望用人民币购买 Dai，可以前往 [otcmaker.com](https://otcmaker.com/)。

# 我可以在哪里看到 Dai 背后的抵押品数据呢?
Dai 稳定系统通过自主的智能合约实现，所有交易都保存在完全公开透明的区块链上。任何人都可以手动查阅或者访问如[Mkr.Tools. ](https://mkr.tools/)的分析工具进行系统审计。

# 哪些机构在使用 Dai?
你可以在[「合作伙伴」](https://github.com/makerdao/awesome-makerdao#partnerships)储存库找到使用 Dai 的机构列表。