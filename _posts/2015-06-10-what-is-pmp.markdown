---
layout: blogs_item
title: 半小时读懂PMP私有广告交易市场
author: AcePeak
categories:
  - 积累
tags:
  - DSP
  - PMP
  - 转载
---

在程序化广告购买领域，现在没有什么比PMP更热门的了。我之前所写的这篇文章——《PMP私有交易市场——程序化广告的新高度》引起了很多反响，很多朋友问，到底什么是PMP，在它之上广告是怎么交易的，有哪些好处，又有什么样的局限？

所以，我写这篇文章，想让你半个小时就弄明白PMP私有交易市场是什么，广告怎么在这个市场中间交易。然后，在后续的几个“半小时”文章中，我将继续介绍PMP的其他内容。


##PMP为什么出现？


想要了解PMP，最好先弄明白互联网广告的新生态，尤其是程序化广告产业链。PMP也好，RTB也好，都是互联网广告的革新——程序化的广告。这也是为什么我先写了一篇半小时读懂互联网广告新生态，在这篇文章中，认真了解Ad Exchange和RTB是很有意义的。如果你看了这篇文章，你就知道RTB的广告生态必须依赖于Ad Exchange的存在。Ad Exchange如同一个大的自由市场，各路媒体把自己空闲的广告位在Ad Exchange中登记售卖，而广告主则委托DSP在Ad Exchange中为在这些位置上展现自己的广告而不断竞价。在这个市场中，一切都是平等的，供和需对每一个人都敞开，规则对每个人都一样，若我希望在某个广告位上出现我的广告，我需要记住唯一的规则——价高者得，然后确保我的出价高于别人。


但问题是，RTB是背对背的拍卖，而且在电光火石的100毫秒左右的时间内，你只有一次出价机会。这意味着原本你看好的一个人出现在了某个广告位上，你信心满满的出了高价准备让自己的广告展示在他/她的面前，但却因为另一个更加疯狂的出价者抢走了这次广告展示机会。因此，RTB显然具有不确定性，这种不确定性与SEM（PPC）的排名竞价是非常类似的，你并不是不能控制，但是你无法实现精确控制，或者只能实现部分控制。你并不能事先确保这个广告位在某事某刻一定能被你占据，你也不能事先确保一个固定的价格。竞价——瞬息万变、捉摸不定、无法精确预知，支配这个世界的规则是概率和基于实时统计的干预，但无论如何我不能让它如钟表般精确。

这绝对是对互联网广告工作方式的一个剧烈颠覆，过去我们购买的是广告位，但在RTB环境下我们购买的是给人（受众）展示广告的机会，广告位反而不是那么重要了。同样，过去的互联网广告是平面广告的售卖方法——事先选择广告位置，确定投放的期间，然后谈好价钱，再然后到时看广告便行了。一切都很精确，我们事先已经知道广告会出现在哪里，也知道我们要花多少钱。不过，一旦我们花了钱，确定了广告位置和时间（位置和时间，就是我们所说的排期计划），广告的效果就是“谋事在人成事在天”了，我们虽然仍然能够实时统计查看广告的产出，但却无法实时干预。

所以，RTB广告的特点是“两个不确定和一个可干预”——不确定广告位、不确定广告价格，但是广告效果可以实时干预；传统互联网广告则是“两个确定和一个不可干预”——广告位和价格确定，但效果不可干预。这也算是各有利弊吧。所以这也是为什么很多广告主仍然不能把所有的广告投放都交给RTB的原因，毕竟商业生活中，不确定性是每天都要面对的“讨厌鬼”，能回避它且回避它。

