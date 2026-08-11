# AI工作流日報 — 2026-06-23
> 涵蓋範圍：2026-06-22 06:00 ~ 2026-06-23 06:00 (TST)

> 📌 Claude 摘要：六月穩定性危機持續加劇——6/22 單日三度中斷後 6/23 再度全面當機，Downdetector 報告破 8,000 筆；Anthropic 7/8 起啟用身分驗證引發隱私爭議；Artifacts 功能讓 Claude Code session 變可分享即時網頁，企業工作流再進一步。

## 🧠 Prompt 技巧 & 使用心得
[1] **Willison 用 Claude Code 移植 Moebius 0.2B 至瀏覽器**：僅 0.2B 參數的圖像修補模型，透過 Claude Code 輔助成功跑在 WebGPU 上。([來源](https://simonwillison.net/2026/Jun/22/porting-moebius/))

[2] **Context 架構取代 Prompt 工程**：2026 年瓶頸不在模型而在 context——讓 Claude 每次 session 前讀取個人設定檔，不再從零開始。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

[3] **Willison 解析 Claude Code 定價混亂**：詳細梳理 Pro $20 vs Max $100/$200 方案差異，建議多數人留 Pro 即可。([來源](https://simonwillison.net/2026/apr/22/claude-code-confusion/))

## 🔧 工作流整合案例
[4] **Claude Code Artifacts 上線**：session 產物可轉為即時可分享網頁——PR 導覽、儀表板、release checklist 均可即時更新，Team/Enterprise 方案可用。([來源](https://venturebeat.com/data/anthropics-claude-code-artifacts-update-brings-live-shared-dashboards-and-interactive-workspaces-to-enterprises))

[5] **Claude Design 六月大更新**：設計系統匯入、WYSIWYG 畫布編輯、雙向 /design-sync 與 Claude Code 整合，Pro 以上方案開放 beta。([來源](https://venturebeat.com/technology/anthropic-ships-major-claude-design-overhaul-with-design-system-imports-code-round-trips-and-a-fix-for-its-token-burning-problem))

[6] **Cloudflare Temporary Accounts for AI Agents**：`wrangler deploy --temporary` 讓 agent 無需帳號即可部署 Worker，60 分鐘內認領永久化。([來源](https://blog.cloudflare.com/temporary-accounts/))

## 🛠️ 新工具 & 套件
[7] **Claude Code v2.1.185 安全強化**：Auto mode 擴展至 Bedrock/Vertex/Foundry、危險 git 指令攔截、fallbackModel 三層後備、/cd 即時換目錄。([來源](https://code.claude.com/docs/en/whats-new))

[8] **Anthropic 身分驗證 7/8 生效**：消費者方案可能被要求提供政府證件 + 臉部掃描，Persona 為驗證夥伴，Team/Enterprise/API 豁免。([來源](https://techcrunch.com/2026/06/22/anthropic-says-claude-may-want-to-see-your-id/))

[9] **awesome-claude-code-toolkit 持續擴充**：135 agents、35 skills、176+ plugins、14 MCP configs，社群最完整 Claude Code 工具包。([來源](https://github.com/rohitg00/awesome-claude-code-toolkit))

## 💬 社群熱門討論
[10] **6/22 單日三度中斷 + 6/23 再當機**：6/22 凌晨 00:37 UTC、早上 08:13 UTC、晚間 19:14 UTC 連三波；6/23 再度全面中斷報告破 8,000，IPO 前穩定性受質疑。([來源](https://www.techtimes.com/articles/318925/20260623/claude-outage-tops-8000-reports-agentic-pipeline-failures-mount-before-anthropic-ipo.htm))

[11] **Fable 5 免費試用 6/22 截止但模型仍離線**：出口管制第 11 天，全球用戶無法使用，付費轉換窗口形同虛設。([來源](https://explainx.ai/blog/is-fable-5-back-2026))

[12] **OALABS：新手駭客用 Claude+Codex 入侵 14 家公司**：分析逾 1,000 個 agent session，攻擊者僅需模糊 prompt，AI 自動完成偵查、漏洞利用與資料收割。([來源](https://research.openanalysis.net/claude/codex/hacking/ai%20hacking/llm/redteam/policy%20violation/2026/06/16/compromised-claude-hacking.html))
