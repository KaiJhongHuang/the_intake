# AI工作流日報 — 2026-11-06
> 涵蓋範圍：2026-11-05 06:00 ~ 2026-11-06 06:00 (TST)

> 📌 Claude 摘要：Anthropic 正式推出個人理財功能串接銀行帳戶，同日高盛限縮交易員使用 Claude Code，選舉護欄測試成績亮眼；Simon Willison 站台持續更新 datasette 系列工具。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude 選舉護欄測試 100% 達標**：Anthropic 針對期中選舉測 600 題，Opus 4.7 適當回應率 100%、Sonnet 4.6 為 99.8%。([來源](https://decrypt.co/365486/anthropic-election-safeguards-claude-ai-us-midterms))

[2] **多輪影響操作偵測仍有缺口**：多輪情境測試 Sonnet 4.6 約 90%、Opus 4.7 約 94%，顯示複雜社交工程攻擊仍具挑戰。([來源](https://pulse2.com/anthropic-strengthens-claude-election-safeguards-ahead-of-2026-u-s-midterms/))

[3] **Willison 引用 Paul Ford 論瀏覽器即應用平台**：Simon Willison 11/5 貼文轉引 Paul Ford 對瀏覽器作為應用平台的觀點，值得 prompt 設計者思考前端互動框架。([來源](https://simonwillison.net/2026/Nov/5/paul-ford/))

## 🔧 工作流整合案例

[4] **Claude Personal Finance 上線串接銀行帳戶**：透過 Plaid 連結銀行與信用卡，唯讀分析消費分類、帳單與異常收費，Pro/Max/Ultra 美國 beta。([來源](https://techcrunch.com/2026/11/05/claude-can-now-analyze-your-spending-with-its-new-personal-finance-tool/))

[5] **高盛限縮 Claude Code 與 Copilot 僅供 12K 工程師**：Bloomberg 報導高盛十月起將交易員與銀行家排除在 AI 編碼工具之外，僅保留工程團隊存取權。([來源](https://unusualwhales.com/news/goldman-sachs-restricts-staff-ai-coding-tools-bloomberg))

[6] **Anthropic 整合 Democracy Works 選舉資料**：Claude 在選舉日顯示無黨派投票橫幅與官方開票資訊，來源為 Democracy Works 資料庫。([來源](https://gaugr.app/en/blog/claude-ai-election-safeguards-2026-midterms-guide))

## 🛠️ 新工具 & 套件

[7] **v2.1.318 釋出登入到期可見與設定安全強化**：新增 `loginExpiresAt` 欄位、非互動模式遇損壞設定檔停止而非覆寫、mod fork 支援 effort 參數。([來源](https://releasebot.io/updates/anthropic/claude-code))

[8] **NVIDIA Auto Ontology 開源語義層**：Apache 2.0 授權，為 AI 代理 SQL 查詢建構圖譜式定義與血統，支援 Databricks/Snowflake/Postgres/DuckDB。([來源](https://www.marktechpost.com/2026/11/01/nvidia-auto-ontology-open-source-semantic-layer-ai-agents/))

[9] **Willison 發布 datasette-llm 0.1a10 與 datasette-apps 0.3a0**：datasette 生態系持續擴展，新版整合 LLM 功能至資料探索工作流。([來源](https://simonwillison.net/))

[10] **Kimi K3.1 Pro 權重原定 11/4 釋出**：Moonshot 十月底開放 API，承諾 11/4 公開權重（100 萬 token 上下文），截至發稿未確認是否已上線。([來源](https://letsdatascience.com/news/moonshot-releases-kimi-k31-pro-api-open-weights-due-nov-4-786e160c))

## 💬 社群熱門討論

[11] **HN 熱議「AI 迫使企業處理技術債」**：IEEE 文章登 HN 首頁獲 1136 分 660 則討論，工程師社群認同 AI 暴露數十年累積的技術債。([來源](https://news.ycombinator.com/front))

[12] **HN「Gemini 訂閱戶聊天紀錄仍被訓練」646 分**：使用者揭露 Google Gemini 即使付費帳戶仍將對話用於模型訓練，引發隱私爭議。([來源](https://news.ycombinator.com/front))

[13] **IPO 估值傳從 $2T 下修至 $1.5T**：Reuters 報導機構投資人因 Q3 營收成長放緩，將 Anthropic IPO 估值預期從 $2T 壓至約 $1.5T。([來源](https://aiweekly.co/alerts/reuters-anthropic-ipo-investors-push-valuation-down-to-15t-from-2t-over-q3))
