# AI工作流日報 — 2026-06-15
> 涵蓋範圍：2026-06-14 06:00 ~ 2026-06-15 06:00 (TST)

> 📌 Claude 摘要：Fable 5 / Mythos 5 禁令風暴持續延燒——76 名資安專家聯名要求解禁，Amazon 被揭露為事件幕後推手；同日 Anthropic 遭集體訴訟指控 Max 方案用量不實。6/15 雙重截止日到來：Agent SDK 計費分拆生效、Sonnet 4 / Opus 4 正式退役。

## 🧠 Prompt 技巧 & 使用心得

[1] **「Fix this code」非越獄**：Katie Moussouris 指出觸發禁令的技巧僅為「防禦型提示」，任何公開模型皆可復現。([Fortune](https://fortune.com/2026/06/15/fix-this-code-three-words-behind-us-government-shut-down-anthropic-fable-mythos-ai-models-katie-moussouris-open-letter/))

[2] **Datasette Agent 沙箱實驗**：Simon Willison 用 MicroPython + WASM 沙箱測試 GPT-5.5 程式碼生成，目前尚未成功逃脫。([simonwillison.net](https://simonwillison.net/))

## 🔧 工作流整合案例

[3] **Agent SDK 計費分拆今日生效**：claude -p、GitHub Actions 等程式化用量移至獨立信用池，Pro $20 / Max 5x $100 / Max 20x $200，不再吃訂閱額度。([Bind AI](https://blog.getbind.co/claude-code-pricing-changes-june-15-what-youll-actually-pay-2026/))

[4] **Sonnet 4 / Opus 4 今日正式退役**：API 呼叫 claude-sonnet-4-0、claude-opus-4-0 將回傳錯誤，官方建議遷移至 Sonnet 4.6 或 Opus 4.8。([MindStudio](https://www.mindstudio.ai/blog/claude-sonnet-4-opus-4-deprecation-migration-guide))

[5] **CircleCI MCP Server 上線**：將 CI/CD pipeline 資料接入 Claude Code 等 MCP 客戶端，可自然語言查詢建置失敗原因。([CircleCI](https://circleci.com/blog/circleci-mcp-server))

## 🛠️ 新工具 & 套件

[6] **MCP 工具自動補全規範落地**：6/11 起 MCP Server 可宣告工具支援輸入自動補全，提升 Host 端互動效率。([Speakeasy](https://www.speakeasy.com/mcp/release-notes))

[7] **AWS MCP Server 正式 GA**：6/9 更新 Proxy 版本指引與 uv 安裝說明，正式脫離預覽。([AWS](https://aws.amazon.com/blogs/aws/the-aws-mcp-server-is-now-generally-available/))

## 💬 社群熱門討論

[8] **#FreeFable 公開信**：Alex Stamos 等 76 名資安專家聯名致函商務部長 Lutnick，主張禁令傷害防禦方多於攻擊方，要求恢復 Fable 5。([Axios](https://www.axios.com/2026/06/15/anthropic-fable-security-leaders-trump-admin))

[9] **Amazon 被指為禁令推手**：報導揭露 CEO Jassy 親電財政部，將內部安全研究轉交白宮，直接促成出口管制令。([Fortune](https://fortune.com/2026/06/14/how-a-warning-from-amazon-led-the-white-house-to-shut-down-anthropics-mythos-model/))

[10] **Anthropic 遭 Max 用量集體訴訟**：6/14 加州北區聯邦法院受理，原告指控 Max 5x / 20x 方案實際用量低於廣告承諾。([Decrypt](https://decrypt.co/371201/anthropic-lawsuit-allegedly-misleading-claude-ai-pricing))

[11] **Anthropic 急派工程師赴華府**：公司正與政府協商修復方案，目標儘速恢復 Fable 5 存取。([TechTimes](https://www.techtimes.com/articles/318376/20260615/anthropic-races-lift-fable-5-export-ban-top-engineers-sent-washington-deal.htm))
