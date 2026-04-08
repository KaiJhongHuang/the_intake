# AI工作流日報 — 2026-04-08
> 涵蓋範圍：2026-04-07 06:00 ~ 2026-04-08 06:00 (TST)

> 📌 Claude 摘要：Anthropic 發布 Claude Mythos Preview 並啟動 Project Glasswing，將最強安全研究模型限縮於資安夥伴使用；智譜 AI 的 GLM-5.1 以開源之姿登頂 SWE-Bench Pro，主打 8 小時長時任務；Claude 服務連續第三天出現不穩定。整體趨勢：AI agent 的「長時自主作業」與「安全攻防」成為本週雙主軸。（以上為 Claude 推測性整理）

## 🧠 Prompt 技巧 & 使用心得

[1] **規劃先行原則**：Claude Code 最佳實踐強調「先審查計畫再寫程式」，加上 "don't implement yet" 可防止跳過修訂直接產碼。([來源](https://github.com/shanraisshan/claude-code-best-practice))

[2] **參考實作驅動開發**：提供開源專案的優質實作作為範例，Claude 產出品質會大幅提升，優於從零設計。([來源](https://boristane.com/blog/how-i-use-claude-code/))

[3] **Simon Willison 談 Glasswing 必要性**：Willison 認為 Mythos 的資安能力已強到必須限制存取，支持 Anthropic 的決定。([來源](https://simonwillison.net/2026/Apr/7/project-glasswing/))

## 🔧 工作流整合案例

[4] **Project Glasswing 啟動**：Anthropic 向 AWS、Apple、Microsoft 等約 40 間機構提供 Mythos Preview 存取，附 1 億美元使用額度與 400 萬捐助開源資安。([來源](https://fortune.com/2026/04/07/anthropic-claude-mythos-model-project-glasswing-cybersecurity/))

[5] **Lightning MCP 付款外掛**：新 MCP 外掛讓 Claude 等 agent 可透過 Lightning Network 自主支付 API 費用，解決 agent 無銀行帳戶的痛點。([來源](https://news.ycombinator.com/item?id=47669920))

[6] **Goose 遷移至 Linux Foundation AAIF**：Block 的開源 AI agent Goose 移交 Agentic AI Foundation，支援 15+ 模型供應商，Apache 2.0 授權。([來源](https://aitoolly.com/ai-news/article/2026-04-07-block-launches-goose-an-open-source-extensible-ai-agent-for-automated-engineering-tasks))

## 🛠️ 新工具 & 套件

[7] **Claude Mythos Preview 發布**：Anthropic 新旗艦模型，自主發現 FreeBSD 17 年 RCE 漏洞，資安能力超越現有所有模型，暫不公開釋出。([來源](https://techcrunch.com/2026/04/07/anthropic-mythos-ai-model-preview-security/))

[8] **GLM-5.1 開源登頂 SWE-Bench Pro**：智譜 AI 754B 參數模型，MIT 授權，可自主作業 8 小時，得分 58.4 超越 GPT-5.4 與 Opus 4.6。([來源](https://venturebeat.com/technology/ai-joins-the-8-hour-work-day-as-glm-ships-5-1-open-source-llm-beating-opus-4))

[9] **Transformers v5 發布**：Hugging Face 推出 Transformers v5，強調模組化模型定義，持續每週新增 1-3 個模型支援。([來源](https://huggingface.co/blog/transformers-v5))

## 💬 社群熱門討論

[10] **Claude 連續三日不穩定**：4/8 再度出現登入失敗與效能下降，官方狀態頁顯示正常但 Downdetector 報告激增，用戶對穩定性信心動搖。([來源](https://www.ibtimes.com.au/claude-ai-down-again-april-8-2026-anthropic-outage-hits-users-after-yesterdays-major-incident-1865761))

[11] **GLM-5.1「8 小時工作日」引熱議**：開發者社群討論 agent 能否真正持續 8 小時不崩潰，HN 討論串關注實際表現與 benchmark 差距。([來源](https://news.ycombinator.com/item?id=47677853))

[12] **Mythos 安全限制引正反辯論**：部分開發者認同 Anthropic 負責任釋出，另一派擔憂能力封鎖將造成安全研究不對等。([來源](https://www.cnbc.com/2026/04/07/anthropic-claude-mythos-ai-hackers-cyberattacks.html))
