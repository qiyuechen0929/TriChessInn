# TriChessInn · 三棋小馆

![banner](banner.svg)


> 三棋博弈，智慧人生 · 纯前端三棋对弈合集

[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E.svg?logo=javascript&logoColor=black)](#)
[![Canvas](https://img.shields.io/badge/Canvas-2D-8B4513.svg)](#)
[![Status](https://img.shields.io/badge/Status-Demo-green.svg)](#)

## 简介

`TriChessInn`（三棋小馆）是一个纯前端、单文件的**三棋对弈合集**，汇聚三种经典的中国传统棋类游戏——**象棋、围棋、五子棋**。水墨芦苇画风格的界面，古风雅韵，打开即玩。

## 功能特性

- 🏮 **三棋合一**：象棋、围棋、五子棋三大国粹棋艺汇聚一堂，一套界面三种玩法
- ♟️ **象棋**：传统棋艺，智力的较量——楚河汉界，车马炮象士将，完整走法规则
- ⚫ **围棋**：黑白世界，策略的巅峰——标准 19 路棋盘（或项目所实现棋盘），提子、围空
- 🔘 **五子棋**：五子连珠，简单的规则，无限的可能
- 🎯 **三档 AI 难度**：每种棋均可选简单（随机落子）/ 中等（攻守兼顾）/ 困难（评估函数）对手
- 🖋️ **水墨芦苇画意境**：芦苇画村落、远景迷雾、水墨晕染背景，东方美学风格
- 💾 **本地存档**：游戏进度自动保存到 `localStorage`
- ⚡ **零构建单文件**：一个 HTML 搞定全部逻辑与样式，复制即用

## 技术栈

| 技术 | 用途 |
| --- | --- |
| HTML5 + CSS3 | 界面结构与水墨芦苇画视觉风格 |
| JavaScript ES6 | 三种棋类引擎 + AI 逻辑 |
| Canvas API | 棋盘与场景绘制 |
| localStorage | 游戏进度持久化 |
| SPA 架构 | 单页面应用，无构建、无依赖 |

## 快速开始

### 方式一：直接打开

将 `三棋小馆.html` 下载到本地，**双击用浏览器打开**即可。

### 方式二：本地服务器运行

```bash
# Python
python -m http.server 8080

# 或 Node.js
npx serve .

# 然后访问
open http://localhost:8080
```

### 方式三：在线部署

将 HTML 文件直接拖入任意静态托管平台（GitHub Pages、Vercel、Netlify、Cloudflare Pages 等）即可上线。

## 游戏玩法

1. 打开游戏进入主菜单，点击「开始游戏」
2. 从象棋 / 围棋 / 五子棋中选择想玩的棋类
3. 选择 AI 难度（简单 / 中等 / 困难）
4. 与 AI 对弈，享受棋局

### 三种棋类

| 棋类 | 图标 | 特色 |
| --- | --- | --- |
| 象棋 | ♟️ | 传统棋艺，智力的较量 |
| 围棋 | ⚫ | 黑白世界，策略的巅峰 |
| 五子棋 | 🔘 | 五子连珠，简单的规则，无限的可能 |

## 项目结构

```
trichess-inn/
└── 三棋小馆.html   # 全部代码（三种棋引擎 + AI + 场景），单文件即项目
```

## 浏览器兼容性

- 支持 HTML5 与现代浏览器（Chrome / Edge / Firefox / Safari）
- 纯本地运行，无需网络与后端

## License

[MIT](LICENSE) © 2025 TriChessInn Contributors

## 致谢

- 致敬中国传统棋文化

## 作者

ChenQiyue

---

最后更新：2026-08-06
