---
sidebar_position: 1
title: 创建算力实例
sidebar_label: 创建算力实例
---

算力实例常用来做算法开发和模型微调，在少量训练数据的前提下可以选择单卡、或者整机 8 卡的实例申请使用，提供本地数据盘，和关联文件存储，使用终端进行算法开发、微调，使用完成后下载成果，释放算力实例。

## 操作步骤

1.进入左侧侧边栏中的**算力实例**，点击**创建实例**。

<img src={require('../../../../../static/img/getstarted/getstarted-1.png').default} alt="创建实例" style={{width: '600px', height: 'auto'}} />

2.在**创建实例**页面：选择**地区**，选择**计费方式**（按量计费或者包日、包周、包月），选择**GPU型号**、**数量**、**规格**，选择**镜像**（内置了不同的深度学习框架），最后创建即可。如果你需要更大的硬盘用于存放数据，那么请设置需要扩容的大小。

<img src={require('../../../../../static/img/getstarted/getstarted-create-instance3.png').default} alt="租用实例" style={{width: '1000px', height: 'auto'}} />

3.返回算力实例页面，等待算力实例创建完成。已创建成功的实例显示在列，且状态为运行中。

![创建算力实例-操作步骤-示意图](../../../../../static/img/containerinstance/containerinstance-1.png)

4.算力实例创建完成后，通过JupyterLab或者SSH连接使用算力实例。

