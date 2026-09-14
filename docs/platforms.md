# VPN 平台与客户端指南：Windows、macOS、Linux、iPhone、Android

同一个 VPN 或代理配置，在不同平台上的使用方式可能完全不同。选择客户端时，应先确认设备系统，再确认配置格式、协议支持和需要的网络功能。

## Windows

常见选择：Clash Verge Rev、v2rayN、sing-box。

- **Clash Verge Rev**：适合习惯规则、策略组和 Clash 配置的用户。
- **v2rayN**：Windows 平台常见的图形化客户端，适合管理节点和相应配置。
- **sing-box**：适合希望在多个平台使用相近配置体系的用户。

重点关注：系统代理、TUN、DNS、规则和订阅格式。

## macOS

常见选择：Clash Verge Rev、V2rayU、sing-box、Surge。

macOS 的系统代理机制、网络权限和 DNS 设置与 Windows 不完全相同。遇到浏览器正常、其他程序不走代理的情况，需要区分系统代理和应用自身的网络配置。

## Linux

常见选择：sing-box 以及支持相应配置格式的 Clash 系客户端。

Linux 环境通常需要结合发行版、桌面环境、systemd、路由表和 DNS 配置进行判断。

## iPhone / iPad

常见选择：Shadowrocket、Quantumult X、Surge、sing-box。

iOS 对 VPN 权限、后台运行和系统网络扩展有自己的限制。配置导入后如果表现异常，应同时检查订阅格式、VPN 权限和当前网络环境。

## Android

常见选择：Clash Meta、NekoBox、V2rayNG、sing-box。

Android 不同厂商可能对后台运行、电池优化和 VPN 权限进行额外限制。如果连接一段时间后自动断开，应检查系统的电池和后台策略。

## 快速选择

| 设备 | 优先参考 | 重点问题 |
| --- | --- | --- |
| Windows | Clash Verge Rev / v2rayN / sing-box | TUN、规则、系统代理 |
| macOS | Clash Verge Rev / V2rayU / sing-box / Surge | DNS、系统代理、TUN |
| Linux | sing-box / Clash 系客户端 | 路由、DNS、systemd |
| iPhone / iPad | Shadowrocket / Quantumult X / Surge / sing-box | VPN 权限、订阅、策略 |
| Android | Clash Meta / NekoBox / V2rayNG / sing-box | 后台运行、电池优化 |

相关资料：[客户端指南](./clients.md) · [代理与网络协议](./protocols.md) · [网络排查](./troubleshooting.md)

客户端名称仅表示常见选择，不代表本项目对第三方软件提供维护或技术担保。