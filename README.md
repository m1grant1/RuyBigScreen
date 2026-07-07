<div align="center">

# 如意数据大屏 · RuyBigScreen

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](./LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](./.github/CONTRIBUTING.md)
[![Stars](https://img.shields.io/github/stars/m1grant1/RuyBigScreen.svg)](https://github.com/m1grant1/RuyBigScreen/stargazers)
[![Forks](https://img.shields.io/github/forks/m1grant1/RuyBigScreen.svg)](https://github.com/m1grant1/RuyBigScreen/network/members)

一个**从 0 到 1** 教你做数据可视化大屏的开源项目，代码即教程，跟着抄就能跑起来。

[在线预览](#-在线预览) · [快速开始](#-快速开始) · [项目结构](#-项目结构) · [贡献](#-贡献) · [许可证](#-许可证)

</div>

---

## ✨ 项目简介

**RuyBigScreen（如意数据大屏）** 是一个面向初学者的数据可视化大屏开源项目，旨在帮助大家**从零开始**学习如何自己动手制作一个炫酷、实用的数据可视化大屏。

项目会持续更新多个大屏模板，覆盖不同行业、不同场景，你只需要：

1. 拉下代码
2. 装上依赖
3. 跑起来

就能拥有一个能直接演示的大屏，**所有的代码、配置、思路都会在 README 里讲清楚**，真的做到"代码即教程"。

> 🪄 "如意"取自中文"称心如意"，寓意希望每个用这个项目的人都能轻松做出自己满意的大屏。

## 🎯 适用人群

- 前端初学者，想入门数据可视化
- 后端 / 数据分析师，想做一个能演示的看板
- 产品 / 运营，需要快速搭一个汇报用的大屏
- 任何对"数据 + 视觉"感兴趣的人

## 🧰 技术栈

| 类别       | 技术选型                          |
| ---------- | --------------------------------- |
| 前端框架   | Vue 3 / React 17（按模板区分）    |
| 可视化库   | ECharts 5 / DataV / D3.js         |
| 构建工具   | Vite 4 / Webpack 5                |
| 包管理     | pnpm / npm / yarn                 |
| 数据请求   | Axios / Fetch                     |
| 样式       | Less / Sass / Tailwind            |
| 部署       | Nginx / Vercel / GitHub Pages     |

> 不同模板用到的技术栈可能略有不同，每个模板目录下都有自己的 `README.md` 详细说明。

## 🚀 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/m1grant1/RuyBigScreen.git
cd RuyBigScreen
```

### 2. 进入某个模板目录

```bash
# 示例：进入"销售数据大屏"模板
cd templates/sales-dashboard

# 安装依赖
npm install   # 或 pnpm install / yarn

# 启动开发服务
npm run dev
```

### 3. 打开浏览器

按终端输出的地址（一般是 `http://localhost:5173`）访问，就能看到效果啦 🎉

## 📁 项目结构

```
RuyBigScreen/
├── templates/                # 各种大屏模板
│   ├── sales-dashboard/      # 销售数据大屏
│   ├── covid-tracker/        # 疫情数据大屏（示例）
│   └── ...                   # 持续新增中
├── docs/                     # 项目文档与教程
│   ├── getting-started.md    # 新手入门
│   ├── echarts-tips.md       # ECharts 使用技巧
│   └── deployment.md         # 部署指南
├── .github/                  # GitHub 配置（Issue 模板、PR 模板等）
├── LICENSE                   # MIT 开源协议
└── README.md                 # 你正在看的这个文件
```

> 📌 **每个模板都是一个独立的小项目**，自带 `package.json`、独立依赖、独立运行，互不影响。

## 🌐 在线预览

> 在线预览地址会在每个模板的 README 中给出，欢迎部署后补充。

## 📚 教程与文档

- [新手入门 · 从环境到第一个大屏](./docs/getting-started.md)（待补充）
- [ECharts 常用图表速查](./docs/echarts-tips.md)（待补充）
- [大屏适配方案 · 1920×1080 之外怎么办](./docs/screen-adapt.md)（待补充）
- [部署指南 · 让大屏跑在服务器上](./docs/deployment.md)（待补充）

> 文档持续更新中……也欢迎你 [提 Issue](#-贡献) 告诉我们你最想看的内容。

## 🤝 贡献

非常欢迎你一起把这个项目做得更好！🎉

你可以这样参与：

- 🐛 **反馈 Bug**：在 [Issues](../../issues) 提一个 bug
- 💡 **提出新需求**：想要哪个场景的大屏模板？开个 issue 描述一下
- 🧩 **贡献代码**：参考 [贡献指南](./.github/CONTRIBUTING.md)（待补充），提交 PR
- 📖 **完善文档**：文档写错、写漏了？欢迎直接提 PR
- ⭐ **点个 Star**：这是对项目最大的支持

## 🗓️ 更新计划

- [x] 初始化项目结构 + README + MIT License
- [ ] 销售数据大屏模板（Vue 3 + ECharts + Vite）
- [ ] 智慧城市 / 交通大屏模板
- [ ] 疫情 / 公共卫生数据大屏模板
- [ ] 大屏适配、主题切换教程
- [ ] 后端 mock 数据方案

> 看到这里发现漏了什么？开个 issue 告诉我们 👀

## 📜 许可证

本项目基于 [MIT](./LICENSE) 协议开源 —— 你可以自由地使用、修改、分发，无论是个人项目还是商业项目，请保留原作者版权即可。

## 🙏 致谢

感谢以下开源项目（排名不分先后）：

- [Apache ECharts](https://github.com/apache/echarts)
- [DataV](http://datav.aliyun.com/portal/school/atlas/area_selector)
- [Vue.js](https://github.com/vuejs/core)
- [Vite](https://github.com/vitejs/vite)

以及所有为本项目提过 Issue、PR、Star 的朋友们 ❤️

---

<div align="center">

**如果觉得这个项目对你有帮助，欢迎 Star ⭐ 让更多人看到！**

Made with ❤️ by [m1grant1](https://github.com/m1grant1) and [contributors](../../graphs/contributors)

</div>
