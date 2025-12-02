---
# 布局模式：首页
layout: home

# 1. 顶部 Hero 区域 (最显眼的大标题)
hero:
  name: "Project Name"
  text: "项目复盘与技术沉淀"
  tagline: "从零开始构建，记录开发过程中的每一个踩坑与高光时刻。"
  
  # 这里的图片可以换成你自己的 logo，或者直接用 emoji 代替
  image:
    src: https://vitepress.dev/vitepress-logo-large.webp
    alt: 项目Logo

  # 两个核心按钮
  actions:
    - theme: brand
      text: 🚀 开始阅读
      link: /guide/getting-started
    - theme: alt
      text: 🐙 GitHub 源码
      link: https://github.com/你的用户名/你的仓库名

# 2. 特性网格区域 (即使不写代码，这里也能配出漂亮的九宫格)
features:
  - icon: 💡
    title: 项目背景
    details: 为什么要做这个项目？解决了什么痛点？这里记录最初的灵感与需求分析。
  - icon: 🛠️
    title: 技术栈
    details: Vue 3 + VitePress + GitHub Actions。零成本部署，极致的文档体验。
  - icon: 🧩
    title: 核心模块
    details: 详细拆解系统的各个功能模块，从前端组件到后端逻辑的完整复盘。
  - icon: 🐞
    title: 踩坑记录
    details: 那些年我们修过的 Bug。记录开发过程中遇到的难题与最终解决方案。
  - icon: ⚡
    title: 性能优化
    details: 如何让项目跑得更快？记录加载速度优化与代码重构的心得。
  - icon: 📝
    title: 持续更新
    details: 文档将随着项目迭代长期维护，欢迎订阅关注最新的开发动态。

---

<div style="text-align: center; margin-top: 40px;">

## 🎯 关于本站

这是一个纯静态的文档站点，用于记录我个人项目的全生命周期。
这里没有复杂的废话，只有**真实的开发经验**和**可复用的代码片段**。

> "好记性不如烂笔头，把代码写成文档，是程序员进阶的必经之路。"

</div>

### 📚 快速导航

- **[新手入门](/guide/getting-started)**：如何运行本项目？
- **[架构设计](/guide/architecture)**：系统是如何搭建的？
- **[部署指南](/guide/deploy)**：如何把项目发布到线上？

<br>
<hr>
<br>

<div style="display: flex; gap: 20px; justify-content: center; align-items: center;">
  <span>By <b>你的名字</b></span>
  <span>|</span>
  <span>2024 Project Review</span>
</div>
