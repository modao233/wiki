
# <img src="./logo.png" alt="alt text" width="30px" height="30px"> The VIG Coin Project 

# 必读

[[理念](./philosophy.md)]
[[白皮书](./White-Paper.md)]
[[演进路线](./Roadmap.md)] 



[[矿池搭建](./Pool.md)][[节点与钱包服务搭建](./vigcoin-node-and-wallet-service-setup.md)]

# VIG Coin wiki
VIG Coin的知识库

# VIG Coin是什么？

VIG Coin是开源的加密币项目，它类似于比特币，旨在解决货币电子化，去中心化，实现货币发行量的相对恒定等功能。

# VIG Coin的总量是多少？

VIG Coin的总量是1亿个，并且永远不会增发。预留20%的币用于未来对币的运营，开发，推广。其它币全部投放入矿池。


# VIG Coin的源码在那里？

VIG Coin的源码在[https://github.com/vigcoin/coin](https://github.com/vigcoin/coin)

# VIG Coin当前基于POW，未来会基于POR

算法：

| 区块高度 | 算法 |
| ------------- | ------------- |
| 1-197999 | cryptonight |
| 198000- | cryptonight_v7 |

VIG反对ASIC造成的算力垄断以不赞成POW造成的资源浪费。
所以未来会基于POR（Proof of Requests)来生产币或者获得收益。
也就是一种基于服务器请求服务的共识算法。

# POR(Proof of Requests）
POR的目标是让币的生产过程可循环，有价值。  
目前加密币最大的价值就是打包交易。所以POR就是打包交易的证明。  
同时POR可以避免算力竞争，导致资源的浪费。  
POR是交易请求驱动的货币，不是算力驱动的货币。  
这样交易过程是不受计算机的速度影响的。  
交易越多，节点或者说是服务节点的收益就越大。  
所以可以保持更好的去中心化与产生一个良性的竞争环境。  

# VIG Coin的目标是什么？

1. 基于比特币的去中心化理念，并努力在机制上保障去中心化
2. 实现币的交易能力，以及币币交易能力，降低中心化交易所对货币的操纵
3. 实现更加友好的货币
4. 实现加密币的循环生态。

# VIG Coin不是应用平台，不会考虑应用的开发

VIG Coin旨在推动加密币技术的普及，而不是推动去中心化的应用的普及。如果未来VIGCoin的四个目标都达成后，VIGCoin才有可能开新的项目去做去中心化的应用。

# 钱包

VIG Coin的钱包源码：
https://github.com/vigcoin/wallet
会开发的小伙伴可以自行编译。

不会开发的小伙伴可以下载64位的钱包。

