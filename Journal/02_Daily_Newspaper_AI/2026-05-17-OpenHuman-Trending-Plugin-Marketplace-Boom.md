# AI工作流日報 — 2026-05-17
> 涵蓋範圍：2026-05-16 06:00 ~ 2026-05-17 06:00 (TST)

> 📌 Claude 摘要：本日焦點為 OpenHuman 登頂 GitHub Trending、Claude Code v2.1 plugin 生態持續壯大、以及 Code with Claude London 倒數兩天。Anthropic 在 Codex 競爭壓力下連續提升用量上限，開發者生態熱度不減。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Code Fast Mode 預設升級 Opus 4.7**：5/14 起 /fast 自動使用 Opus 4.7，輸出速度提升 2.5 倍，品質不變。([來源](https://code.claude.com/docs/en/fast-mode))

[2] **worktree.bgIsolation: "none" 設定上線**：背景 session 可直接編輯工作目錄，不需建立 worktree，適合大型 monorepo。([來源](https://code.claude.com/docs/en/changelog))

[3] **Projected context cost 估算加入 /plugin 瀏覽面板**：安裝 plugin 前可預覽每次呼叫的 token 成本估計。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例

[4] **OpenHuman 登頂 GitHub Trending**：本地優先開源桌面 AI Agent，串接 118+ 服務，7800 星，一週成長 150%。([來源](https://www.techtimes.com/articles/316731/20260516/agent-that-reads-you-first-openhuman-tops-github-trending-inverting-playbook.htm))

[5] **Code with Claude London 5/19 開幕**：三軌並行（Research / Platform / Code），加開 5/20 Extended 場給獨立開發者。([來源](https://claude.com/code-with-claude/london))

[6] **Claude Code 週用量上限提升 50%**：Pro/Max/Team/Enterprise 即日起至 7/13，堆疊先前 5hr 翻倍優惠，對抗 Codex 出走潮。([來源](https://pasqualepillitteri.it/en/news/2494/claude-code-weekly-limits-50-percent-anti-codex-anthropic-2026))

## 🛠️ 新工具 & 套件

[7] **Claude Code Plugin Marketplace 突破 4200 技能**：含 770+ MCP Server，月訪客 16 萬，plugin 依賴鏈自動管理上線。([來源](https://claudemarketplaces.com/))

[8] **Sakana AI RL Conductor（ICLR 2026）**：7B 模型用 RL 指揮 GPT-5、Claude Sonnet 4、Gemini 2.5 Pro 協作，GPQA-Diamond SOTA。([來源](https://venturebeat.com/orchestration/how-sakana-trained-a-7b-model-to-orchestrate-gpt-5-claude-sonnet-4-and-gemini-2-5-pro))

[9] **OpenHuman v0.53.43 安全疑慮浮現**：KnightLi 獨立評測指出安裝路徑與權限範圍過寬，社群建議先 sandbox 測試。([來源](https://www.knightli.com/en/2026/05/15/openhuman-open-source-personal-ai-agent/))

## 💬 社群熱門討論

[10] **Axios：Anthropic 收緊限制 vs OpenAI 搶 Agent 用戶**：第三方 harness 用量納入獨立計量，「吃到飽」AI 訂閱時代恐終結。([來源](https://www.axios.com/2026/05/14/anthropic-claude-price-openai-tokens))

[11] **Simon Willison 宣布 Datasette 官方 Blog**：用 Claude Code for Web 建置 iNaturalist 照片整合，展示 beats 系統。([來源](https://simonwillison.net/2026/May/13/welcome-to-the-datasette-blog/))

[12] **Claude Code v2.1 修復 MCP SSE 記憶體洩漏**：HTTP/SSE MCP Server 串流非協議資料時 response body 上限設為 16 MB。([來源](https://github.com/anthropics/claude-code/blob/main/CHANGELOG.md))
