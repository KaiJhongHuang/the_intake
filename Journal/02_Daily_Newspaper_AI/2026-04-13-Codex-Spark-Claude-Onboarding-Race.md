# AI工作流日報 — 2026-04-13
> 涵蓋範圍：2026-04-12 06:00 ~ 2026-04-13 06:00 (TST)

> 📌 Claude 摘要：本日焦點在「即時編碼」競賽白熱化——OpenAI 推出 GPT-5.3-Codex-Spark 主打 1000 tokens/秒響應、Anthropic 以 Claude Code v2.1.101 加強團隊協作與企業 TLS 支援。MCP 生態出現 MemPalace 熱度造假爭議，Pinterest 則成為 MCP 生產級部署代表。此為 Claude 綜合觀察，非事實報導。

## 🧠 Prompt 技巧 & 使用心得

[1] **Context Engineering 取代 Prompt Engineering**：2026 年真正的槓桿點，是結構化輸入、而非措辭精修。([來源](https://www.the-ai-corner.com/p/claude-best-practices-power-user-guide-2026))

[2] **Anthropic 內部測試**：無引導嘗試成功率約 33%，差距不在 Prompt 品質而在執行前的結構化準備。([來源](https://mindwiredai.com/2026/03/25/claude-code-creator-workflow-claudemd/))

[3] **CLAUDE.md 保持 ~2500 tokens / 100 行**：直接載入系統提示並持續占用 context，寫太多反而稀釋指令效力。([來源](https://mindwiredai.com/2026/03/25/claude-code-creator-workflow-claudemd/))

[4] **限制破解技巧**：常開新對話而非巨型 thread，指令寫成「修 42 行」而非「修 auth bug」以節省 quota。([來源](https://nicholasrhodes.substack.com/p/claude-usage-limits-fix))

## 🔧 工作流整合案例

[5] **Claude Code v2.1.101 推出 /team-onboarding**：自動根據使用者使用模式，產出團隊新人上手指南。([來源](https://claude-world.com/articles/claude-code-21101-release/))

[6] **v2.1.101 預設信任 OS CA 憑證**：企業內網 TLS proxy 不再需要額外設定，降低部署阻力。([來源](https://claude-world.com/articles/claude-code-21101-release/))

[7] **/ultraplan 自動建立預設雲端環境**：不再需要先走 web setup，遠端會話可直接啟動。([來源](https://claude-world.com/articles/claude-code-21101-release/))

[8] **Pinterest 在工程流程導入 MCP 生產**：InfoQ 報導其從 POC 轉為日常內部平台的案例。([來源](https://www.infoq.com/news/2026/04/mcp-pinterest/))

## 🛠️ 新工具 & 套件

[9] **OpenAI 發布 GPT-5.3-Codex-Spark**：首款主打即時編碼模型，>1000 tokens/秒，與 Claude 搶開發者體驗。([來源](https://openai.com/index/introducing-gpt-5-2-codex/))

[10] **GPT-5.4 全面 rollout ChatGPT / Codex / API**：首個具備 native computer-use 能力的通用模型，多應用協作可行。([來源](https://www.chatgptimagegenerator.org/2026/04/09/openai-rolls-out-gpt-5-4-across-chatgpt-codex-and-the-api/))

[11] **Codex Pro 方案上線 $100/月**：主打長時高強度會話，含 GPT-5.4 無限 + 10 倍 Codex 用量，對標 Claude Max。([來源](https://www.chatgptimagegenerator.org/2026/04/09/openai-rolls-out-gpt-5-4-across-chatgpt-codex-and-the-api/))

[12] **claude-code-skills Marketplace v1.46.0 更新（4/11）**：社群持續擴充技能庫，含 Git 自動化、測試、Code Review 專屬 skill。([來源](https://github.com/daymade/claude-code-skills))

## 💬 社群熱門討論

[13] **MemPalace 熱度造假爭議**：MCP-native 記憶系統 4 月爆紅，社群 review 指 LongMemEval 分數其實來自底層 vector store，非宣稱的 Palace 架構。([來源](https://dev.to/jangwook_kim_e31e7291ad98/top-15-mcp-servers-every-developer-should-install-in-2026-n1h))

[14] **Polymarket 預測 Claude 4.7 五月底前發布 83%**：因 3 月原始碼洩漏曾提及 Opus 4.7 與 Sonnet 4.8，加上 5/6 Code with Claude 活動催化。([來源](https://polymarket.com/event/claude-4pt7-released-by))

[15] **Codex 老模型 4/14 下架潮**：GPT-5.1/5.2-codex 等即將從 Codex for ChatGPT 移除，使用者回饋工作流中斷需急遷移。([來源](https://developers.openai.com/codex/changelog))

[16] **Simon Willison 重構 LLM Python 函式庫**：現有抽象層無法涵蓋 server-side tool execution 等新特性，計畫大改。([來源](https://simonwillison.net/tags/llm/))
