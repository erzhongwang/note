---
sidebar_label: '硬件介绍'
title: 家庭服务器硬件介绍
tags:
  - server
---

import LinkCard from '@site/src/components/LinkCard';

:::note
折腾家庭服务器半年有余，本文介绍一下我搭建家庭服务器的硬件选择和选购经验。
:::

## 网络设备

### 光猫

原本想淘宝购买，替换掉运营商自带光猫，但担心配置复杂一直没下手。刚巧联通今年推出了全屋FTTR的套餐服务，免费更换了光猫，宣传上能够支撑千兆网络。实际体验下来，发热较之前的光猫大幅降低，看来光猫应该不构成瓶颈了。

### 无线路由器

家里一共安装了两个无线路由器，均作为AP使用，而主路由采用主机安装的软路由，这部分后续再讲。无线路由器一台为华硕的AX12，一台为小米。

#### 华硕 AX12

这一台购买时还没有搭建软路由，目前仅作为AP其实有点奢侈了。购买时主要考虑两点：
1. 外观设计，在路由器中，这款设计算是比较好看的了，摆在外面也不会太丑。
2. 华硕的路由器众所周知可以刷梅林或官改系统，以实现科学上网，在不配置软路由的情况下，这是最便捷的实现方式。

#### 小米路由器

租的房子自带的小米路由器，本来想扔掉，转头想想正好可以用来控制全屋智能。家里的智能设备基本都是小米的，数量也不少，专门用一个路由器来控制这些设备，也能降低华硕路由器的负载和连接数。

### 交换机

家里一共配备了三台交换机，一台4口10G交换机，两台8口1G交换机。

#### TP-LINK

这是一台四口10G交换机，支持10G，5G，2.5G，1G的自适应速率。
主要用于连接主服务器，PBS(备份服务器)，华硕无线路由。实现主服务器虚拟机间，以及虚拟机与备份服务间的高速传输。

#### TP-LINK

这是一台八口1G交换机，TP这一款性价比较高，价格实惠，