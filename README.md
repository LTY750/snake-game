<!-- 语言切换 -->
<div style="text-align: center; margin: 20px 0;">
  <input type="radio" name="lang" id="lang-zh" checked hidden>
  <label for="lang-zh" style="cursor:pointer; padding:6px 12px; border:1px solid #ccc; border-radius:4px; background:#f5f5f5; margin:0 4px; font-size:14px;">🇨🇳 中文</label>
  
  <input type="radio" name="lang" id="lang-en" hidden>
  <label for="lang-en" style="cursor:pointer; padding:6px 12px; border:1px solid #ccc; border-radius:4px; background:#f5f5f5; margin:0 4px; font-size:14px;">🇬🇧 English</label>
</div>

<!-- 中文内容 -->
<div class="zh-content">

<div align="center">

# 🐍 Snake Game

### 一个精致的原生 Web 贪吃蛇小游戏

基于 **HTML5 Canvas + CSS3 + Vanilla JavaScript** 构建  
支持 **多模式玩法、主题切换、排行榜、成就系统、移动端滑动控制**

<br>

[🌐 在线体验](https://snake-game-emxwyrvk.edgeone.cool)

<br>

![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-UI-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

## 📖 项目简介

这是一个用 **原生前端技术** 实现的贪吃蛇游戏项目。  
它不仅保留了经典玩法，还加入了更适合展示和体验的增强功能：

- 进入页面先 **选择游戏模式**
- 每个模式都带有 **玩法说明**
- 多套主题配色可切换
- 历史成绩自动保存
- 成就系统增强可玩性
- 手机端支持 **滑动控制方向**

相比传统的“打开就玩”，这个版本更强调 **交互体验、视觉表现、项目完整度**，适合作为 GitHub 展示项目、学习 Canvas 动画项目，或前端练手作品。

---

## 🤖 AI 辅助说明

本项目在开发过程中 **借助了 AI 工具进行辅助生成与优化**，包括但不限于：

- 游戏功能设计思路整理
- 部分界面结构与样式优化
- 代码重构与问题排查
- README 文档撰写与完善

但项目并非“直接一键生成后不做处理”，而是在实际开发过程中进行了：

- 人工选择功能方案
- 手动调整交互逻辑
- 反复测试与修复问题
- 按照自己的需求持续修改与完善

你可以把它理解为：

> **这是一个由开发者主导、AI 参与辅助完成的前端小游戏项目。**

---

## ✨ 功能亮点

### 🎮 多种游戏模式
- 🏁 **经典模式**：传统贪吃蛇，吃得越多速度越快
- 🧱 **迷宫模式**：地图中加入障碍物，需要更谨慎走位
- ⏱️ **限时模式**：在 60 秒内尽可能获得更高分数
- 🌊 **无界模式**：撞墙不会死，会从另一侧出现
- 🏃 **冲刺模式**：初始速度更快，更考验反应力

### 🎨 视觉与交互
- 多主题切换：翡翠 / 日落 / 海洋 / 霓虹 / 樱桃
- 毛玻璃风格 UI 面板
- 动态渐变背景与发光效果
- 蛇头高光、眼睛朝向、食物脉冲动画
- 模式卡片式选择，先了解玩法再进入游戏

### 🏆 数据与成长
- 本地排行榜（自动保存历史成绩）
- 最高分显示
- 成就解锁系统
- 模式成绩记录

### 📱 多端适配
- 桌面端方向键 / WASD 控制
- 手机端滑动控制
- 触屏设备优化交互
- 响应式布局

### 🔊 反馈机制
- 吃食物、死亡、成就解锁音效
- 静音开关
- 部分设备支持振动反馈

---

## 🌐 在线体验

你可以直接访问下面的地址在线试玩：

👉 **https://snake-game-emxwyrvk.edgeone.cool**

---

## 🕹️ 游戏流程

### 1. 进入网页
- 看到游戏画布
- 看到当前分数面板
- 看到模式卡片及介绍

### 2. 选择模式
点击任意模式卡片，查看该模式的玩法说明：

- 经典：标准贪吃蛇体验
- 迷宫：增加障碍物挑战
- 限时：60 秒冲分
- 无界：可以穿墙
- 冲刺：高速度挑战

### 3. 点击开始
点击 `START` 后：
- 模式卡片自动隐藏
- 游戏正式开始
- 控制区保留操作按钮 / 滑动控制

### 4. 游戏结束
- 显示本局得分
- 写入历史排行榜
- 可以切换模式后重新开始

---

## 🎮 操作方式

### 桌面端
| 操作 | 按键 |
|------|------|
| 向上 | `↑` / `W` |
| 向下 | `↓` / `S` |
| 向左 | `←` / `A` |
| 向右 | `→` / `D` |
| 暂停 / 继续 | `Space` / `Esc` |

### 移动端
| 操作 | 方式 |
|------|------|
| 控制方向 | 在屏幕上滑动 |
| 开始游戏 | 点击 `START` |
| 暂停 | 点击暂停按钮 |

---

## 🧠 模式说明

### 🏁 经典模式
最标准的贪吃蛇玩法。  
每吃到一个食物就会加速，撞墙或撞到自己即结束。

### 🧱 迷宫模式
地图内会出现障碍布局。  
你不仅要避开自己，还要绕开地图障碍，容错率更低。

### ⏱️ 限时模式
在固定 **60 秒** 内获取尽可能高的得分。  
最后 10 秒会进入紧张倒计时状态。

### 🌊 无界模式
蛇可以从地图一侧穿到另一侧。  
这个模式中，墙不再致命，核心难点变成对蛇身的管理。

### 🏃 冲刺模式
更快的初始速度和更强的加速节奏。  
适合想要挑战高强度操作的玩家。

---

## 🛠️ 技术栈

- **HTML5**
  - 页面结构
  - Canvas 画布载体

- **CSS3**
  - 动态背景
  - 毛玻璃效果
  - 模式卡片 UI
  - 响应式布局
  - 动画与过渡

- **Vanilla JavaScript**
  - 游戏逻辑
  - 模式切换
  - 动画循环
  - 本地存储
  - 音效与输入控制

---

## ⚙️ 技术实现要点

### 1. Canvas 渲染
使用 `CanvasRenderingContext2D` 绘制：
- 蛇身
- 蛇头
- 食物
- 障碍物
- 背景网格

### 2. 平滑移动
通过插值（`lerp`）实现蛇移动时的平滑过渡，避免纯格子跳动感。

### 3. 模式系统
不同模式通过配置对象统一管理，例如：
- 初始速度
- 最低步进间隔
- 是否允许穿墙
- 是否启用障碍物
- 是否有时间限制

### 4. 本地存储
使用 `localStorage` 保存：
- 当前主题
- 历史成绩
- 成就解锁状态
- 游戏统计数据

### 5. 触屏适配
检测是否为触屏设备：
- 隐藏方向按钮
- 显示滑动提示
- 用滑动代替点击方向输入

---

## 📂 项目结构

```bash
snake-game/
│
├── index.html      # 主文件（HTML + CSS + JS）
└── README.md       # 项目说明文档