从媒体的角度看，上面的不确定性也造成RTB广告也不是他们进行广告资源售卖的第一选择。那些众人追捧的优质资源，比如“爸爸去哪儿”视频的前贴片广告，总有广告主愿意出天价购买它，既如此，又何必把这些明星资源放到公共的自由市场（Ad Exchange）去竞卖呢？这个道理实际在任何的市场中都是存在的。比如北京的潘家园旧货市场，这是全球六大古董和工艺品公开交易市场之一，每天有大量的商品在这里被交易，但是真正被交易的精品却少之又少。那些真正的好东西在被放到潘家园的摊位上之前就已经被消息灵通的私人直接买走了。媒体的优质资源同样如此，这些资源如果放到公开市场中，受RTB广告的两个不确定性（不确定广告位且不确定价格）影响，很有可能不能被完全交易出去，或是即使全部交易出去也有可能无法达到媒体预期的价格。当然，各种可能性都是存在的，说不定这些资源在公开市场上反而全部卖出了高价——但一切在交易尘埃落定前全部都只是可能性。可能性的同义词是不确定性，我说过，人们讨厌不确定性。

![RTB广告特点](/img/150610_2.jpg)

（上面这张图很好地说明了RTB广告的特点。RTB不按照广告位进行售卖，而是根据受众（人）来售卖广告，并且你的广告是否能显示给这个人，取决于你愿意出的价格。因此RTB广告的广告位是无法预先确定的，广告价格也不可能在竞价之前就精确知道。）

既然这个世界上有不需要公开自由市场就能够完成双方都满意的交易的可能性，那干嘛还非要到公开市场上去呢？因此，这种情况下的买卖双方不再去公开市场，也就是说他们不会去Ad Exchange中“搞拍卖”，而是寻求一个私下交易的场所，在“一个月黑风高”的地方“偷偷”完成买卖，这个场所就是PMP，即Private Marketplace（私有交易市场）的缩写。因此你也就可以发现，PMP实际上是和Ad Exchange相对应的概念，前者是私下里的交易场所，后者是公开交易场所。
PMP是什么
看了前面的文字，大家可能会困惑了，传统的广告交易不就是“私有的”吗？如果我不做RTB的广告购买，而是跟新浪或者优酷的广告销售部门直接联系购买广告位，这不就是“私下交易”了吗？或者说，几乎所有我们过去传统的广告都是私有购买方式，那么PMP，这个听起来玄而又玄的东西，究竟是什么？

这个问题真是好问题，因为它直击关键。没错，传统广告交易几乎都是私有的，但它不是程序化的广告。PMP的交易也是私有的，同时，它还是程序化的广告。这是跟传统广告最本质的区别。或者换句话说，PMP的交易方式与传统广告类似（但实际上因为程序化的影响，二者并不完全一样），但工作方式（即程序化广告）却和传统广告完全不同。

因此我们可以给PMP下一个定义，即它是将传统广告的私有的交易方式与程序化广告的工作方式相结合的新互联网广告形式。传统广告的私有交易有一个非常强大的好处，那就是广告位置都是在广告上线之前就必须确定好的。比如，大家在电视上看到的广告，肯定是早在好几周甚至好几个月前就被广告主预定下来的，不可能在广告要播出的那一刻，才由电视台到处询问谁要这个时间的广告。

互联网上（尤其是PC上）的大多数广告也是同样如此。这种方式保证了广告在投放前已经完全确定了时间、位置和价格，不存在任何不确定性。人们当然喜欢这种方式，因为这种方式帮助广告主提前锁定了他们想要的资源。PMP的特征之一，就是要尽可能地保留这种方式，尽可能地消除人们讨厌的“不确定性”。

![PMP整合RTB与传统广告资源](/img/150610_1.jpg)

另一方面，PMP也希望能够把程序化广告（例如RTB）的好处引入进来。如果你读过我前面提到的两篇文章，你就知道程序化好处有很多神奇的地方，最鲜明的，就是利用计算机智能，根据受众的情况或是其他规则来动态管理和操纵广告的投放工作，从而在几乎实时的情况下随时调控广告，实现广告效果的提升。

所以，你可以认为，PMP ≈ 消除不确定性 + 程序化广告。不过这个等号不是等于，是约等于，后面你会知道为什么这里不能放上等于号。

我这么说你可能还是“不明觉厉”，没事，接着看。

##PMP的交易方式