[Windows 64 钱包](https://github.com/vigcoin/wallet/releases/download/1.0.0-a1/vigcoin-windows-64.zip)


[Linux 64 钱包](https://github.com/vigcoin/wallet/releases/download/1.0.0-a1/vigcoin-linux-64.zip)

(欢迎小伙伴提供其它版本的编译结果，将提供100币作为奖励，并在以后的运营中终身享受分红）

## 钱包使用

### 一定要备份钱包

1. 钱包启动后会默认创建一个钱包，这个时候钱包的地址在不同的平台是不一样的。所以你最好自己保存一个钱包文件。
2. 出于安全原因，钱包每次更新后会重新生成，所以如果不小心断电，钱包的内容可能会来不及保存。造成钱包损坏，所以在使用钱包前，一定要做好备份。

备份钱包的命令：文件-》备份钱包。

### 找到钱包地址

钱包地址位于：钱包"接收"栏。
VIG Coin钱包一定是B开头的，挖矿时一定要注意。
比如：BKC4AgG14PnQyfpEeEQSNSYjhBo5237Yf1pScL4c9rQ4LQTngRWHeEuJcSmW8cc6AjA3vgGSLR3odRtphDGnQAVHEuJN8p9
是一个正确的地址。
比如：AKC4AgG14PnQyfpEeEQSNSYjhBo5237Yf1pScL4c9rQ4LQTngRWHeEuJcSmW8cc6AjA3vgGSLR3odRtphDGnQAVHEuJN8p9
是一个错误的地址（A开头）

# 挖矿

VIG Coin的产生是通过挖矿实现的。
目前VIG Coin是基于cryptnight算法来实现的。
所以所有支持cryptonight算法的挖矿软件都可以用来挖VIG Coin.

推荐使用xmr-stak

## xmr-stak挖矿

项目地址：
[https://github.com/fireice-uk/xmr-stak](https://github.com/fireice-uk/xmr-stak)

[WIN64](https://github.com/fireice-uk/xmr-stak/releases/download/2.4.5/xmr-stak-win64.zip)

挖矿时填入正确的参数即可，参数可以在这里找到：

http://pools.vigcoin.org/#/getting_started

## 官方矿池

http://pools.vigcoin.org/

## 矿池的搭建

[详情](./Pool.md)

# 贡献

VIG Coin的发展离不开所有贡献者的参与。

项目最初成立的时候矿池服务器就是由网友提供的。

网站的网页服务是由GITHUB免费提供的

群友，网友们也都非常积极的投身于项目的测试，开发。

所有的一切，都体现了开源加密币的活力与价值。

## 贡献的回报

1. 提供服务器用于矿池的网友，将获得矿池的所有收益。
2. 提供服务器用于交易所的网友，将获得60%的交易费用的分成。
3. 参与开发的人员将永久获得每月交易所综合收益抵消成本后的60%左右的分成中的分成。
4. 参与测试，推广的人员将获得当期交易所综合收益抵消成本后的30%左右的分成中的分成。
5. 当期交易所综合收益10%左右用于稳定挖矿与币价，以及再循环，支持创新等


## 贡献项目与要求

### 矿池
对于矿池服务器的要求：
1. 系统为Ubuntu 16.04 版本或者安装有docker服务的linux主机
2. 权限一般要求是sudo, 或者是docker组的普通用户
3. 空闲空间至少有1G以上，未来随着`.vigcoin`目录里的块高增加需要增加空间

## 开发者

开发者的回报是永远性的，只要参与了贡献，以后社区运营的纯利润所得都会有分红的。
开发者的回报的发放主要是根据当前贡献的代码来确定的。
如果开发者的代码完全被替换，将获得最低分红。
具体方案在社区成熟后执行。


# VIG Coin的加密币基本法

加密币通常没有明确的理念支撑，即便是比特币也一样只有技术说明白皮书。
实际上加密币如果没有理念的支撑就会使人走向贪婪与欺骗之路。
ICO与各种空气币的泛滥就是一个证明。

所以VIG Coin旨在以理念为主导去推进加密币的完善。

1. 去中心化是一个基本的原则与基本前提
2. 所以无论是算力，挖矿，运营都应该走去中心化的路线
3. 去中心化并不是抹杀区别，而是将区别控制在一定的范围内，所以VIG推荐采用分级能力。即将能力或者权力分级，一般不超过五级。比如算力分级成五级，那么无论是量子计算机，还是其它的计算机与最差的计算机之间的差别也只有5.这样有利于减少算力差距过大算成的垄断现象。
4. 运营者，矿工，开发人员，商户，最终用户是VIG Coin的基本权力组织
5. 所有权力组织享有投票权，当且仅当所有组织达成共识时，才会被执行。
6. 所有的代码必须开源，必须自由获得，任何人都可以基于代码去独自运营，并且获得利益。
7. 不同的权力组织的意见具有不同的权重。开发者: 4, 运营者: 2.5, 矿工: 1, 商户: 1.5, 最终用户: 1

# 去中心化

去中心化不同的人有不同的理解，下面我将几个VIG Coin对去中心化的理解归纳如下：

1. 节点创建的自由
2. 节点的100%独立性
3. 节点不受除代码外的其它约束
4. 任何节点可以在任何时候选择上线或者下线
5. 任何人可以在任何国家，地区接入
6. 任何人不能操纵其它节点
7. 交易不依赖任何一个特别的交易所







