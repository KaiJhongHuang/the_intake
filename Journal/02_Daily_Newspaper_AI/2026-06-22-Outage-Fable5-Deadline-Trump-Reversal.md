# AI工作流日報 — 2026-06-22
> 涵蓋範圍：2026-06-21 06:00 ~ 2026-06-22 06:00 (TST)

> 📌 Claude 摘要：今日焦點集中在 Claude 全球 90 分鐘大當機、Fable 5 免費存取最後一天、以及川普態度反轉不再視 Anthropic 為國安威脅。身份驗證政策 7/8 啟動引發隱私討論，Claude Code 持續迭代加入 Artifacts 與 Auto Mode 擴展至第三方雲端。

## 🧠 Prompt 技巧 & 使用心得

[1] **Fable 5 vs GPT-5.5 基準實測**：HN 討論顯示 Fable 5 規劃能力勝出，但程式執行表現兩者接近。([來源](https://news.ycombinator.com/item?id=48517973))

[2] **Fable 5 安全分類器過嚴**：社群反映合法資安工作流被拒絕，Anthropic 尚未回應調整時程。([來源](https://news.ycombinator.com/item?id=48492210))

[3] **Spec-Driven Development 工作流**：HN Show 專案示範用規格文件驅動 Claude Code 開發，減少來回修正。([來源](https://news.ycombinator.com/item?id=48231575))

## 🔧 工作流整合案例

[4] **Claude Code Artifacts 上線**：6/18 Beta 推出，開發 Session 可產出即時互動網頁，支援 PR 導覽、儀表板與 Checklist。([來源](https://venturebeat.com/data/anthropics-claude-code-artifacts-update-brings-live-shared-dashboards-and-interactive-workspaces-to-enterprises/))

[5] **Auto Mode 擴展至 Bedrock/Vertex/Foundry**：第三方雲端現可啟用 Auto Mode，以背景安全檢查取代權限彈窗。([來源](https://releasebot.io/updates/anthropic/claude-code))

[6] **sqlite-utils 4.0rc1 發布**：Simon Willison 6/21 釋出，整合 migrations 系統與 nested transactions，強化 AI 資料管線基礎工具。([來源](https://simonwillison.net/2026/Jun/21/sqlite-utils-40rc1/))

[7] **/design-sync 雙向同步**：Claude Design 與 Claude Code 間可匯入設計系統並即時同步變更。([來源](https://explainx.ai/blog/claude-design-june-2026-update-design-sync-2026))

## 🛠️ 新工具 & 套件

[8] **awesome-claude-code-toolkit**：135 agents、35 skills、176+ plugins 的 Claude Code 生態全集，GitHub 持續更新中。([來源](https://github.com/rohitg00/awesome-claude-code-toolkit))

[9] **trends-agent-claude MCP**：單一 MCP Server 連接 Google/YouTube/TikTok/Reddit/Amazon 等 10+ 趨勢數據源，免費層可用。([來源](https://github.com/trendsmcp/trends-agent-claude))

[10] **last30days-skill 登頂 Trending**：以 .mcpb 格式安裝的 AI agent 技能，可跨 Reddit/X/YouTube/HN 研究任意主題並產出摘要。([來源](https://github.com/mvanhorn/last30days-skill))

[11] **Claude Code /plugin list 指令**：新版加入 plugin 管理指令，配合 managed deployment 版本控制。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 💬 社群熱門討論

[12] **Claude 全球 90 分鐘大當機**：UTC 6/22 00:37 起五模型同時異常，含 Opus 4.8/4.7/4.6、Sonnet 4.6、Haiku 4.5，02:06 全面恢復。([來源](https://cybersecuritynews.com/anthropic-claude-ai-outage/))

[13] **川普不再視 Anthropic 為國安威脅**：G7 峰會與 Amodei 午餐後態度軟化，但商務部 6/12 禁令與五角大廈供應鏈限制仍未撤銷。([來源](https://www.cnbc.com/2026/06/19/trump-tells-axios-he-no-longer-views-anthropic-as-national-security-threat.html))

[14] **TechCrunch 深度分析：打壓 Anthropic 誰受益**：指出 Amazon CEO Jassy 向白宮通報 Fable 5 護欄繞過問題引爆連鎖效應。([來源](https://techcrunch.com/2026/06/21/when-the-trump-administration-cracks-down-on-anthropic-who-benefits/))

[15] **Fable 5 免費存取今日截止**：6/22 後 Pro/Max/Team/Enterprise 方案不再包含 Fable 5，改為按量計費（$10/$50 per M tokens）。([來源](https://www.developersdigest.tech/blog/claude-fable-5-june-22-deadline))

[16] **身份驗證 7/8 啟動**：消費者用戶可能需提供政府 ID 與自拍，委由 Persona 平台處理，觸發條件與拒絕後果均未公開。([來源](https://techcrunch.com/2026/06/22/anthropic-says-claude-may-want-to-see-your-id/))
