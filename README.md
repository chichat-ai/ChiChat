# ChiChat

**Build your own AI companion, piece by piece.**

<img width="1440" height="1066" alt="ChiChat-cantonese-burst-11" src="https://github.com/user-attachments/assets/4efe0a6c-4475-4cce-98af-59d6e55ef693" />
<p align="center">
  <img width="300" alt="localhost_8081_chat (4)" src="https://github.com/user-attachments/assets/ecb9cd14-012f-4390-90bd-7a71a5194416" />
  <img width="300" alt="localhost_1113_chat" src="https://github.com/user-attachments/assets/aab6cfab-36be-4c76-80e2-f52377d9d63f" />
</p>
<p align="center">
  <img height="300" alt="Artboard-3-copy-16" src="https://github.com/user-attachments/assets/c7ae8aa6-a3c3-43ea-9bd6-bbabdc2f090c" />
  <img height="300" alt="Artboard 3 copy 2" src="https://github.com/user-attachments/assets/620b1b0d-807c-46a9-81a7-9e73608db769" />
  <img height="300" alt="Artboard 3 copy 14" src="https://github.com/user-attachments/assets/48056209-675d-4d4c-8a95-a3d4bc24610c" />
  <img height="300"  alt="Simulator Screenshot - iPhone 17 Pro Max - 2026-05-24 at 16 48 46" src="https://github.com/user-attachments/assets/f8257d66-add6-4211-bc25-39ea6c30afa4" />
<img height="300"  alt="Simulator Screenshot - iPhone 17 Pro Max - 2026-05-24 at 16 46 46" src="https://github.com/user-attachments/assets/1fd4abc1-bea7-4e61-9809-e57bf33b5c23" />
<img height="300"  alt="Simulator Screenshot - iPhone 17 Pro Max - 2026-05-24 at 16 46 29" src="https://github.com/user-attachments/assets/76ac3666-c897-4061-a87d-e2ad0f415f06" />  
</p>
<p align="center">
  <img width="300" alt="Artboard 14 copy 2" src="https://github.com/user-attachments/assets/dc74e770-a4a4-4073-b24e-c09e68111506" />
  <img width="400" alt="Artboard 16 copy 4" src="https://github.com/user-attachments/assets/be3857b1-7818-4f92-99f0-0b0093f8c2d8" />
</p>

ChiChat is a highly customizable AI chatbot and AI companion experience for everyday users. Instead of giving everyone the same assistant, ChiChat lets people assemble their own AI companion like Lego: choose the model, voice, language style, personality, memory, and interaction mode.

Most AI chatbots are fixed: one default model, one default voice, one default personality, and one default way to interact. ChiChat goes in the opposite direction. It treats AI companions as something people can shape, personalize, and continuously evolve.

ChiChat supports custom LLMs, voice-first conversations, Cantonese voice interaction, customizable personalities, custom prompts, and modular chatbot building. It is designed for non-technical users who want an AI that feels personal, flexible, and alive — not just a generic assistant.

You can use ChiChat to create a Cantonese-speaking AI companion, a voice-based AI friend, a study partner, a language practice partner, a roleplay character, a productivity buddy, or a custom assistant for daily routines.

Cantonese voice is an important part of ChiChat. Cantonese is not just a translation layer; it carries rhythm, intimacy, humor, identity, and cultural context. ChiChat aims to make Cantonese-speaking AI companions feel more natural, expressive, and personal.

ChiChat is currently in active development. This repository is used as the public product home for product direction, updates, technical notes, and launch materials. ChiChat is not currently open source.

---

# ChiChat 中文介绍

**像拼乐高一样，构建属于你自己的 AI 伙伴。**

ChiChat 是一个面向普通用户的高度自定义 AI 聊天机器人 / AI 伙伴产品。我们不想让每个人都使用同一个标准化助手，而是希望用户可以像拼乐高一样，自由组合不同的大模型、声音、语言风格、人格、记忆和交互方式，构建真正适合自己的 AI 伙伴。

大多数 AI 聊天机器人都是固定的：一个默认模型、一个默认声音、一个默认人格，以及一种默认交互方式。ChiChat 选择相反的方向。我们认为 AI 伙伴不应该是固定模板，而应该是可以被用户塑造、个性化，并且持续进化的。

ChiChat 支持自定义大语言模型、语音优先聊天、广东话 / 粤语语音交互、自定义人格、自定义提示词，以及模块化的聊天机器人搭建体验。它面向非技术用户设计，不需要用户下载代码、编译项目或配置复杂系统。

你可以用 ChiChat 创建一个会说广东话 / 粤语的 AI 伙伴、一个可以语音聊天的 AI 朋友、一个学习搭子、一个语言练习伙伴、一个角色扮演对象、一个效率助手，或者一个适合日常生活习惯的自定义助手。

广东话 / 粤语语音是 ChiChat 很重要的一部分。广东话不只是普通话或英文的翻译版本，它有自己的节奏、亲切感、幽默感、身份认同和文化语境。ChiChat 希望让广东话 AI 伙伴变得更自然、更有表达力，也更贴近用户自己。

ChiChat 目前正在积极开发中。这个仓库目前作为 ChiChat 的公开产品主页，用于展示产品方向、更新记录、技术说明和发布材料。ChiChat 目前暂未开源。

---

# 20260523

**2026年5月23日 重要更新**

### 自定义模型与助手
- **自定义大语言模型 API** —— 可接入你偏好的模型服务，按使用场景灵活切换。
- **助手专属设定** —— 支持为不同助手配置专属模型与语音风格，让每个助手更贴合具体任务。

### 创作与预览体验
- **多格式内容预览** —— 支持 HTML、Mermaid、ECharts、SVG 预览，图表、流程与页面内容展示更直观。
- **设备语音播报** —— 支持调用设备内置语音能力，带来多语言、连贯自然的朗读体验。

### 性能与稳定性
- **串流处理优化** —— 提升长内容输出时的响应速度与连接稳定性。
- **整体架构调优** —— 深度优化运行性能，进一步提升日常使用的流畅度与可靠性。

---

## Links

- Website: https://ChiChat.ai

## License / 许可

Copyright © 2026 ChiChat LLC. All rights reserved.

This repository is a public product page for ChiChat and does not include source code. All product descriptions, screenshots, images, brand assets, and related materials are owned by ChiChat LLC.

版权所有 © 2026 ChiChat LLC。保留所有权利。

本仓库是 ChiChat 的公开产品展示页，不包含源代码。所有产品介绍、截图、图片、品牌素材及相关内容归 ChiChat LLC 所有。
