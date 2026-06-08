# AI工作流日報 — 2026-06-08
> 涵蓋範圍：2026-06-07 06:00 ~ 2026-06-08 06:00 (TST)

> 📌 Claude 摘要：WWDC 2026 前夕消息密集，iOS 27 Extensions 將開放 Claude 成為 Siri 替代預設 AI，這是 Claude 進入消費級蘋果生態的里程碑。同時 Microsoft 揭露 Claude Code GitHub Action 安全漏洞（已修補），6/15 計費改制逼近引發社群焦慮，last30days-skill 登頂 GitHub Trending 反映 Agent 技能生態持續爆發。

## 🧠 Prompt 技巧 & 使用心得

[1] **Dynamic Workflows 實戰指南**：社群整理平行子代理調度最佳做法，建議先開 auto mode 再下「Create a workflow」指令啟動。([InfoQ](https://www.infoq.com/news/2026/06/dynamic-workflows-claude-code/))

[2] **Context Engineering 取代 Prompt Engineering**：2026 年重點已從寫好 prompt 轉向管理上下文，Skills 機制讓 Claude 自動匹配已儲存工作流。([AI Maker](https://aimaker.substack.com/p/anthropic-claude-updates-q1-2026-guide))

[3] **Bun 用 Dynamic Workflows 移植 Zig→Rust**：Jarred Sumner 以 750K 行 Rust、99.8% 測試通過率完成移植，11 天合併，展示千代理平行審查實力。([DevOps.com](https://devops.com/claude-codes-dynamic-workflows-take-on-the-tasks-that-were-too-big-to-automate/))

## 🔧 工作流整合案例

[4] **iOS 27 Extensions 開放 Claude 為 Siri 替代 AI**：WWDC 2026 前夕確認 Apple 將讓用戶在設定中選 Claude、ChatGPT 或 Gemini 取代 Siri 預設 AI。([AI Weekly](https://aiweekly.co/node/2611))

[5] **Siri 以 Gemini 重建，第三方 AI 市集成形**：Apple 與 Google 簽約年付約 $10 億，新 Siri 獨立 App 上線，Writing Tools 與 Image Playground 同步開放第三方。([TechCrunch](https://techcrunch.com/2026/06/08/wwdc-2026-what-to-expect-from-siris-highly-anticipated-revamp-to-apple-intelligence-and-ios-27/))

[6] **Claude Code 6/15 計費改制細節**：互動式使用不變，Agent SDK / claude -p 移至獨立額度池（Pro $20、Max 5x $100、Max 20x $200），用完即停，社群反應強烈。([TechTimes](https://www.techtimes.com/articles/317625/20260602/anthropic-ends-subscription-subsidy-agents-june-15-credit-pool-replaces-flat-rate-access.htm))

[7] **Microsoft 揭露 Claude Code GitHub Action 漏洞**：Read tool 未受沙箱限制，惡意 Issue 可竊取 CI/CD 密鑰，Anthropic 已於 v2.1.128 修補。([Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/06/05/securing-ci-cd-in-agentic-world-claude-code-github-action-case/))

## 🛠️ 新工具 & 套件

[8] **last30days-skill 登頂 GitHub Trending**：跨 Reddit、X、YouTube、HN、Polymarket 平行搜尋後合成摘要，27.7K 星，支援 Claude Code 外掛安裝。([GitHub](https://github.com/mvanhorn/last30days-skill))

[9] **taste-skill 同步上榜 Trending**：Leonxlnx 開發的個人化推薦 Agent 技能，與 last30days-skill 並列 Top 3。([GitHub Trending](https://github.com/trending))

[10] **NVIDIA Nemotron 3 Ultra 上架**：550B 參數美國最強開源權重模型，300+ tok/s，上架 Hugging Face、NIM、OpenRouter。([LLM Stats](https://llm-stats.com/llm-updates))

## 💬 社群熱門討論

[11] **Anthropic 呼籲全球暫停前沿 AI 開發**：內部報告指 Claude 已撰寫自身 80% 以上程式碼，接近遞迴自我改進，提議多實驗室協調暫停機制。([Fortune](https://fortune.com/2026/06/05/anthropic-ai-pause-development-recursive-self-improvement/))

[12] **IPO 前發安全報告引質疑**：$965B 估值、S-1 機密提交後數日即發暫停呼籲，批評者認為是 IPO 造勢與安全立場並行策略。([Gizmodo](https://gizmodo.com/anthropic-sorta-calls-for-pause-on-ai-development-you-should-sorta-take-it-seriously-2000768115))

[13] **6/15 計費改制社群焦慮**：HN 用戶指出 Max 方案 99% 使用量為非互動式，改制後成本將「遠超負擔」，預期大量重度用戶遷移至 API 直接付費。([Dev Tool Picks](https://devtoolpicks.com/blog/anthropic-splits-claude-subscriptions-agent-sdk-credit-june-2026))

[14] **r/ClaudeAI 突破 90 萬會員**：社群最常見討論為使用疑難與計費不滿，反映 Claude 用戶基數持續膨脹但摩擦點猶存。([GummySearch](https://gummysearch.com/r/ClaudeAI/))
