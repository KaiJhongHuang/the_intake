# AI工作流日報 — 2026-06-25
> 涵蓋範圍：2026-06-24 06:00 ~ 2026-06-25 06:00 (TST)

> 📌 Claude 摘要：今日最大事件為 Anthropic 正式控告阿里巴巴 Qwen 團隊以 2.5 萬假帳號進行史上最大 Claude 蒸餾攻擊，Bloomberg 6/24 獨家曝光。Claude Tag 於 Slack 上線 beta，Anthropic 內部已有 65% 程式碼經由 Tag 產出。Claude Code v2.1.191 釋出 /rewind 指令與 37% CPU 串流節省。工程主管坦承 AI 協作使開發體驗趨於孤獨，推動配對程式改善團隊互動。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code「孤獨體驗」反思**：Anthropic 工程主管 Fiona Fung 坦承 Agent 密集使用讓工程師孤立，推配對程式與駭客松改善。([來源](https://fortune.com/2026/06/23/anthropic-engineering-head-claude-code-lonely-experience-big-tech-morale/))

[2] **browser-compat-db 資料轉換**：Simon Willison 6/24 用 Claude Code 將 Mozilla 瀏覽器相容性資料轉為 66MB SQLite，搭 Datasette Lite 即可查詢。([來源](https://simonwillison.net/2026/Jun/24/browser-compat-db/))

[3] **HN「你的 AI 開發技術棧？」**：熱議討論中多人推薦 Claude Code 配 tmux 管理多 Agent，搭規格驅動開發減少來回修正。([來源](https://news.ycombinator.com/item?id=48413629))

## 🔧 工作流整合案例

[4] **Claude Tag 上線 Slack Beta**：團隊可 @Claude 分派任務、接手半成品工作，具「ambient」主動追蹤功能，Anthropic 內部 65% 程式碼由 Tag 產出。([來源](https://www.anthropic.com/news/introducing-claude-tag))

[5] **MuleSoft MCP Connector 1.6**：新增 Elicitation（自動釐清需求）與 Structured Output（格式化 Agent 回應），降低生產環境歧義。([來源](https://blogs.mulesoft.com/news/mcp-connector-updates/))

[6] **Apple Foundation Models 整合 Claude**：LanguageModel 協定讓 iOS 27 開發者一行切換 Claude/Gemini，Xcode 27 內建 Claude 輔助寫碼。([來源](https://www.apple.com/newsroom/2026/06/apple-aids-app-development-with-new-intelligence-frameworks-and-advanced-tools/))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.191 發布**：新增 /rewind 指令可還原 /clear 前對話、修復背景 Agent 停止後復活 Bug、串流更新合併省 37% CPU。([來源](https://code.claude.com/docs/en/changelog))

[8] **zilliztech/claude-context**：MCP 語義程式碼搜尋外掛，為 Claude Code 提供完整 codebase 上下文，GitHub Trending 上升中。([來源](https://github.com/zilliztech/claude-context))

## 💬 社群熱門討論

[9] **阿里巴巴蒸餾攻擊曝光**：Anthropic 致函白宮與參議院，控 Qwen 團隊用 2.5 萬假帳號、2880 萬次交互蒸餾 Claude，為史上最大規模。([來源](https://www.cnbc.com/2026/06/24/anthropic-alibaba-distillation-campaign.html))

[10] **HN 討論 2026 開發工作流現狀**：多數回覆認為 Claude Code 搭 debian lxc 專機 + 規格驅動是現行最佳實踐，IDE 外掛式漸退。([來源](https://news.ycombinator.com/item?id=48445024))

[11] **Claude Tag 隱私疑慮**：TechCrunch 報導 Tag 會持續學習 Slack 頻道內容，社群擔憂企業敏感資訊外流風險。([來源](https://techcrunch.com/2026/06/23/anthropics-claude-tag-is-learning-your-company-one-slack-message-at-a-time/))
