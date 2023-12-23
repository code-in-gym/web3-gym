# web3 入门计划 202208-09

> 此篇文章版权属于@polebug 所有。其他媒体、网站或个人转载使用时不得进行商业性的原版原式的转载，也不得歪曲和篡改本网站所发布的内容。
由于本人也是刚入圈的小白，如有错误，欢迎指正~
> 

此篇文章记录一下我这六周左右的学习内容：

---

### **WEEK 1: 区块链的基础知识**

- 密码学基础
- 区块链基础
- 相关金融知识
- 学习比特币底层技术
- 学习以太坊原理

MIT 区块链课程 (15.S12)	https://ocw.mit.edu/courses/15-s12-blockchain-and-money-fall-2018/video_galleries/video-lectures/ 
只看了Session1-Session5：
传统金融、区块链技术、相关加密算法	90	是非常好的区块链入门课程，老师讲课的节奏慢且课程易懂。密码学部分讲的不多，只说了区块链中用到的密码学技术。前两节涉及货币，金融方面的知识，第三节到第五节在谈区块链技术，主要围绕bitcoin白皮书展开讲解。
bitcoin white paper 	https://bitcoin.org/en/bitcoin-paper
比特币底层设计	100	上mit课的时候，听老师讲了一遍，之后又自己再看了一遍。感觉还没有完全懂，后续值得再读
《精通以太坊》	https://github.com/inoutcode/ethereum_book
读了一、二、五章，以太坊基础概念
	70	这几章讲的很浅，基本是概念介绍，比较适合小白读


总结：

第一周学习计划预期是7.31～8.7，但由于我中途几天忙着搬家，延期了一周结束。

第一周的学习量还是挺大的，MIT那前五节都在1h15m左右，白皮书大概看了2-3h，《精通以太坊》内容比较少和浅，大概看了2h。总共是大概10h左右，工作日1h30m+周末刚好能够刷完。

这一周最难的应该是白皮书，技术点介绍的很精简，感觉看懂了又没看懂，后续我会再拿出来看看，以及MIT15.S12也值得补完后续的章节。

---

### **WEEK 2: 以太坊和智能合约**

- 了解智能合约相关的基础概念
- 学习智能合约常用的标准，ERC20
- 学习Solidity基本语法，动手写代码


以太坊官方文档	https://ethereum.org/en/developers/docs/
区块链、智能合约相关的基础概念，ERC20
	80	官方文档基本翻完了，介绍的内容比较浅，解释了很多概念。想入门的小白可以去看看。
《精通以太坊》	https://bitcoin.org/en/bitcoin-paper
第八章智能合约	60	概念部分比官网讲的好一点，偏总结性；也有solidity开发部分内容，但我没试过，感觉对小白来说有点复杂
cryptozombies	https://cryptozombies.io/zh/course/
是一个solidity智能合约编程的游戏教学网站，我刷了前三节，比较适合没啥积极性的小白入门刷	55	一开始觉得还挺有趣的，但刷到后面感觉不太行，学的内容比较零散和片面，入门还行，但无法深入领会solidity各种语法特性和编程风格等

总结：

第二周把以太坊官方的文档拿出来翻了个遍，然后再看了下《精通以太坊》智能合约部分，这些大概是看了4h左右，这周剩下的时间在学solidity。

我这周找到的solidity入门课程cryptozombies比较一般，一开始是在以太坊官网上有看到推荐，再加上我以前也看到这个僵尸课程的好评，所以就去刷了一下这个课程。我第一次尝试这种游戏教学，一开始觉得挺好玩的，刷到第二章第三章感觉不行了，发现这种填充部分代码的方式，没法让我比较深入的理解语法。下周就换了个教程学solidity。

对这周的学习不是很满意，花了时间，但是真正学会的很少。属于是垃圾游戏毁我青春了属。不推荐大家去浪费时间造僵尸哈。

---

### **WEEK 3: NFT 生态，智能合约**

- 了解 NFT 生态
- 学习常见的智能合约标准，ERC721/ERC1155
- 学习几个热门项目的技术原理： POAP，ENS，Arweave
- 动手写一个简单的 NFT 合约
- 学习部署和开发一个简单的智能合约，学习相关工具

