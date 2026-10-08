# BattMetric

BattMetric 是用于电池与电化学数据分析的桌面软件。本仓库只提供已公开发布的安装包、校验信息、签名更新元数据、发布说明和面向用户的帮助内容；产品源码不在此公开。

## 下载与版本

当前 Windows 与 macOS 稳定版为 [v0.3.6](https://github.com/battmetric/battmetric-public/releases/tag/v0.3.6)，同一个平台安装包支持跟随系统、简体中文和 English。请从 [Releases 页面](https://github.com/battmetric/battmetric-public/releases)选择平台附件，并按发行说明核对安装步骤和签名状态。

macOS 使用 `channels/stable-macos.json`，Windows 使用 `channels/stable-windows.json`；桌面端读取各自平台的 appcast。原 `channels/stable.json` 保留历史版本，下载页优先采用平台频道。签名元数据用于核验公开发行。

旧 Windows 0.3.1、旧英文包，以及 macOS 0.3.4及更早版本，请备份设置、项目和授权缓存后手动安装统一包一次，以使用当前更新签名密钥。旧包没有语言偏好字段时，首次采用“跟随系统”；固定英文需要选择 English 并重启。

macOS 包支持 Apple Silicon、macOS 13+，使用 ad-hoc 签名且未公证；Windows 包未 Authenticode 签名。后续统一包更新保留已有的显式语言选择和用户数据。

## 安装前校验

1. 确认文件链接来自本仓库对应版本的 Release。
2. 对照同一 Release 公布的 SHA-256 校验值，核对下载文件。
3. 按该版本发行说明核对 Windows／macOS 的平台签名或公证状态；不要推断所有版本具有相同签名状态。

来源、校验值或发行说明无法核实时，请暂缓安装。

## 许可、支持与安全

BattMetric 为专有软件；本仓库内容的条款见 [LICENSE.md](LICENSE.md)，第三方组件遵循其各自许可。

对于已发布版本的一般问题，可以提交 GitHub Issue，写明版本、操作系统、架构和脱敏后的复现步骤。不要在公开 Issue 发送 License 码、研究数据、个人信息、凭据或漏洞细节。安全问题按 [安全报告说明](SECURITY.md)走私密渠道。
