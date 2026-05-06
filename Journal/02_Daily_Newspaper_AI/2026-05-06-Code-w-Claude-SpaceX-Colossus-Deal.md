# AI工作流日報 — 2026-05-06
> 涵蓋範圍：2026-05-05 06:00 ~ 2026-05-06 06:00 (TST)

> 📌 Claude 摘要：今日由 Anthropic「Code w/ Claude 2026」大會主導，同時宣布 SpaceX Colossus 1 算力合作、金融 Agent 模板、Managed Agents 三大新功能，及 Claude Code 速率上限翻倍。生態一日內資訊量極大，標誌 Anthropic 從模型公司全面轉向平台公司。

## 🧠 Prompt 技巧 & 使用心得
[1] **Simon Willison：Vibe Coding 與 Agentic Engineering 界線模糊化**：隨著 Agent 可靠度提升，他坦承不再逐行審查產出，警告「偏差正常化」風險。([來源](https://simonwillison.net/2026/May/6/vibe-coding-and-agentic-engineering/))
[2] **Managed Agents「Outcomes」功能**：撰寫 rubric 定義成功標準，獨立 grader 在隔離 context 中評分，內部測試顯示任務成功率最高提升 10 個百分點。([來源](https://claude.com/blog/new-in-claude-managed-agents))
[3] **Managed Agents「Dreaming」研究預覽**：排程回顧歷史 session 與記憶庫，自動萃取模式並策展記憶，讓 Agent 跨 session 持續進步。([來源](https://thenewstack.io/anthropic-managed-agents-dreaming-outcomes/))

## 🔧 工作流整合案例
[4] **Anthropic 發布 10 組金融 Agent 模板**：涵蓋 pitchbook 建置、KYC 篩查、月結帳等，以 Cowork 插件與 Managed Agents cookbook 兩種形式提供。([來源](https://fortune.com/2026/05/05/anthropic-wall-street-financial-services-agents-jamie-dimon/))
[5] **Claude M365 Add-ins 全面上線**：Excel、PowerPoint、Word 原生整合，Outlook 即將跟進；跨應用 context 自動攜帶。([來源](https://www.anthropic.com/news/finance-agents))
[6] **金融資料連接器擴展**：新增 FactSet、S&P Capital IQ、MSCI、PitchBook、Moody's、Verisk 等資料源。([來源](https://winbuzzer.com/2026/05/06/anthropic-ships-ten-ai-agents-for-finance-as-both-xcxwbn/))
[7] **Multi-Agent Orchestration 公測**：一個 Agent 可協調多個 Agent 平行執行，各自擁有隔離 context，提升品質與速度。([來源](https://sdtimes.com/ai/new-in-claude-managed-agents-dreaming-outcomes-and-multiagent-orchestration/))

## 🛠️ 新工具 & 套件
[8] **Code w/ Claude 2026：Code Review 功能正式發布**：多 Agent 審查 PR，檢查邏輯錯誤、安全漏洞與邊界情況，Anthropic 內部全員使用。([來源](https://simonwillison.net/2026/May/6/code-w-claude-2026/))
[9] **Claude Code Remote Agents**：可從手機遠端操控筆電上的 Claude Code，支援 API、webhook 或 thin client 互動。([來源](https://simonwillison.net/2026/May/6/code-w-claude-2026/))
[10] **CI Auto-fix GitHub Action**：自動偵測 bot 留言（linter、安全掃描），用 Claude Code 修復後推回 PR。([來源](https://paddo.dev/blog/claude-code-auto-fix-pr-lifecycle/))
[11] **Claude Code Desktop App 強調**：全螢幕 GUI，支援預覽與富媒體輸出，與 IDE 版共用 Claude Agent SDK。([來源](https://9to5google.com/2026/05/06/claude-code-is-getting-higher-usage-limits-doubled-for-most-users/))
[12] **Claude Code --plugin-url 旗標**：新增從 URL 取得 plugin .zip 的 session 載入功能。([來源](https://code.claude.com/docs/en/changelog))
[13] **Simon Willison 發布 llm-echo 0.5a0 & datasette-llm 0.1a7**：前者提供假 echo model 供自動化測試，後者增加模型預設選項設定。([來源](https://simonwillison.net/2026/May/5/llm-echo/))

## 💬 社群熱門討論
[14] **Anthropic × SpaceX Colossus 1 算力合約**：取得 300MW、22 萬張 Nvidia GPU，Claude Code 五小時速率上限即日翻倍，Pro/Max 移除尖峰時段限制。([來源](https://www.anthropic.com/news/higher-limits-spacex))
[15] **Shopify、Mercado Libre 目標 Q3 達成 90% 自主編碼**：在 Code w/ Claude 大會上作為客戶案例分享。([來源](https://simonwillison.net/2026/May/6/code-w-claude-2026/))
[16] **API 流量年增 17 倍**：Anthropic 在大會公布平台使用量數據。([來源](https://simonwillison.net/2026/May/6/code-w-claude-2026/))
[17] **HN 持續討論 Claude Code Pro 方案爭議**：四月短暫移除後雖恢復，社群仍關注後續定價策略走向。([來源](https://news.ycombinator.com/item?id=47854477))
[18] **SpaceX 合作含太空算力探索**：雙方表態有意開發數 GW 級太空運算能力。([來源](https://www.cnbc.com/2026/05/06/anthropic-spacex-data-center-capacity.html))
