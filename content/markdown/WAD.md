+++
date = '2025-01-21T20:39:12+08:00'
draft = false
title = 'WAD：从游戏模组到数字资产隐喻'
+++

1993年，id Software为《DOOM》设计的WAD（Where's All the Data）文件格式开创了游戏模组社区的先河。30年后，这个缩写恰如其分地叩击着数字时代的核心命题：在云服务与智能设备编织的巨网中，我们的数据究竟栖身何处？当我们谈论"数字资产"时，真正需要守护的究竟是什么？

<!--more-->

## 可再生与不可再生的数字生命体

朋友曾吐槽自己手机存了十几个微信安装包：“每次更新都像在收集限定皮肤。”我笑他不懂“断舍离”——那些随时能下载的软件安装包，就像便利店货架上的矿泉水，喝完了再买便是。真正需要小心轻放的，是那些一旦丢失就无处赎回的“数字孤品”：凌晨三点迸发的灵感随笔、孩子第一次叫“爸爸”的录音、甚至十年前某个暴雨天随手拍下的咖啡馆窗景。

这类数据像是时光琥珀，封存着无法复刻的人生切片。它们教会我一个道理：在数字世界，“备份”是最深情的告白。

所有数据都遵循着独特的生命周期：从信息胚胎的诞生，到分布式存储中的裂变增殖，直至最终的数据湮灭。在这个轮回中，可再生数据与不可再生数据构成了数字生态的两极。

可再生数据如同数字蒲公英：
微信安装包、临时工程文件、公开网络资源...这些随时可再生的数据就像呼吸空气中的氧气，存储它们如同收集落叶——当腾讯强制升级客户端时，你的旧版本安装包不过是一堆二进制落叶。

不可再生数据则是数字DNA：
生日烛光下的抓拍、深夜迸发的灵感随笔、孩子第一次走路的视频...这些数据承载着不可复制的时空坐标。就像考古学家永远无法复原破碎的陶片，丢失的童年影像会永久抹去记忆的某个切面。

## 云端迷城与本地堡垒

三年前被Notion的颜值蛊惑，兴冲冲把日记本搬上云端。某个航班上想记录灵感，却看着加载图标上演"爱的魔力转圈圈"，瞬间悟了：把全部身家托付云端，就像把存折交给海鸥保管——优雅是优雅，就是取钱得看潮汐。

先来科普一下Notion这个软件，Notion是国外出品的一款笔记软件，我个人也非常喜欢Notion的简约设计。

但是，Notion在我看来最大的一个缺点是，整个服务全部都是云端的。

也就是说，如果我在一个网络不好的环境中，或者没有网络的环境中，是不能使用Notion的。虽然现在完全和网络分离的环境比较少，但总归不能排除这种可能，这就意味着，假如我暂离了网络，或者Notion运营方出现了故障，再或者国内特殊的网络环境出现变化，我将找不回我的任何数据，我的所有数据实际上并不在我的手中。

在当时，我只写了少量几篇文章，并没有什么价值，但是这种“不稳定”的状态还是促使我换一种解决方案，因此我改用Github Pages+本地的方案搭建起了现在这个博客。虽然没有什么是永恒的，但我相信Github的性质和运行决定了这一组合远比Notion要稳定得多，平常我可以简单的讲本地和云端进行同步，即使是在最坏的结果下，我仍然可以在本地保有我所有的数据，有选择，就是Notion所不能带给我的安全感。

迁移到GitHub Pages+本地存储后，倒体会出些老派文人的乐趣。Markdown文件像是电子墨水屏，自带祛魅效果；Git提交记录堪比数字茶渍，留着些修改时的抓狂痕迹。现在我的数据版图像俄罗斯套娃：

- 本地硬盘是贴身日记本

- 私有仓库像上锁的保险箱

- 公开部署则是临街橱窗

## 数字方舟建造指南

理想的存储方案就像寻找三体运动中的稳定解，需在多个维度间找平衡：

安全vs便捷：

NAS像是自家金库，安全但得操心防潮防火；网盘好比银行保险箱，省心却要看人脸色。我的折中方案是把私密照片存加密硬盘，工作文档放企业云盘，至于猫片？当然要上传到宠物社区接受云撸猫。

