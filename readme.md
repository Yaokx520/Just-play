
<div align="center">
  <h1>⚡ Just-play</h1>
  <b>⚡ Flash games are dead. Long live the flash game. ⚡</b><br><br>
  一个致敬 Flash 小游戏黄金时代的 HTML5 游戏合集<br>
  <i>An HTML5 game collection that pays tribute to the golden age of Flash mini-games.</i>
</div>

<br>

<div align="center">

![Games](https://img.shields.io/badge/Games-8-9b5de5?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Canvas](https://img.shields.io/badge/Canvas-Game-37e0e8?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-ff9d2e?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-0-28c840?style=flat-square)

[中文](#-中文) | [English](#-english)

**▶ 点击即玩 Click to play** https://yaokx520.github.io/Just-play/

</div>

---

## 🕹️ 简介 / Overview

**中文**

Just-play 是一个纯前端实现的网页小游戏合集：八款即开即玩的小游戏，从星空接物到肉鸽塔防，覆盖休闲、街机、益智与策略。

所有游戏均为**单 HTML 文件**实现，**无需构建、无需依赖、无需插件**，双击即可游玩。视觉风格复刻了 2004 年前后的 Flash 小游戏站——立体按钮、CRT 扫描线、像素标题与光泽导航栏，而底层则使用现代开放标准（Canvas 2D + Web Audio API）重制。

> 💡 注：Adobe 已于 2020 年终止 Flash Player 支持，本合集**不使用任何 swf 文件**，而是用现代 Web 技术还原 Flash 游戏的视觉语言与手感。

**English**

Just-play is a front-end-only collection of eight drop-and-play browser mini-games —
from cosmic catchers to roguelike tower defense, covering casual, arcade, puzzle and strategy.

Every game ships as a **single HTML file** — no build step, no dependencies, no plugins.
The art direction recreates the Flash-game portals of the 2004 era (beveled buttons,
CRT scanlines, pixel typography, glossy nav bars), while the implementation is modern
and open-standards based (Canvas 2D + Web Audio API).

> 💡 Note: Adobe ended support for Flash Player in 2020. This collection contains **no swf
> files**; it recreates the Flash aesthetic and feel using modern web technologies.

---

## ✨ 特性 / Features

| | 中文 | English |
|---|---|---|
| 🎮 | 八款游戏一库打包，秒开秒玩 | Eight games in one repo, instant play |
| 🧩 | 每款单文件、零依赖、60 FPS | Single file per game, zero dependencies, 60 FPS |
| 🖼️ | 复刻 2004 年 Flash 小游戏站视觉 | Authentic 2004 Flash-portal look and feel |
| 📱 | 键盘、鼠标、触屏三端操作 | Keyboard, mouse, and touch controls |
| 💾 | 最高分 / 进度保存在 localStorage | High scores and progress saved to localStorage |
| 🔊 | Web Audio 实时合成音效，可一键静音 | Synthesized sound effects with a mute toggle |
| 📴 | 完全离线可用，无需联网 | Works fully offline |
| 🧪 | 纯开放标准，无 Flash、无插件 | Open web standards only — no Flash, no plugins |

---
---

## 🎮 游戏一览 / Games

同一套复古街机审美，八款游戏合集。

| 角标 | 游戏 Game | 分类 Genre | 一句话 Tagline | 评分 | 在线 Play |
|:---:|---|---|---|:---:|---|
| 🆕 | 星尘快跑 Stardust Rush | 街机 · 反应 | 星空穿梭接星币，连击冲最高分 | 9.4 | [打开](https://yaokx520.github.io/Just-play/1.html) |
| 🔥 | 霓虹弹球 Neon Pinball | 弹幕 · 休闲 | 弹球反弹清霓虹砖，越弹越爽 | 8.8 | [打开](https://yaokx520.github.io/Just-play/2.html) |
| | 像素深海 Pixel Abyss | 探索 · 解谜 | 深潜像素海底，解谜寻宝避水母 | 8.2 | [打开](https://yaokx520.github.io/Just-play/3.html) |
| | 方块农场 Block Farm | 模拟 · 放置 | 种菜收获，放置经营你的小农场 | 7.9 | [打开](https://yaokx520.github.io/Just-play/4.html) |
| 🔥 | 星际塔防 Star Defense | 策略 · 塔防 | 布塔守星球，抵御外星虫群 | 9.1 | [打开](https://yaokx520.github.io/Just-play/5.html) |
| | 熔岩跑酷 Lava Runner | 跑酷 · 极限 | 熔岩追身，越跑越快的极限闪避 | 8.5 | [打开](https://yaokx520.github.io/Just-play/6.html) |
| 🆕 | 战争进化史 Evo Wars | 策略 · 进化 | 五时代进化肉鸽塔防，随机词缀塔 | 9.2 | [打开](https://yaokx520.github.io/Just-play/7.html) |
| | 疯狂小人大战 Stickman Brawl | 格斗 · 对战 | 火柴人同屏乱斗，道具随机掉落 | 8.7 | [打开](https://yaokx520.github.io/Just-play/8.html) |

> 评分为站内玩家综合评分（满分 10）；🆕 新游 / 🔥 热门。

---

## 📋 玩法速查 / Quick Reference

| 游戏 Game | 核心玩法 Core Loop | 主要操作 Controls |
|---|---|---|
| 星尘快跑 | 接物 → 连击倍率 → 提速进阶 | `←` `→` / 拖动 |
| 霓虹弹球 | 发球反弹 → 清砖连击 → 连锁加分 | `←` `→` 控制挡板 / 点击发射 |
| 像素深海 | 深潜探索 → 解谜开门 → 收集宝藏 | 方向键 / 拖动 |
| 方块农场 | 种植收获 → 放置收益 → 扩建农场 | 鼠标点击 / 触屏 |
| 星际塔防 | 布防建塔 → 抵御波次 → 科技升级 | 鼠标点击 + 数字键 |
| 熔岩跑酷 | 跳跃闪避 → 越跑越快 → 挑战极限 | `Space` 跳跃 / 点击 |
| 战争进化史 | 出兵建塔 → 波次三选一 → 时代进化 | 鼠标点击 + 数字键出兵 |
| 疯狂小人大战 | 移动攻击 → 拾取道具 → 活到最后 | `WASD` + `J` `K` |
---

## 🌟 精选：星尘快跑 / Spotlight: Stardust Rush

驾驶收集艇在星空中穿梭，接取星币与宝石、躲避故障炸弹、争取最高连击倍率。

### 操作 / Controls

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

## 🚀 快速开始 / Getting Started

**中文** 克隆或下载本仓库，用浏览器打开 `index.html` 进入合集首页，点击任意游戏即玩。
**English**  Clone or download this repository, open `index.html`, and click any game to play.

```bash
git clone https://github.com/Yaokx520/Just-play.git
cd Just-play
# 直接双击 index.html，或起个本地服务
python3 -m http.server 8000
```

**点击即玩 Click to play** https://yaokx520.github.io/Just-play/


---

## ❓ 常见问题 / FAQ

> **Q：还需要安装 Flash 吗？**
> 完全不需要。所有游戏都是纯 HTML5 实现，任何现代浏览器都能直接玩。

> **Q：为什么分数/进度丢失了？**
> 存档保存在浏览器 localStorage 中，清除浏览器数据会重置进度。

> **Q：手机上能玩吗？**
> 可以。全部游戏适配触屏操作，横竖屏均可游玩。

---

## 📄 许可 / License

[MIT](./LICENSE) © Yaokx520

自由使用、修改、分发；用于学习与交流时注明出处即可。
