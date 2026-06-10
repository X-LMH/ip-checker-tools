# 🌐 Anti-Association & IP Purity Detection Tools | 全球优质 IP 纯净度与防关联检测工具推荐

你还在用 `ping0.cc` 或者那些“万人骑”的共享节点 IP 吗？

这正是导致你的 X (Twitter) 账号频繁被风控、主流 AI 平台（ChatGPT/Claude）无法访问、或者网速慢到崩溃的核心原因。真正的高端玩家和跨境开发者，都在用更深度的防关联检测工具。

> 💡 **最佳浏览体验**：由于 GitHub 官方限制了网页自动弹出新窗口，**请按住 `Ctrl` 键（Mac 用户按 `Cmd` 键）点击链接**，或**直接用鼠标滚轮点击**，即可在浏览器新标签页中打开工具网站！

---

## 💻 命令行超级工具（开发者/终端玩家首选）

### 🌟 [IPQuality](https://github.com/xykt/IPQuality) — 开源一键 IP 质量体检脚本
* **核心功能**：通过一行命令，在 Linux/WSL 终端中瞬间输出最全面的 IP 深度体检报告。
* **深度指标**：
  * **多库联检**：聚合 IPinfo、ipregistry、IP2Location、AbuseIPDB 等 5 大风控数据库，精准判定 **家宽（Residential）** 或 **机房（Hosting）** 属性。
  * **全面风控评分**：直观展示 Scamalytics、IPQS 等主流欺诈风险指数，判定是否为代理/Tor/VPN。
  * **流媒体与 AI 解锁**：一键检测对 **ChatGPT、Netflix、TikTok、Disney+** 等平台的原生/DNS 解锁状态及落地地区。
* **快速使用**：
  `bash <(curl -sL https://Check.Place) -I`
---

## 🛠️ 网页端精选工具清单

### 1. [IP Pure](http://ippure.com) — 深度风险扫描
* **核心功能**：专注于检测 IP 的**纯净度得分**。
* **应用场景**：直观评估当前节点是否被主流风控系统标记为黑名单、刷量或高风险 IP。

### 2. [IP 检查网](https://ipjiance.net) — 基础信息核验
* **核心功能**：检测 IP 的**基本地理位置与 ISP 信息**。
* **应用场景**：快速核对当前节点的物理定位、所属运营商（ISP），确保代理全局生效。

### 3. [IP.NET.COFFEE](https://ip.net.coffee/claude/) — Claude/AI 专属出口检测
* **核心功能**：精准检测当前 **Claude AI 出口 IP** 的状态与纯净度。
* **深度指标**：
  * **IP 属性辨析**：精准识别 **住宅（Residential）** / **机房（Hosting/DC）** / **原生 IP**。
  * **高阶防护**：支持欺诈风险指数、DNS 泄漏、UDP 支持、浏览器指纹（Fingerprint）和历史安全性评估。

### 4. [IPInfo.cv](https://ipinfo.cv) — 全能网络工具箱（Clash 绝配）
* **核心功能**：全能型 IP 诊断工具，特别适合排查 **Clash / v2ray / Sing-box 分流** 情况。
  * 📊 **网络性能**：全球 Ping、TCP 测试、支持**地图可视化**的 MTR 路由追踪。
  * 🔍 **分流诊断**：提供精准的分流测试与深度 DNS 查询。

### 5. [BrowserLeaks](https://browserleaks.com/ip) — 权威防关联与隐私泄漏检测
* **核心功能**：全方位隐私漏洞排查，拒绝真实身份“裸奔”。
* **应用场景**：深度检测是否通过 **WebRTC、DNS 泄漏、IPv6 泄漏** 等渠道，向目标网站暴露了你真实的国内 IP 或本地设备信息。

---

## 👏 致谢 / Acknowledgments

本项目思路与工具推荐源自以下优质内容分享，特此致敬：

* **核心灵感**：[@0xJoveXu 的 X (Twitter) 推文](https://x.com/0xJoveXu/status/2056370562273063133?s=20)
* **开源贡献**：感谢 [@xykt](https://github.com/xykt) 维护的 `IPQuality` 开源项目，为终端用户提供了极佳的检测便利。

本项目在此基础上进行了工具扩充与排版优化，方便开发者与跨境用户长期收藏查阅。整理不易，瑞思拜！🫡

---

> 💡 **总结**：如果你的节点能完美通过以上工具的层层风控筛查（尤其是 `IPQuality` 报告中展现出极低风险与家宽属性），说明其质量极高，属于万中无一的“独享级”优质网络。**欢迎 Star 收藏，以备不时之需！**
