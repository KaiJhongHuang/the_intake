# AI工作流日報 — 2026-07-28
> 涵蓋範圍：2026-07-27 06:00 ~ 2026-07-28 06:00 (TST)

> 📌 Claude 摘要：今日最大事件是 MCP 2026-07-28 規範正式發布，協議核心轉向無狀態架構，為啟動以來最大改版。同日 Anthropic 研究團隊公開 Claude Mythos Preview 破解密碼學演算法的成果，Dario Amodei 亦發文表態不支持禁止開放權重模型。社群方面，Ethan Mollick 更新版 AI 使用指南引發 Simon Willison 討論，焦點已從聊天轉向 Agent 系統。

## 🧠 Prompt 技巧 & 使用心得
[1] **Mollick更新AI使用指南，焦點轉向Agent系統**：Ethan Mollick發布最新指南，強調AI已從聊天互動轉為可完成數小時工作的Agent系統。([來源](https://www.oneusefulthing.org/p/an-opinionated-guide-to-which-ai-b22))
[2] **Willison評Mollick指南：Gemini落榜Agent類別**：Simon Willison點評該指南，指出Google在Codex/Cowork類Agent工具仍缺席。([來源](https://simonwillison.net/2026/Jul/27/an-opinionated-guide-to-which-ai-to-use-to-do-stuff/))
[3] **Mollick隔日再更新納入Opus 5與Codex語音模式**：Opus 5與Codex語音模式上線後，Mollick即時補充指南內容，感嘆跟進速度之難。([來源](https://x.com/emollick/status/2081475928086003869))

## 🔧 工作流整合案例
[4] **MCP 2026-07-28規範正式發布，核心轉無狀態**：第五版MCP規範上線，移除Session狀態，伺服器可部署於Serverless與邊緣架構。([來源](https://blog.modelcontextprotocol.io/posts/2026-07-28/))
[5] **Claude平台同步支援MCP 2026-07-28新規範**：Anthropic宣布Claude將整合新版MCP，帶來更強OAuth/OIDC授權與版本化擴充。([來源](https://claude.com/blog/bringing-mcp-2026-07-28-to-claude))
[6] **MCP無狀態架構實測：免Sticky Session、純輪詢負載均衡**：微軟Azure團隊發文說明新規範如何簡化MCP伺服器部署與擴展。([來源](https://techcommunity.microsoft.com/blog/appsonazureblog/mcp-just-went-stateless-%E2%80%94-what-the-2026-spec-changes-about-scaling-on-app-servic/4530222))

## 🛠️ 新工具 & 套件
[7] **Claude Mythos Preview破解HAWK與AES密碼學弱點**：Anthropic研究團隊公布Mythos在60小時內將HAWK金鑰強度減半，並加速縮減版AES攻擊200-800倍。([來源](https://www.anthropic.com/research/discovering-cryptographic-weaknesses))
[8] **Kimi K3開放權重正式釋出，2.8T參數史上最大**：Moonshot AI於7/27在Hugging Face發布96個safetensors分片共1.56TB，Together AI與Modal同步提供託管。([來源](https://qz.com/moonshot-ai-kimi-k3-open-weights-download-072726))

## 💬 社群熱門討論
[9] **Amodei發文：Anthropic從未主張禁止開放權重模型**：Dario Amodei回應美國官員考慮限制中國開放權重模型一事，稱無危險能力的開放權重模型是公共財。([來源](https://www.anthropic.com/news/position-open-weights-models))
[10] **共享對話遭Google索引事件收尾，robots.txt已修復**：Anthropic於7/28前完成robots.txt更新，搜尋引擎已移除索引，但敏感資料曾短暫曝光。([來源](https://techcrunch.com/2026/07/27/psa-your-claude-shared-chats-and-artifacts-may-have-ended-up-on-google/))
[11] **MCP無狀態規範登HN首頁引發熱議**：開發者社群討論新規範對既有MCP伺服器的遷移影響與Serverless部署優勢。([來源](https://news.ycombinator.com/item?id=49088058))
