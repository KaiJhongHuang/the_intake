# AI工作流日報 — 2026-05-07
> 涵蓋範圍：2026-05-06 06:00 ~ 2026-05-07 06:00 (TST)

> 📌 Claude 摘要：Code w/ Claude 大會後續效應持續發酵——SpaceX/xAI Colossus 算力交易讓 Claude Code 限額翻倍，Managed Agents 三大新功能（Dreaming、多代理編排、Outcomes）正式亮相，Simon Willison 坦承 vibe coding 與 agentic engineering 的界線正在模糊。這是 Anthropic 基礎設施與產品層同時躍進的一天。

## 🧠 Prompt 技巧 & 使用心得
[1] **Boris Cherny 拒用「vibe coding」一詞**：Claude Code 負責人在 Code w/ Claude 大會表示厭倦該詞，讓 Claude 建議替代說法，產出「agentic engineering」。([來源](https://letsdatascience.com/news/claude-code-creator-rejects-vibe-coding-phrase-0a44b68d))
[2] **Simon Willison 坦承兩者正在融合**：他發文承認自己在生產級程式碼中已不再逐行審查 AI 產出，vibe coding 與 agentic engineering 界線模糊。([來源](https://simonwillison.net/2026/May/6/vibe-coding-and-agentic-engineering/))
[3] **CLAUDE.md 規劃技巧**：Medium 文章指出在 CLAUDE.md 加入「先陳述假設再寫程式」指令，可將 20 個決策點的正確率從約 1% 提升至接近 100%。([來源](https://medium.com/ai-systems-lab/claude-md-setup-tips-that-will-10x-your-claude-code-workflow-1d7d23793755))

## 🔧 工作流整合案例
[4] **SpaceX/xAI Colossus 算力交易**：Anthropic 簽約取得 Colossus 1 全部算力，逾 300MW、22 萬張 NVIDIA GPU，Claude Code 五小時限額即日翻倍。([來源](https://www.anthropic.com/news/higher-limits-spacex))
[5] **Managed Agents 三大新功能**：Dreaming（記憶整合自我改進）、多代理編排（最多 20 個平行專家）、Outcomes + Webhooks 於 Code w/ Claude 大會公布，均進入公測。([來源](https://claude.com/blog/new-in-claude-managed-agents))
[6] **Harvey 用 Dreaming 提升法律 Agent**：法律 AI 公司 Harvey 測試 Dreaming 後，Agent 任務完成率提升約六倍。([來源](https://www.digitaltrends.com/computing/anthropic-just-taught-claude-to-dream-between-tasks-and-it-makes-agents-meaningfully-smarter/))
[7] **n8n MCP 可由 Claude 直接建立工作流**：n8n 官方 MCP Server 現支援從自然語言描述建立、部署、除錯 n8n 工作流。([來源](https://blog.n8n.io/n8n-mcp-server/))

## 🛠️ 新工具 & 套件
[8] **Claude Code：Opus 4.7 為 Max/Team 預設模型**：新增 xhigh 努力等級，推薦用於大多數 agentic 編碼工作，兼顧智慧與 token 效率。([來源](https://releasebot.io/updates/anthropic/claude-code))
[9] **API 限額大幅調升**：Tier 1 每分鐘輸入 token 上限提升 1500%、輸出提升 900%，各層級均有顯著增加。([來源](https://9to5google.com/2026/05/06/claude-code-is-getting-higher-usage-limits-doubled-for-most-users/))
[10] **llm-gemini 0.31 發布**：Simon Willison 更新 LLM CLI 的 Gemini 插件至 0.31 版。([來源](https://simonwillison.net/2026/May/7/llm-gemini/))

## 💬 社群熱門討論
[11] **Colossus 環境爭議**：Simon Willison 指出 Colossus 1 的燃氣渦輪機曾未取得清潔空氣法許可即運轉，且與當地醫院就診率上升有關聯。([來源](https://simonwillison.net/2026/May/7/xai-anthropic/))
[12] **五角大廈 CTO 排除與 Anthropic 和解**：Pentagon CTO Emil Michael 重申 Anthropic 仍在黑名單，即使 Mythos 引發政府興趣也不改立場。([來源](https://thehill.com/policy/technology/5868214-pentagon-anthropic-mythos/))
[13] **「Dreaming」用語引發反彈**：批評者認為 Anthropic 以「做夢」命名 AI 功能，危險地模糊了軟體自動化與人類意識的界線。([來源](https://easternherald.com/2026/05/07/anthropic-dreaming-ai-humanized-machines-backlash/))
