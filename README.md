# Magisk on WSA Weekly Build

## 介绍

不会用Actions又或者没有耐心？没问题！我提供了MagiskOnWSA的每周构建，保证随时都有新版本！

## 如何使用？

下载很简单！你只需在右下角的Release点击一下，看到了那个WSA-with-magisk-GApps-pico_xxx.zip了吗？点下去！下载完成后，只需要解压到一个空间足够的地方，然后运行里面的Install.ps1，就可以了！就是这么方便！

## 显示“在此系统上禁止运行脚本”

在管理员权限的PowerShell里输入set-executionpolicy remotesigned并回车。

## 发布的配置是什么？

默认为64位x86正式版，移除亚马逊应用商店，Pico版Gapps，使用稳定版Magisk。

## 致谢

- [LSPosed](https://github.com/LSPosed/): MagiskOnWSA作者
- [StoreLib](https://github.com/StoreDev/StoreLib): 下载WSA使用的API作者
- [Magisk](https://github.com/topjohnwu/Magisk): Magisk项目仓库
- [The Open GApps Project](https://opengapps.org): Gapps来源
- [WSA-Kernel-SU](https://github.com/LSPosed/WSA-Kernel-SU): 安装Magisk方案的仓库
- [WSAGAScript](https://github.com/ADeltaX/WSAGAScript): 整合Gapps方案的仓库
- [ChatGPT](https://chat.openai.com/): Bug查找
