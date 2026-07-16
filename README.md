# 晨昏 · Weightly

**AI 陪伴式减重管理产品(App + Web)。** 早晚体重记录、日历看每日数值、趋势可视化,以及一个会陪伴、能用语音/文字帮你记录的 AI 助手「小昏」。和小程序线最本质的区别是:AI 助手不是锦上添花的功能,而是这条产品线存在的理由。

> 与小程序线的关系:小程序版「晨昏·体重日历」(仓库 `Molly-gith/weight-tracker`,uni-app / uniCloud)已冻结、保留国内入口;本仓库是全新技术栈(Expo + Express + PostgreSQL)重做,承载 AI Agent 的长期方向。

## 仓库结构

* `prototype/` —— 各版本可交互原型(先设计、后写码)。目前:
  * `weightly-v1.html` —— **V1 原型**:早/晚体重、日历数值、趋势图、右下角悬浮 AI 助手,App 端手机布局。
* `showcase/index.html` —— **原型展示页**,汇总各版本原型入口与设计说明。
* `index.html` —— 站点入口,自动跳转到原型展示页(以后 Web 应用上线可替换为应用首页)。
* `.github/workflows/deploy-pages.yml` —— 自动把静态原型页发布到 GitHub Pages。
* `PLANNING.md` —— 产品定位、技术栈决策、分阶段路线图(新会话读它即可获得完整上下文)。

## 在线地址

* 原型展示页:`https://molly-gith.github.io/Weightly/showcase/`
* V1 原型直达:`https://molly-gith.github.io/Weightly/prototype/weightly-v1.html`

> 链接生效需要:① 仓库为 Public(或对私有仓库启用 Pages 的套餐);② 仓库 Settings → Pages → Source 设为 **GitHub Actions**。设好后每次推送到 `main` 会自动重新发布。

## 当前阶段

正处于 **V1 原型设计**阶段(交互式原型,先确认方向再写真代码)。V1 范围:早晚体重记录、日历数值、趋势图表、陪伴式 AI 助手(语音/文字记体重 + 情绪陪伴)。**不含**饮食、运动、营养知识库(见 `PLANNING.md` 的路线图,分别是后续阶段)。
