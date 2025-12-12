# Henry's Alpha Station 🌌

> V7.0 Ultimate Edition

**Henry's Alpha Station** 是一个专为捕捉高波动、高回报（Alpha）机会而设计的单页美股/加密货币监控看板。它采用极简的深色赛博朋克风格，集成了 TradingView 实时图表组件，旨在提供最纯粹的行情观察体验。


## ✨ 核心特性

* **🏝️ 灵动岛导航 (Dynamic Island)**: 顶部悬浮的胶囊式导航栏，适配移动端和桌面端，横向滚动，极致节省空间。
* **📱 移动端 Flow 布局**: 专为手机优化的流式滚动体验，图表与数据无缝衔接，无卡顿。
* **⏱️ 智能刷新机制**: 内置 10 分钟自动刷新倒计时，防止挂机时页面数据过期，无需手动 F5。
* **🎨 赛博朋克美学**: 深邃黑背景 + 霓虹色标签（蓝/紫/红/金/绿），视觉聚焦，适合长时间盯盘。
* **📊 核心板块监控**:
    * **🌌 太空经济**: RKLB, ASTS, LUNR
    * **🔥 高胜赔博弈**: SMCI, TSLA, UPST, TNXP, APP
    * **🤖 AI 基建与数据**: NVDA, PLTR, MU, SOUN, ALAB, SERV
    * **🪙 币圈生态**: MSTR, CLSK, RIOT, COIN
    * **🧬 生物科技 Alpha**: WVE, ALNY, VKTX
    * **🏭 周期与复苏**: AAL, MGA

## 🚀 快速开始

### 方式一：直接运行
只需要下载本仓库中的 `index.html` 文件，用浏览器（Chrome/Safari/Edge）直接打开即可使用。

### 方式二：GitHub Pages 托管 (推荐)
你可以利用 GitHub Pages 免费生成一个在线链接，随时随地在手机上访问：

1.  将本项目 Fork 或 Push 到你的 GitHub 仓库。
2.  进入仓库 **Settings (设置)** -> **Pages**。
3.  在 **Build and deployment** 下的 **Branch** 选项中，选择 `main` (或 `master`) 分支，点击 **Save**。
4.  等待约 1 分钟，GitHub 会生成一个 `https://你的用户名.github.io/仓库名/` 的链接。
5.  **Add to Home Screen**: 在手机浏览器打开该链接，选择“添加到主屏幕”，即可像 App 一样全屏使用。

## 🛠️ 自定义配置

本项目由纯 HTML/CSS/JS 编写，无复杂的构建过程，修改极其简单。

### 修改/添加股票
打开 `index.html`，搜索 `tradingview-widget-container` 或具体的股票代码（例如 `NVDA`）。

1.  **修改代码**: 找到 `"symbol": "NASDAQ:NVDA"`，将其替换为你想要的股票代码（例如 `"NYSE:BABA"`）。
2.  **修改标签**: 找到 `<div class="modern-badge tag-neon-blue">NVDA 核心</div>`，修改文字和颜色类名。

**颜色类名参考：**
* `tag-neon-blue` (科技/通用)
* `tag-neon-red` (杠杆/高风险)
* `tag-neon-purple` (量子/前沿)
* `tag-neon-gold` (加密货币)
* `tag-neon-green` (医药/环保)
* `tag-neon-danger` (极高风险/警告)

## 📂 文件结构

```text
.
└── index.html   # 核心文件，包含所有布局、样式和逻辑
