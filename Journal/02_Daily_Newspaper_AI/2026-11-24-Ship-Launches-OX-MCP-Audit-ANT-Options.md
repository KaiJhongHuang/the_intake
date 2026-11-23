# AI工作流日報 — 2026-11-24
> 涵蓋範圍：2026-11-23 06:00 ~ 2026-11-24 06:00 (TST)

> 📌 Claude 摘要：Anthropic 推出 Claude Ship 整合 PR 審查、修復與核准三合一代理，為上市後首個重大產品發布；OX Security 掃描逾 1.5 萬 MCP 伺服器揭示 22% 存在注入風險；ANT 股票選擇權首日上線交易活躍。

## 🧠 Prompt 技巧 & 使用心得

[1] **Claude Ship /ship 指令**：在 Claude Code 輸入 /ship 可一鍵推送、開 PR、自動審查並處理 CI 失敗。([來源](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes/))

[2] **Code Review 三段深度**：Claude Ship 支援 Quick、Standard、Deep 三級審查，團隊可依 PR 重要性選擇。([來源](https://www.unite.ai/anthropic-launches-claude-ship-to-review-fix-and-approve-prs/))

[3] **Anthropic 內部數據**：啟用 Ship 後合併 PR 量六至九月翻倍，revert 率降逾 40%，為內部自報數據。([來源](https://9to5mac.com/2026/11/23/anthropic-launches-new-claude-ship-feature-for-builders/))

## 🔧 工作流整合案例

[4] **Claude Ship 三合一代理**：整合 Code Review（GA）、PR Steward（beta）與 Claude Approvals（beta），Team/Enterprise 可用。([來源](https://techcrunch.com/2026/11/23/anthropic-launches-claude-ship-letting-ai-agents-review-fix-and-approve-code-changes/))

[5] **PR Steward 自動修復**：偵測 CI 失敗與合併衝突後自動推送修正，不具核准或合併權限。([來源](https://www.testingcatalog.com/anthropic-launches-claude-ship-to-review-and-approve-prs/))

[6] **Claude Approvals 政策核准**：依團隊撰寫的核准政策判斷 PR 是否可自動通過，仍受分支保護規則約束。([來源](https://cellcog.ai/blog/claude-ship/))

[7] **LangSmith Tool Gateway 公測**：LangChain 推中心化 MCP 工具閘道，管理憑證、稽核與存取，支援 Claude Code。([來源](https://langchain.com/blog/langsmith-tool-gateway))

## 🛠️ 新工具 & 套件

[8] **agent-mcts 上架 PyPI**：用蒙地卡羅樹搜索包裹 Claude Code，每節點配一 git worktree 與 session。([來源](https://pypi.org/project/agent-mcts/))

[9] **OX Security MCP 掃描報告**：分析 15,465 個 MCP 伺服器，22% 標記存在 prompt 注入或工具投毒風險。([來源](https://www.ox.security/ebooks/15465-mcp-servers-0-governance/))

[10] **DataGroomr MCP 伺服器**：為 Salesforce 推出資料品質 MCP 端點，可供其他 AI 代理存取清理後的 CRM 資料。([來源](https://www.destinationcrm.com/Articles/ReadArticle.aspx?ArticleID=177113))

## 💬 社群熱門討論

[11] **ANT 選擇權首日交易**：Anthropic 上市後首批選擇權上線，據報交易活躍，盤前股價回升約 4.5%。([來源](https://www.investing.com/equities/anthropic-news))

[12] **ANT 盤後跌逾 3%**：Claude Ship 發布同日 ANT 盤後下跌超 3%，市場仍在消化 IPO 後估值。([來源](https://seekingalpha.com/news/4675797-anthropic-unveils-claude-ship-aimed-at-pull-requests))

[13] **HN 熱議 agent-mcts**：Show HN 帖以蒙地卡羅樹搜索結合 Claude Code 生成程式碼引發討論。([來源](https://github.com/duanyytop/agents-radar/issues/4417))

[14] **AISI 統計 MCP 工具暴增**：英國 AI 安全研究所報告公開 MCP 工具從 5,000 增至 177,000，下載量達 1,400 萬。([來源](https://www.aisi.gov.uk/work/how-are-ai-agents-used-evidence-from-177000-ai-agent-tools))
