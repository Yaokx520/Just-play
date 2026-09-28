<div align="center">
Just-play
<div align="center">
⚡ Flash games are dead. Long live the flash game.⚡
<div align="center">
   一个致敬 Flash 小游戏黄金时代的 HTML5 游戏合集
   
# ⚡ 星尘快跑 Stardust Rush

**一个致敬 2000 年代 Flash 小游戏黄金时代的 HTML5 网页街机游戏**
*An HTML5 arcade game that pays tribute to the golden age of 2000s Flash mini-games.*

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-Game-37e0e8?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-ff9d2e?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-0-28c840?style=flat-square)

[中文](#-中文) | [English](#-english)

</div>

---

## 🕹️ 简介 / Overview

**中文**

《星尘快跑》是一款纯前端实现的网页小游戏：驾驶收集艇在星空中穿梭，接取星币与宝石、躲避故障炸弹、争取最高连击倍率。

游戏采用单 HTML 文件实现，**无需构建、无需依赖、无需插件**，双击即可游玩。视觉风格复刻了 2004 年前后的 Flash 小游戏站——立体按钮、CRT 扫描线、像素标题与光泽导航栏，而底层则使用现代开放标准（Canvas 2D + Web Audio API）重制。

> 💡 注：Adobe 已于 2020 年终止 Flash Player 支持，本项目**不使用任何 swf 文件**，而是用现代 Web 技术还原 Flash 游戏的视觉语言与手感。

**English**

Stardust Rush is a browser-based mini-game built entirely with front-end technologies.
Pilot your collection ship through the cosmos, catch stars and gems, dodge glitch bombs,
and push your combo multiplier to the limit.

It ships as a **single HTML file** — no build step, no dependencies, no plugins.
The art direction recreates the Flash-game portals of the 2004 era (beveled buttons,
CRT scanlines, pixel typography, glossy nav bars), while the implementation is modern
and open-standards based (Canvas 2D + Web Audio API).

> 💡 Note: Adobe ended support for Flash Player in 2020. This project contains **no swf
> files**; it recreates the Flash aesthetic and feel using modern web technologies.

---

## ✨ 特性 / Features

| | 中文 | English |
|---|---|---|
| 🎯 | 三种道具：星币、宝石、红心，外加故障炸弹 | Three item types (star, gem, heart) plus glitch bombs |
| 🔥 | 连续接取触发倍率加成，最高 ×5 | Combo multiplier up to ×5 |
| 📈 | 每 300 分提速一档，难度递进 | Difficulty scales every 300 points |
| 💥 | 粒子爆发、屏幕震动、受击红闪 | Particle bursts, screen shake, hit flash |
| 🔊 | Web Audio 实时合成音效，可一键静音 | Synthesized sound effects with a mute toggle |
| 💾 | 最高分保存在 localStorage | High score saved to localStorage |
| 📱 | 支持键盘、鼠标、触屏三种操作方式 | Keyboard, mouse, and touch controls |
| 🧩 | 单文件、零依赖、60 FPS | Single file, zero dependencies, 60 FPS |

---

## 🚀 快速开始 / Getting Started

### 玩法（无需安装）

**中文** 下载本仓库，直接用浏览器打开 `index.html` 即可开始游戏。
**eng** Clone or download this repository and open `index.html` in your browser. That's it.
**点击即玩 Click to play** https://yaokx520.github.io/Just-flash/

### 操作说明 / Controls

| 动作 Action | 按键 Key |
|---|---|
| 左右移动 Move | `←` `→` 或 `A` `D`，鼠标 / 触屏拖动 |
| 开始游戏 Start | `Enter` 或点击按钮 |
| 暂停 Pause | `P` / `Space` |
| 静音 Mute | 右上角喇叭图标 |

### 计分规则 / Scoring

- ⭐ **星币 Star**：+10 分
- 💎 **宝石 Gem**：+25 分
- ❤️ **红心 Heart**：+1 条命（最多 5 条）
- 💣 **炸弹 Bomb**：-1 条命，清空连击
- 每连续接取 5 个物品，倍率 +1，最高 ×5；漏接或被击中则连击清零

---


