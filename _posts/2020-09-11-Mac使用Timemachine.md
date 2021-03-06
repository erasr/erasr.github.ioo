---
layout:     post
title:      Mac使用Timemachine自动备份
subtitle:   Timemachine谁用谁知道
date:       2020-09-11
author:     V
header-img: img/post-bg-github-cup.jpg
catalog: true
tags:
    - Mac
---

#### 引言

我相信很多人都有丢失文件的经历，然后想尽各种办法找回数据。我就中过一次枪。所以说与其等到真的意外丢失了文件再着急，不如从现在开始，养成随时备份的好习惯。

对于Mac用户，Timemachine你值得一试。

#### 1. 准备硬盘

首先，我们需要一块移动硬盘。我直接用的是在老电脑上卸下来的，500GB。然后在网上买了个透明的硬盘盒。如果没有老电脑可以拆，在网上买块新的也行。

![](/img/Timemachine/1.jpeg)

**[透明移动硬盘盒（点我购买）价格：24.9元](https://union-click.jd.com/jdc?e=&p=AyIGZRtfEAQTBVwdWh0yFgBSHV4UBhQAUhJrUV1KWQorAlBHU0VeBUVNR0ZbSkdETlcNVQtHRVNSUVNLXANBRA1XB14DS10cQQVYD21XHgNSHF0QAxYBUhxSJXxqfCVIC3AAdwFPcyx2fRJkIU1BfUQeC2UaaxUDEwRWHVgRChs3ZRtcJUN8B1QaWRcBFgZlGmsVBhoPXB1SFQUVA1ceaxICGzdVH1wRABcGXBtdFGxTRAcrayUBIjdlG2sWMlBpVxxcFgVGBlRLXkECFwFRHVIVBkJUBh5dRwMaDlVJCBAyEAZUH1I%3D)**

**[西部数据（WD）移动硬盘 2.5寸 USB3.0 价格：349元](https://union-click.jd.com/jdc?e=&p=AyIGZRNdEQoXAV0eUyUGFAZcG1wcBRAPXSsfSlpMWGVCHlBDUAxLBQNQVk4YCQQAQB1AWQkFHUVBRhkSQw9THUJVEEMFSgxUVxZPI0AOFgFUElsSCxUFXRNrRVRlZwB%2FG0tiRWEiQzxLemEAA0tTUw4eN1QrWxQDEQRTGF8dCyI3VRxrVGwVDlceWiUDIgdRE1McCxMGXB5ZEQQiAFUSaxUGFQNXHlocAhQGO1oYRzIiN1YrayUCIgRlWTUXBkUOUxNfFFUbV1AeWxMLGwABTwwcVRIAUxlbHQFCVWUZWhQGGw%3D%3D)**

#### 2. 初始化硬盘

准备好硬盘后，下边要对硬盘进行初始化。

打开系统自带的「磁盘工具」，在左侧选中自己的硬盘，点击上方的「抹掉」。在弹出的对话框中，名称自己随便设置一个，格式选择「Mac OS 扩展（区分大小写 日志式）」（默认项）。最后点击「抹掉」，等待完成即可。

![](/img/Timemachine/2.png)

**建议让Timemachine独占硬盘**

#### 3. 加密磁盘

当做完上述步骤后，Mac会自动提示你是否使用该硬盘对Mac备份。同时为了数据的安全性，建议在弹出的对话框中勾选「给备份磁盘加密」。

![](/img/Timemachine/4.png)

随后在弹出的对话框中输入密码和提示信息即可。

![](/img/Timemachine/5.png)

这个加密过程是非常缓慢的，加密速度大概在20~30MB之间。如果加密100GB的数据，大概耗时1小时左右。不过，加密过程可以中断，你可以随时把硬盘推出，等下次你再接上硬盘的时候，Mac会自动进行上次未完成的加密。

#### 4. 排除不需要备份项

我们还可以根据自己的需求选择不需要备份的文件。

打开时间机器-》选项，将不需要备份的文件添加上去即可。

我自己没有排除。下载项啥的我也备份了，省的到时候再去重新下载了。

#### 5. 备份数据

() 菜单 >“系统偏好设置”，然后点按「时间机器」。然后点按「选择备份磁盘」，选中你刚才初始化的硬盘。首次备份的话，时间会很长。但是以后Timemachine会只备份更改过的数据，所以会很快完成备份。

记得把「自动备份」勾选上。这样以后会自动进行备份，不需要人为干涉。

![](/img/Timemachine/6.png)

#### 6. 恢复数据

在菜单栏点按时间机器的图标，然后点按「进入时间机器」，会出现如下界面。

![](/img/Timemachine/7.png)

是不是很酷。

现在你就可以选择需要还原的数据进行还原了。