以太坊官方文档 + OpenZepplin 官网	https://ethereum.org/en/developers/docs/

https://docs.openzeppelin.com/contracts/4.x/erc721

Token标准，ERC721/1155
	80	我觉得这两个官方文档都写的不错，不仅解释了 Token Standard 的概念，各个标准之间的区别，而且列出了标准中包含的 Method 和 Event，并给出示例代码让新手学习
学习感兴趣的项目：POAP，ENS，Arweave	POAP+ENS官方文档，不推荐

Arweave官方文档+白皮书： https://arwiki.wiki/#/en/karma		了解完 NFT 生态之后，我选择了这三个热门项目进行深入了解。POAP 和 ENS 没啥特别的技术能学的，而且官网的技术文档几乎为0，只是介绍了一下概念。Arweave 是最让我喜欢的项目，技术有意思且难，白皮书+官方的技术文档也写的非常不错，推荐一看
Youtube: Smart Contract Programmer	https://www.youtube.com/watch?v=xv9OmztShIw&list=PLO5VPQH6OWdVQwpQfw9rZ67O6Pjfo6q-p

智能合约开发部分	90	看到别人推荐这个up主，就去看了看，发现他的视频讲的极好，易懂且不拖延，能让人跟着一起高效学习编程。我一般很嫌弃这种编程视频课，但他的视频真的不错hhhh
学习智能合约相关的工具：Remix + Hardhat + OpenZepplin	Remix: https://remix.ethereum.org/

Hardhat: 
https://hardhat.org/tutorial/creating-a-new-hardhat-project 

openzepplin:
https://docs.openzeppelin.com/contracts/4.x/api/token/erc721	100	Remix 是一个在线的智能合约编译器，Hardhat 是本地的智能合约开发环境，这周把常用的工具都熟悉了一下，从测试到编译到运行。OpenZepplin 上有许多智能合约开发常用的API，这周也了解了一遍，但学习还比较浅，毕竟还在入门阶段，之后慢慢熟悉这些生产工具

总结：

这周学习成就满满，除了POAP和ENS这俩没啥技术的项目之外，其他的学习内容我觉得都挺好的！不踩坑的感觉真好！上周已经把智能合约的概念搞明白了，这周主要是看NFT+继续学solidity。

先是找了几篇文章看NFT生态，然后选了自己喜欢的三个项目（比较偏基建），POAP和ENS就不吐槽了，Arweave技术文档很好，白皮书也很有意思，推荐大家看这个。

然后继续是智能合约部分，我上周踩了cryptozombies的坑，这周偶然发现Smart Contract Programmer这个up的视频，就去看了。发现讲的很好，配合文字版教程一起食用，我觉得是比较适合我的方式。

以及在同事康康的推荐下，去用了hardhat和remix，动手写了一个简单的NFT合约（几乎是示例代码），跑了一遍编译+测试+部署，还挺有意思。

看着内容很多，但实际上并不是很花时间：
token标准(1h) + NFT项目(3h) + 工具学习(3h) + Smart Contract Programmer(3h)
总共就是工作日1h30m+周末而已

---

### **WEEK 4：DeFi 生态与技术**

- 了解 DeFi 基础知识
- 了解 DeFi 生态
- 了解相关传统金融知识
- 了解 Uniswap 的原理，白皮书

以太坊官方文档	https://ethereum.org/en/developers/docs/
DeFi概念部分，不推荐
	40	一开始找学习资料的时候，我先是去看的各种官方文档，Ethereum/Uniswap 等，想看看这些官网有没有基础概念方面的介绍。之后发现官方文档对于DeFi都只是泛泛而谈，根本学不到什么，也了解不了全面的概念。这里就不推荐大家去各种官方文档搜索基础概念了
DeFi Mooc 课程	原版：https://www.youtube.com/watch?v=j_Gf7E1vAhE

Lecture 1：DeFi基础概念，生态
Lecture 4：传统金融知识
可以在b站找到中文翻译版	90	这个课程的教学节奏很快，拿第一讲来说，短短45分钟介绍了DeFi几乎所有基础概念，以及整个DeFi生态。第四讲介绍了传统金融知识，也是信息量巨大。所以这两讲其实2h左右，但课后需要花很多的时间再去消化和搜索相关的知识，是比较费劲的。第四讲之后的内容讲的比较深，介绍了预言机、借贷、衍生品等比较复杂的内容，这周没来得及进一步学习，这个坑以后再填吧。推荐想要了解DeFi概念的朋友去看这个课。
Uniswap 官网	https://docs.uniswap.org/

