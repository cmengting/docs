---
sidebar_position: 1
title: 概要
sidebar_label: 概要
---

### 算力实例中的目录
在使用服务器实例时，不同的存储盘有不同的用途和特点。理解这些盘的用途和性能有助于合理分配资源，提高工作效率。以下是不同存储盘的详细说明及其使用方法。

在实例中查看磁盘使用情况请在终端中执行：source /root/.bashrc

| 名称     | 路径                           | 大小   | 性能 | 类型 | 说明                                                         |
|----------|--------------------------------|--------|------|------|--------------------------------------------------------------|
| 系统盘   | 根目录/及其以下所有路径 (以下特殊路径除外) | 30GB  | 快   | 高性能本地存储 |实例关机数据不会丢失。一般系统依赖以及Python安装包都会安装在系统盘下，也可以存放代码等小容量的数据；实例关机可选择将已有环境和数据保存至镜像中，下次开机数据恢复。 |
| 数据盘   | 可自定义，建议设置为/root/data               | 50GB起  | 一般    | 共享存储 | 可以实现挂载在不同算力实例上。 |
| 文件存储 | /存储管理中用户自定义的挂载路径 | 自定义 | 一般 | 共享存储 | 可以实现挂载在不同算力实例上。 |