上一节讲了，PMP的特征之一是私下的交易，理论上能够提前锁定资源，但与传统的私下交易方式并不完全等同。或者说，它是传统私下交易方式在程序化时代的推陈出新。PMP的交易方式跟传统广告交易方式有什么差异呢？回答这个问题，我们需要具体了解PMP的几种交易方式。

第一种，也是最基础的一种交易方式被称为PDB，即Private Direct Buy（私有直接购买），这种方式简单讲，是一对一（1v1）的购买方式。这种购买方式，与我们传统的广告采买方式基本上没有区别，即广告主找媒体确定好广告位置和价格，然后按照排期规定的时间进行广告投放。在传统方式中，广告排期（spot plan）是这个交易过程的关键，而在PDB中，也完全如此。

PDB这种方式，是广告主最容易接受的方式。首先，与传统采买方式一致意味着广告位资源是预先保证的，一旦排期确定，PO（purchase order）下达，广告位资源就肯定不可能易主。再者，不改变传统的广告采买过程意味着内部的组织和工作流程都不需要发生什么变化，因此也就没有“政治”问题（你懂的）。更何况，在此之上还能实现程序化的好处，有百利而无一害，何乐不为。

PDB方式支持传统的CPD（Cost Per Day）的广告采买方式，也支持CPM（Cost Per Milli，即广告被千次曝光所需的成本）和CPC（Cost Per Click）的方式。

![PDB广告模式](/img/150610_2.jpg)

第二种，被称为Preferred Deals（优先交易），与第一种方式相比，情况略有不同。第一种方式下，广告位资源是广告投放前就锁定的，但在这种方式下，广告资源具有一定的不确定性。这个不确定性并不是指广告位不能被锁定，也不是指广告的价格不能预先谈好，而是指这个广告位的展示量，不能预先保证。什么意思呢，比如你看中了网站分析在中国(www.chinawebanalytics.cn)的这个博客上的某个广告位，这个广告位碰巧是按照CPM方式出售的。由于我的网站的流量每天都不一样，有时候多，有时候少，因此这个广告位上广告的展示次数不能预先确定，这就意味着尽管广告位可以卖给你，但是展示量却保证不了，这样你在我这个广告位上做广告的预算就不能精确预知了。

更何况，我的这个广告位因为是按照CPM来出售的，也就不一定只是卖给你，我可能同时还卖给了另外一个广告主，并且我还保证了给他每天确保1000次展示，而卖给你就只能是在卖个另一个广告主之后，是他买走的1000次之外的剩下的展现量。即先紧着别人用，剩下的才能给你，这种情况下，量就更不容易保证了。这个例子是现实世界中常常发生的情况，对于另外那个广告主而言，他跟我的购买方式实际上是第一种，即PDB的购买方式，而跟你，则是Preferred Deals的购买方式。从这里可以看出来，媒体在释放广告资源的时候，PDB方式的优先级，要高于Preferred Deals方式，而Preferred Deals的优先级，又高于需要完全竞价的RTB。

当然了，Preferred Deals也是双向选择的，媒体不能保证你的广告资源的展示量，你当然也可以把自己不需要的量进行退回，这样你就有了一点点“选人”，即按照受众情况来进行投放的权利。这里我不引申太多，在后面的文章中我会涉及。

![Preferred Deals广告方式](/img/150610_2.jpg)

Preferred Deals方式只支持CPM和CPC的采买方式，传统的CPD方式不可以。为什么？这个问题留给大家想一想，相信答案不难找。

第三种，被称为Private Auction（私有竞价，或者私下竞价），这种方式比前两种方式都要复杂一点点，但其实并不难理解。如果说第一种PDB的方式是纯净无广告主为广告位资源竞争的世界，那么Preferred Deals就开始有了跟其他广告主竞争广告位的可能性，只是因为优先级不够高，所以也就没有直接冲突。不过，如果你有钱，任性，你觉得凭什么我的优先级就要比别人低一些，我不服，这个时候怎么办？

