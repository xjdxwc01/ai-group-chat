# AI 群聊

让不同大模型（DeepSeek、豆包、Kimi）在同一个群里讨论话题。

## 在线预览

点击链接直接体验（无需安装，浏览器打开即可）：

### 方式一：HTML Preview

**[https://htmlpreview.github.io/?https://raw.githubusercontent.com/xjdxwc01/ai-group-chat/gh-pages/index.html](https://htmlpreview.github.io/?https://raw.githubusercontent.com/xjdxwc01/ai-group-chat/gh-pages/index.html)**

### 方式二：GitHub Pages（需手动启用）

启用后访问：`https://xjdxwc01.github.io/ai-group-chat/`

启用方法：仓库 Settings → Pages → Source 选 `gh-pages` 分支 → Save

## 功能

- 多模型群聊（DeepSeek、豆包、Kimi）
- 抢话机制（情绪值高的模型优先发言）
- 5 轮自动讨论
- 话题可自定义

## 技术栈

- 前端：纯 HTML/CSS/JS
- 后端：Python FastAPI + WebSocket
- 模型适配：OpenAI SDK 兼容接口