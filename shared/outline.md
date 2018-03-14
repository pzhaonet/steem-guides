## 《Steem 指南》实施纲要 | Outline of the *Steem Handbook* Project

![](images/banner.jpg)

### 总纲

1. 本书书名；《Steem 基础及开发指南》，简称“Steem 指南”，英文名 *Steem Handbook*。
2. 本书的核心价值：协作。
  - 本书的目的不在于推出更多的教程——这样的教程历史上已经有很多，重写没有意义。我们的目的，是推出一套相对完整的系统化指南。所有参与者，切忌单打独斗。此事只有从大局出发，通力协作，才可能完成，否则没有意义。
  - 编辑部的建立和分组，是第一层协作。
  - 各组分别招兵买马，是第二层协作。
  - 搜集历史资料，联系前人作者授权或修改，是第三层协作。
  - 日后的更新和维护，是第四层协作。
  - 通过这些协作，既发挥旧帖余热，又挖掘新人潜力，在新人跟前辈之间建立纽带，达到弘扬社区文化的目的。
3. 本书严禁抄袭和洗稿。一经发现，无论是作者还是编者，永远列入黑名单。
  - 转帖务必征得原作者同意，注明出处；
  - 引用务必注明出处；
  - 在原帖基础上修改得到的新帖，务必跟原作者协商署名；
  - 欢迎所有人监督。
