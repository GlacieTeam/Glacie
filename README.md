# Glacie - BDS Cross-Version Protocol Compatibility

![English](https://img.shields.io/badge/English-inactive?style=for-the-badge)
[![简体中文](https://img.shields.io/badge/简体中文-informational?style=for-the-badge)](README.zh.md)

[![QQ](https://img.shields.io/badge/642538983-pink?style=for-the-badge&logo=qq)](https://qm.qq.com/q/1yn1ZHEoyY)
[![Discord](https://img.shields.io/discord/1346034987136192523?style=for-the-badge&logo=discord)](https://discord.gg/7uJNS3tNa6)

[![Latest Tag](https://img.shields.io/github/v/tag/GlacieTeam/Glacie?label=Latest%20Tag&style=for-the-badge)](https://github.com/GlacieTeam/Glacie/releases)
[![Stars](https://img.shields.io/github/stars/GlacieTeam/Glacie.svg?style=for-the-badge)](https://github.com/GlacieTeam/Glacie/stargazers)  
[![Downloads](https://img.shields.io/github/downloads/GlacieTeam/Glacie/total?style=for-the-badge&color=%2300ff00)](https://github.com/GlacieTeam/Glacie/releases)
[![Issues](https://img.shields.io/github/issues/GlacieTeam/Glacie.svg?style=for-the-badge)](https://github.com/GlacieTeam/Glacie/issues)

# What is Glacie?
Glacie is a server-side mod that allows players to seamlessly connect to servers running a different version from their client-eliminating issues where version mismatches would normally prevent joining.

In essence, Glacie acts as a translator by converting differences in data packets between various versions, enabling players on different versions to connect to the server.

# Mod Loader
- Currently, we support [**LeviLamina**](https://github.com/LiteLDev/LeviLamina) and [**Endstone**](https://github.com/EndstoneMC/endstone) mod loader.
- If you don't know which one to choose, [**LeviLamina**](https://github.com/LiteLDev/LeviLamina) is recommended.

# Installation
## LeviLamina
- Lip
```bash
lip install github.com/GlacieTeam/Glacie
```
## Endstone
- Download the release and unzip the zip package, then put the `Glacie.dll` into the plugins folder

# Precautions
- If you are using [**Endstone**](https://github.com/EndstoneMC/endstone) mod loader, do not install any addon on your server. Addons and Glacie are not compatible on [**Endstone**](https://github.com/EndstoneMC/endstone) mod loader, and there will be problems when used at the same time.
- If you are using [**Endstone**](https://github.com/EndstoneMC/endstone) mod loader, you must set `block-network-ids-are-hashes=true` in `server.properties` manually (the default value is `true`), otherwise players from different versions will not be able to see any blocks.
> We highly recommend using [**LeviLamina**](https://github.com/LiteLDev/LeviLamina) mod loader instead.

# Supported Clients
| Minecraft Version | Protocol Version | Support Status     | Support Planned    |
| ----------------- | ---------------- | ------------------ | ------------------ |
| <= 1.21.4x        | <= 748           | :x:                | No Plan to Support |
| 1.21.50/51        | 766              | :white_check_mark: | Already Supported  |
| 1.21.60/61/62     | 776              | :white_check_mark: | Already Supported  |
| 1.21.70           | 786              | :white_check_mark: | Already Supported  |
| 1.21.80           | unknown          | :x:                | Upcoming Support   |

# Communication & FAQ
- Join our [Discord](https://discord.gg/7uJNS3tNa6) community: https://discord.gg/7uJNS3tNa6
- Join our [QQ Group](https://qm.qq.com/q/1yn1ZHEoyY): 642538983

# Feedback
- [Open an issue](https://github.com/GlacieTeam/Glacie/issues) to report bugs.

# License
- [GitHub Release](https://github.com/GlacieTeam/Glacie/releases) is the sole and exclusive official source for downloading. Any other source of download is unauthorized and constitutes illegal reproduction. 
- Unauthorized reproduction, integration, or redistribution is strictly prohibited.

## Copyright © 2025 GlacieTeam. All rights reserved.
