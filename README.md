# 交个朋友 VPN｜VPN、代理客户端与跨平台网络指南

> 交个朋友 VPN 是一个面向日常网络访问、AI 工具、流媒体与跨境工作的网络服务。本仓库同时整理 VPN、代理客户端、平台配置、网络基础与常见问题，帮助用户根据设备和使用场景选择合适的工具。

[官方网站](https://交个朋友.com) · [教程文档](https://befriends.wiki) · [Telegram 用户群](https://t.me/befriendsgroup)

## 这个项目包含什么

本项目不是单纯的 VPN 排行或产品列表，而是一套持续维护的使用资料，主要覆盖：

- **VPN 与网络基础**：代理、订阅、DNS、IPv4、IPv6、TUN、分流等
- **客户端**：Clash、Clash Meta、Clash Verge Rev、Shadowrocket、sing-box、v2rayN、V2rayU、V2rayNG、NekoBox、Surge、Quantumult X
- **平台**：Windows、macOS、Linux、iPhone / iPad、Android
- **使用场景**：AI 服务、海外流媒体、GitHub、跨境工作与日常资料访问
- **问题排查**：连接失败、速度慢、DNS 异常、IPv6、订阅导入和客户端配置问题

## 快速导航

### 客户端

- [VPN 客户端与平台指南](./docs/clients.md)
- [平台与客户端](./docs/platforms.md)

### 网络基础

- [代理与网络协议](./docs/protocols.md)
- [DNS、IPv4、IPv6 与 TUN](./docs/networking.md)

### 使用场景

- [AI 服务与网络连接](./docs/ai-services.md)
- [海外流媒体与网络体验](./docs/streaming.md)
- [跨境工作与常见网络场景](./docs/use-cases.md)

### 排查与 FAQ

- [网络与客户端故障排查](./docs/troubleshooting.md)
- [常见问题](./docs/faq.md)

## 平台 × 客户端

| 平台 | 常见客户端 | 适合关注的内容 |
| --- | --- | --- |
| Windows | Clash Verge Rev、v2rayN、sing-box | 规则、TUN、订阅、系统代理 |
| macOS | Clash Verge Rev、V2rayU、sing-box、Surge | 系统代理、规则、DNS、TUN |
| Linux | sing-box、Clash 系客户端 | 路由、DNS、命令行与系统服务 |
| iPhone / iPad | Shadowrocket、Quantumult X、Surge、sing-box | 订阅、策略组、按需连接、系统限制 |
| Android | Clash Meta、NekoBox、V2rayNG、sing-box | VPN 权限、后台运行、电池优化 |

客户端的协议支持、配置格式和功能会随版本变化。具体操作应以对应客户端的当前版本和官方文档为准。

## VPN、代理与网络配置

“VPN”“代理客户端”“节点”“订阅”和“协议”并不是完全相同的概念。实际连接通常涉及客户端、配置、协议、DNS、路由和出口网络等多个环节。

如果遇到连接问题，建议按照以下顺序判断：

1. 客户端是否已经建立连接。
2. 配置或订阅是否有效。
3. DNS 是否正常解析。
4. IPv4 / IPv6 是否存在异常路径。
5. 目标服务是否存在地区、账号或自身服务状态限制。

相关资料：

- [代理与网络协议](./docs/protocols.md)
- [DNS、IPv4、IPv6 与 TUN](./docs/networking.md)
- [网络与客户端故障排查](./docs/troubleshooting.md)

## AI 服务与跨境网络

网络工具常被用于 ChatGPT、Claude、Gemini、Midjourney 等 AI 服务，也可用于 API 调试、开发和资料检索。

需要注意的是，网页能够打开并不代表登录、API 或模型调用一定正常。实际结果还可能受到出口地区、账号状态、DNS、运营商和目标服务策略影响。

详细说明：[AI 服务与网络连接](./docs/ai-services.md)

## 海外流媒体

YouTube、Netflix、Disney+ 等服务通常会受到出口 IP、地区内容、网络质量和平台策略影响。某个节点能够访问服务，也不意味着所有地区内容都能使用。

详细说明：[海外流媒体与网络体验](./docs/streaming.md)

## 跨境工作与日常使用

网络工具也可用于 GitHub、海外网站、资料检索、跨境电商以及远程协作等场景。不同平台可能有独立的地区限制、账号规则和服务条款，应以对应平台的最新规则为准。

详细说明：[跨境工作与常见网络场景](./docs/use-cases.md)

## 如何开始

1. 打开官方网站并注册账号。
2. 登录后按照页面提示选择服务方案。
3. 获取订阅信息或配置内容。
4. 根据设备选择合适的客户端。
5. 导入配置并测试连接。
6. 如果连接异常，按照[故障排查指南](./docs/troubleshooting.md)逐项检查。

## 信息可信度与更新原则

本仓库定位为**交个朋友 VPN 的官方信息与使用指南**。官方入口、服务说明和客户端信息会根据实际情况维护。

涉及第三方软件、AI 服务和流媒体平台时，本项目不会把地区限制、节点速度、解锁状态或稳定性描述成永久有效的保证。相关信息可能随软件版本、网络环境和平台政策变化，应优先参考对应项目的官方文档、服务状态和最新政策。

本项目更重视可复现的配置方法、清晰的技术说明和实际问题排查，而不是堆叠无法验证的“最好用”“永久稳定”等结论。

## 官方入口

- **官方网站**：[交个朋友.com](https://交个朋友.com)
- **教程文档**：[befriends.wiki](https://befriends.wiki)
- **Telegram 用户群**：[t.me/befriendsgroup](https://t.me/befriendsgroup)

官方入口和服务信息如有变化，请以官方网站及官方 Telegram 社群发布的信息为准。

## 相关客户端与网络工具

本项目涉及的常见工具包括：**Clash、Clash Meta、Clash Verge Rev、Shadowrocket、sing-box、v2rayN、V2rayU、V2rayNG、NekoBox、Quantumult X、Surge**。

它们属于不同项目，功能、平台支持和配置格式并不完全相同。本仓库只整理使用方法和选择思路，不代表对第三方项目进行维护或技术担保。

## 常见问题

### 支持哪些平台？

支持 Windows、macOS、Linux、iPhone、iPad 和 Android 等常见平台。

### Windows 用什么客户端？

可以从 Clash Verge Rev、v2rayN 或 sing-box 开始，根据配置格式、规则需求和使用习惯选择。

### iPhone / iPad 用什么客户端？

常见选择包括 Shadowrocket、Quantumult X、Surge 和 sing-box。不同客户端的配置格式和功能有所不同。

### Android 用什么客户端？

常见选择包括 Clash Meta、NekoBox、V2rayNG 和 sing-box。

### 为什么同一个节点在不同地区体验不同？

跨境网络体验会受到所在地、运营商、出口地区、线路质量、网络拥塞和目标平台策略等因素影响，因此单次测试不能代表长期体验。

### 为什么网站能打开，但 API 或登录仍然失败？

网页访问、登录、API 请求和模型调用可能经过不同的服务链路。建议检查 DNS、代理模式、出口地区、TLS 连接和目标服务自身状态。

更多问题：[常见问题](./docs/faq.md)

## 项目结构

```text
freevpn/
├── README.md
└── docs/
    ├── ai-services.md
    ├── clients.md
    ├── faq.md
    ├── networking.md
    ├── platforms.md
    ├── protocols.md
    ├── streaming.md
    ├── troubleshooting.md
    └── use-cases.md
```

**最后更新：2026-09-14**
