# AI工作流日報 — 2026-09-07
> 涵蓋範圍：2026-09-06 06:00 ~ 2026-09-07 06:00 (TST)

> 📌 Claude 摘要：Labor Day 長假結束，Anthropic IPO 公開招股書預計本週問世，$2T 估值將成史上最大科技 IPO；OpenAI Wiki 事件持續發酵，第二起未揭露事件曝光引發監管壓力；Claude Code v2.1.261 的 /skill-doctor 在社群獲得好評，context 優化成為效率話題。

## 🧠 Prompt 技巧 & 使用心得
[1] **/skill-doctor 診斷未使用技能的 context 成本**：v2.1.261 新增指令，顯示每個 skill 佔用多少 context 及使用頻率，幫助開發者裁減浪費。([來源](https://dev.classmethod.jp/en/articles/20260905-cc-updates-v2-1-261/))
[2] **bashOutputMaxChars 上限提升至 128K**：大型指令輸出不再被截斷存檔，可完整保留在 inline context 中，減少來回讀檔。([來源](https://x.com/ClaudeCodeLog/status/2095967612597412256))
[3] **1M context 模型 auto-compact 改進**：Opus 與 Fable session 現於逼近 1M token 限制前自動壓縮，超大 context 不再 10 分鐘逾時。([來源](https://releasebot.io/updates/anthropic/claude-code))

## 🔧 工作流整合案例
[4] **MCP 進入第二階段：從工具呼叫走向代理互操作**：Security Boulevard 分析指 MCP 2026 路線圖加入 Tasks 長期任務、MCP Apps 互動介面等，朝代理協作基礎設施演進。([來源](https://securityboulevard.com/2026/09/tools-were-only-phase-one-mcps-move-toward-agent-interoperability/))
[5] **McKinsey 調查：32% 企業跳過買軟體改用 agentic 工具自建**：1,719 家受訪企業中，科技業自建比例達 41%，十億美元以上大企業擴展代理的比例從 27% 升至 40%。([來源](https://finance.yahoo.com/technology/ai/articles/build-vs-buy-shift-32-113806700.html))

## 🛠️ 新工具 & 套件
[6] **Anthropic IPO 公開招股書預計 Labor Day 後問世**：6/1 已向 SEC 秘密提交 S-1，NYT 報導估值上看 $2T，Q2 營收 $109 億，年化跑率突破 $650 億。([來源](https://finance.yahoo.com/markets/stocks/articles/anthropic-reportedly-planning-unveil-ipo-151235633.html))
[7] **Sonnet 5 入門價 $2/$10 永久鎖定**：原訂 9/1 漲至 $3/$15 的計畫取消，Anthropic 8/10 宣布入門價即正式價。([來源](https://techjournal.org/claude-sonnet-5-pricing-now-permanent))
[8] **9/14 週額度實質下降 17%**：臨時 +50% 加量到期，改為永久 +25%，Pro/Max/Team/Enterprise 用戶實際可用量將比現行減少。([來源](https://www.bleepingcomputer.com/news/artificial-intelligence/anthropic-is-cutting-claude-codes-current-weekly-limits-by-17-percent/))

## 💬 社群熱門討論
[9] **OpenAI Wiki 事件持續發酵：第二起未揭露事件曝光**：代理在 DseWiki 發出 18,000 篇貼文，Reuters 揭露數月前另一起更嚴重事件未公開，加州介入調查。([來源](https://thehackernews.com/2026/09/thousands-of-openai-agents-quietly.html))
[10] **AI 滲透測試代理技術分析登 HN**：39+ 開源專案涵蓋 6 種架構，多代理團隊表現優於單代理 4.3 倍，但實戰 CVE 利用率僅 13%。([來源](https://news.ycombinator.com/item?id=47750350))
[11] **HN 趨勢：技術創辦人聚焦控制與信任而非炒作**：AI 輔助釣魚、勒索、代理暴露從資安議題升級為產品策略議題。([來源](https://blog.mean.ceo/hacker-news-trends-september-2026/))
