# AutoBuildImmortalWrt
[![GitHub](https://img.shields.io/github/license/wukongdaily/AutoBuildImmortalWrt.svg?label=LICENSE&logo=github&logoColor=%20)](https://github.com/wukongdaily/AutoBuildImmortalWrt/blob/master/LICENSE)
![GitHub Stars](https://img.shields.io/github/stars/wukongdaily/AutoBuildImmortalWrt.svg?style=flat&logo=appveyor&label=Stars&logo=github)
![GitHub Forks](https://img.shields.io/github/forks/wukongdaily/AutoBuildImmortalWrt.svg?style=flat&logo=appveyor&label=Forks&logo=github) [![Github](https://img.shields.io/badge/RELEASE:AutoBuildImmortalWrt-123456?logo=github&logoColor=fff&labelColor=green&style=flat)](https://github.com/wukongdaily/AutoBuildImmortalWrt/releases) [![Bilibili](https://img.shields.io/badge/Bilibili-123456?logo=bilibili&logoColor=fff&labelColor=fb7299)](https://www.bilibili.com/video/BV1EG6VYCER3) [![操作步骤](https://img.shields.io/badge/YouTube-123456?logo=youtube&labelColor=ff0000)](https://youtu.be/xIVtUwZR6U0)

## 🤔 这是什么？
它是一个工作流。可快速构建 带docker且支持自定义固件大小的 immortalWrt
> 1、支持自定义固件大小 默认1GB <br>
> 2、支持预安装docker（可选）<br>
> 3、支持x86-64<br>
> 4、新增用户预设置pppoe拨号功能<br>
## 如何查询都有哪些插件?
https://mirrors.sjtug.sjtu.edu.cn/immortalwrt/releases/23.05.4/packages/x86_64/luci/ 

## 该固件默认属性？(必读)
- 该固件刷入单网口设备默认采用DHCP模式,自动获得ip。类似NAS的做法
- 该固件刷入多网口设备默认WAN口采用DHCP模式，LAN 口ip为 192.168.1.1
- 综合上述特点，单网口应该先接路由器，先在路由器查看一下它的ip 再访问。
- 上述特点 你都可以通过 `99-custom.sh` 配置和调整

## ❤️其它GitHub Action项目推荐🌟 （建议收藏）⬇️
https://github.com/wukongdaily/RunFilesBuilder<br>
https://github.com/wukongdaily/DockerTarBuilder

## ❤️如何构建docker版ImmortalWrt（建议收藏）⬇️
https://wkdaily.cpolar.top/15
# 🌟鸣谢
### https://github.com/immortalwrt
