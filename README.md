# OpenWrt for Pi 4B

[![Stars](https://img.shields.io/github/stars/iamNCJ/Openwrt-Pi4.svg?label=Stars&style=social)](https://github.com/iamNCJ/Openwrt-Pi4/stargazers) [![Forks](https://img.shields.io/github/forks/iamNCJ/Openwrt-Pi4.svg?label=Fork&style=social)](https://github.com/iamNCJ/Openwrt-Pi4/network/members)

# 使用方法

前往[Release](https://github.com/iamNCJ/Openwrt-Pi4/releases)下载最新镜像刷入即可。刷入后最好手动扩容来利用全部的磁盘空间。

# 特性

- 针对树莓派4进行性能调优
- 精简系统，极致性能
- 虚拟化支持 (Docker)
- L2TP VPN拨号支持
- DoH支持
- SS obfs插件支持

---

## Usage

Go to [Release](https://github.com/iamNCJ/Openwrt-Pi4/releases) to download images and flash into a sd card.

> Note: You'd better resize your rootfs to make full use of your sd card.

## Features

- Thx to [P3TERX's repo](https://github.com/P3TERX/Actions-OpenWrt)
- Built using GitHub Actions
- Tuned for Better Performance on Raspberry Pi 4
- Simplified System
- Added Support for L2TP
- Enabled Virtulization Support for LXC & Docker
- Enabled MJPG-Streamer with v4l2 usb cameras
- Enabled obfs Plugin for SS

## Known Issue

- Wireless AP not functioning, probably due to upper source's problem

## Acknowledgments

- [P3TERX](https://github.com/P3TERX)
- [Microsoft](https://www.microsoft.com)
- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub](https://github.com)
- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [mxschmitt/action-tmate](https://github.com/mxschmitt/action-tmate)
- [csexton/debugger-action](https://github.com/csexton/debugger-action)
- [Cisco](https://www.cisco.com/)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)

## License

[MIT](https://github.com/iamNCJ/Openwrt-Pi4/blob/master/LICENSE) © NCJ
