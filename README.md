# snake-game
贪吃蛇游戏
<div align="center">

# 🐍 Snake Game

**一个精致的贪吃蛇网页游戏 — 零依赖，单文件，开箱即玩**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

[🎮 在线试玩](#-快速开始) · [✨ 功能特性](#-功能特性) · [🎨 主题预览](#-主题预览) · [🛠 技术细节](#-技术细节)

</div>

---

## ✨ 功能特性

### 🎮 游戏玩法
- **经典贪吃蛇** — 吃食物增长身体，撞墙或撞自己则游戏结束
- **渐进加速** — 每吃一个食物速度提升，最高可达 2.9x
- **平滑插值动画** — 蛇的移动在帧间插值，告别格子跳跃感
- **方向输入队列** — 支持快速连续转向，不会吞键

### 🎨 视觉体验
- **5 套主题配色** — 翡翠 / 日落 / 海洋 / 霓虹 / 樱桃，一键切换
- **毛玻璃 UI** — `backdrop-filter` 磨砂质感面板
- **动态光晕背景** — 浮动模糊光球随主题变色
- **Canvas 渲染** — 渐变蛇身、脉冲食物、蛇眼跟随方向转动

### 📱 多端适配
- **键盘** — 方向键 + WASD
- **触屏按钮** — 游戏中自动放大，触摸即时反馈
- **滑动手势** — 在画布上滑动控制方向，支持连续转向
- **响应式布局** — 桌面三栏 / 移动端自适应

### 💾 数据持久化
- **排行榜** — 自动保存最近 10 局得分，按分数排序
- **最高分记录** — 实时显示历史最佳，破纪录时弹出提示
- **主题记忆** — 下次打开自动恢复上次选择的主题
- **一键清空** — 支持清除所有历史记录

---

## 🎨 主题预览

| 翡翠 Emerald | 日落 Sunset | 海洋 Ocean | 霓虹 Neon | 樱桃 Cherry |
|:---:|:---:|:---:|:---:|:---:|
| 🟢 | 🟠 | 🔵 | 🟣 | 🔴 |
| `#4CAF50` | `#ff9a44` | `#00d4ff` | `#b537f2` | `#ff4081` |
| 经典绿 | 暖橙落日 | 深海蓝 | 赛博紫 | 粉红樱花 |

> 点击控制面板顶部的彩色圆点即可切换主题，主题选择会自动保存到 `localStorage`。

---

## 🎮 快速开始

### 在线游玩

直接用浏览器打开 `index.html` 即可，无需任何构建工具或服务器。

```bash
# 克隆仓库
git clone https://github.com/<your-username>/snake-game.git

# 进入目录
cd snake-game

# 用浏览器打开（任选一种）
open index.html          # macOS
xdg-open index.html      # Linux
start index.html         # Windows
