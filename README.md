# TinymarksProject

# Tinymarks

## 理念 | Vision
### 中文
Tinymarks 是“生命的档案馆”，基于 Nostr 协议，铭刻每个平凡人的微小生命痕迹，防止“第二次死亡”（被遗忘）。受《秋园》和《寻梦环游记》启发，我们记录单一主人公的核心价值、情感联结或独特痕迹，通过去中心化存储和社区共鸣，让逝者在文明记忆中永存。用户可倾诉亲人故事，感受“Ta被珍视”，以 500 字符文本、记忆致敬、微评构建温暖空间。

### English
Tinymarks is a "museum of lives," built on the Nostr protocol, etching every ordinary person's tiny life marks to prevent their "second death" (being forgotten). Inspired by *The Autumn Garden* and *Coco*, we capture a single protagonist's core values, emotional bonds, or unique traces. Through decentralized storage and community resonance, the deceased live on in civilization’s memory. Users share loved ones’ stories, feeling "they are cherished," with 500-character stories, tributes, and micro-comments.

## 功能 | Features
- 上传 ≤500 字符的故事（分段：背景、故事、意义） | Stories ≤500 characters (background, story, meaning)
- 记忆致敬（心形计数） | Memory tributes (heart counter)
- 微评（≤10 字符，≤3 条） | Micro-comments (≤10 characters, ≤3 per story)
- 标签分类，热门记忆页面 | Tag-based discovery, popular memories page
- 去中心化存储（Nostr 协议） | Decentralized storage (Nostr protocol)
- 中文/英文支持，预留 Crowdin 翻译 | Chinese/English support, Crowdin integration planned

## 路线图 | Roadmap
### 阶段 1（0-1 个月 | 0-1 Month）
- 发布静态 demo：React + Tailwind CSS，模拟故事上传/展示。
- 集成 Nostr 协议，连接公共中继（如 wss://relay.damus.io）。
- GitHub 开源，招募翻译和插件开发者。

### 阶段 2（1-3 个月 | 1-3 Months）
- 实现 Nostr 事件（kind: 1000 故事，kind: 7 致敬，kind: 1 微评）。
- 添加 NIP-04 加密审核，NIP-29 群聊共鸣。
- 集成 Crowdin，支持多语言翻译。

### 阶段 3（3-6 个月 | 3-6 Months）
- 支持 IPFS 备份，增强数据永存。
- 开发插件：纪念日提醒、AI 创作模板。
- 举办“记忆之光”活动，推广感人故事。

## 部署 | Deployment
1. 克隆：`git clone https://github.com/tinymarks/tinymarks.git`
2. 安装 Vercel CLI：`npm install -g vercel`
3. 部署：`vercel`
4. 配置 Nostr 中继：默认 wss://relay.damus.io, wss://nos.lol。
5. 访问演示版本，体验故事上传/共鸣。

## 联系 | Contact
- 邮箱：tinymarks.project@proton.me
- X 平台：@Tinymarks (待创建)
