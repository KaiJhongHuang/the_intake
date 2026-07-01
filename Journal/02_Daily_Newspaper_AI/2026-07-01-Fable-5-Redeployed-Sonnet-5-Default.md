# AI工作流日報 — 2026-07-01
> 涵蓋範圍：2026-06-30 06:00 ~ 2026-07-01 06:00 (TST)

> 📌 Claude 摘要：今日最大事件是 Fable 5 在出口管制解除後正式全球復活，搭載新的網路安全分類器可封鎖 99% 已知越獄手法；同步 Claude Code v2.1.197 將 Sonnet 5 設為預設模型。生態面 X 平台推出官方 MCP Server，MCP Python SDK v2 進入 beta。整體方向：旗艦模型回歸搭配安全強化，Sonnet 5 以低價高效接管日常代理工作流。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fable 5 新分類器封鎖越獄達 99%**：針對 Amazon 研究員發現的漏洞訓練專屬安全分類器，但可能誤擋部分良性安全請求。([來源](https://www.anthropic.com/news/redeploying-fable-5))

[2] **Sonnet 5 新分詞器多吃 30% tokens**：相同文本在 Sonnet 5 下產生約多三成 token，開發者需重新評估成本與上下文預算。([來源](https://platform.claude.com/docs/en/about-claude/models/whats-new-sonnet-5))

[3] **Sonnet 5 諂媚與幻覺率低於 4.6**：官方基準顯示 Sonnet 5 不良行為（配合濫用、欺騙、諂媚）發生率均低於前代。([來源](https://www.anthropic.com/news/claude-sonnet-5))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.197 預設切換至 Sonnet 5**：原生 1M 上下文，入門價 $2/$10 per Mtok 至 8/31，支援組織預設模型設定。([來源](https://x.com/ClaudeCodeLog/status/2072020221003481382))

[5] **X 平台推出官方 MCP Server**：讓 Claude Code、Cursor、Grok Build 等 MCP 相容工具透過使用者帳號權限直連 X API。([來源](https://techcrunch.com/2026/06/30/x-now-offers-an-mcp-server-to-make-its-platform-easier-for-ai-tools-to-use/))

[6] **MCP Python SDK v2 beta 發布**：無狀態核心配合 HTTP 傳輸必帶 Mcp-Method 標頭，穩定版預計 7/27 發布。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))

## 🛠️ 新工具 & 套件

[7] **Fable 5 全球復活**：美商務部解除出口管制，7/1 起 Claude.ai、Claude Code、Cowork 全平台可用，附臨時用量上限。([來源](https://9to5google.com/2026/07/01/anthropic-fable-5-returns-to-claude/))

[8] **Mythos 5 同步解禁**：恢復對 Project Glasswing 合作夥伴的防禦性網安用途存取。([來源](https://www.cnbc.com/2026/06/30/anthropic-says-trump-admin-has-lifted-export-controls-on-claude-fable-5-and-mythos-5.html))

[9] **Cursor 手機版上線 App Store**：付費訂閱者免費使用，7/5 前 Composer 2.5 打 75 折。([來源](https://www.techrepublic.com/article/news-spacex-cursor-ai-coding-agents-iphone/))

[10] **Claude Code 背景工作階段可靠性提升**：長時間指令與工作流在程序重啟後可續跑，Windows 端改為背景交接而非終止。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 💬 社群熱門討論

[11] **HN 熱議 Fable 5 復活與安全限制取捨**：部分開發者擔憂新分類器過度過濾合法安全研究用途。([來源](https://news.ycombinator.com/item?id=48463808))

[12] **Coding Agent 生態走向可組合堆疊**：The New Stack 分析 Cursor、Claude Code、Codex 形成編排-執行-審查三層分工而非單一工具整合。([來源](https://thenewstack.io/ai-coding-tool-stack/))

[13] **Simon Willison「Hack Your Summer」第二梯開放**：免費參加，7/13 開課、7/8 截止報名，教授 AI 工具實作技巧。([來源](https://simonwillison.net/2026/Jun/28/hack-your-summer/))
