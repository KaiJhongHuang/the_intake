# AI工作流日報 — 2026-11-25
> 涵蓋範圍：2026-11-24 06:00 ~ 2026-11-25 06:00 (TST)

> 📌 Claude 摘要：Anthropic 在 MCP 兩週年發布重大協定擴展，Skills over MCP 進入公測、Tasks 與 Elicitation 正式 GA，MCP SDK 月下載量突破七億；ANT 第四個交易日跌破 $83 IPO 價，創辦人各售 $2.8 億股份引發市場關注；Canva MCP 全面開放，設計工具正式接入 AI 代理生態。

## 🧠 Prompt 技巧 & 使用心得

[1] **Skills over MCP 公測**：MCP 伺服器可隨工具發布技能指引，Claude 按需載入，Pro/Max/Ultra 預設啟用。([來源](https://claude.com/resources/articles/skills-over-mcp-tasks-and-more))

[2] **Elicitation 正式 GA**：MCP 伺服器可暫停執行向使用者請求結構化輸入，填完後自動續行工作流。([來源](https://alphasignal.ai/news/anthropic-expands-mcp-with-skills-background-tasks-and-direct-file-transfers))

[3] **Ship 後續實測心得**：社群開始實測 approvals.yml 政策檔，發現需精確定義路徑與規則才能避免誤核准。([來源](https://dev.to/kargatharaaakash/how-to-try-claude-ship-today-ship-a-starter-approvalsyml-and-the-settings-that-decide-what-5655))

## 🔧 工作流整合案例

[4] **MCP Tasks 正式 GA**：伺服器可啟動背景長時任務，Claude 同時繼續處理其他工作，ZoomInfo 為首批用戶。([來源](https://fourweekmba.com/ai-anthropic-makes-mcp-tasks-ga-in-claude-10000-connectors/))

[5] **Canva MCP 全面開放**：設計工具 MCP 端點取消候補名單，所有開發者可自助接入 AI 代理。([來源](https://www.canva.dev/blog/developers/canva-mcp-ga/))

[6] **MCP SDK 月下載破七億**：Anthropic 公布 MCP SDK 月下載量達七億次，Claude 連接器超過一萬個。([來源](https://the-decoder.com/anthropic-tops-700-million-monthly-mcp-sdk-downloads-and-expands-the-protocol-for-more-autonomous-ai-agents))

[7] **LeanData MCP 上線**：Go-to-market 排程與編排工具接入 Claude 與 ChatGPT，可直接操作路由規則。([來源](https://www.rutlandherald.com/news/business/leandata-introduces-mcp-bringing-orchestration-and-scheduling-into-claude-and-chatgpt/article_a40fad24-77c0-56d0-b7f6-e4e071f7d7b2.html))

## 🛠️ 新工具 & 套件

[8] **Opus 4.5 淘汰日到期**：官方標示退役日「不早於 11/24」，建議遷移至 Opus 5 或 5.5。([來源](https://platform.claude.com/docs/en/models/opus-4-5/overview))

[9] **GanttPRO MCP 套件**：npm 套件 @redcollar/ganttpro-mcp 包裹 REST API，可從 Claude Code 操作專案排程。([來源](https://www.pkgstats.com/pkg:@redcollar/ganttpro-mcp))

## 💬 社群熱門討論

[10] **ANT 跌破 $83 IPO 價**：第四個交易日 ANT 盤中跌至約 $79，收盤約 $82，較首日收盤 $97 跌逾 15%。([來源](https://www.fastcompany.com/91648273/ant-stock-is-down-why-anthropic-shares-dipped-below-ipo-price))

[11] **Amodei 兄妹各售 $2.8 億**：SEC 文件顯示 CEO 與總裁各以 IPO 價 $83 向承銷商出售約 338 萬股。([來源](https://finance.yahoo.com/markets/stocks/articles/dario-daniela-amodei-sold-280-125759121.html))

[12] **MCP 兩週年里程碑引討論**：社群關注 MCP 從協定到生態的爆發式成長，七億下載與萬級連接器成焦點。([來源](https://agentpedia.codes/blog/mcp-turns-two-skills-over-mcp-tasks-elicitation))