技术文档，V1/V2/V3白皮书	70	周末花了大量时间在阅读 Uniswap 白皮书上，说实话有点难懂，v1 还算小白友好，大部分内容在介绍概念上。但 v2 v3 的白皮书，介绍新版的改进时，引入了大量的数学公式，需要花时间去思考，有点难懂

总结：

这周进行得挺艰难的，一方面是DeFi的学习资料太少，而且很难有质量好的，另一方面是我对金融方面真的是没有什么知识积累，真·从0开始学习DeFi。

我一开始找DeFi系统性的文档/课程，四处碰壁，大多数都是简单解释下DeFi是什么，对我一个DeFi小白来说总是找不到什么满意的课程，好在Albert推荐了DeFi Mooc给我！看了之后，感觉这个课程就是我想要的那种，从DeFi各种基础概念，再到金融知识解释。虽然这个课程的质量平平无奇，但我觉得它已经足够好了。

这周还去啃了啃Uniswap的白皮书，第一次看DeFi这种白皮书真是太难懂了。我本身就是个金融小白，到v2 v3还有各种数学证明，简直难度剧增，至今都觉得不是特别理解。不过有可能是我学的东西太少了，预言机、借贷、衍生品这些都没来得及去看。

之后得好好补补DeFi！

---

### **WEEK 5: Web3 项目常用的工具**

（偏后端）

- 学习web3相关的后端技术
    - 与智能合约交互
    - 与 transactions/blocks/event logs相关的逻辑
    - 与钱包相关的逻辑、验证签名
- 熟悉etherscan
- 了解一些有趣的 DApp 设计：IPFS, FIL

web3相关的go后端开发	https://goethereumbook.org/en/ 	90	我平时工作就是web3相关的go开发，所以对这块还算了解。把goethereumbook的内容再动手写了一遍
熟悉etherscan	https://etherscan.io/	90	一直感觉对etherscan不是很会用，找了一些文章和youtube，学习了一下etherscan的基本使用。感觉还是很必要的。
学习感兴趣的DApp：IPFS, FIL	IPFS：https://github.com/ipfs/ipfs

FIL：https://filecoin.io/filecoin.pdf	90	这周选了我很喜欢的存储方向进行学习，从IPFS到FIL到Powergate。因为对去中心化存储不了解，看白皮书花了很多时间，把里面的技术栈都去学习了一下。之后抽个时间再仔细整理一下这块只是。

总结：

最后一周还算轻松，算是我目前最熟悉的一块，因为我现在的工作就是web3相关的后端开发，平时会碰上一些使用场景，这周也算是系统性的再去学习了一下。

现在有趣的项目有很多，我就挑了一个经常被使用到的IPFS，啃了白皮书之后发现去中心化存储还挺有意思的，顺着白皮书再去补了一下相关的技术：BitTorrent，DHT，SFS等等，又再去看了Filecoin的设计。感觉去中心化存储也是个大坑，未来会考虑系统化再去学习。

[学习列表](https://www.notion.so/f8ffdd19936c4e14976a14e07271d9bd?pvs=21)

[WEEK 2: 学习以太坊和智能合约](https://www.notion.so/ebed458a1b204c31b6e587c4d0b89890?pvs=21)

[WEEK 2: 学习以太坊和智能合约 (1)](https://www.notion.so/09490162c17a49648e21e8b749cb5533?pvs=21)

[WEEK 2: 学习以太坊和智能合约 (1)](https://www.notion.so/9c4d53077c5646738e1a17c59d42d98d?pvs=21)

[WEEK 2: 学习以太坊和智能合约 (2)](https://www.notion.so/8902dea226c44f2488d5d2929faed323?pvs=21)

---

以上。

这段学习时间过得很快乐，有时候加班到晚上9点多，10点还能接着学hhhhhhh。

其实我之前每天也会抽一点时间出来充电，只是搬家之后太无聊了，就把学习记录po在网上。感谢大家的喜欢！未来也一起学习吧！