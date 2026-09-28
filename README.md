# BattMetric

BattMetric 是用于电池与电化学数据分析的桌面软件。本仓库只提供已公开发布的安装包、校验信息、签名更新元数据、发布说明和面向用户的帮助内容；产品源码不在此公开。

## 下载与版本

当前公开稳定版为 [v0.3.1](https://github.com/battmetric/battmetric-public/releases/tag/v0.3.1)。请从本仓库的 [Releases 页面](https://github.com/battmetric/battmetric-public/releases)选择所需平台的附件，并以对应发行说明确认支持平台、安装步骤和签名状态。未来版本须在正式发布后才视为公开稳定版。

`channels/stable.json` 与平台 appcast 是面向更新客户端的签名稳定频道；不要把候选包、草稿或第三方镜像当成正式发行。

## 安装前校验

1. 确认文件链接来自本仓库对应版本的 Release。
2. 对照同一 Release 公布的 SHA-256 校验值，核对下载文件。
3. 按该版本发行说明核对 Windows／macOS 的平台签名或公证状态；不要推断所有版本具有相同签名状态。

来源、校验值或发行说明无法核实时，请暂缓安装。

## 许可、支持与安全

BattMetric 为专有软件；本仓库内容的条款见 [LICENSE.md](LICENSE.md)，第三方组件遵循其各自许可。

对于已发布版本的一般问题，可以提交 GitHub Issue，写明版本、操作系统、架构和脱敏后的复现步骤。不要在公开 Issue 发送 License 码、研究数据、个人信息、凭据或漏洞细节。安全问题按 [安全报告说明](SECURITY.md)走私密渠道。
