# AI工作流日報 — 2026-06-01
> 涵蓋範圍：2026-05-31 06:00 ~ 2026-06-01 06:00 (TST)

> 📌 Claude 摘要：Anthropic 正式向 SEC 提交 S-1 機密文件，成為首家啟動 IPO 的主要 AI 實驗室，年化營收達 $470 億。Claude Code 連發 v2.1.157-158 兩版，plugin 自動載入與 Auto mode 登陸三大雲端。六月 15 日計費分池倒數中，Simon Willison 則轉貼文章反思 AI 訂閱引發的專案蔓延現象。

## 🧠 Prompt 技巧 & 使用心得

[1] **AI 訂閱催生專案蔓延**：Willison 轉貼文章指出 AI 輕鬆啟動 16+ 專案，多數非本意產物。([來源](https://simonwillison.net/2026/May/31/the-solution-might-be-cancelling-my-ai-subscription/))

[2] **多工具組合成主流模式**：資深工程師日常同時搭配 Cursor + Claude Code + Codex 三工具分工協作。([來源](https://thenewstack.io/claude-code-vs-cursor-vs-codex-vs-antigravity-2026/))

## 🔧 工作流整合案例

[3] **v2.1.158 Auto mode 擴展三雲端**：Auto mode 登陸 Bedrock、Vertex 與 Foundry，設環境變數即可啟用。([來源](https://releasebot.io/updates/anthropic/claude-code))

[4] **v2.1.157 Plugin 自動載入**：.claude/skills 目錄下 plugin 免 marketplace 自動載入，`claude plugin init` 一鍵搭建。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.157))

[5] **六月 15 日計費分池倒數**：Agent SDK、claude -p 與第三方代理移至獨立額度池，手動 CLI 不受影響。([來源](https://codersera.com/blog/anthropic-june-2026-billing-change-claude-code/))

## 🛠️ 新工具 & 套件

[6] **Datasette 1.0a32 發布**：Willison 開源數據探索工具新版，持續強化 AI 代理對話介面。([來源](https://simonwillison.net/2026/May/31/datasette/))

[7] **ServiceNow Build Agent GA**：正式入駐 Cursor、Claude Code、Copilot 等主流編碼工具。([來源](https://newsroom.servicenow.com/press-releases/details/2026/ServiceNow-Build-Agent-now-works-inside-every-major-AI-coding-tool-governed-by-default/default.aspx))

## 💬 社群熱門討論

[8] **Anthropic 提交 S-1 啟動 IPO**：$9,650 億估值首家遞件 AI 實驗室，搶先 OpenAI 與 SpaceX。([來源](https://www.cnbc.com/amp/2026/06/01/anthropic-ipo-s1-prospectus.html))

[9] **Reuters 揭營收年化計算法**：消費制取 28 天銷售×13 加訂閱月費×12，合計年化 $470 億。([來源](https://simonwillison.net/2026/May/31/anthropic-run-rate/))

[10] **HN 熱議「Claude 非你的架構師」**：開發者警告不應讓 AI 主導系統架構決策，引發正反辯論。([來源](https://news.ycombinator.com/item?id=48259784))
