# AI工作流日報 — 2026-04-21
> 涵蓋範圍：2026-04-20 06:00 ~ 2026-04-21 06:00 (TST)

> 📌 Claude 摘要：Amazon 追加 250 億美元投資 Anthropic 並鎖定 5GW 算力，為本日最大事件；同日 Google 內部備忘錄曝光 Brin 組建突擊隊追趕 Claude 在 agentic coding 的領先地位，兩大巨頭的動作凸顯 AI 基礎設施與程式碼代理能力已成競爭核心。

## 🧠 Prompt 技巧 & 使用心得

[1] **Context Engineering 取代 Prompt Engineering**：2026 年模型品質提升，任務周圍的結構比措辭技巧更重要。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

[2] **Claude Code 上下文控制**：社群建議將 context 使用率壓在 30% 以下，超過 40% 效能明顯衰退。([來源](https://code.claude.com/docs/en/best-practices))

[3] **用 AskUserQuestion 讓 Claude 先訪談**：大型功能開發前讓 Claude 主動提問，可減少來回修正次數。([來源](https://github.com/shanraisshan/claude-code-best-practice))

## 🔧 工作流整合案例

[4] **Amazon 追加 $25B 投資 Anthropic**：鎖定 5GW Trainium 算力，Claude Platform 控制台已整合進 AWS 主控台。([來源](https://www.anthropic.com/news/anthropic-amazon-compute))

[5] **Anthropic 承諾十年 $100B 用於 AWS**：涵蓋 Trainium2/3 晶片，2026 年底前上線近 1GW 容量。([來源](https://www.cnbc.com/2026/04/20/amazon-invest-up-to-25-billion-in-anthropic-part-of-ai-infrastructure.html))

[6] **Opus 4.7 正式上架 Amazon Bedrock**：AWS 週報確認，搭配 AWS Interconnect GA 一同發布。([來源](https://aws.amazon.com/blogs/aws/aws-weekly-roundup-claude-opus-4-7-in-amazon-bedrock-aws-interconnect-ga-and-more-april-20-2026/))

## 🛠️ 新工具 & 套件

[7] **Claude Code v2.1.116 發布**：/resume 大型 session 快 67%、思考 spinner 顯示進度、多項 MCP 啟動加速。([來源](https://github.com/anthropics/claude-code/releases))

[8] **datasette 1.0a28 釋出**：Simon Willison 持續迭代，強化 LLM 整合插件生態。([來源](https://simonwillison.net/2026/Apr/17/datasette/))

## 💬 社群熱門討論

[9] **Brin 內部備忘錄曝光**：Google 組突擊隊追趕 Claude 在 agentic coding 的領先，內部評 Gemini 寫程式不如 Claude。([來源](https://www.techradar.com/ai-platforms-assistants/we-must-urgently-bridge-the-gap-googles-sergey-brin-says-gemini-is-behind-claude-in-one-important-ai-field-according-to-leaked-memo))

[10] **Gartner：2028 年多數企業將棄用輔助式 AI**：轉向結果導向工作流平台，未轉型軟體商面臨 80% 利潤壓縮。([來源](https://www.gartner.com/en/newsroom/press-releases/2026-04-02-gartner-expects-most-enterprises-to-abandon-assistive-ai-for-outcome-focused-workflow-by-2028))

[11] **Anthropic 年化營收突破 $30B**：較 2025 年底 $9B 大幅成長，但尖峰時段可靠性問題仍被社群熱議。([來源](https://fortune.com/2026/04/14/anthropic-claude-performance-decline-user-complaints-backlash-lack-of-transparency-accusations-compute-crunch/))

[12] **Claude Opus 用 $2,283 寫出 Chrome 漏洞利用鏈**：研究者用 2.3B tokens 針對 Discord 內嵌 Chrome 138 成功彈出 calc，引發修補速度討論。([來源](https://www.hacktron.ai/blog/i-let-claude-opus-to-write-me-a-chrome-exploit))
