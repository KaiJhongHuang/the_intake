# AI工作流日報 — 2026-11-20
> 涵蓋範圍：2026-11-19 06:00 ~ 2026-11-20 06:00 (TST)

> 📌 Claude 摘要：ANT掛牌Nasdaq首日收$97.17漲17%估值$1.76T，v2.1.328將auto mode擴展至Bedrock/Foundry/Vertex全雲端，Microsoft Ignite推Copilot Autopilot自主代理，Cognition發布Devin Bots多代理管理器挑戰Duet與Dots，主要銀行陸續限制第三方AI代理帳戶存取——AI代理正從工具轉為需要治理框架的「數位員工」。

## 🧠 Prompt 技巧 & 使用心得

[1] **v2.1.328 auto mode全雲端**：Opus/Sonnet 4.6在Bedrock、Foundry、Vertex及閘道均可跳過權限提示，加速無人值守工作流。([來源](https://x.com/ClaudeCodeLog/status/2123226990551445634))

[2] **mcp_tool hooks支援onFailure: block**：v2.1.328新增MCP工具hook失敗阻斷，出錯時自動擋下後續動作防止連鎖錯誤。([來源](https://github.com/anthropics/claude-code/releases))

[3] **/code-review精簡輸出**：多數模型現僅報告bug與CLAUDE.md違規，減少雜訊提升審查效率。([來源](https://clauding.de/en/posts/claude-code-2-1-328-auto-mode-drittanbieter/))

## 🔧 工作流整合案例

[4] **Copilot Autopilot上線**：Microsoft Ignite發表持久自主代理，擁有Entra身分與記憶，Frontier客戶已開始接收。([來源](https://microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work))

[5] **Wells Fargo AI代理責任歸客戶**：11/24生效新條款明定第三方AI代理活動風險由用戶自負，須主動通知撤銷。([來源](https://www.americanbanker.com/news/wells-fargo-wants-customers-to-prove-theyve-revoked-ai-agents))

[6] **Citi禁第三方AI代理登入帳戶**：僅允許核准開放銀行供應商以唯讀方式存取資料，BoA亦研擬責任協議。([來源](https://thepaypers.com/fintech/news/citi-and-bank-of-america-restrict-ai-agents-from-accessing-accounts))

## 🛠️ 新工具 & 套件

[7] **Cognition Devin Bots**：持久多代理管理器拆解大型專案分派Devin實例，beta用戶PR合併量增4.5倍。([來源](https://fortune.com/2026/11/17/exclusive-cognition-bets-on-devin-bots-coding-agents-in-challenge-to-anthropics-duet-and-openais-dots/))

[8] **AG-UI Protocol 16.4K星**：開放事件協定連接AI代理與web/mobile/terminal前端，已整合Claude Agent SDK。([來源](https://github.com/ag-ui-protocol/ag-ui))

[9] **Cursor Plugins市集開放**：Agent Plugin開放標準上線，Superpowers技能庫提供TDD、除錯與平行代理方法論。([來源](https://cursor.com/en-US/marketplace))

## 💬 社群熱門討論

[10] **ANT掛牌首日收$97.17漲17%**：IPO定價$83募$813億史上最大，開盤$111.50尾盤回落，全日估值$1.76T。([來源](https://www.forbes.com/sites/fionariley/2026/11/19/anthropic-ipo-live-stock-closes-day-at-97-up-more-than-17/))

[11] **Gemini 4 Neon現身程式碼**：Google網頁端出現Neon模型引用，推測為新Flash Lite層級，尚未正式發布。([來源](https://nokiapoweruser.com/gemini-4-neon-spotted-google-ai-rumors/))

[12] **Willison發布代理沙盒原型**：為Claude Code、Codex、Pi設計三套外部沙盒，減少持續核准提示導致的安全疲勞。([來源](https://simonwillison.net/))
