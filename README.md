# 交个朋友 VPN｜2026 VPN、Clash、Shadowrocket、sing-box、v2rayN 使用指南

> 交个朋友 VPN 是面向 Windows、macOS、Linux、iPhone、iPad 和 Android 用户的网络服务与使用指南，围绕 VPN、代理客户端、订阅配置、AI 服务、流媒体和跨境网络使用场景整理实用资料。
>
> **交个朋友 VPN，永久免费。**

[官方网站](https://交个朋友.com) · [教程文档](https://befriends.wiki) · [Telegram 用户群](https://t.me/befriendsgroup)

## 交个朋友 VPN 是什么？

交个朋友 VPN 是一个面向日常网络访问和跨平台使用的 VPN 服务，同时提供客户端、订阅配置和网络问题排查相关资料。

与只提供一个连接入口的 VPN 服务不同，实际使用通常还涉及客户端、订阅、代理协议、DNS、路由、TUN 模式以及设备系统权限。因此，这个仓库除了介绍交个朋友 VPN，也整理常见客户端和网络配置方法，方便不同设备的用户快速找到对应资料。

目前常见的使用组合包括：

- **Windows**：Clash Verge Rev、v2rayN、sing-box
- **macOS**：Clash Verge Rev、V2rayU、sing-box、Surge
- **Linux**：sing-box、Clash 系客户端
- **iPhone / iPad**：Shadowrocket、Quantumult X、Surge、sing-box
- **Android**：Clash Meta、NekoBox、V2rayNG、sing-box

客户端并不是 VPN 服务本身。Clash、Shadowrocket、sing-box、v2rayN 等属于第三方客户端，具体功能、配置格式和平台支持应以各项目当前版本为准。

## 快速开始

如果你只是希望开始使用交个朋友 VPN，可以按照下面的流程：

1. 打开[官方网站](https://交个朋友.com)。
2. 注册并登录账号。
3. 按页面说明获取订阅或配置内容。
4. 根据自己的设备选择客户端。
5. 将订阅导入客户端。
6. 建立连接后测试网页、AI 服务或其他目标服务。
7. 如果出现连接、DNS、速度或订阅问题，再根据对应平台的排查指南处理。

教程资料：[交个朋友 VPN 使用文档](https://befriends.wiki)

---

## Windows VPN：Clash、v2rayN、sing-box

Windows 用户通常会接触 Clash Verge Rev、v2rayN 和 sing-box。

### Clash Verge Rev

Clash Verge Rev 是 Windows 上常见的 Clash 系客户端之一，适合使用订阅、规则和 TUN 模式的用户。

如果你的订阅提供 Clash / Mihomo 兼容配置，可以在客户端中导入订阅，再根据需要启用系统代理或 TUN 模式。

### v2rayN

v2rayN 是 Windows 平台常见的代理客户端，适用于 V2Ray/Xray 等生态中的多种配置方式。不同版本对协议和配置格式的支持可能存在差异。

### sing-box

sing-box 是跨平台网络代理工具，在 Windows、macOS、Linux、Android 和 iOS 等平台均有相关应用或集成方案。对于希望使用较新协议和统一配置体系的用户，可以查看对应版本文档。

更多内容：[Windows VPN 与客户端指南](./docs/clients.md)

## macOS VPN：Clash Verge Rev、V2rayU、sing-box、Surge

macOS 用户可以根据订阅格式和自己的使用习惯选择客户端。

常见选择包括：

- Clash Verge Rev
- V2rayU
- sing-box
- Surge

macOS 上除了客户端本身，还需要关注系统代理、DNS、规则以及 TUN / 网络扩展权限。某些客户端升级后配置方式可能发生变化，因此遇到问题时应优先查看当前版本说明。

## iPhone / iPad VPN：Shadowrocket、Quantumult X、Surge、sing-box

iOS 和 iPadOS 的网络工具与 Windows、macOS 的使用方式有所不同。

常见客户端包括：

- **Shadowrocket**：适合导入代理订阅并使用策略组、规则等功能。
- **Quantumult X**：支持较丰富的规则、策略和网络配置。
- **Surge**：面向高级用户，提供较完整的网络调试和规则能力。
- **sing-box**：适合希望使用 sing-box 配置体系的用户。

实际支持的订阅格式、节点协议和功能取决于客户端当前版本。

如果只是希望把交个朋友 VPN 的订阅用于 iPhone 或 iPad，先确认订阅格式与客户端兼容，再进行导入即可。

## Android VPN：Clash Meta、NekoBox、V2rayNG、sing-box

Android 平台常见客户端包括 Clash Meta、NekoBox、V2rayNG 和 sing-box。

Android 使用代理工具时，除了订阅和协议，还需要注意 VPN 权限、后台运行、电池优化以及系统厂商的后台限制。部分手机系统可能主动结束后台网络服务。

如果出现连接一段时间后自动断开，可以重点检查系统的电池优化和后台活动权限。

## Linux VPN：sing-box 与代理客户端

Linux 用户通常更关注路由、DNS、TUN、系统服务以及命令行配置。

sing-box 在 Linux 环境中的使用方式与桌面客户端有所不同。如果将代理配置作为系统服务运行，还需要同时检查服务状态、路由规则、DNS 和防火墙设置。

更多网络基础资料：[DNS、IPv4、IPv6 与 TUN](./docs/networking.md)

---

## Clash、Shadowrocket、sing-box、v2rayN 有什么区别？

这些名称经常一起出现在 VPN、代理订阅和网络配置教程中，但它们并不是同一种东西。

| 工具 | 常见平台 | 主要用途 |
| --- | --- | --- |
| Clash / Clash Meta | Windows、macOS、Android 等 | 订阅、规则、策略组、代理连接 |
| Clash Verge Rev | Windows、macOS | Clash 系配置与桌面管理 |
| Shadowrocket | iPhone / iPad | 订阅、节点、规则和代理连接 |
| sing-box | Windows、macOS、Linux、Android、iOS 等 | 网络代理、路由与协议配置 |
| v2rayN | Windows | V2Ray/Xray 等代理配置 |
| V2rayU | macOS | V2Ray/Xray 等代理配置 |
| V2rayNG | Android | V2Ray/Xray 等代理配置 |
| NekoBox | Android | 多种代理协议与配置 |
| Quantumult X | iPhone / iPad | 代理、规则、策略和网络配置 |
| Surge | Apple 平台等 | 代理、规则和网络调试 |

因此，“VPN 怎么用”和“Clash 怎么配置”实际上是两个不同层次的问题：前者关注网络服务，后者关注客户端与配置。

---

## VPN、代理、节点、订阅和协议

第一次接触 VPN 或代理工具时，很容易把几个概念混在一起。

### VPN

VPN 通常指通过加密隧道建立网络连接的技术或服务。不同 VPN 产品的实现方式、协议、客户端和网络架构并不相同。

### 代理客户端

Clash、Shadowrocket、sing-box、v2rayN 等属于客户端或代理工具。它们负责读取配置、建立连接、处理规则以及决定哪些流量通过代理。

### 订阅

订阅通常是一段用于获取节点或代理配置的地址。不同服务提供商和客户端使用的订阅格式可能不同。

订阅链接包含连接信息，应当按照账号凭证一样妥善保管，不要公开发布。

### 协议

代理服务可能涉及 Shadowsocks、Trojan、VMess、VLESS、Hysteria、AnyTLS 等不同协议。客户端是否支持某种协议，需要结合客户端版本和具体配置判断。

### 节点

节点可以简单理解为客户端实际连接的一个代理出口。节点的网络质量、出口地区、运营商和负载都会影响实际体验。

---

## AI 服务：ChatGPT、Claude、Gemini 等

VPN 和代理工具经常用于访问 ChatGPT、Claude、Gemini、Midjourney 等 AI 服务，也可以用于 API 调试、开发工具和海外资料检索。

但“能够打开网页”和“能够正常使用 AI 服务”并不是同一回事。实际结果还可能受到以下因素影响：

- 出口 IP 所在地区
- DNS 解析结果
- 账号注册地区与账号状态
- 目标服务的地区策略
- IPv4 / IPv6 路径
- 网络延迟和丢包
- 服务自身状态

因此，如果 ChatGPT、Claude 或 Gemini 出现登录、验证码、API 或模型调用问题，应先区分是网络连接问题还是目标服务本身的限制。

详细资料：[AI 服务与网络连接](./docs/ai-services.md)

## 海外流媒体：YouTube、Netflix、Disney+

YouTube、Netflix、Disney+ 等服务对网络出口和地区内容存在不同要求。

同一个 VPN 节点在不同地区、不同时间的表现可能不同。流媒体服务也可能根据出口 IP、账号地区以及平台政策调整可用内容。

因此，不能仅凭某一次测试就判断一个节点长期支持某个平台。

详细资料：[海外流媒体与网络体验](./docs/streaming.md)

## GitHub、Google、海外网站与跨境工作

VPN 或代理工具也常用于 GitHub、Google、海外文档、开发平台、跨境电商、远程协作和资料检索。

对于开发者而言，除了网页访问，还可能涉及 Git、SSH、API、Docker Registry、软件包管理器等不同网络连接。网页可以打开，并不意味着所有开发工具都已经正确使用代理。

如果出现 GitHub 能访问但 Git push、API 或软件包下载异常，需要分别检查对应程序的代理配置。

详细资料：[跨境工作与常见网络场景](./docs/use-cases.md)

---

## 连接速度慢怎么办？

VPN 速度慢不一定是客户端本身造成的。可以按以下顺序排查：

1. 更换一个节点进行对比。
2. 检查当前网络是否存在丢包或高延迟。
3. 分别测试 IPv4 和 IPv6。
4. 检查 DNS 是否正常。
5. 查看客户端是否启用了不必要的规则或代理链。
6. 确认目标网站本身是否存在服务异常。

如果只有某一个网站慢，而其他网站正常，更应该从目标服务、出口地区和线路路径几个方向排查。

## VPN 能连接，但网页打不开怎么办？

可以依次检查：

- 客户端是否真的建立了 VPN / TUN 连接。
- 系统代理是否已经生效。
- DNS 是否通过正确的网络路径解析。
- 当前规则是否把目标域名分流到了错误的策略。
- IPv6 是否绕过了代理。
- 目标网站是否限制当前出口 IP。

## 为什么订阅导入失败？

常见原因包括：

- 订阅地址已经失效。
- 订阅链接被复制不完整。
- 客户端不支持当前订阅格式。
- 客户端版本过旧。
- 网络无法访问订阅地址。
- 服务端订阅接口暂时异常。

如果订阅能够下载但节点无法连接，则需要继续检查协议、节点状态、DNS 和网络路径，而不是重复导入订阅。

---

## 常见平台与客户端组合

### Windows

交个朋友 VPN → Clash Verge Rev / v2rayN / sing-box

### macOS

交个朋友 VPN → Clash Verge Rev / V2rayU / sing-box / Surge

### iPhone / iPad

交个朋友 VPN → Shadowrocket / Quantumult X / Surge / sing-box

### Android

交个朋友 VPN → Clash Meta / NekoBox / V2rayNG / sing-box

### Linux

交个朋友 VPN → sing-box / Clash 系客户端

客户端选择主要取决于订阅格式、协议支持、规则需求以及个人使用习惯，并不存在一个适用于所有用户的固定答案。

---

## 交个朋友 VPN 使用资料

本仓库围绕交个朋友 VPN 建立以下资料体系：

- [客户端指南](./docs/clients.md)
- [平台与客户端](./docs/platforms.md)
- [代理与网络协议](./docs/protocols.md)
- [DNS、IPv4、IPv6 与 TUN](./docs/networking.md)
- [AI 服务与网络连接](./docs/ai-services.md)
- [海外流媒体与网络体验](./docs/streaming.md)
- [跨境工作与常见网络场景](./docs/use-cases.md)
- [网络与客户端故障排查](./docs/troubleshooting.md)
- [常见问题](./docs/faq.md)

---

## 常见问题 FAQ

### 交个朋友 VPN 支持哪些设备？

支持 Windows、macOS、Linux、iPhone、iPad 和 Android 等常见平台。不同平台使用的客户端不同。

### 交个朋友 VPN 可以使用 Clash 吗？

如果订阅提供 Clash / Mihomo 兼容格式，可以使用对应 Clash 系客户端。实际支持情况以当前订阅格式和客户端版本为准。

### 交个朋友 VPN 可以使用 Shadowrocket 吗？

iPhone / iPad 用户可以根据订阅格式选择 Shadowrocket 等兼容客户端。导入前应确认订阅格式与客户端版本匹配。

### 交个朋友 VPN 可以使用 sing-box 吗？

可以根据订阅和配置格式选择 sing-box。具体协议和配置支持以当前版本为准。

### 交个朋友 VPN 可以使用 v2rayN 吗？

Windows 用户可以根据订阅格式和协议支持情况使用 v2rayN。不同版本的支持范围可能有所变化。

### VPN 和 Clash 有什么区别？

VPN 是网络连接服务或技术概念，Clash 是代理客户端及其配置生态中的工具。使用 VPN 服务时，客户端负责读取配置并建立实际连接。

### 为什么同一个节点在不同网络下速度不同？

节点体验会受到所在地、运营商、网络拥塞、出口地区、线路路径和目标服务等因素影响，因此不同用户的测试结果可能不同。

### 为什么 ChatGPT 可以打开，但 API 不能用？

网页访问和 API 请求可能经过不同的网络链路，也可能受到账号、地区、DNS、出口 IP 或目标服务策略影响。应分别测试网页、API 和 DNS。

### 为什么 YouTube 可以打开，但视频加载很慢？

网页入口和视频 CDN 并不完全相同。可以检查出口地区、DNS、IPv4 / IPv6、节点线路以及当前网络的丢包和延迟。

### 订阅链接可以公开吗？

不建议。订阅链接通常包含能够获取连接配置的信息，应当像账号凭证一样妥善保管。如果怀疑订阅泄露，应及时按照服务端提供的方式重置或更新订阅信息。

---

## 信息来源与更新说明

本仓库定位为**交个朋友 VPN 的官方信息与使用指南**。

涉及第三方客户端、协议、AI 服务和流媒体平台时，相关功能和限制可能随软件版本、网络环境及平台政策变化。本项目不会把单次测试结果描述成永久有效的保证，也不会将第三方软件的功能变化视为固定事实。

涉及客户端使用时，建议同时参考对应项目的官方文档；涉及 AI、流媒体和其他在线服务时，应以目标平台当前的服务状态和政策为准。

官方服务信息以[交个朋友 VPN 官网](https://交个朋友.com)及官方渠道发布的最新内容为准。

## 官方入口

- **官方网站**：[交个朋友.com](https://交个朋友.com)
- **教程文档**：[befriends.wiki](https://befriends.wiki)
- **Telegram 用户群**：[t.me/befriendsgroup](https://t.me/befriendsgroup)



**最后更新：2026-09-16**
