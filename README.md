# 个人成长进度条 (Growth Progress Tracker)

[![Release](https://img.shields.io/badge/version-v0.4-brightgreen.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)]()
[![Deploy](https://img.shields.io/badge/demo-GitHub%20Pages-orange.svg)]()

> 「个人成长进度条」是一款帮助用户记录、可视化、分析自己在七个维度成长进度的全能追踪 App。

本项目 v0.4 版本完成了从“可点击原型”到“真实可用单机闭环”的升级。告别静态硬编码数据，实现了完整的账号注册登录、前端数据持久化（localStorage）以及基于真实记录的动态成长报告。

[👉 点击这里在线体验 Live Demo](换成你的 GitHub Pages 链接)

---

## ✨ 核心特性 (Features)

* [cite_start]👤 **完整账号体系**：支持用户名/密码注册与登录 [cite: 12][cite_start]。每个账号数据独立隔离 [cite: 12][cite_start]，退出登录后重新登录可完整恢复历史数据 [cite: 12]。
* [cite_start]💾 **本地数据持久化**：基于 `localStorage` 实现 [cite: 6, 19][cite_start]，技能进度、历史打卡记录、个人资料及自定义主题配色均自动保存在本地 [cite: 14, 15, 16, 17]。
* [cite_start]📅 **真实打卡与连续天数**：打卡行为实时写入数据 [cite: 6, 24][cite_start]，自动更新技能累计次数 [cite: 24][cite_start]，并按真实日期计算全局连续打卡天数（Streak）[cite: 24]。
* [cite_start]📊 **动态成就与年度报告**：拒绝编造数据 [cite: 26][cite_start]。年度报告完全根据用户的真实打卡轨迹生成，包含高光技能与阶段统计 [cite: 26]。
* [cite_start]🎨 **个性化与细节优化**：支持主题配色自定义 [cite: 17][cite_start]，优化 iOS 风格时间滚轮等细节交互控件 [cite: 30]。
* [cite_start]🔍 **技能库探索**：提供丰富内置技能，支持关键字搜索与一键快速激活初始空状态 [cite: 28]。

---

## 📸 界面预览 (Screenshots)

*(提示：可以在此处上传你的实际页面截图)*

| 首页与进度 | 打卡时光轴 | 动态年度报告 |
| :---: | :---: | :---: |
| ![首页](https://via.placeholder.com/250x500?text=Home) | ![时光轴](https://via.placeholder.com/250x500?text=Timeline) | ![年度报告](https://via.placeholder.com/250x500?text=Report) |

---

## 🛠 技术栈 (Tech Stack)

* **前端**：HTML5 / CSS3 / JavaScript (ES6+)
* [cite_start]**数据存储**：浏览器原生 `localStorage` [cite: 6, 19]
* [cite_start]**部署方式**：GitHub Pages 静态托管 [cite: 6]

---

## 🚀 快速开始 (Quick Start)

### 1. 在线体验
直接访问已部署好的演示地址：[https://liuyixuan896-source.github.io/-/]

### 2. 本地运行
无需配置复杂的运行环境，下载即用：

```bash
# 克隆本项目
git clone [https://github.com/liuyixuan896-source/-.git]

# 进入项目目录
cd 仓库名

# 在浏览器中直接打开 index.html 即可运行
