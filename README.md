# ChnProxyRule List

**"Together WE MAKE CHINESE ONLINE SERVICES GREAT AGAIN!"**

## Introduction 简介

本项目灵感和大部分数据源来自[Unblock-Youku](https://github.com/uku/Unblock-Youku/blob/master/shared/urls.js)。某些商业网络环境下（比如我们学校）改DNS不能上网，也不能用HTTP代理，所以想了个办法利用Unblock-Youku项目的数据做了个Autoproxy List，可供某些[Shadowsocks](https://github.com/shadowsocks)客户端和SwitchOmega使用，从而解决国外IP服务限制问题。

This is a project inspired and forked from [Unblock-Youku](https://github.com/uku/Unblock-Youku/blob/master/shared/urls.js). Since some enterprise networks do not allow using 3rd-party DNS servers or HTTP proxies (e.g. our University) while they do allow some encrypted SOCKS proxy connections. So I can use this list with Shadowsocks (proxying back to China) as an alternative choice for the original Unblock-Youku project.

Basically I just copy all their rules and change it to Adblock Plus Filter list format. It should works with some proxies software like [Shadowsocks](https://github.com/shadowsocks) or SwitchyOmega in Chrome.

## Usage 使用方法

将此Autoproxy List地址填入您的代理软件中：

```
https://raw.githubusercontent.com/huming2207/ChnProxyRoute/master/ChnList.txt
```

如果您的代理软件（如SwitcyOmega）不支持Base64编码的Autoproxy List，可以尝试常规编码的文件。地址如下：

```
https://raw.githubusercontent.com/huming2207/ChnProxyRoute/master/ChnList-Raw.txt
```

## Special thanks to 特别感谢

- [Unblock-Youku](https://github.com/uku/Unblock-Youku)