4. 本书以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh) 授权。
5. 发布方式：初稿首发在 Steem 上（标签：cn steem-guides）；最终版发布在网站 steemh.org，提供[网页](http://steemh.org)、[pdf](http://steemh.org/steemh.pdf)、[epub](http://steemh.org/steemh.epub) 三种格式。
6. 相关文章统计：[steemr.org](http://steemr.org)。
7. 参与人员清单：见[共享表单](https://drive.google.com/open?id=1WexEjJhNe_UgjaGlp07I4gmECBYRRGlisrGFe6YjD0s) 。
8. 协作平台： GitHub 的 [pzhaonet/steem-guides](https://github.com/pzhaonet/steem-guides) 项目。详见本文的“协作平台”一节。项目首页可以看到以章节数字编号的 .Rmd 文件，供各章作者更新内容。
9. 篇章结构：见本文的“篇章结构”一节。
10. 素材：见本文“素材汇总”一节。
11. 写作规范：使用 Markdown 基础语法。详见本文“写作规范”一节。
12. 本纲要的原始链接和讨论如下。修订和升级以本文为准。

- [发起：《Steem 指南》团队写作构想](https://steemit.com/cn/@dapeng/steem-guide-start)
- [《Steem 指南》进展：协作平台](https://steemit.com/cn/@dapeng/steeme-guides-project-ready)
- [《Steem 指南》进展：篇章结构](https://steemit.com/cn/@dapeng/steem-guides-book-structures)
- [《Steem 指南》进展：素材汇总](https://steemit.com/cn/@dapeng/steem-guides-giants-shoulders)
- [《Steem 指南》进展：写作规范](https://steemit.com/cn/@dapeng/steem-guides-writing-rules)
- [《Steem 指南》进展：认领任务](https://steemit.com/cn/@dapeng/steem-guides-claim-tasks)
- [《Steem 指南》进展：新增网站](https://steemit.com/cn/@dapeng/steem-guides-new-sites)
- [《Steem 指南》进展：启航宣言](https://steemit.com/cn/@dapeng/steem-guides-milestone)

### 缘起

前辈写尽的话题，总是被一而再再而三的重复写。昨天，原想写写 steem 账号密码的注意事项。写之前搜了一下，发现早就被大家写过了，于是索性整理了一篇 [steem 账号密码安全帖子汇总](https://steemit.com/cn/@dapeng/steem-or-collections-of-posts-on-steem-keys) ，并纳入到 steemr.org 的新人指南里。

可惜的是，这个新人指南并不理想。

虽然帖子归了类，但是仍然缺乏系统性，例如：

- 某个要点在多篇帖子里重复讲了几遍，或者某个内容的一部分在 A 帖里，另一部分在 B 帖里。
- 排在前面的帖子里讲的概念，到后面帖子里才找得到解释。
- 有的文章，结构上写得非常完善，可惜因为世事变迁，有些数据和内容需要更新。

这没法苛求。毕竟是不同作者在不同时期写的嘛。作者想改也改不了。

不如写一本全面系统的 steem 使用介绍。

一个篱笆三个桩。自己写，不如召集一批壮士群策群力。

### 发布方式

这本书全部开源。

初稿由章节作者本人发布在 steemit 上，修改稿以 markdown 格式放在 github 上共享，成书以网页形式和 pdf 格式在社区内共享。

如果写得好，并且 steem 发展得好，有市场的话，说不定可以正式出版为纸质书。狂一点的话，说不定这本书能成为 steem 中国的开山之作。

### 预期收益

**乐观估计**：

- 这本书的本质是个教程。各个章节的初稿，可以由负责该章节的作者本人发布在 utopian.io 的 Tutorial 类别里，能得到第一笔收益。（更新：刚刚有朋友提醒，乌托邦最近改了规则，连 Tutorial 也只能提交英文了。这么说来，想得到这笔收益的话，得自己或找人翻译过去。）
- 如果得到大佬的点赞甚至转发，作者会得到第二笔收益。
- 为本书搭建一个网站，放上广告，广告费是第三笔收益。不多，就当没有这笔钱吧。
- 如果成书口碑好，并且 steem 发展得有市场，说不定可以由出版社正式出版，稿费/版税到时候再谈，那么会得到第四笔收益。多少得看卖得好不好。
- 如果书卖得好，可以翻译成英文再卖一轮，会得到第五笔收益。

以上是我画的大饼。

**悲观估计**：

被 utopian 拒稿；没有大佬支持点赞；出版社不看好销量；写着写着，steem 黄了。

这种情况下，收益就是我个人的点赞和转发 + 网站的广告收入 + 一本排版精良的 pdf 书。

以上是我泼的冷水。

实际情况可能在乐观和悲观之间，所以对我来说都是可以接受的。

### 协作方式。

团队协作写书，最容易出的问题就是版本混乱。这问题如果不先想好，将来统稿时就是一场灾难。每个人习惯的写作工具有不同，无论选哪种工具，都必然会有人不习惯，需要学习。那么，我们索性从一开始就选最好的工具。版本控制的最佳工具，是 GitHub。

很多人误以为 GitHub 只给程序员用，太高深，其实不然。志愿者 @rileyge 专门为本项目写了[一篇教程](https://steemit.com/cn/@rileyge/github)，手把手教大家如何协作写咱们这本书。感兴趣的朋友可以关注他。此外，我再推荐个教程：[文科妹子教你如何多人一起在 GitHub 上写小说](https://www.zhihu.com/question/20070065)。

本书的 GitHub 项目已经建好，挂在我名下，叫 pzhaonet/steem-guides（[访问地址](https://github.com/pzhaonet/steem-guides)）。为了让大家练手，项目下专门有个 `shared/test.md` 文件，就假装是我们未来的书稿，大家可以跟着 @rileyge 的教程在这个文件上随便试验。

原则上来说，我们这个 steem-guides 就是个开源项目，那么通过 utopian.io 给 steem-guides 来写教程、找 bug、提建议等等都应该是可行的。大家可以拿这个项目去乌托邦试试，说不定能赚些钱。在 utopian.io 找 pzhaonet/steem-guides 这个项目就行。utopian 的使用方法见 steemr.org 的首页。

GitHub 虽然很好，但并不容易学。其实我本人也不熟。如果大家实在用不好，那么最坏的打算是，专门请一位懂 GitHub 的志愿者来收集各位作者的原始文稿，再 PR 到 GitHub 上。

有朋友留言提醒教程更新和升级的问题。GitHub 能很好地解决这个问题。比如说，书某个章节发在 steem 上的版本虽然发文 7 天后不能修改，但是作者本人仍然可以来 GitHub 上修改，读者来看这本书的新版就行了。

### 篇章结构

大体结构如下图。各章的具体内容由各组自行决定。需注意各章节之间的呼应和衔接。

![](https://github.com/pzhaonet/steem-guides/raw/master/shared/outline.jpg)

### 写作规范

- 首选参考资料
  - [使用 Markdown 来让你的文章更易于阅读、更美观 @oflyhigh](https://steemit.com/cn/@oflyhigh/markdown)。
  - [中文排印指南 @momok](https://steemit.com/cn/@momok/steemit-cn)。
- 授权和署名
  - 本书暂定以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.zh) 授权。如有异议，欢迎留言。
  - 参与本书的全部贡献者（作者、编者、美工、校对等），遵从各人意愿（真名、id、匿名均可），在封面共同署名。
  - 各章节的作者和编者，在各章节标题处单独署名。
- 内容和文风
  - 尽量写一些变动不会太大的内容，书会有比较长的生命力。
  - 简明扼要。可以适当口语化，但不要有太多的口水词和罗圈话。尽量提供干货。
- 书稿格式
  - 书稿统一用标准的 markdown 语法来书写（见上文的首选参考资料），保存为纯文本文件。除非特殊需求，不使用扩展语法。这是为了方便移植。本帖末尾给了例子。
  - 连续两个回车来分段。也就是说，在文本文件里，两段之间要有个空行。本帖末尾给了例子。
  - 在使用 `@` 符号时，请使用转义符`\`。例如，如果想呈现`@steemh`，那么请在书稿里输入`\@steemh`。
  - 建议使用 typora 编辑器，这里有个简易[教程](https://steemit.com/cn/@dapeng/markdown-steemit-tips-the-best-markdown-editors)。
- 章节
  - 我们的书稿生成程序会自动给章节编号，所以请勿手动编号。
  - 章标题和节标题之间不要有正文。也就是说，所有的正文文字都从属于某个节。
  - 本书最多分到三级标题（即“小节”），也就是 markdown 里的三个 `#` 号。不要出现四级标题。如果需要的话，用粗体表示更低一级的标题即可。
  - 务必不要用 `#` 的方式把某段文字加粗或扩大字号。`#` 开头仅用作章节标题。
  - 请在章节标题处以脚注形式注明自己的贡献（作者，编辑，校对等）。本帖末尾给了例子。
- 插图
  - 请插入本地图片，不要插入网络图片。如果需要插入网络图片，请先把图片下载到本地。同时注意不要侵犯别人图片的版权。
  - 使用 markdown 标准语法来插入图片，即 `![]()`。本帖末尾给了例子。
  - 尽量使用静态图片（jpg，png），避免使用动态图片（gif）；当然，如果动态图片对展示内容效果更好的话，也无妨，但请备好能够替代的静态图片。这是为了方便做 pdf 和纸质书。
- 标点符号
  - 请按照中文的标点符号规则书写。例如，省略号是`……`而不是`......`，也不是`。。。`。
  - 最好不要用像“:)”的表情符号，除非十分有必要——想想印在纸质书里的感觉。
  - 简单规范见[《中文文案排版指北》](https://github.com/mzlogin/chinese-copywriting-guidelines)。详细规范见[《中文排版需求》](https://www.w3.org/TR/clreq/)。


下面是个简单的模板，演示了标题、正文分段、超级链接、插图。

```
# 基本常识 

## 什么是 SBD ^[作者：\@steemh：编辑：\@dapeng；校对： \@meixia。] {#what-is-sbd}

SBD 就是那啥啥（见 steemit [官方网站](http://steemit.com)）。

下面是个图示。

![](fig/sbd.jpg)
```

### 素材汇总

《Steem 指南》的编写，主要在“编”，不在“写”。

**如果同一题材有前人写好的旧帖，我们优先用旧帖，最大程度上尊重前人做过的工作，最大程度上减少资源浪费**。

有朋友留言说，不如把素材先填到书的骨架里，丰满起来比较好看。我觉得这样不妥，因为未经原作者授权。在编写这本书的时候，我们要自始至终有“原作者权益”的概念，避免造成不愉快和不必要的纠纷。

我们已经有了一座图书馆，里面堆满了有用的资料。

不要重复写前人已经写过的东西。如果旧帖涉及的信息陈旧，只需很小改动的话，请原作者修改即可。如果原作者没时间或没兴趣修改，可以协商后换人修改，共同署名。

只有以下两种情况下，才需要从零去写：

1. 原作者不授权;
2. 从来没人写过。

这里，我搜集整理了可用的资料，以备大家查阅。由于我本人的兴趣长期局限在技术和迎新上，所以对文学创作方法、币圈投资策略等领域的文章不太熟悉，这些帖子可以在 @rivalhw @tumutanzi @htliao 等作者的帖子里找到，在此恕难一一列举。欢迎大家去发现，留言补充。

此外，请善用搜索引擎。

- 新人指南搜集整理的资料，见 [steemr.org](http://steemr.org/) 首页或 @jubi 创建的 [steemit.wang](http://steemit.wang/)
- Steemit 官网的[欢迎页面](https://steemit.com/welcome) ，里面除了新手操外，还有全面的帮助文档，白皮书，蓝皮书等。
- @oflyhigh 的很多技术文章。有技术问题先不要自己写，先读 O 神文章，很可能已经有了。这些文章没有明显标识，需要从头逐个找。可以去 [chainbb](https://chainbb.com/@oflyhigh) 从最末页按时间顺序找。
- @deanliu 的 Steem十講。
  - [[預告\] Steem十講即將開始 ... 歡迎參與討論。](https://steemit.com/cn/@deanliu/steem)
  - [[ Steem十講之第一講 \] 行為的主體](https://steemit.com/cn/@deanliu/2qg2ar-steem)
  - [[ Steem十講之第二講 \] Steem之鏈](https://steemit.com/cn/@deanliu/steem-steem)
  - [[ Steem十講之第三講 \] Curation，上帝之手？](https://steemit.com/cn/@deanliu/steem-curation)
  - [[ Steem十講之第四講 \] 面子，還是裡子？The social factor](https://steemit.com/cn/@deanliu/steem-the-social-factor)
  - [[ Steem十講之第五講 \] 透明人？On Transparency](https://steemit.com/cn/@deanliu/steem-on-transparency)
  - [[ Steem十講之第六講 \] 人生相對論 Relativity of Life](https://steemit.com/cn/@deanliu/steem-relativity-of-life)
  - [[ Steem十講之題外話 ] 在區塊鏈上，你需要露多少？](https://steemit.com/blockchain/@deanliu/4cw1f7-steem)
- @lemooljiang 的新手生存系列文章：

  - [新人生存指南之一：steem介绍(更新版)](https://steemit.com/cn/@lemooljiang/4c9adi-steem)
  - [新人生存指南之二：翻墙注册更新版 ](https://steemit.com/cn/@lemooljiang/4xxuhj)
  - [新人生存指南之三：创作赚钱（更新版）](https://steemit.com/cn/@lemooljiang/7dxgdv)
  - [新人生存指南之四：图文编辑三板斧（更新版）](https://steemit.com/cn/@lemooljiang/4mddsq)
  - [新人生存指南之五：司第目工具红宝书(第三版)](https://steemit.com/cn/@lemooljiang/3xqvw9)
  - [新人生存指南之六：新图床supload，顺便赚点比特币](https://steemit.com/cn/@lemooljiang/supload)
  - [新人生存指南之七：P图神技](https://steemit.com/cn/@lemooljiang/p)
  - [新人生存指南之八：快速查询及归类](https://steemit.com/cn/@lemooljiang/3xem6o)
  - [新人生存指南之九：勤于打扫，与垃圾号绝交](https://steemit.com/cn/@lemooljiang/3s29oy)
  - [新人生存指南之十：一分钟注册新帐户（需要付费）](https://steemit.com/cn/@lemooljiang/6hgzux)
  - [新人生存指南之十一：Markdown语法规范（视频版，steemit专用）](https://steemit.com/cn/@lemooljiang/markdown-steemit)
  - [新人生存指南之十二：好玩的表情包和字体图标](https://steemit.com/cn/@lemooljiang/4rxtdx)
  - [新人生存指南之十三：极速提现](https://steemit.com/cn/@lemooljiang/km1n4)
  - [新人生存指南之十四：steemit上的长跑](https://steemit.com/cn/@lemooljiang/6jrje-steemit)
  - [新人生存指南之十五：密码即一切](https://steemit.com/cn/@lemooljiang/2dfqrq)

- @yuxi 的 python steem api 介绍系列
  - [在Ubuntu  16上配置Python和Steem开发环境](https://steemit.com/cn/@yuxi/ubuntu-16-python-steem) 
  - [Python Steem  API介绍系列#1 － 账户篇 ＋ 8 SBD非技术类问题有奖问答](https://steemit.com/cn/@yuxi/python-piston-api-1-8-sbd) 
  - [Python Steem API介绍系列#2 －  帖子读取篇](https://steemit.com/cn/@yuxi/python-api-2) 
  - [Python Steem API介绍系列#3  - 发帖回复点赞篇](https://steemit.com/cn/@yuxi/python-steem-api-3) 
  - [Python Steem API介绍系列#4  - 转账操作篇](https://steemit.com/cn/@yuxi/python-steem-api-4) 
  - [Python Steem  API介绍系列#5 - steempy命令行工具篇](https://steemit.com/cn/@yuxi/python-steem-api-5-steempy) 
  - [搭建免费的云端Steem Python开发环境](https://steemit.com/cn/@yuxi/steem-python) 


- @justyy 的 R 语言教程
  - [R  Tutorial - Connecting to STEEMSQL - R 教程之 怎么样连接到 STEEMSQL 数据库](https://steemit.com/cn/@justyy/r-tutorial-connecting-to-steemsql-r-steemsql) 
  - [R  Tutorial - How rich is SteemIt Wechat Group? R 语言教程 - STEEMIT微信群有多少钱？](https://steemit.com/cn/@justyy/r-tutorial-how-rich-is-steemit-wechat-group-r-steemit) 
  - [R  Tutorial - Knowing when a Steem Whale vote? R 教程之 STEEM大鲸啥时候点赞的？](https://steemit.com/cn/@justyy/r-tutorial-knowing-when-a-steem-whale-vote-r-steem) 
  - [R  Tutorial - New Way to Connect to SteemSQL via RStudio - R 教程之通过 RStudio  来快速连接SteemSQL](https://steemit.com/cn/@justyy/r-tutorial-new-way-to-connect-to-steemsql-via-rstudio-r-rstudio-steemsql) 



- @incrediblesnow 的新人入门手册系列

  - [欢迎来到 Steemit! - 新人入门手册](https://steemit.com/cn/@incrediblesnow/jklx2-steemit)
  - [带你们去看看新版Busy.org！](https://steemit.com/cn/@incrediblesnow/busy-org)  [如何浏览Steemit.com？ - 新人入门手册](https://steemit.com/cn/@incrediblesnow/steemit-com)  
  - [Steemit 上的禁忌与注意事项  - 新人入门手册](https://steemit.com/steemit/@incrediblesnow/3lyojl-steemit)  
  - [Steemit 上钱包与钱币的介绍  - 新人入门手册](https://steemit.com/cn/@incrediblesnow/45qzqw-steemit)            

- @yellowbird 的系列文章
  - [steemit写作技巧之白描](https://steemit.com/cn/@yellowbird/3whpem)
  - [steemit里那些作者们是如何给文章取个好标题的？](https://steemit.com/cn/@yellowbird/tkrqo-steemit)
  - [steemit写作技巧之讲好一个故事](https://steemit.com/cn/@yellowbird/5w3vc3)
  - [steemit写文排版常用技巧](https://steemit.com/cn/@yellowbird/3aeewa-steemit)
  - [steemit写作你需要了解的一些事](https://steemit.com/cn/@yellowbird/steemit-about-steemit-writing)
  - [人人都应该学会写作](https://steemit.com/cn/@yellowbird/7scg15)
  - [steemit上写作的“损失厌恶”心理现象](https://steemit.com/cn/@yellowbird/3cbscb-steemit)
  - [steemit上的注意力经济](https://steemit.com/cn/@yellowbird/7dqts1-steemit)
  - [steemit写作收入1万用了四个月，从1万到2万却只用了两个星期](https://steemit.com/cn/@yellowbird/steemit-1-1-2)
  - [被大鲸点赞和留言是什么感受](https://steemit.com/cn/@yellowbird/6x8mv3)
  - [Steem交易转账操作/ About BlockTrades](https://steemit.com/cn/@yellowbird/steem-about-blocktrades)
  - [Busy.org另一个steemit](https://mp.weixin.qq.com/s/cf4Zw5F7mC-Jf5cIw85zZg)
  - [说说steemit里的三种货币](https://mp.weixin.qq.com/s/HbGRlVXE-I5omUB_cgpAkw)
  - [Steem and Bitshares](https://steemit.com/cn/@yellowbird/steem-and-bitshares)
  - [持有STEEM的我当了回股东/STEEM DPOS](https://steemit.com/cn/@yellowbird/steem-steem-dpos)
  - [五分钟方便快捷注册steemit](http://mp.weixin.qq.com/s/BEjXJxxfNq1J05xg5Wf95g)
  - [基于STEEM区块链的SMTs/My understanding of SMTs](https://steemit.com/cn/@yellowbird/steem-smts-my-understanding-of-smts)
  - [对比STEEM来聊聊YOYOW](https://steemit.com/cn/@yellowbird/steem-yoyow)
  - [对比STEEM、YOYOW来看PressOne](https://steemit.com/cn/@yellowbird/steem-yoyow-pressone)
  - [去中心化的视频分享网站DTube初体验](https://steemit.com/cn/@yellowbird/dtube)

- @wang-peilin 的 steemit 文章总结
  - [怎样用3分钟注册好一个Steemit账号？](https://steemit.com/cn/@wang-peilin/3-steemit)
  - [Steemit新人手册：怎么发表一篇文章](https://steemit.com/cn/@wang-peilin/2a5cby-steemit)
  - [翻译自@sndbox：什么是点赞（投票）？](https://steemit.com/cn/@wang-peilin/4tbrfn-sndbox)
  - [怎么把SBD转化为Steem Power(SP)——关于Power UP的带图教程](https://steemit.com/cn/@wang-peilin/sbd-steem-power-sp-power-up)
  - [新人手册：什么是SP？什么是VP？为什么我不能发帖，评论，回复了？怎样分配我的点赞？](https://steemit.com/cn/@wang-peilin/sp-vp)
  - [文章的真实收益远大于显示收益！怎样快速计算文章的真实收益？](https://steemit.com/cn/@wang-peilin/uvu5x)
  - [怎么用BTC等数字货币购买SP（Steem Power）？](https://steemit.com/cn/@wang-peilin/sp-steem-power)
  - [怎么用SBD购买SP(Steem power)?](https://steemit.com/cn/@wang-peilin/sbd-sp-steem-power)
  - [Steemit用户手册：为什么文章收益会变化？](https://steemit.com/cn/@wang-peilin/5uvrhi-steemit)
  - [翻译自@sndbox：什么是加密货币？什么是区块链？](https://steemit.com/steemit/@wang-peilin/sndbox)
  - [翻译自@sndbox：基础知识介绍——什么是Steem见证人？](https://steemit.com/cn/@wang-peilin/sndbox-steem)
  - [Steemit新人手册：请不要长篇大论的写文章](https://steemit.com/cn/@wang-peilin/2v3jvb-steemit)
  - [Steemit新人手册：请不要抱怨大佬们不给你点赞](https://steemit.com/cn/@wang-peilin/6jzhkj-steemit)
  - [Steemit新人手册：Busy，CNSteem,Utopian(乌托邦)是什么？它们有什么优缺点？](https://steemit.com/cn/@wang-peilin/steemit-busy-cnsteem-utopian)
  - [Steemit用户手册：一个小技巧，帮你快速省时浏览文章，回复消息](https://steemit.com/cn/@wang-peilin/3vmuhh-steemit)
  - [新人手册：Steemit的文章编辑方法，Markdown的一些使用技巧](https://steemit.com/cn/@wang-peilin/steemit-markdown)
  - [23条建议让你在steemit成功！ 23 Tips to Help You Succeed!](https://steemit.com/cn/@wang-peilin/23-steemit-23-tips-to-help-you-succeed)
  - [Facebook会在未来取代Steemit吗？](https://steemit.com/cn/@wang-peilin/facebook-steemit)
  - [Steemit可能成为未来人类的主流炫富手段](https://steemit.com/cn/@wang-peilin/3hvez8-steemit)
  - [Steem未来的价格能打败比特币（B T C）突破天际吗？](https://steemit.com/cn/@wang-peilin/steem-b-t-c)

