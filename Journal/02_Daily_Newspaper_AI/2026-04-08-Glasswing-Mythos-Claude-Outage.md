# AI工作流日報 — 2026-04-08
> 涵蓋範圍：2026-04-07 06:00 ~ 2026-04-08 06:00 (TST)

> 📌 Claude 摘要：今日三大焦點——Anthropic 公布 Project Glasswing 計畫與 Claude Mythos Preview，限定釋出給 50+ 企業用於資安漏洞挖掘；Claude Code v2.1.92 推出 /powerup 互動教學與 MCP 500K 持久化；Claude 4/7 再度大當機 90 分鐘，引發開發者對可靠性的重新評估。此為 Claude 綜合觀察。

## 🧠 Prompt 技巧 & 使用心得

[1] **Simon Willison 力挺 Project Glasswing 策略**：認為限制 Claude Mythos 僅供資安研究員使用是必要之舉，避免濫用。([來源](https://simonwillison.net/2026/Apr/7/project-glasswing/))

[2] **Claude Code v2.1.92 推出 /powerup 互動教學**：終端內動畫課程涵蓋 18 個主題，從入門到進階功能。([來源](https://help.apiyi.com/en/claude-code-v2-1-92-mcp-persistence-powerup-tutorial-en.html))

[3] **per-model /cost 成本分析**：訂閱用戶現可透過 /cost 指令查看每個模型用量與快取命中率細節。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.92))

## 🔧 工作流整合案例

[4] **MCP Tool 結果持久化上限 500K**：透過 `_meta["anthropic/maxResultSizeChars"]` 註解，支援大型資料庫 schema 不截斷。([來源](https://daily1bite.com/en/blog/ai-tutorial/claude-code-april-2026-update))

[5] **Write 工具 diff 效能提升 60%**：針對大型檔案及含 tab/$ 符號的內容，計算速度顯著加快。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.92))

[6] **Bedrock 互動式設定精靈上線**：從登入畫面即可引導 AWS 認證、區域設定與模型鎖定。([來源](https://github.com/anthropics/claude-code/releases/tag/v2.1.92))

## 🛠️ 新工具 & 套件

[7] **Anthropic 公布 Project Glasswing 計畫**：$1 億額度開放 50+ 企業存取 Claude Mythos Preview 挖掘資安漏洞。([來源](https://www.anthropic.com/glasswing))

[8] **Claude Mythos 挖出數千個零日漏洞**：涵蓋所有主要作業系統與瀏覽器，包括 17 年前 FreeBSD 的 RCE 漏洞 (CVE-2026-4747)。([來源](https://thehackernews.com/2026/04/anthropics-claude-mythos-finds.html))

[9] **Glasswing 聯盟成員曝光**：AWS、Apple、Broadcom、Cisco、Google、JPMorgan、微軟、Nvidia、Palo Alto 等共同參與。([來源](https://red.anthropic.com/2026/mythos-preview/))

[10] **headless 模式支援 defer 權限延遲**：PreToolUse hooks 可暫停工具呼叫，用 `-p --resume` 重新評估。([來源](https://daily1bite.com/en/blog/ai-tutorial/claude-code-april-2026-update))

## 💬 社群熱門討論

[11] **Claude 4/7 再度大當機約 90 分鐘**：登入、語音模式、Claude Code 認證全面失效，自 10AM 開始爆量錯誤。([來源](https://www.ibtimes.com.au/claude-ai-down-again-claude-ai-down-again-anthropic-faces-fresh-outage-frustrating-users-april-1865701))

[12] **「Claude Code auth 掛了一半開發者 Twitter 癱瘓」**：開發者把 AI 當日常協作者，當機時產能直接歸零。([來源](https://www.techradar.com/news/live/claude-anthropic-down-outage-april-6-2026))

[13] **Anthropic 切斷 OpenClaw 訂閱方案**：4/4 起 Claude 訂閱無法用於 OpenClaw 等第三方 harness，需改 API 計費。([來源](https://www.theregister.com/2026/04/06/anthropic_closes_door_on_subscription/))

[14] **Anthropic 提供一次性額度補償**：等同月費的額外用量額度，可兌換至 4/17，安撫社群反彈。([來源](https://mlq.ai/news/anthropic-ends-paid-access-for-claude-in-third-party-tools-like-openclaw/))
