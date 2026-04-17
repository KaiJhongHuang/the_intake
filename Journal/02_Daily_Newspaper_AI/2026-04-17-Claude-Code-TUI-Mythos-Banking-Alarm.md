# AI工作流日報 — 2026-04-17
> 涵蓋範圍：2026-04-16 06:00 ~ 2026-04-17 06:00 (TST)

> 📌 Claude 摘要：Claude Code v2.1.110 帶來 TUI 全螢幕與行動推播，Opus 4.7 的 xhigh effort 成為新預設甜蜜點；Karpathy 啟發的 CLAUDE.md 突破 15K 星。Mythos 監管警報全面升級——IMF/世銀春季會議上多國財金首長警告 AI 恐威脅全球銀行體系，英國銀行本週獲得受控存取。（以上為 Claude 綜合觀察，非事實報導）

## 🧠 Prompt 技巧 & 使用心得

[1] **Karpathy CLAUDE.md 突破 15K 星**：修正 LLM 過度工程、忽略既有模式、擅加依賴三大通病，準確率從 65% 升至 94%。([GitHub](https://github.com/forrestchang/andrej-karpathy-skills))

[2] **Opus 4.7 xhigh effort 成新預設**：介於 high 與 max 之間，100K token 下已超越 Opus 4.6 max，兼顧效能與成本。([The AI Corner](https://www.the-ai-corner.com/p/claude-opus-4-7-guide-benchmarks-2026))

[3] **claude-memory-compiler 開源**：受 Karpathy 知識庫架構啟發，Hooks 自動記錄 session，Agent SDK 萃取決策與教訓。([GitHub](https://github.com/coleam00/claude-memory-compiler))

## 🔧 工作流整合案例

[4] **Claude Code v2.1.110 發布**：新增 /tui fullscreen 無閃爍渲染、行動推播通知、/recap session 摘要回顧功能。([GitHub Releases](https://github.com/anthropics/claude-code/releases/tag/v2.1.110))

[5] **/ultrareview 雲端多 Agent 審查**：以 max effort 平行分析架構、邏輯、安全、效能，Pro/Max 用戶每週期免費 3 次。([Pasquale Pillitteri](https://pasqualepillitteri.it/en/news/925/claude-opus-4-7-complete-guide-features))

[6] **1 小時 Prompt Cache 上線**：v2.1.110 新增 ENABLE_PROMPT_CACHING_1H 環境變數，API/Bedrock/Vertex 均可啟用。([Claude Code Docs](https://code.claude.com/docs/en/changelog))

## 🛠️ 新工具 & 套件

[7] **llm-anthropic 0.25 釋出**：Simon Willison 更新 LLM CLI 外掛，支援 Opus 4.7 及最新 API 功能。([simonwillison.net](https://simonwillison.net/2026/Apr/16/llm-anthropic/))

[8] **Datasette 1.0a27 發布**：搭配 datasette-export-database 0.3a1 與 datasette-ports 0.3 同步更新。([simonwillison.net](https://simonwillison.net/2026/Apr/15/datasette/))

[9] **Hugging Face Transformers v5**：統一推理與訓練流程，簡化模型定義架構。([Hugging Face Blog](https://huggingface.co/blog/transformers-v5))

## 💬 社群熱門討論

[10] **IMF 春季會議警告 Mythos 威脅銀行體系**：多國財金首長於華府會議表達 AI 自主漏洞挖掘恐衝擊全球金融穩定。([Irish Times](https://www.irishtimes.com/business/2026/04/17/latest-ai-models-could-threaten-world-banking-system-financial-officials-warn/))

[11] **英國銀行本週獲 Mythos 受控存取**：FCA、財政部與 NCSC 主導，允許銀行在正式發布前測試系統。([Bloomberg](https://www.bloomberg.com/news/articles/2026-04-16/anthropic-plans-to-bring-mythos-to-uk-banks-within-the-next-week))

[12] **BoE Bailey：Mythos 可能「炸開整個資安世界」**：英格蘭銀行行長於哥倫比亞大學演講中發出最強警告。([Bloomberg](https://www.bloomberg.com/news/articles/2026-04-14/boe-s-bailey-urges-regulators-to-assess-ai-cyber-risk-to-banks))

[13] **Anthropic 拒絕 8000 億美元估值融資**：TechCrunch 報導 Anthropic 暫不接受 VC 條件，IPO 最快十月啟動。([TechCrunch](https://techcrunch.com/2026/04/15/anthropic-shrugs-off-vc-funding-offers-valuing-it-at-800b-for-now/))

[14] **BoE 正式測試 AI 對金融系統風險**：英格蘭銀行跨市場韌性小組與 AI 專案組將於兩週內召開 Mythos 專題會議。([Insurance Journal](https://www.insurancejournal.com/news/international/2026/04/17/866194.htm))
