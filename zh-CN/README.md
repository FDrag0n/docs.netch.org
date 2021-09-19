<!-- README.md -->

<p align="center"><img src="https://github.com/netchx/netch/blob/master/Netch/Resources/Netch.png?raw=true" width="128" /></p>

<div align="center">

# Netch
简单的代理客户端

[![](https://img.shields.io/badge/telegram-group-green?style=flat-square)](https://t.me/netch_group)
[![](https://img.shields.io/badge/telegram-channel-blue?style=flat-square)](https://t.me/netch_channel)
[![](https://img.shields.io/github/downloads/netchx/netch/total.svg?style=flat-square)](https://github.com/netchx/netch/releases)
[![](https://img.shields.io/github/v/release/netchx/netch?style=flat-square)](https://github.com/netchx/netch/releases)
</div>

## 特性
有些功能没有在 1.0 版本中实现

### 模式
- `ProcessMode` - 使用 Netfilter 过滤进程流量
- `ShareMode` - 使用 WinPcap / Npcap 共享代理给局域网设备
- `TunMode` - 基于 WinTUN 驱动的 TUN/TAP 网络代理
- `WebMode` - 网页代理模式

### 协议
- [`Socks5`](https://www.wikiwand.com/en/SOCKS)
- [`Shadowsocks`](https://github.com/shadowsocks/shadowsocks-libev)
- [`ShadowsocksR`](https://github.com/shadowsocksrr/shadowsocksr-libev)
- [`Trojan`](https://github.com/p4gefau1t/trojan-go)
- [`VMess`](https://github.com/v2fly/v2ray-core)
- [`VLess`](https://github.com/xtls/xray-core)

### 其他
- UDP NAT FullCone (受限于你的服务器)
- .NET 5.0 x64

## 捐赠
- `XMR` `48ju3ELNZEa6wwPBMexCJ9G218BGY2XwhH6B6bmkFuJ3QgM4hPw2Pra35jPtuBZSc7SLNWeBpiWJZWjQeMAiLnTx2tH2Efx`
- `ETH` `0x23dac0a93bcd71fec7a95833ad030338f167f185`

## 赞助商
<a href="https://www.jetbrains.com/?from=Netch"><img src="https://raw.githubusercontent.com/netchx/netch/main/jetbrains.svg" alt="JetBrains" width="200"/></a>

- [NeroCloud](https://nerocloud.io)

## 许可证
```
The MIT License (MIT)

Copyright (c) 2019 Netch

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
