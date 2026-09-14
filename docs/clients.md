# VPN 客户端指南：Clash、Shadowrocket、sing-box、v2rayN

VPN 或代理服务真正落地到设备上，通常需要通过客户端完成配置、订阅导入、代理模式、规则和网络权限管理。不同客户端支持的平台、协议和配置格式并不相同，因此选择客户端时应先确定设备和实际需求。

## 按平台选择客户端

| 平台 | 常见客户端 | 适合关注 |
| --- | --- | --- |
| Windows | Clash Verge Rev、v2rayN、sing-box | 规则、TUN、系统代理、订阅 |
| macOS | Clash Verge Rev、V2rayU、sing-box、Surge | 系统代理、规则、DNS、TUN |
| Linux | sing-box、Clash 系客户端 | 路由、DNS、命令行与系统服务 |
| iPhone / iPad | Shadowrocket、Quantumult X、Surge、sing-box | 订阅、策略组、按需连接 |
| Android | Clash Meta、NekoBox、V2rayNG、sing-box | VPN 权限、后台运行、电池优化 |

## Clash / Clash Meta / Clash Verge Rev

Clash 生态常见于需要规则分流、策略组和订阅管理的场景。不同项目并不是同一个客户端：Clash Verge Rev、Clash Meta 及其他 Clash 系客户端在平台、内核和配置支持方面存在差异。

适合关注：

- YAML 配置和订阅格式
- 规则集与策略组
- TUN 模式
- 系统代理
- DNS 设置

## Shadowrocket

Shadowrocket 是 iPhone / iPad 上常见的网络工具，适合需要订阅导入、规则和策略组管理的用户。具体协议和配置支持以当前版本为准。

使用时可以重点检查：

- 订阅是否能够正常更新
- 代理规则是否匹配
- 系统 VPN 权限是否正常
- DNS 是否符合预期

## sing-box

sing-box 是跨平台网络工具，适合需要更灵活配置、不同协议组合或跨设备使用的场景。Windows、macOS、Linux、Android 和 iOS 均存在相应客户端或集成方案，但具体功能随项目版本变化。

## v2rayN

v2rayN 是 Windows 平台常见的图形化客户端，适合使用相应配置格式并希望通过桌面界面管理节点、订阅和代理设置的用户。

## V2rayU

V2rayU 是 macOS 平台常见客户端之一。使用前应确认当前版本支持的配置格式以及系统版本兼容性。

## V2rayNG

V2rayNG 是 Android 平台常见客户端。Android 厂商的后台限制、电池优化和 VPN 权限可能影响实际连接，需要结合系统设置检查。

## NekoBox

NekoBox 是 Android 平台常见的网络客户端之一。具体协议、配置格式和内核能力应以当前版本文档为准。

## Surge

Surge 支持 Apple 平台上的网络代理、规则和策略管理。它的配置体系与 Clash 系客户端并不完全相同，导入配置前应确认格式是否匹配。

## Quantumult X

Quantumult X 是 iPhone / iPad 上常见的网络工具，支持规则、策略和网络配置。具体配置语法和功能以当前版本说明为准。

## 客户端选择思路

不要只根据“哪个客户端最好”来选择。更实用的判断方式是：

1. **先看平台**：Windows、macOS、iOS、Android 和 Linux 的系统机制不同。
2. **再看配置格式**：确认订阅或配置是否被客户端支持。
3. **再看功能**：是否需要规则分流、TUN、策略组、DNS 控制等。
4. **最后看维护状态**：第三方客户端更新速度和系统兼容性会变化。

相关资料：[平台与客户端](./platforms.md) · [代理与网络协议](./protocols.md) · [故障排查](./troubleshooting.md)

客户端属于第三方项目，本仓库仅整理选择和使用思路，不代表对第三方软件提供维护或技术担保。