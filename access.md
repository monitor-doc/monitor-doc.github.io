---
description: 介绍接入寻链云监控的接入操作
---

# 开始接入

### 1.打开寻链云监控网址：[https://monitor.xunlian.co/](https://monitor-magua.xunlian.co/)

### 2.注册登录。目前支持微信扫码注册和登录，登录后可绑定手机号和设置登录密码，绑定手机号后并设置登录密码后也可通过手机号密码登录。

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

### 3.打开“设备”菜单，点击“添加设备”，“复制”监控安装命令。

<div data-full-width="false">

<figure><img src=".gitbook/assets/image (2).png" alt=""><figcaption></figcaption></figure>

</div>

### 4.进入设备操作系统，[切换到root权限](qa/command.md#qie-huan-dao-root-quan-xian)。

```
sudo -i
然后输入当前用户密码
```

### 5.粘贴命令执行。

```
bash <(curl https://monitor.xunlian.co/api/install/唯一识别码)
```

PS：上面命令是个参考，每个用户的命令是不一样的。

### 6.看到如下结果即为安装成功。

安装成功截图

<figure><img src=".gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

安装失败截图



常见安装失败的原因。

* 没有使用root用户执行
* 网络不通

PS：内测阶段一个账号限制安装5台设备。如需安装更多设备，请[联系我们](qa/contactus.md)。

