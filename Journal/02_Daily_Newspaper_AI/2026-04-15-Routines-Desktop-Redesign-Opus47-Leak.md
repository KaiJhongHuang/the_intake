# AI工作流日報 — 2026-04-15
> 涵蓋範圍：2026-04-14 06:00 ~ 2026-04-15 06:00 (TST)

> 📌 Claude 摘要：本日三條主線——(1) Claude Code Routines 研究預覽正式上線，支援排程／API／GitHub 事件三種觸發，讓 prompt 在 Anthropic 雲端自行跑、不用開筆電；(2) Claude Code 桌面 app 大改版，同視窗多 session 平行、側邊欄、內建 terminal 與檔案編輯；(3) The Information 爆料 Opus 4.7 與 AI 設計工具（網站／簡報）本週上線，同日 Fortune／VentureBeat 集中報導「Claude 被 nerf」社群怒火，Boris Cherny 承認默認 effort 降至 medium。此為 Claude 綜合觀察，非事實報導。

## 🧠 Prompt 技巧 & 使用心得

[1] **Routine prompt 須完全自足**：每次執行 stateless，prompt 要寫明成功標準、失敗模式、輸出格式。([來源](https://claude.com/blog/introducing-routines-in-claude-code))

[2] **先在互動 session 驗證**：prompt 先在一般 Claude Code 跑穩，再轉排程，避免自動化跑壞資料。([來源](https://findskill.ai/blog/claude-code-routines-setup-guide/))

[3] **Overnight 修 bug 範例**：每日 2am 自動從 Linear 拉最優先 bug，嘗試修復並開 draft PR，早上審即可。([來源](https://thenewstack.io/claude-code-can-now-do-your-job-overnight/))

[4] **Side chat 不回流主執行緒**：⌘／Ctrl + ; 開側邊對話問問題，不污染主任務 context。([來源](https://claude.com/blog/claude-code-desktop-redesign))

[5] **Skills 取代每次重述偏好**：把優化過的工作流存成 Skill，匹配到 context 時 Claude 自動套用。([來源](https://smart-webtech.com/blog/claude-code-workflows-and-best-practices/))

## 🔧 工作流整合案例

[6] **Routines 三種觸發**：cron 排程、API 呼叫、GitHub webhook，由 Anthropic 雲端代跑，不用自己維運 infra。([來源](https://www.thetechoutlook.com/new-release/software-apps/claude-introduces-routines-in-claude-code-in-the-research-preview-available-for-claude-code-users-on-pro-max-team-and-enterprise-plans/))

[7] **Routines 打包 repo 與 connectors**：一次設定好 repo 權限與 MCP 連線，之後排程跑免再授權。([來源](https://claude.com/blog/introducing-routines-in-claude-code))

[8] **桌面側邊欄多 repo 切換**：一個視窗並行管理多個專案 session，可依狀態／專案／環境過濾分組。([來源](https://blockchain.news/ainews/claude-code-desktop-update-run-multiple-sessions-side-by-side-with-new-sidebar-latest-2026-analysis))

[9] **內建 terminal + file editor**：同 app 內跑測試／build、直接編檔、看 HTML/PDF 預覽，不用切視窗。([來源](https://9to5mac.com/2026/04/14/anthropic-adds-repeatable-routines-feature-to-claude-code-heres-how-it-works/))

[10] **Zoom MCP Connector**：Claude Cowork／Code 可讀 Zoom 會議摘要、逐字稿、錄影，自動產 action items。([來源](https://www.uctoday.com/productivity-automation/zoom-launches-mcp-connector-for-claude-giving-meeting-data-a-life-beyond-zoom/))

[11] **Zoom Plugin for Claude Code**：自動排 sprint planning／standup，把會議內容直接帶進開發 workflow。([來源](https://news.zoom.com/zoom-meeting-intelligence-in-claude/))

## 🛠️ 新工具 & 套件

[12] **Claude Code Routines 研究預覽**：Pro/Max/Team/Enterprise 可用，額度 5／15／25／25 個 routines/day。([來源](https://pasqualepillitteri.it/en/news/851/claude-code-routines-cloud-automation-guide))

[13] **Claude Code 桌面 redesign**：新側邊欄、drag-and-drop、快速 diff viewer、HTML/PDF preview。([來源](https://www.thurrott.com/a-i/anthropic/334911/anthropic-redesigns-claude-app-on-desktop-for-parallel-agents))

[14] **Opus 4.7 本週上線（爆料）**：The Information 稱為 Opus 4.6 遞進版，同日曝光 AI 設計工具。([來源](https://dataconomy.com/2026/04/15/anthropic-to-launch-claude-opus-4-7-this-week/))

[15] **Anthropic AI 設計工具**：可產網站與簡報，已和 Figma 打通轉編輯稿，Figma/Wix 股價應聲下跌。([來源](https://techbriefly.com/2026/04/15/anthropic-to-launch-claude-opus-4-7-and-new-ai-design-tool-this-week/))

[16] **Mythos 攻擊能力受測**：英國 AISI 測試 CTF/多步攻擊，能力超越過往模型但仍無法穩定打硬目標。([來源](https://www.helpnetsecurity.com/2026/04/14/claude-mythos-test-attack-capabilities-limits/))

## 💬 社群熱門討論

[17] **「Anthropic 在 nerf Claude？」**：Fortune、VentureBeat、Inc、Register 集中報導高強度用戶集體抗議。([來源](https://fortune.com/2026/04/14/anthropic-claude-performance-decline-user-complaints-backlash-lack-of-transparency-accusations-compute-crunch/))

[18] **Boris Cherny 承認降 effort**：默認改為 medium 回應「吃 token 太兇」，但未明確公告造成信任裂痕。([來源](https://venturebeat.com/technology/is-anthropic-nerfing-claude-users-increasingly-report-performance))

[19] **Compute crunch 臆測升溫**：社群懷疑 Anthropic 資料中心容量跟不上，與 OpenAI/xAI 多十億合約差距明顯。([來源](https://www.inc.com/leila-sheridan/users-say-anthropics-claude-is-getting-worse-a-quiet-change-may-be-to-blame/91330914))

[20] **Register 評 Routines 只是聰明 cron**：點出和 n8n/Zapier 差異在 Claude 自己跑，但本質仍是觸發器。([來源](https://www.theregister.com/2026/04/14/claude_code_routines/))