当下vs未来：

用Word写稿时总担心.doc格式有天变成数字甲骨文，现在改投Markdown阵营，仿佛给文字买了终身保险。有次打开2005年的.txt文件，纯文本的质朴反而比花哨的富文本更经得起时间考验。

公有vs私有：

把游记同步到博客像是往海里扔漂流瓶，某天竟收到南极科考队员的评论；而私密日记用Veracrypt加密，密码强度高得自己都常输错。这种公私分明的存储方式，倒像是给数据世界划出了客厅与卧室。

除去Github存储像这样的一些文字和代码之外，我另外使用的大容量存储服务是Onedrive，和office 365集成到系统内，使用体验非常不错，国外还有谷歌等一众网盘，国内也有一众知名网盘还有各家手机厂商的云服务，都是一种云存储。

还有一种存储方式是直接把内容放到媒体网站上，也可以视为一种存储，只是允许公开查看，如果愿意接受把发布内容作为一种形式也可以，比如为了记录我的游戏履历，我也会在Bilibili上传我的游戏录像，因为这些数据并不是什么隐私数据，也没有更深层次的内容，公开发布允许任何人查看，并且作为私人的一种存储方式完全可行。

纯网络存储方案最大的问题也就在纯网络上，全部数据漂浮在云端同样会带来非常大的限制，比如我之前使用的Notion，在网络不好的情况下就等同于我失去了我的数据，类似的云手机云电脑的概念，看上去都像是一种胡闹。

现在无论是手机系统还是打开某个网盘性质的软件，都会弹出各种帮你备份的提示，或者各种请求去访问你的私人数据帮你备份，这种情况下本地数据也会在网盘有同样的一份备份，在换机之后，在各种环境下，基本都不会失去自己的数据，而且成本好像也并不高，但是真的有这么好的事吗？

## 便利性与控制权的永恒博弈

当我们讨论云存储时，本质上在探讨一个现代性悖论：
```
graph LR
A[便利性] -->|吞噬| B[控制权]
B -->|反噬| C[数据安全]
C -->|倒逼| A
```

国内网盘的"净网事件"揭示了一个残酷现实：存储在他人服务器上的数据，本质上是一份数字人质。百度网盘将用户文件替换为8秒警告视频的操作，堪比数字版的"特洛伊木马"——你以为在运输家具，实则运送着随时可能自毁的定时炸弹。

更隐蔽的风险来自设备厂商的云服务绑定。现在来讨论一个问题，用户在云端存储的数据属于用户还是数据服务商？这一点显然没有争议，服务商只是“代替”用户“保管”数据，原数据百分百属于用户，但是如果根据法律要求，服务商需要审查用户数据，又该如何对待用户的数据呢？厂商有资格审查用户存储的文件吗？涉及到的隐私问题又该由谁承担？

从已有的例子来看，网盘的服务商大多并不遵守对个人隐私权的保护，随意审查删除更换用户的数据，还有些更为现实的例子，例如国内的互联网服务基本都是手机认证实现实名，如果更换手机号后其他人买到了这个手机号，没有更换绑定手机号的账户所有数据等于完全泄露。

并且云盘也是一个相当强力的垄断渠道，设想一个场景，你在某手机厂商自带的云存储中存了几十GB的私人数据，那么下次换手机你会换其他厂商的吗？当然是可以换，但是显然会出现大量的数据迁移成本，如果是嫌麻烦的用户，那么就相当于用户绑定了该厂商而丧失了部分选择权。

当你的数字记忆被封装在某个品牌云空间时，换机决策就变成了情感勒索：是承受数据迁移的阵痛，还是继续被生态链温柔禁锢？

## 在比特之海抛下锚点

数字资产的价值不在于字节数量，而在于其承载的生命密度。当我们用RAID阵列守护家庭影像，用Git版本控制记录思想轨迹，本质上是在虚拟世界中复刻原始人的篝火仪式——用有序的存储对抗熵增，用可控的存档延展记忆。

下次点击"上传"按钮前，不妨自问：如果明天所有云服务同时消失，我的数字存在能否在本地硬盘上完成文明重启？这个问题的答案，就是你在比特海洋中的诺亚方舟。