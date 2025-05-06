# Glacie - BDS跨版本协议兼容

[![English](https://img.shields.io/badge/English-informational?style=for-the-badge)](README.md)
![简体中文](https://img.shields.io/badge/简体中文-inactive?style=for-the-badge)

[![642538983](https://img.shields.io/badge/642538983-pink?style=for-the-badge&logo=qq)](https://qm.qq.com/q/1yn1ZHEoyY)
[![Discord](https://img.shields.io/discord/1346034987136192523?style=for-the-badge&logo=discord)](https://discord.gg/7uJNS3tNa6)

[![Latest Tag](https://img.shields.io/github/v/tag/GlacieTeam/Glacie?label=Latest%20Tag&style=for-the-badge)](https://github.com/GlacieTeam/Glacie/releases)
[![Stars](https://img.shields.io/github/stars/GlacieTeam/Glacie.svg?style=for-the-badge)](https://github.com/GlacieTeam/Glacie/stargazers)  
[![Downloads](https://img.shields.io/github/downloads/GlacieTeam/Glacie/total?style=for-the-badge&color=%2300ff00)](https://github.com/GlacieTeam/Glacie/releases)
[![Issues](https://img.shields.io/github/issues/GlacieTeam/Glacie.svg?style=for-the-badge)](https://github.com/GlacieTeam/Glacie/issues)

# 什么是Glacie？
Glacie是一个Mod，让玩家可无缝连接到与客户端版本不同的服务器，无需担心版本不匹配导致的无法加入问题。

Glacie实际上是一个翻译器，试图通过翻译不同版本之间的数据包差异，来允许不同版本的玩家进入服务器。

# 服务端模组加载器
- 截至目前，我们支持 [**LeviLamina**](https://github.com/LiteLDev/LeviLamina) 和 [**Endstone**](https://github.com/EndstoneMC/endstone) 模组加载器
- 如果你不知道选哪一个，我们推荐使用 [**LeviLamina**](https://github.com/LiteLDev/LeviLamina)


# 安装
## LeviLamina
- Lip
```bash
lip install github.com/GlacieTeam/Glacie
```
## Endstone
- 从release下载最新版本并解压压缩包，将 `Glacie.dll` 放入插件文件夹里面。

## 客户端
- 从release下载最新版本并解压压缩包，运行 `LaunchMinecraft.bat` 注入 `Glacie.dll` 至客户端。

# 注意事项
- 如果你正在使用 [**Endstone**](https://github.com/EndstoneMC/endstone) 加载器，请不在在服务器上安装任何 Addon。 Addons 和 Glacie 在 [**Endstone**](https://github.com/EndstoneMC/endstone) 平台上并不兼容，同时使用会出现问题。
- 如果你正在使用 [**Endstone**](https://github.com/EndstoneMC/endstone) 加载器，你需要手动在 `server.properties` 里面设置 `block-network-ids-are-hashes=true` (默认值是 `true`)，否则来自其他版本的玩家看不见任何方块。
> 我们强烈推荐使用 [**LeviLamina**](https://github.com/LiteLDev/LeviLamina) 加载器。

# 支持的客户端
| Minecraft 版本    | 协议版本          | 当前支持情况        | 计划支持情况 |
| ----------------- | ---------------- | ------------------ | ----------- |
| <= 1.21.4x        | <= 748           | :x:                | 无计划支持   |
| 1.21.50/51        | 766              | :white_check_mark: | 已经支持     |
| 1.21.60/61/62     | 776              | :white_check_mark: | 已经支持     |
| 1.21.70/71/72/73  | 786              | :white_check_mark: | 已经支持     |
| 1.21.80           | 800              | :white_check_mark: | 已经支持     |
| 1.21.90           | 未知             | :x:                | 即将支持     |

# 本地化翻译
你可以帮助我们改进翻译

# 交流 & 提问
- 加入我们的 [Discord](https://discord.gg/7uJNS3tNa6) 社区：https://discord.gg/7uJNS3tNa6
- 加入我们的 [QQ交流群](https://qm.qq.com/q/1yn1ZHEoyY): 642538983

# 反馈
- 请通过 [提交Issue](https://github.com/GlacieTeam/Glacie/issues) 来反馈bug

# 许可
- [GitHub Release](https://github.com/GlacieTeam/Glacie/releases) 是唯一官方下载源。其它任何下载源都是未经授权的非法转载。
- 未经许可，严禁任何转载、整合和二次分发。

## 版权所有 © 2025 GlacieTeam, 保留所有权利.
