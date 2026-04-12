# AI工作流日報 — 2026-04-12
> 涵蓋範圍：2026-04-11 06:00 ~ 2026-04-12 06:00 (TST)

> 📌 Claude 摘要：HumanX 大會成 Claude 話題主場，Project Glasswing／Mythos 持續發酵；Claude Code v2.1.101 推出 `/team-onboarding` 切入企業導入痛點，GitNexus 以 Graph RAG MCP 登上 GitHub Trending 第一，社群焦點從「Agent 炫技」轉向「Context 工程」。此為 Claude 綜合觀察，非事實報導。

## 🧠 Prompt 技巧 & 使用心得

[1] **Context engineering 勝過 prompt 措辭**：社群共識，System prompt/memory/examples 架構比單句咒語更能拉高 Claude 品質。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

[2] **XML 標籤包多段指令**：使用 `<task>` `<context>` `<output_requirements>` 已成 Claude 內部慣例，外部使用者複製可提升結構化輸出。([來源](https://www.buildfastwithai.com/blogs/claude-ai-prompt-codes-2026))

[3] **單訊息批次多任務**：引用洩漏 Claude Code system prompt 發現——提示 Claude「同時處理多任務」觸發內建並行分派。([來源](https://www.dbreunig.com/2026/04/04/how-claude-code-builds-a-system-prompt.html))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.101 `/team-onboarding`**：從本地 Claude Code 使用紀錄自動產出新進同事入門指南，切入企業採購痛點。([來源](https://claude-world.com/articles/claude-code-21101-release/))

[5] **OS CA 憑證信任內建**：企業 TLS 代理無需額外設定即可使用，`/ultraplan` 遠端會話自動建立預設雲環境。([來源](https://www.mejba.me/blog/claude-code-2-1-101-release))

[6] **Claude Code 2.1.104 緊急微調**：2.1.101 發布後約 31 小時推出跟進版，調整 prompt token 分配與 bundle 體積。([來源](https://x.com/ClaudeCodeLog/status/2043203801172066470))

## 🛠️ 新工具 & 套件

[7] **GitNexus 登 GitHub Trending 第一**：Tree-sitter 解析程式庫成知識圖譜，透過 MCP 餵結構化上下文給 Claude Code／Cursor。([來源](https://blog.pebblous.ai/blog/gitnexus-code-knowledge-graph-2026/en/))

[8] **awesome-claude-plugins 指標庫**：n8n workflow 自動追蹤 Claude Code plugin 採用度，4/11 已索引 11,905 個 repo。([來源](https://github.com/quemsah/awesome-claude-plugins))

[9] **antigravity-awesome-skills 達 1,400+**：可跨 Claude Code／Cursor／Codex／Gemini CLI 安裝的 agentic skill 庫，近期新增 bundles 與官方 skill 集。([來源](https://github.com/sickn33/antigravity-awesome-skills))

[10] **Claude Mythos Preview 戰果更新**：Progressive Robot 彙整 6 大事實，Mythos 已在每個主流 OS／瀏覽器發現可利用零日。([來源](https://www.progressiverobot.com/2026/04/11/what-is-project-glasswing/))

## 💬 社群熱門討論

[11] **HumanX 會場「Claude 狂熱」**：CNBC 現場報導 6,500 名高管湧入 SF，OpenAI 失去話題主導權，Anthropic 展位被擠爆。([來源](https://www.cnbc.com/2026/04/11/vibe-check-from-ai-industry-humanx-anthropic-is-talk-of-the-town.html))

[12] **Simon Willison 讚 SQLite 3.53.0**：同日貼文聚焦 SQLite 新版，社群視為 Claude Code 本地持久化層的重要後端升級。([來源](https://simonwillison.net/2026/Apr/11/sqlite/))

[13] **紐時：Mythos 為何不公開**：RTÉ 轉述 NYT 深度報導，Anthropic 以全球網路安全風險為由，拒絕公開 Claude Mythos 權重。([來源](https://www.rte.ie/news/business/2026/0412/1567631-anthropic-claude-ai/))

[14] **Security Magazine 專家圓桌**：資安研究員評 Glasswing——擔憂 50 企業內測洩漏複製 Mythos 能力，敦促透明化稽核。([來源](https://www.securitymagazine.com/articles/102226-what-are-security-experts-saying-about-claude-mythos-and-project-glasswing))

[15] **Reddit 工作流實戰**：用戶分享「Reddit mining + Claude」驗證三個商業點子——LLM 介入把 signal/noise 拉高一個量級。([來源](https://medium.com/@mohit15856/i-used-reddit-claude-to-validate-3-business-ideas-in-one-week-cb190bfb39b1))
