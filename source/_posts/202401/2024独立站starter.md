---
title: 别再被贩卖焦虑了，小白新人都可以5分钟内完全免费快速自建美轮美奂的Woocommerce独立站（2024年）
date: 2024-01-31 9:21:40
categories: 
- 独立站
tags:
- 2024年woocommmerce教程
---
网上教程千千万，很多教程都是上来直接动手shopify，不可否认shopify启动确实快，但是用独立站平台有几个风险点：

1. 不可控，不知道什么原因被封站。
2. 难以迁移，如果shopify站做起来了，路径依赖只能一路走到黑，要迁移到wix etsy woocommerce等成本就高了，基本要重做。
3. 难以拓展，虽然可以用Hydrogen做shopify的无头电商，但是如果放弃使用shopify作为后台，那么前端就要重新去对接新的后端，徒增工作量。既然开发无头电商了，为什么还要选择平台作为后端呢？
4. 后期费用高，据了解shopify都是年付的，虽然目前单站价格不高，但仍有可能会有价格调整。
5. 电商必须要收单，个人收单最低要求要有个体户注册商家Paypal才能在shopify里收单，派安盈 strip那些就更不用说了，需要公司资质，虽然可以挂靠，但是时效和可靠性就低了。而woocommerce可以用个人PayPal收单，目前可以用跨境宝零手续费提现。

所以个人认为shopify只适合1刀三个月快速滚服快速试错的模式。然而如果希望能长久运营一个独立站，个人认为还是最好确保站点可控，平台类不合适，woocommerce自建站才更贴合细水长流的模式。

## 个人做独立站的最佳流程

1. 本地开发：localWp
2. 购置服务器或者saas
3. 迁移到正式

### 买Saas还是买vps搭建wp

个人认为用siteground或者namecheap等等的saas服务更好，因为woocommerce还是需要一些性能的，至少需要买4H8G的vps，一年费用也不低，证书虽然可以用免费，但是saas还会提供证书和email代发。买了saas不代表就得一直用它，开头也说了，wp最大的优势是可迁移，如果这一年用的不满意或者觉得第二年费用太高，直接迁移走就好。

### 本地开发

进入主题，本地开发推荐的工具是LocalWp，为什么不用宝塔或者小皮面板等直接部署wp这类呢？因为不够专业，localwp可以直接装IDE插件做本地开发，一键admin功能等等，专为wordpress而生。

1. 先去[localwp](https://localwp.com/)官网下载工具，安装，创建新站

![1706682783150](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706682783150.png)

2. 配置

在Appearance的Theme里安装Astra模板

![1706683429351](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706683429351.png)

3. Starter Template里搜索E-Commerce选择一个电商的装进去

![1706683527152](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706683527152.png)

安装完之后发现插件里就装了四个东西，woocommerce就带进来了

![1706683617122](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706683617122.png)

现在首页已经是一个可以用的电商页面了，但是整个流程是走不通的，因为不能付款收单，所以要补充收单插件

5. 收单插件
   在Add Plugins搜索Pay，安装激活Woocommerce Paypal Payment![1706683957022](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706683957022.png)
   连接Paypal

   ![1706684343574](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706684343574.png)
   连接成功如下图

   ![1706684997685](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706684997685.png)

   确保支付方式启用![1706685685733](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706685685733.png)

---

好了，现在可以走通全流程了，添加了商品之后，checkout，就可以用paypal支付

![1706685738226](https://claytonweb3.4everland.store/2024%E7%8B%AC%E7%AB%8B%E7%AB%99starter/1706685738226.png)

那么整个流程就结束了，大概10分钟内就能完成这个流程
