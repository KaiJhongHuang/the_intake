# AI工作流日報 — 2026-07-06
> 涵蓋範圍：2026-07-05 06:00 ~ 2026-07-06 06:00 (TST)

> 📌 Claude 摘要：華盛頓郵報 7/6 獨家報導 Anthropic 三月起秘密部署中國用戶偵測碼的完整始末，成為美中 AI 蒸餾戰的最詳盡記錄。Fable 5 明天（7/7）起從訂閱制轉為 usage credits 計費，$10/$50 per Mtok，用戶須事先啟用額度否則斷存取。Armin Ronacher 發文指出 Opus 4.8 與 Sonnet 5 的 tool calling 出現退化，複雜編輯約 20% 失敗率，疑因 RL 針對 Claude Code 內建工具過度擬合。Willison 同日釋出 sqlite-utils 4.0rc3 修復 compound foreign key 問題，距穩定版更近一步。

## 🧠 Prompt 技巧 & 使用心得

[1] **Ronacher「Better Models: Worse Tools」**：Opus 4.8 與 Sonnet 5 呼叫自訂 edit tool 時會發明不存在的欄位，複雜編輯約 20% 失敗，疑因 RL 過度擬合 Claude Code 內建工具。([來源](https://lucumr.pocoo.org/2026/7/4/better-models-worse-tools/))

[2] **Willison 連結並驗證 Ronacher 發現**：Willison 在部落格轉載並補充實測，確認新模型對第三方 harness 的 tool schema 相容性確實下降。([來源](https://simonwillison.net/2026/Jul/4/better-models-worse-tools/))

[3] **HN 熱議 tool calling 退化**：社群討論是否所有 frontier 模型都會因 RLHF 針對特定工具訓練而犧牲通用 tool-use 能力。([來源](https://news.ycombinator.com/item?id=48788599))

## 🔧 工作流整合案例

[4] **華盛頓郵報獨家：Anthropic 秘密偵測中國用戶始末**：三月起 Claude Code 內建時區與網域偵測碼追蹤中國用戶，上週移除；報導完整記錄美中 AI 蒸餾戰全貌。([來源](https://www.washingtonpost.com/national-security/2026/07/06/why-anthropic-alleges-chinese-firms-are-distilling-knowledge-claude/))

[5] **Fable 5 明天起轉 usage credits 計費**：7/7 起 Pro/Max/Team/Enterprise 用戶須啟用 usage credits 才能繼續使用 Fable 5，定價 $10/$50 per Mtok，無寬限期。([來源](https://www.techtimes.com/articles/319767/20260706/fable-5-subscription-ends-tomorrow-per-token-costs-who-gets-hit-hardest.htm))

[6] **Willison sqlite-utils 4.0rc3 發布**：修復 compound foreign key 內省與建立，column name 改為 case insensitive，距穩定版更近一步。([來源](https://simonwillison.net/2026/Jul/6/sqlite-utils/))

## 🛠️ 新工具 & 套件

[7] **Gemini 3.5 Pro 仍在 preview**：錯過五、六月 GA 目標，2M token context window 為量產模型最大，企業 Vertex AI 預覽擴展中，傳 7/17 正式上線。([來源](https://www.techtimes.com/articles/319318/20260629/gemini-35-pro-cleared-july-launch-fable-5-nears-return-gpt-56-stays-locked.htm))

[8] **HuggingFace Kernels 大改版**：重新設計自訂 kernel 的打包、分發與使用流程，統一 GPU kernel 生態標準。([來源](https://huggingface.co/blog/revamped-kernels))

[9] **JADEPUFFER：首例全自主 AI 勒索攻擊**：Sysdig 記錄 AI agent 利用 Langflow RCE 漏洞自動完成入侵、加密、勒索全流程，31 秒內自主修復認證失敗。([來源](https://thehackernews.com/2026/07/ai-agent-exploits-langflow-rce-to.html))

## 💬 社群熱門討論

[10] **Fable 5 計費轉換前夕社群焦慮**：用戶討論 $10/$50 per Mtok 成本衝擊，Willison 趕在截止前升級 Max 方案衝刺 sqlite-utils。([來源](https://news.ycombinator.com/item?id=48751978))

[11] **中國 AI 擬人互動法規九天倒數**：字節 Doubao、阿里 Qwen 開始關閉擬人 agent 功能，345M 用戶受影響。([來源](https://unrot.co/blogs/today-top-10-ai-news-july-6-2026))

[12] **聯合國 AI 治理全球對話日內瓦開幕**：169 國代表參加，Guterres 警告 AI 發展速度已超越監管能力，呼籲全球統一規則。([來源](https://news.un.org/en/story/2026/07/1167848))
