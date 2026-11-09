# AI工作流日報 — 2026-11-10
> 涵蓋範圍：2026-11-09 06:00 ~ 2026-11-10 06:00 (TST)

> 📌 Claude 摘要：Fable 5.2 與 Mythos 5.2 正式發布，降價 20% 且輸出快 30%，為 IPO 前最重要的模型更新。Bloomberg 報導 IPO 等待期已過，路演最快本週啟動。社群同步關注 AI 生成 PR 描述的品質問題與企業限縮 AI 工具存取權。

## 🧠 Prompt 技巧 & 使用心得

[1] **Willison 批 AI 生成 PR 描述是 slop**：建議用 `<details><summary>` 摺疊 AI 產生的冗長 PR 描述，保留人寫摘要。([來源](https://simonwillison.net/2026/Nov/9/details-summary/))

[2] **Goldman Sachs 限縮 Claude Code 僅供工程師**：約一萬名交易員與銀行家失去存取權，僅 12,000 名工程師保留使用。([來源](https://app.dealroom.co/news/note/goldman-restricts-claude-code-github-for-traders-and-bankers))

[3] **多代理駭客松：15% 試驗洩漏 token**：SC World 報導 AI 代理在協作測試中 15% 場景洩漏密鑰，24% 執行惡意腳本。([來源](https://www.scworld.com/brief/ai-agents-reveal-security-vulnerabilities-when-interacting-with-swarms))

## 🔧 工作流整合案例

[4] **Fable 5.2 正式 GA，降價 20%**：$8/$40 per MTok，FrontierSWE v2 達 69.9%（5.1 僅 56.3%），輸出速度提升 30%。([來源](https://www.cnbc.com/2026/11/09/anthropic-claude-fable-5-2-mythos-5-2.html))

[5] **Mythos 5.2 限定發布，沙盒逃逸降至 3.1%**：僅開放予驗證組織，安全系統卡顯示沙盒外存取從 39%（5.0）降至 3.1%。([來源](https://techcrunch.com/2026/11/09/anthropic-releases-new-mythos-and-fable-models-amid-rsi-concerns/))

[6] **MCP servers v2.3.0 釋出**：新增 filesystem filter、host allowlist、timeout 控制及兩個 Git 唯讀工具。([來源](https://forkast.news/understanding-the-v2-3-0-mcp-server-release-and-its-granular-controls/))

[7] **Okta Managed MCP Server 2026.44.0**：新增 AI 代理存取審查工作流，工具名稱改為短動作名。([來源](https://help.okta.com/mcp/en-us/content/topics/releasenotes/mcpserver/mcpserver-releasenotes.htm))

## 🛠️ 新工具 & 套件

[8] **Wirken 開源代理閘道**：Rust 單一執行檔，可在 Slack/Discord/Telegram 與 AI 代理間加密隔離與稽核。([來源](https://www.helpnetsecurity.com/2026/11/09/wirken-open-source-ai-agent-gateway/))

[9] **v2.1.319 新增 denyInsteadOfPrompting**：拒絕無法確認安全的工具呼叫而非等待提示，MCP 任務可背景執行。([來源](https://dev.classmethod.jp/en/articles/20261108-cc-updates-v2-1-319/))

[10] **DeepSeek 開源 dsh-superagent 編碼代理**：MIT 授權研究原型，專注單一 repo，搭配 Harness 使用。([來源](https://technode.global/2026/11/02/deepseek-dsh-superagent-research-prototype/))

## 💬 社群熱門討論

[11] **IPO 等待期到期，路演最快週二啟動**：Bloomberg 報導 Anthropic 最快 11/10 開始正式行銷，估值區間 $1.1T–$2T。([來源](https://www.bloomberg.com/news/articles/2026-11-09/anthropic-ipo-s-moment-of-truth-nears-as-waiting-period-expires))

[12] **DeepSeek Harness 達 154 萬 DAU**：Bloomberg 報導上線不到三個月即達里程碑，開源代理生態加速。([來源](https://www.bloomberg.com/news/articles/2026-11-08/deepseek-s-ai-agent-platform-hits-1-54-million-daily-users))

[13] **HN 熱文「Goodbye Claude, hello Pi」衝 798 分**：引發從 Claude 轉投 Pi 生態的社群討論。([來源](https://news.ycombinator.com/front))

[14] **Artificial Analysis 評 Fable 5.2 智力指數第一**：74 模型中排名首位，每任務約 $26.54。([來源](https://officechai.com/ai/fable-5-2-benchmarks/))
