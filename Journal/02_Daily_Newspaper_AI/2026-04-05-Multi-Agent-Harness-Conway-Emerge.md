# AI工作流日報 — 2026-04-05
> 涵蓋範圍：2026-04-04 06:00 ~ 2026-04-05 06:00 (TST)

> 📌 Claude 摘要：本週 Anthropic 動作密集——三 Agent Harness 公開、Conway 平台曝光、第三方計費調整、生技收購——顯示公司正從「模型供應商」加速轉型為「AI 平台生態系」。社群端則圍繞多 agent 可觀測性與開源框架快速發展，Simon Willison 連發兩款新工具，反映 AI 工作流生態正步入「工具鏈成熟期」。

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

[9] **Simon Willison 發布 research-llm-apis**：用 Claude Code 讀取各大 LLM 供應商 HTTP API，為 LLM 抽象層重構蒐集設計資料。([來源](https://simonwillison.net/2026/Apr/5/research-llm-apis/))

[10] **scan-for-secrets 0.2 釋出**：Simon Willison 新作，Python CLI 掃描資料夾中的 API key 等機密字串，支援串流輸出。([來源](https://simonwillison.net/2026/Apr/5/scan-for-secrets/))

## 💬 社群熱門討論

[11] **agents-observe 登上 Show HN**：開源 Claude Code 多 agent 即時監控儀表板，透過 hooks 串流所有工具呼叫與子 agent 狀態至 React UI。([來源](https://github.com/simple10/agents-observe))

[12] **GitHub 每週 2.75 億次 commit**：Kyle Daigle 揭示 2025 年全年 10 億次 commit，目前飆升至每週 2.75 億次，AI 編碼推波助瀾。([來源](https://simonwillison.net/2026/Apr/4/kyle-daigle/))

[13] **Anthropic 以 4 億美元收購 Coefficient Bio**：進軍生技 AI，用 AI 加速藥物發現與生物研究。([來源](https://techcrunch.com/2026/04/03/anthropic-buys-biotech-startup-coefficient-bio-in-400m-deal-reports/))

[14] **「漏洞研究已死」引熱議**：Simon Willison 轉載 Thomas Ptacek 文章，指出最新前沿模型對漏洞研究領域造成巨大衝擊。([來源](https://simonwillison.net/2026/Apr/3/vulnerability-research-is-cooked/))

