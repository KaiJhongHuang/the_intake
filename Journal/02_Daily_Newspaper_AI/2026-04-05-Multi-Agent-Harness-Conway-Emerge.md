# AI工作流日報 — 2026-04-05
> 涵蓋範圍：2026-04-04 06:00 ~ 2026-04-05 06:00 (TST)

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison 談 Agentic Engineering 三大模式**：在 Lenny's Podcast 分享每日使用的 red/green TDD、templates、hoarding 三種 agent 工作流模式。([來源](https://simonwillison.net/2026/Apr/2/lennys-podcast/))

[2] **多 Agent 分工模式成社群共識**：Reddit 開發者建議主 session 用 Opus 做複雜推理，subagent 用 Sonnet 處理聚焦任務，透過 CLAUDE_CODE_SUBAGENT_MODEL 控制。([來源](https://www.morphllm.com/claude-code-reddit))

[3] **短 session 優於長 marathon**：r/ClaudeAI 共識：每次自主作業前先 commit checkpoint，結果不對直接 rollback 重來，成功率高於硬修。([來源](https://www.morphllm.com/claude-code-reddit))

## 🔧 工作流整合案例

[4] **Anthropic 發布三 Agent Harness 架構**：以 GAN 為靈感，拆分 planner / generator / evaluator 三角色，支援數小時自主全端開發，解決 agent 自我評估過度樂觀問題。([來源](https://www.anthropic.com/engineering/harness-design-long-running-apps))

[5] **Conway 常駐 Agent 平台曝光**：洩漏碼揭露 Anthropic 正測試「Conway」——含 webhook 喚醒、Chrome 整合、.cnw.zip 擴充格式的 always-on agent 環境。([來源](https://dataconomy.com/2026/04/03/anthropic-tests-conway-platform-for-continuous-claude/))

[6] **Claude Code v2.1.92 釋出**：MCP 結果持久化上限提升至 500K chars、Write tool diff 效能提升 60%、新增 Bedrock 互動設定精靈。([來源](https://help.apiyi.com/en/claude-code-v2-1-92-mcp-persistence-powerup-tutorial-en.html))

## 🛠️ 新工具 & 套件

[7] **Claw Code 突破 100K Stars**：基於 Claude Code 洩漏架構的 Rust 開源 clean-room 重寫，含多 agent 編排、tool-calling、終端原生 AI 開發，為史上最快達 100K star 的 repo。([來源](https://claw-code.codes/))

[8] **Anthropic 第三方工具獨立計費**：4/4 起使用 OpenClaw 等第三方工具需額外付費，訂閱方案不再涵蓋。([來源](https://www.newsbytesapp.com/news/science/anthropic-begins-billing-3rd-party-claude-tools-separately-april-4-2026/tldr))

[9] **datasette-llm 0.1a6 發布**：Simon Willison 釋出 Datasette LLM 整合插件新版，供其他插件依賴使用。([來源](https://simonwillison.net/2026/Apr/1/datasette-llm-2/))

## 💬 社群熱門討論

[10] **Anthropic 以 4 億美元收購 Coefficient Bio**：進軍生技 AI，用 AI 加速藥物發現與生物研究。([來源](https://techcrunch.com/2026/04/03/anthropic-buys-biotech-startup-coefficient-bio-in-400m-deal-reports/))

[11] **AnthroPAC 政治行動委員會成立**：Anthropic 成立 PAC 影響政策，員工自願捐款上限 $5,000，計畫兩黨捐助。([來源](https://techcrunch.com/2026/04/03/anthropic-ramps-up-its-political-activities-with-a-new-pac/))

[12] **「漏洞研究已死」引熱議**：Simon Willison 轉載 Thomas Ptacek 文章，指出最新前沿模型對漏洞研究領域造成巨大衝擊。([來源](https://simonwillison.net/2026/Apr/3/vulnerability-research-is-cooked/))

---

📌 Claude 推測：本週 Anthropic 動作密集——三 Agent Harness 公開、Conway 平台曝光、第三方計費調整、生技收購——顯示公司正從「模型供應商」加速轉型為「AI 平台生態系」。社群端 Claw Code 的爆發式成長則反映開發者對開源 agent 框架的強烈需求，後續 Anthropic 與開源社群的競合關係值得關注。
