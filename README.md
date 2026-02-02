# China Congress Timeline - 中国共产党重要会议时间轴

[![GitHub Pages](https://img.shields.io/badge/Live-Demo-brightgreen.svg)](https://leeyanlyn.github.io/china-congress-timeline/)
![Platform](https://img.shields.io/badge/Platform-Web-blue.svg)
![Tech](https://img.shields.io/badge/Tech-Vanilla%20JS-lightgrey)

这是一个基于 **原生 HTML / CSS / JavaScript** 构建的中国重要会议时间轴可视化项目，旨在通过**时间轴 + 筛选 + 搜索 + 详情联动**的方式，帮助用户系统性理解党代会与重要全会的历史脉络。

---

## 🌟 核心功能

- **🕰️ 交互式时间轴 (Timeline Visualization)**  
  横向时间轴展示重要会议节点，支持自动居中定位与滚动同步。

- **🗂️ 会议类型筛选 (Filter System)**  
  支持「全部 / 党代会 / 中央委员会全会」筛选，不同类型具有独立的视觉与布局逻辑。

- **🔍 关键词搜索 (Search)**  
  支持按会议名称与关键词实时过滤，搜索结果与时间轴、年份导航保持同步。

- **📅 年份快速导航 (Year Navigation)**  
  左侧年份列表可快速跳转，对应时间轴节点自动高亮。

- **📖 会议详情面板 (Detail Panel)**  
  点击节点即可查看会议背景与核心内容，详情状态与当前筛选条件保持一致。

---

## 🧠 设计理念

- 强调**信息结构清晰度**而非视觉炫技  
- 使用显式状态管理避免筛选、搜索、滚动之间的冲突  
- 时间轴、年份导航、详情面板三者基于统一状态源联动  
- 不依赖任何前端框架，突出基础能力与可控复杂度

---

## 🛠️ 技术实现

- **Frontend**: 原生 HTML5、CSS3（Flex 布局、响应式设计）、JavaScript（ES6+）
- **State Management**: 基于内存状态的驱动式渲染
- **Deployment**: GitHub Pages

---

## 🚀 如何使用

1. **访问地址**：点击顶部的 [Live Demo] 即可打开项目  
2. **筛选会议**：通过顶部按钮切换不同会议类型  
3. **搜索定位**：输入关键词快速查找相关会议  
4. **查看详情**：点击时间轴节点或年份，查看对应会议内容  

---

## 📂 项目结构

```text
china-congress-timeline/
│
├─ index.html    # 页面结构与核心容器
├─ style.css     # 布局、主题与视觉样式
├─ script.js     # 状态管理、渲染与交互逻辑
└─ data.js       # 会议数据定义
