# GPT Image 2 提示词深度指南

[![Awesome](https://awesome.re/badge.svg)](https://github.com/EvoLinkAI/awesome-gpt-image-2-API-and-Prompts)

基于 [EvoLinkAI/awesome-gpt-image-2-API-and-Prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-API-and-Prompts) 仓库整理的中文版提示词指南，收录 **291 精选案例**（均为真实生成图片），覆盖 7 大类别。

> 在线浏览：[在线浏览](https://autoa2a.github.io/autoa2a-image/) | 来源站点：[www.autoa2a.org](https://www.autoa2a.org)

---

## 目录

- [简介](#简介)
- [什么是 GPT Image 2？](#什么是-gpt-image-2)
- [最新动态](#最新动态)
- [API 使用指南](#api-使用指南)
- [案例分类](#案例分类)
  - [海报与插画 (91)](#海报与插画)
  - [人像与摄影 (51)](#人像与摄影)
  - [UI 与社交媒体 (56)](#ui-与社交媒体)
  - [模型对比 (47)](#模型对比)
  - [广告创意 (16)](#广告创意)
  - [电商 (19)](#电商)
  - [角色设计 (11)](#角色设计)
- [如何贡献](#如何贡献)
- [来源](#来源)

---

## 简介

**Awesome GPT Image 2 API and Prompts** 是一个精心策划的 GPT-Image-2 高质量提示词集合，包含 API 使用模式和可复用的视觉工作流。

你将在这里找到：

- 🎯 覆盖 7 大类别的生产级提示词（人像、海报、UI、电商、广告创意、角色设计、对比）
- 🔌 GPT Image 2 API 集成指南和可调用技能
- 📸 每个提示词案例的真实输出图片

---

## 什么是 GPT Image 2？

**GPT Image 2**（也称 GPT-Image-2 或 gpt-image-2）是 OpenAI 最新的图像生成与编辑模型，原生集成于 ChatGPT 并通过 OpenAI API 开放。

**核心能力：**

| 能力 | 说明 |
|------|------|
| 文生图 | 通过自然语言提示词创建照片级真实感图像、插画、海报、UI 模型等 |
| 图像编辑 | 通过文字指令修改已有图像（修复、扩展、风格迁移） |
| 多轮对话 | 在对话中迭代优化图像 |
| 高保真文字渲染 | 在生成图像中精确渲染文字 |
| 角色一致性 | 跨多次生成保持角色形象一致 |

**开发者选择 GPT Image 2 API 的原因：**
- 一个 API 调用同时完成生成和编辑
- 比之前模型更强的提示词遵循度
- 原生支持宽高比、透明度和批量生成
- 兼容 OpenAI 标准 API 格式（/v1/images/generations）

---

## 最新动态

| 日期 | 更新内容 |
|------|---------|
| 2026-05-19 | 新增 23 个案例（13 人像、8 海报、2 UI） |
| 2026-05-12 | 新增 12 个案例（2 人像、9 海报、1 UI） |
| 2026-05-11 | 新增 16 个案例（5 人像、8 海报、3 广告创意） |
| 2026-05-10 | 新增 19 个案例（4 人像、11 海报、3 UI、1 对比） |
| 2026-05-09 | 新增 19 个案例（6 人像、12 海报、1 对比） |
| 2026-05-08 | 新增 36 个案例（24 人像、6 海报、6 UI） |
| 2026-05-07 | 新增 20 个案例（10 人像、9 海报、1 UI） |
| 2026-05-06 | 新增 7 个案例（2 人像、5 海报） |
| 2026-05-05 | 新增 12 个案例（4 人像、5 海报、3 UI） |
| 2026-05-03 | 新增 10 个案例（1 电商、1 广告、3 人像、2 海报、3 UI） |
| 2026-05-02 | 新增 18 个案例（3 人像、7 海报、4 UI、4 对比） |
| 2026-04-30 | 新增 9 个案例（3 人像、1 海报、3 UI、2 对比） |
| 2026-04-29 | 新增 22 个案例（3 电商、3 广告、4 人像、2 角色、9 海报、1 对比） |
| 2026-04-18 | 仓库首次发布，收录精选案例集 |

---

## API 使用指南

### 快速安装技能

前往 [gpt-image-2-gen-skill](https://github.com/EvoLinkAI/gpt-image-2-gen-skill) 仓库：

`ash
npx evolink-gpt-image -y
`

### 快速连接 API

`ash
curl --request POST \
  --url https://api.evolink.ai/v1/images/generations \
  --header 'Authorization: Bearer YOUR_API_KEY' \
  --header 'Content-Type: application/json' \
  --data '{
  "model": "gpt-image-2",
  "prompt": "A beautiful colorful sunset over the ocean"
}'
`

- [获取 API Key](https://api.evolink.ai)
- [阅读 API 文档](https://docs.evolink.ai)

---

## 案例分类

### 海报与插画

**161 个精选案例** — 涵盖城市主题海报、节日宣传、品牌视觉、插画风格等各类平面设计场景。

### 人像与摄影

**133 个精选案例** — 从便利店街头摄影到高端时尚编辑大片，覆盖多种摄影风格和人像效果。

### UI 与社交媒体

**80 个精选案例** — 移动应用界面设计、网页模型、社交媒体帖子模板等数字产品视觉设计。

### 模型对比

**57 个精选案例** — 展示 GPT Image 2 与其他模型的生成效果对比、风格迁移实验。

### 广告创意

**31 个精选案例** — 商业广告海报、产品宣传图、品牌视觉方案等营销创意内容。

### 电商

**20 个精选案例** — 产品主图、详情页设计、促销海报等电商视觉素材。

### 角色设计

**13 个精选案例** — 动漫角色、3D 角色、IP 形象设计等角色创作方向。

---

## 如何贡献

欢迎通过以下方式参与贡献：

1. **提交新案例**：Fork 本仓库，添加你的 GPT Image 2 提示词和效果图，提交 Pull Request
2. **改进文档**：修正翻译错误、补充说明、优化格式
3. **分享反馈**：通过 Issues 提出建议或报告问题

---

## 来源

- [EvoLinkAI/awesome-gpt-image-2-API-and-Prompts](https://github.com/EvoLinkAI/awesome-gpt-image-2-API-and-Prompts) (CC0-1.0 License)
- [www.autoa2a.org](https://www.autoa2a.org)

> 整理日期：2026年7月1日 · 基础数据来自 EvoLinkAI 仓库，已整理为中文版
*（内容由AI生成，仅供参考）*
