# LightWeight Linux For Rulex Gateway
## 简介
该项目是未来准备给RULEX网关使用的Linux系统，当前版本仅支持ARM64.

## 硬件
目前支持的硬件：
1. 全志A53\A63系列
2. 树莓派64位版本（建议用3B以后的版本)

## 环境
开发环境建议使用ubuntu-20-04，或者使用国产的深度Linux（目前我在用，体验还可以），下面两个关键工具网上一堆教程，这里就不写了：

1. buildroot
2. busybox
> 上述工具全部是最新版（截至 2022年 10月 06日 星期四)

另外还有一些其他工具：
```sh
sudo apt install gcc build-essential bison flex gettext tcl sharutils libncurses-dev zlib1g-dev exuberant-ctags g++ texinfo patch vim libtool bc git jq cloc htop

```
## 计划
未来的计划是基于全志架构，实现一套边缘网关，主要用于智慧楼宇、工控采集等。