# AI工作流日報 — 2026-06-14
> 涵蓋範圍：2026-06-13 06:00 ~ 2026-06-14 06:00 (TST)

> 📌 Claude 摘要：美國政府史上首次對 LLM 發出出口管制令，Fable 5 與 Mythos 5 全球下架成為當日壓倒性焦點；資料留存 30 天政策引爆企業端連鎖反應，Loop Engineering 新範式持續升溫。

## 🧠 Prompt 技巧 & 使用心得
[1] **Loop Engineering 取代手動 Prompt**：Claude Code 負責人 Boris Cherny 宣告「我寫 loop 讓 AI 自行決定下一步」，成 2026 新主流。([來源](https://lushbinary.com/blog/loop-engineering-ai-coding-agents-guide/))
[2] **Fable 5 內建反蒸餾防護**：模型拒絕協助開發競爭 LLM，觸發 ToS 的 prompt 直接封鎖回應。([來源](https://news.ycombinator.com/item?id=48466215))

## 🔧 工作流整合案例
[3] **AWS Bedrock 強制 data_share 模式**：啟用 Fable 5 需開啟 30 天留存，推論資料離開 AWS 邊界進入 Anthropic。([來源](https://www.developersdigest.tech/blog/fable-5-aws-bedrock-data-boundary))
[4] **Microsoft 禁員工用 Fable 5**：因 30 天強制資料留存政策，微軟內部下令迴避 Claude Fable 5。([來源](https://mlq.ai/news/microsoft-blocks-claude-fable-5-for-employees-over-anthropics-30-day-data-retention-policy/))
[5] **Claude Code v2.1.169 Safe Mode**：`--safe-mode` 禁用全部自訂（CLAUDE.md、hooks、MCP），提供乾淨除錯環境。([來源](https://jangwook.net/en/blog/en/claude-code-june-2026-new-features-changelog-developer-guide/))

## 🛠️ 新工具 & 套件
[6] **AWS MCP Server 正式 GA**：託管式遠端 MCP 伺服器，為 AI Agent 提供安全存取全部 AWS 服務。([來源](https://aws.amazon.com/blogs/aws/the-aws-mcp-server-is-now-generally-available/))
[7] **MCP 07-28 RC 發布**：史上最大協議修訂，核心改為 stateless，新增 MCP Apps 與 Tasks 擴充。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28-release-candidate/))
[8] **Willison 發布 micropython-wasm**：用 MicroPython WASM 為 Datasette Agent 建立程式碼執行沙盒。([來源](https://simonwillison.net/))

## 💬 社群熱門討論
[9] **🔥 美出口管制令：Fable 5 / Mythos 5 全球下架**：6/12 17:21 ET 發出史上首道 LLM 禁令，Anthropic 被迫全面停用。([來源](https://www.anthropic.com/news/fable-mythos-access))
[10] **Anthropic 反駁禁令標準**：稱政府僅提供口頭越獄證據，若此標準適用全業界將阻止所有前沿模型上線。([來源](https://fortune.com/2026/06/13/anthropic-disables-fable-mythos-export-controls-national-security-threat/))
[11] **五角大廈 CIO 力挺禁令**：Kirsten Davies 發文「有些事比營收和估值更重要。America First」。([來源](https://www.inquirer.com/news/nation-world/anthropic-trump-administration-pentagon-fable-mythos-deny-foreign-access-amodei-lutnick-20260614.html))
[12] **HN 熱議 30 天資料留存**：開發者質疑留存審查「不當行為」定義模糊，企業零留存協議遭推翻引不滿。([來源](https://news.ycombinator.com/item?id=48464258))
[13] **Willison 轉發官方聲明全文**：在個人部落格完整引述 Anthropic 聲明，成開發者社群第一手參考。([來源](https://simonwillison.net/2026/Jun/13/us-government-directive-to-suspend-access/))
