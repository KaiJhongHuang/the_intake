# AI工作流日報 — 2026-08-02
> 涵蓋範圍：2026-08-01 06:00 ~ 2026-08-02 06:00 (TST)

> 📌 Claude 摘要：開放權重公開信引爆產業路線辯論，Willison 七月電子報同日發布並公開討論；smevals 評測框架浮出水面，提供跨模型小型 eval 方案；Anthropic 罕見疾病 AI 研究補助今日截止申請；Workbench 與實驗性 Prompt API 確認 8/17 退場。整體趨勢：生態工具走向標準化與可量測。

## 🧠 Prompt 技巧 & 使用心得
[1] **smevals 評測框架問世**：Willison 與 Prime Radiant 合作推出小型 eval 套件，可跨模型比較 prompt 與 harness 效能。([來源](https://simonwillison.net/2026/Jul/31/))
[2] **Willison 七月電子報公開**：回顧七月 AI 重大事件，含 Claude Code 團隊爐邊對談與 Oxide 播客開放權重討論。([來源](https://simonwillison.net/2026/Aug/2/july-newsletter/))
[3] **Sonnet 5 tokenizer 隱性成本提醒**：新 tokenizer 同文本多產約 30% token，9/1 促銷結束後實際成本跳升幅度將超越帳面漲幅。([來源](https://www.finout.io/blog/claude-sonnet-5-pricing-2026-the-hidden-costs-and-real-savings-behind-the-cost-neutral-launch))

## 🔧 工作流整合案例
[4] **MCP 2026-07-28 無狀態規範持續推送至 Claude 產品線**：月下載量突破 4 億次，TS 與 Python SDK 累計各破 10 億次下載。([來源](https://claude.com/blog/bringing-mcp-2026-07-28-to-claude))
[5] **SDK 記憶體存取標頭更新**：Python、TS、Go、Java 等八套 SDK 統一改用 agent-memory-2026-07-22 標頭，取代舊版。([來源](https://platform.claude.com/docs/en/release-notes/overview))
[6] **OpenCode 成 GitHub 最高星數 AI 編程代理**：累積 182K+ 星，月活 800 萬開發者，支援 75+ 模型供應商。([來源](https://opencode.ai/))

## 🛠️ 新工具 & 套件
[7] **Workbench 與實驗性 Prompt API 確認 8/17 退場**：generate/improve/templatize prompt 三端點將同步下架。([來源](https://platform.claude.com/docs/en/release-notes/overview))
[8] **Anthropic AI for Science 罕見疾病補助今日截止**：提供最高 $50,000 Claude credits，分基礎研究與臨床開發兩軌。([來源](https://www.anthropic.com/news/rare-disease-research-grants))
[9] **Claude Code 訂閱者 50% 額度加成延至 8/19**：持續為重度用戶提供額外用量空間。([來源](https://platform.claude.com/docs/en/release-notes/overview))

## 💬 社群熱門討論
[10] **開放權重公開信論戰**：微軟領銜 235 家企業簽署「Open Weights and American AI Leadership」，Anthropic 未簽並另發立場文。([來源](https://simonwillison.net/2026/Aug/2/open-letters/))
[11] **Amodei 澄清不主張禁止開放權重**：但堅持對最具能力模型須進行安全測試，提出三項政策方向。([來源](https://www.anthropic.com/news/position-open-weights-models))
[12] **HN 討論 MCP 2026-07-28 部署實務**：開發者關注無狀態架構對現有 server 的遷移成本與 serverless 部署優勢。([來源](https://news.ycombinator.com/item?id=49087737))
