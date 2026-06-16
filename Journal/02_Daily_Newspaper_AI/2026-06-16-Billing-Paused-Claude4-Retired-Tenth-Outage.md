# AI工作流日報 — 2026-06-16
> 涵蓋範圍：2026-06-15 06:00 ~ 2026-06-16 06:00 (TST)

> 📌 Claude 摘要：6/15 是 Anthropic 生態的分水嶺日——Agent SDK 計費拆分臨門喊停、Claude Sonnet 4 與 Opus 4 正式退役，同日 AWS 密集發布 Kiro Pro Max、FinOps Agent 與 Gemma 4 on Bedrock。6/16 Claude 再度當機，12 天內第 10 次中斷，基礎設施壓力持續升高。MCP 生態方面，Nexxen 成為首批同時支援 MCP 與 A2A 的廣告平台。

## 🧠 Prompt 技巧 & 使用心得

[1] **Tool(param:value) 權限語法上線**：Claude Code 新增精細權限規則，可依工具參數搭配萬用字元授權，取代粗放的全工具放行。([來源](https://releasebot.io/updates/anthropic/claude-code))

[2] **--safe-mode 隔離壞設定**：啟動時加 `--safe-mode` 可停用 CLAUDE.md、hooks、MCP 等自訂項，快速排除設定問題。([來源](https://www.digitalapplied.com/blog/claude-code-safe-mode-fallback-models-production-resilience-guide))

[3] **巢狀 Sub-Agent 五層限制**：背景 Sub-Agent 最多 5 層深，面板顯示完整樹狀結構與後代計數，避免失控並行。([來源](https://ofox.ai/blog/claude-code-nested-subagents-2026/))

## 🔧 工作流整合案例

[4] **Nexxen 首發 MCP + A2A 雙協定**：廣告平台 Nexxen 開放外部 AI Agent 經 MCP 與 A2A 連接，支援報表、除錯、QA 等工作流。([來源](https://finance.yahoo.com/technology/ai/articles/nexxen-launches-mcp-agent-agent-130000171.html))

[5] **OpenSearch MCP Apps 上線**：AWS OpenSearch 支援 MCP Apps，在 Claude Desktop / VS Code 內直接調查 logs、traces、metrics。([來源](https://aws.amazon.com/about-aws/whats-new/2026/06/opensearch-agentic-observability-mcp-app/))

[6] **AWS FinOps Agent 公開預覽**：自動調查成本異常、產出報告並推送 Slack，目前免額外費用。([來源](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-aws-finops-agent-in-preview-gemma-4-on-bedrock-kiro-pro-max-and-more-june-15-2026/))

## 🛠️ 新工具 & 套件

[7] **Kiro Pro Max 層級發布**：AWS Kiro 新增 $100/月方案，5000 credits、全模型存取，介於 Pro+ 與 Power 之間。([來源](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-aws-finops-agent-in-preview-gemma-4-on-bedrock-kiro-pro-max-and-more-june-15-2026/))

[8] **Gemma 4 登陸 Bedrock**：Google DeepMind Gemma 4 三款變體上架 Amazon Bedrock，含 31B dense 版本與 256K context。([來源](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-aws-finops-agent-in-preview-gemma-4-on-bedrock-kiro-pro-max-and-more-june-15-2026/))

[9] **Claude Sonnet 4 / Opus 4 正式退役**：6/15 起 claude-sonnet-4 與 claude-opus-4 回傳錯誤，需遷移至 Sonnet 4.6 / Opus 4.8。([來源](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide))

## 💬 社群熱門討論

[10] **Agent SDK 計費拆分臨門喊停**：原定 6/15 將 Agent SDK 移出訂閱池，Anthropic 宣布暫緩，「目前一切不變」。([來源](https://the-decoder.com/anthropic-backs-off-unpopular-billing-overhaul-as-price-war-with-openai-looms/))

[11] **Claude 12 天第 10 次當機**：6/16 Opus 4.8 與 Haiku 4.5 錯誤率飆升，官方僅透過狀態頁更新，未發布事後分析。([來源](https://www.techtimes.com/articles/318514/20260616/claude-outage-tenth-disruption-12-days-exposes-anthropic-infrastructure-strain.htm))

[12] **Fable 5 出口管制持續中**：美國政府以國安為由禁止外國人使用 Fable 5 / Mythos 5，Anthropic 反駁越獄風險被高估。([來源](https://www.anthropic.com/news/fable-mythos-access))
