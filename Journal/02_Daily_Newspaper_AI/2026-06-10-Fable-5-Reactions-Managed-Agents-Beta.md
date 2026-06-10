# AI工作流日報 — 2026-06-10
> 涵蓋範圍：2026-06-09 06:00 ~ 2026-06-10 06:00 (TST)

> 📌 Claude 摘要：Fable 5 正式上線後首日生態全面響應——GitHub Copilot、Amazon Bedrock 同步支援，Simon Willison 與 CodeRabbit 均給予正面但有保留的評價。Managed Agents 公測新增 cron 排程與憑證保險庫，將 Claude 推向無人值守自動化場景。MCP OAuth 令牌劫持漏洞持續發酵。

## 🧠 Prompt 技巧 & 使用心得

[1] **Willison 評 Fable 5**：稱其「感覺很大」，一天內解決複雜問題並自行修正底層 LLM 函式庫四處 Bug。([來源](https://simonwillison.net/2026/Jun/9/claude-fable-5/))

[2] **CodeRabbit 模型評測**：建議 Fable 5 用於自主編碼任務，Code Review 精度仍以 Opus 4.8 為佳。([來源](https://www.coderabbit.ai/blog/fable-5-model-review))

[3] **Fable 5 Prompt 工程要點**：官方建議將 Prompt 視為可重用系統而非一次性指令，複雜任務先列假設再逐步執行。([來源](https://www.globaltechcouncil.org/Claude/claude-fable-5-for-developers-prompt-engineering-api-best-practices/))

## 🔧 工作流整合案例

[4] **Managed Agents 公測更新**：新增 cron 排程部署與憑證保險庫，Rakuten 已用於每週自動分析報表。([來源](https://claude.com/blog/whats-new-in-claude-managed-agents))

[5] **Fable 5 上架 GitHub Copilot**：支援 VS Code 全模式（chat/ask/edit/agent），企業版需管理員手動啟用。([來源](https://github.blog/changelog/2026-06-09-claude-fable-5-is-generally-available-for-github-copilot/))

[6] **Fable 5 上架 Amazon Bedrock**：支援 1M context window、128K 輸出，含安全護欄回退機制。([來源](https://aws.amazon.com/blogs/aws/anthropic-claude-fable-5-on-aws-mythos-class-capabilities-with-built-in-safeguards-now-available/))

## 🛠️ 新工具 & 套件

[7] **Claude Fable 5 正式發布**：Mythos 級能力，高風險查詢自動回退 Opus 4.8，95% 對話不觸發回退。([來源](https://www.anthropic.com/news/claude-fable-5-mythos-5))

[8] **Fable 5 免費至 6/22**：Pro/Max/Team/Enterprise 免費使用，6/23 起改為用量計費，定價 $10/$50 per M tokens。([來源](https://techcrunch.com/2026/06/09/anthropic-released-claude-fable-5-its-most-powerful-model-publicly-days-after-warning-ai-is-getting-too-dangerous/))

[9] **Willison 發布 llm 0.32a3**：新版支援工具呼叫暫停-恢復機制，同日發布 datasette-apps 0.1a1。([來源](https://simonwillison.net/))

## 💬 社群熱門討論

[10] **MCP OAuth 令牌劫持漏洞**：研究者揭露五步攻擊鏈可竊取 OAuth token，Anthropic 回應稱不在修補範圍。([來源](https://www.securityweek.com/claude-code-oauth-tokens-can-be-stolen-through-stealthy-mcp-hijacking/))

[11] **Fable 5 資料留存爭議**：GitHub Copilot 整合要求 30 天資料留存供安全分類器使用，企業用戶表示疑慮。([來源](https://coursiv.io/blog/claude-fable-5-github-copilot))

[12] **Anthropic 公布首起 AI 主導間諜行動**：揭露中國國家級駭客利用 Claude Code 自主滲透約 30 個目標。([來源](https://www.anthropic.com/news/disrupting-AI-espionage))
