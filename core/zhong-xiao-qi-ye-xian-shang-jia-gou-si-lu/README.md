# 中小企业线上架构

## 问题的起因

大约二十年前，我自己建网站和博客，因为那时的网站只能自己建。

后来各种互联网服务越来越成熟，有现成的产品拿来用，交服务费就可以了。交的服务费远低于自己维护的成本。当然，也不仅仅是网站，还有更丰富的更细分行业的服务。我以为自建网站这件事已经是往事，我甚至认为中小企业不需要自建网站。

最近几年，由于一些工作的原因，我留意过很多中小企业的官网。其实也不仅是中小企业，除了专业的互联网公司和大型金融机构以外，绝大部分机构的官网都是极其难用，甚至是不可用，甚至起到负作用。

这几天我为了建自己的博客，顺便做了调查，得出一个很简单的方案。个人博客是用不上这个方案的，但适合中小企业。

这个方案的名字叫做：静态站点生成器，或者SSG or static site generator。

我已经十几年没写过代码了，已经看不懂任何编程语言的任何一个语句了，已经不知道任何一种语言该用什么编译环境或什么解释环境或者什么运行环境了，但是用这个方案我能建一个网站，所以它应该是适合中小企业的。

## **非技术类中小企业线上架构的原则**

* 能没有官网就不要有官网
* 流量入口的分布式架构：不是指技术上的分布式架构，而是指哪里有流量就去哪里。或者叫做流动性架构，或者叫做穷则迂回穿插架构（绝大部分机构的架构都是错误地采用了达则炸他娘的架构），或者叫做战术小分队架构。流量原地消化，那就是战术小分队的意思。
* 一旦有官网，官网的核心作用是：信息的最终解释权：你可以不说，但你一旦发布在官网上，每一点信息都要负责，那涉及业务流程整合
* 一旦有官网，官网的作用绝不是承接流量，因为那涉及复杂的业务流程重构
* 整个架构的核心绝不是技术，而是业务流
* 成本分配比例，给外包技术团队的部分绝不是重点，重点是业务流和内部团队，以及内部团队的战术素养和业务流的匹配

## 自建网站的准确含义

没有彻底地自建网站这回事。

很多中小企业主，认为把自己的东西放在别人的地盘不放心。

就算是腾讯、阿里、google，苹果、亚马逊、facebook也得用别人的服务。

事实上，你总归要用别人的基础设施，基础设施的架构已经有了很多层，你归根结底都在别人的地盘。只有茹毛饮血的时代，人才可能有自己的地盘。我们说的自建网站，只是从最上面一层，稍微往下挪一层。