互联网广告市场，尤其是品牌广告市场，有钱任性的大买家实在太多了，好资源又只有那么多（而且特别是中国，是一个媒体资源特别集中的地方），所以几个广告主都看中了同一个广告位置的情况，实在是屡见不鲜。程序化广告诞生前的传统售卖方式下，决定你能否拿到这个广告位置的不仅仅是钱的问题，还要看时机（先提出合理价格购买的，可能就先搞定了），以及一些你知道的其他的因素（你懂的……）。不过，这绝对不是最佳的资源配置方式，如果这个广告位被售出之后，又有愿意出更大价钱的广告主出现，对媒体来说就是绝对的损失。Private Auction的出现就是希望解决这个问题。

在PMP的Private Auction方式下，媒体把那些众多土豪广告主们都喜欢的广告位置专门拿出来，放到一个半公开的市场中进行售卖。说它半公开，是因为这个市场有点类似于白金俱乐部或是VIP交易室之类的东西，广告主要到达一定的牛逼程度才能够进去。当这个市场中某些个广告资源开始售卖，便通知这些土豪广告主们，请你们进入我们的VIP交易室来采购吧！不过呢，不是直接买，而是广告主们大家一起竞价，价高者得。你看看，这个过程非常类似于我在前面的几篇文章中讲过的RTB的方法，不过RTB所依托的市场，也就是Ad Exchange大市场，是一个菜市场，谁都可以来买，没有准入门槛。但是这个Private Auction的交易场所，就不是菜市场了，而是VIP市场，只有土豪们玩，屌丝们就别掺合了。

同第二种Preferred Deals方式一样，Private Auction方式也必须按照CPM进行交易。由于Private Auction的资源一般都是比较好的优质资源（媒体内部被称为高优先级资源）因此，尽管它也是竞价方式，也不能100%保证你能得到这些资源，但它的广告位资源的可保证度还是比RTB要可靠太多太多了。因此，在下图中，你可以看到橙色的Private Auction介于广告位预留和广告位不预留中线上，只是稍微偏向广告位不预留一些。

![Private Aution广告模式](/img/150610_2.jpg)

前面我们提到了PMP ≈ 消除不确定性 + 程序化广告，公式的等号用了约等号，现在你应该知道原因。PMP的后两种交易方式（Preferred Deals）和（Private Auction）都没有完全消除不确定性。不过，相对于RTB而言，不确定程度肯定是大大降低了。

在Private Auction的交易方式下，PMP，即私有交易市场这种说法才最能体现其本质，而PDB或者Preferred Deals更像是私下里的直接交易，谈不上真正意义上的市场，不过，约定俗成，这三种方式我们都把它归入到PMP的大范畴中去。

目前，在国内，三种方式中最为常见的是第二种，开始变得常见的是第一种，而第三种还几乎没有看到案例。第三种不够普及的原因显然不是技术上的，更像是文化上的。中国人不喜欢竞争，或者，不喜欢公开竞争，我们更信奉在明面上战斗之前，就暗地里先搞定敌人。所以，那些需要共同竞价的方式，无论是公共的，还是有准入门槛的，大家都不喜欢。不过，在美国，第三种方式反而是最为常见的。这是后话了，按下不表。

在国际广告局（IAB）的介绍程序化广告的标准文档中，我们会看到上面所说的四种方式，如下表所示。我就不翻译了，大家自己看。IAB用的名字跟中国人喜欢用的名字（虽然都是英语）有所不同，不过我相信这对你不是问题，你肯定能够很轻松地对号入座。读懂了我上面的文字，下表也就不是问题了。甚至，当我们国家的互联网公司再推出让你莫名其妙的广告产品的时候，你也会立即恍然大悟，原来是这个意思！

![IAB程序化广告](/img/150610_3.png)

再看看新浪的程序化广告产品的宣传册，是不是一眼就看明白了（甚至看到了它措辞上的矛盾之处——既然是Preferred Deals，就很难100%的保量啦。:P）。如下图：

![新浪程序化购买](/img/150610_4.jpg)

好了，这一个半小时就说到这里。在其他的几个“半小时”文章中，我将接着介绍：PMP的价值、PMP的局限性、PMP的效果以及我们如何实现实现PMP。
