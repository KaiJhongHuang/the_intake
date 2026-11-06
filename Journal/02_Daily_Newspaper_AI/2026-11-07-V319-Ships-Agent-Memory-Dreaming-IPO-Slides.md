# AI工作流日報 — 2026-11-07
> 涵蓋範圍：2026-11-06 06:00 ~ 2026-11-07 06:00 (TST)

> 📌 Claude 摘要：本日焦點為 v2.1.319 釋出背景 MCP 執行能力，Anthropic 發表代理記憶四層架構工程文章揭示 Dreaming 機制，IPO 估值因 AI 拋售潮從 $1.5T 進一步下修至 $1.2–1.3T。

## 🧠 Prompt 技巧 & 使用心得

[1] **代理記憶四層架構**：Lance Martin 發表工程文，描述從 transcripts 到 injected context 的四層記憶堆疊。([來源](https://ai-tldr.dev/releases/anthropic-components-of-agent-memory/))

[2] **Dreaming 離線整理**：代理閒置時自動執行「做夢」，讀取過去對話修正錯誤筆記、合併重複並精簡載入量。([來源](https://www.mindstudio.ai/blog/what-is-claude-dreaming-anthropic-managed-agents))

[3] **CL-Bench 記憶提升**：加入記憶後 Opus 5.5 在 CL-Bench 從 0.655 升至 0.838，提升幅度約 28%。([來源](https://ai-tldr.dev/releases/anthropic-components-of-agent-memory/))

[4] **MEMORY.md 載入上限**：Claude Code 啟動時僅讀取 MEMORY.md 索引前 200 行或 25KB，超出部分不載入。([來源](https://ai-tldr.dev/releases/anthropic-components-of-agent-memory/))

## 🔧 工作流整合案例

[5] **v2.1.319 背景 MCP 任務**：長時間 task 型 MCP 呼叫不再阻塞 session，代理可繼續執行，結果以報告回傳。([來源](https://dev.to/delimitter/claude-code-v21319-unblocks-unattended-agent-runs-476e))

[6] **v2.1.319 延遲優化指令**：新增 `/claude-api latency-optimize`，自動掃描 API 程式碼等待瓶頸並測試更快設定。([來源](https://dev.to/delimitter/claude-code-v21319-unblocks-unattended-agent-runs-476e))

[7] **v2.1.319 閘道 auto mode**：遙測或 flag 關閉時無法驗證的呼叫改為詢問或拒絕，不再回退內建分類器。([來源](https://github.com/Mai0313/claude-code-binaries/releases/tag/2.1.319))

[8] **Enterprise 成本標記 beta**：企業組織可用既有成本代碼標記專案支出，追蹤各標記的花費分佈。([來源](https://support.claude.com/en/articles/12138966-release-notes))

## 🛠️ 新工具 & 套件

[9] **Perplexity Teammates**：AI 代理可持續執行工作，每個代理擁獨立桌面環境，使用者可隨時接管操作。([來源](https://tech-insider.org/perplexity-teammates-24-7-ai-agents-for-work-2026))

[10] **Google Cloud Agent Compute Engine**：代理 session 配獨立身分與短期憑證，治理工具擴展至跨環境代理管控。([來源](https://itbrief.co.uk/story/google-cloud-launches-ai-agent-engine-governance))

[11] **claude-mem 破 103K 星**：跨 session 持久記憶外掛，支援八款編碼代理，AI 壓縮歷史上下文自動注入。([來源](https://trendshift.io/repositories/128381))

## 💬 社群熱門討論

[12] **IPO 估值下修至 $1.2–1.3T**：WSJ 與 Bloomberg 報導投資人因 AI 拋售施壓，從 $1.5T 再降，路演時程存疑。([來源](https://sg.finance.yahoo.com/news/anthropic-ipo-valuation-discussions-fall-135856342.html))

[13] **NPR：Claude 投票問題三分之一答錯**：IFPG 獨立測試顯示 Claude 錯誤率最高，ChatGPT 十分之一，與 Anthropic 自測 100% 形成對比。([來源](https://npr.org/2026/11/02/nx-s1-6025407/chatbots-midterms-voting-advice))

[14] **HN 首頁六成 AI 內容**：Zeli 分析工具統計 Hacker News 前版面約 60% 為 AI 相關或 AI 生成內容。([來源](https://zeli.app/story/49435728))
