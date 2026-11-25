# 棱镜造物 PrismLab — 独立效率软件与浏览器扩展作品集

- **创作者 / 工作室**：棱镜造物 PrismLab
- **面包多官方店铺主页**：https://mbd.pub/o/prismlab （本 GitHub 仓库及 GitHub Pages 在线演示站归属于上述面包多创作者账号）
- **开发理念**：100% 纯本地离线优先（Local-First）· 零数据上传 · 轻量即买即用 · 拒绝臃肿订阅

---

## 已发布与在线体验产品

### 1. 《密桥 SafeBridge》— AI 合同与文档本地双向脱敏还原工作台（v1.0.0）
- **定位**：在将机密合同、协议或业务文档发给 DeepSeek / Kimi / ChatGPT 审阅前，1 秒在浏览器本地完成甲乙方公司名、统一社会信用代码（GB 32100 校验）、法定代表人、银行账号与大小写金额双向脱敏，AI 审改后 1 秒无损还原真名与原格式 Word（`.docx`）。
- **在线免费体验工作台**：[`./safebridge.html`](./safebridge.html)
- **安全架构**：单文件零依赖运行，CSP 策略强制 `connect-src 'none'` 物理阻断外网上传，Ed25519 离线验签激活 Pro。

### 2. 《屏隐替身 StageMask》— 网页录屏截图脱敏与仿真数据替换扩展（v1.0.0）
- **定位**：面向 Microsoft Edge / Google Chrome 的演示隐私保护扩展。支持点选/框选模糊打码、网页敏感字段一键替换为仿真演示数据、金额等比缩减脱敏（`0.05×–0.80×`）、按域名零闪现记忆与共享屏幕自动防护（Share Shield）。
- **在线交互演示页**：[`./stagemask.html`](./stagemask.html)
- **隐私政策与服务条款**：[`./privacy.html`](./privacy.html) ｜ [`./terms.html`](./terms.html)
