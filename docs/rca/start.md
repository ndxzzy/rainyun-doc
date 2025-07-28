---
title: 快速上手
description: 快速上手
sidebar_position: 1
---


## 🤔 云应用是什么？
云应用RCA（Rain Cloud Apps）是雨云基于Kubernetes开发的容器应用平台，为用户开发、部署和使用容器应用提供了全新的平台，产品经过精心设计，具有高可用、高灵活性、易用的特点。

云应用内置提供App、网站、数据库三大板块，并且提供内置的应用商店，首批上架数百款App，并且适配1Panel等第三方商店。

云应用可以让您在不买服务器的情况下快速部署包括Alist、Cloudreve等数百种热门应用！并且对应用的更新、文件管理、设置等方便快捷。

> 您可以简单理解为，这是一个秒级部署、按量付费、高可用、不需要服务器，随时可以动态扩容的1Panel / 宝塔面板！
> 有兴趣请详细查阅：https://forum.rainyun.com/t/topic/11254

## ❓怎么用
先在 [我的项目](https://app.rainyun.com/apps/rca/project) 处创建一个新的项目，然后到 [应用商店](https://app.rainyun.com/apps/rca/store) 找到您需要的应用，部署后通过他的 **服务** 来访问即可！

想了解更多？来看看详细介绍吧！

## 🛍️ 应用商店
我们精心准备了数百款热门应用，随着社区的扩展，会有更多不同的App加入进来，特别感谢1Panel社区的应用模板，没有1Panel社区，雨云的首批应用不会如此丰富。
您可以根据不同的分类选择不同的应用，不同的应用有不同的资源需求。
![image|690x355](https://forum.rainyun.com/uploads/default/optimized/2X/8/8214097c6af5ed34d5ba48c0df48a9890cfdfa99_2_1380x710.jpeg)

在安装应用的页面，可以修改应用的资源分配，这会影响项目的每小时计费（详细计费方法请看下面）

以Cloudreve应用为例，应用有一个默认的40033端口用于访问，也可以自行修改为需要的端口，后续通过设定的端口来访问。并且可以调整应用的资源限制量。

![image|690x414, 100%](https://forum.rainyun.com/uploads/default/optimized/2X/f/fee2a36421bd3922db1ace9abb4c60334832b08a_2_1380x828.jpeg)
如果一切完美可以点击安装。

## 项目
应用将自动安装到您创建的项目中，在应用管理TAB可以看到已安装的应用。
![image|690x397, 100%](https://forum.rainyun.com/uploads/default/optimized/2X/d/db221a50bb1335b5ef02f9d40c45f623163c271c_2_1380x794.jpeg)

请等待一会儿让应用自动安装，通常只需要几秒钟，但是状态刷新可能要1分钟左右，可以访问应用的服务来测试是否可以访问。
![image|690x139, 75%](https://forum.rainyun.com/uploads/default/original/2X/2/20872e46784d65fb05b0db9a5b2087c5f8a8fe32.png)

一旦应用就绪，变成运行中，可以点击端口的图标，会自动为您复制地址:端口，尝试在浏览器进行访问吧！
![image|690x358, 75%](https://forum.rainyun.com/uploads/default/original/2X/d/d40a12b9d4150b549ce66c77fd6bd35e3bec7f9d.jpeg)

安装好了！几秒钟的时间，您的高可用Cloudreve应用就安装好了。
![image|690x356](https://forum.rainyun.com/uploads/default/optimized/2X/3/3170b39f77fbaadba1cf236dffc0b06fe274fb65_2_1380x712.png)

但是用户名密码在哪里查看？

## 🔧 应用管理
根据应用的介绍，此应用需要我们打开应用的日志来获得帐号密码。
![image|690x464, 75%](https://forum.rainyun.com/uploads/default/original/2X/c/c8c43a72869130e008a395273e563a2c8960b61f.jpeg)

在 [我的项目](https://app.rainyun.com/apps/rca/project) 处打开刚才创建的项目，在 **应用管理** 选项卡点击应用，打开应用管理。

点击 **日志**，可以查看应用的日志，看来红色框框里面就是我们需要的帐号和密码了！
![image|690x305](https://forum.rainyun.com/uploads/default/original/2X/8/81a8a499f3ed5522830405087fc58656b8733f30.jpeg)

复制后试试，登陆成功了！
![image|690x322](https://forum.rainyun.com/uploads/default/optimized/2X/9/9c568aa4e5c67e0152bb39d8886e855d46869bac_2_1380x644.jpeg)

## 🌐 添加网站
HTTP和端口访问看起来不太安全和稳定，那能不能通过域名和HTTPS来访问我们的网盘呢？当然可以了，只需要在项目的网站管理处添加一个**应用代理**类型的网站。
![image|690x196, 75%](upload://yZq1KW2ABiz2OLodTjkn6cCsCb1.png)
可以选择由雨云自动分配一个域名给您，或者使用您的自定义域名。
![image|690x341](https://forum.rainyun.com/uploads/default/original/2X/4/4aa180a3de29f0dd75237ebcb92befd7d0264b74.jpeg)

完成创建后点击网站详情，即可看到分配给您的域名。
![image|690x270](https://forum.rainyun.com/uploads/default/optimized/2X/d/da7cd169a45ef897c6a5b8046ce76fb5e55e8132_2_1380x540.jpeg)
一个使用带有HTTPS的，使用域名的网盘就完成了！
![image|690x304](https://forum.rainyun.com/uploads/default/original/2X/0/0212dffd60db2a78fb910081fcc366a7b317a811.png)

## 💰计费
那么怎么计费呢？
很简单，根据安装的应用、IP数量、流量每小时扣除“雨点”。
您可以在云应用菜单栏看到雨点以及消费记录页面的选项。
![image|418x324, 50%](https://forum.rainyun.com/uploads/default/original/2X/8/8286bc7907a0c5c9b9a0e704afe0862d1845d419.png)
雨点是独立的单位，可以按需充值，充值越多越便宜。而且项目列表显示了预计按照目前所安装的应用和配置、IP地址数量，每个月大概会消耗多少雨点。
![image|631x500, 50%](https://forum.rainyun.com/uploads/default/optimized/2X/7/7f928a091535c380eb812ec9d2bf65e09685bd93_2_630x500.jpeg)

详细单价可以查看[计费说明](/docs/rca/traffic)。

## 🫂 加入社区
对应用的使用有疑问吗？对云应用产品有什么好的建议吐槽的吗？
点击链接加入QQ群聊【雨云云应用RCA用户群】：https://qm.qq.com/q/XAr4hM6gcE

## 结语
是不是很简单呢，就算没有用过云服务器，也会很容易上手，因为他就是被设计为简单易用！如果您觉得云应用方便，请分享给更多人使用！
而且我们在和更多开发者合作，如果您需要创建应用，请使用[应用模板](https://app.rainyun.com/apps/rca/app-template)功能！还可以上架给其他人使用。
对docker-compose的导入和支持也正在进行中，敬请期待！
让我们一起壮大云应用RCA的社区吧！
还有更多使用方法教程分享陆续在路上，敬请期待！