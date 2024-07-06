---
description: cesss
---

# cess链节点

## 链节点 <a href="#lian-jie-dian" id="lian-jie-dian"></a>

### 建议一台机器一个链节点 <a href="#jian-yi-yi-tai-ji-qi-yi-ge-lian-jie-dian" id="jian-yi-yi-tai-ji-qi-yi-ge-lian-jie-dian"></a>

一台机器部署一个链节点，部署多个存储节点，存储节点共用这个链节点

### 新增加cess链节点参数说明 <a href="#xin-zeng-jia-cess-lian-jie-dian-can-shu-shuo-ming" id="xin-zeng-jia-cess-lian-jie-dian-can-shu-shuo-ming"></a>

点击cess链节点菜单，新增链节点

* 部署目录

部署目录是存储链节点数据的空间，前期保留500G够用

* P2P端口

P2P端口用户和其他用户链的通信，建议映射到公网保持链稳定

* RPC端口

提供给存储节点链接使用

* 容器名称

默认保持cess-chain就行

* 镜像

创建docker容器使用的镜像

* 是否强制

防止这台机器部署过，存在相同的目录，可以执行强制删除
