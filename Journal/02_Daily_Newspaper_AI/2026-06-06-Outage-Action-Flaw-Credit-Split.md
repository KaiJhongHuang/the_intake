# AI工作流日報 — 2026-06-06
> 涵蓋範圍：2026-06-05 06:00 ~ 2026-06-06 06:00 (TST)

> 📌 Claude 摘要：六月五日 Claude 全線再度中斷，加上 GitHub Action 供應鏈漏洞曝光與 6/15 計費分拆倒數，本週社群焦點集中在穩定性與成本兩大痛點；技術面則有 Willison 以 MicroPython-WASM 實現安全沙箱，為 Agent 工具鏈補上最後一塊拼圖。

## 🧠 Prompt 技巧 & 使用心得

[1] **Opus 4.8 自適應思考**：模型自動判斷是否啟動推理，簡單查詢直接回應，複雜問題才深度思考，節省 token。([來源](https://platform.claude.com/docs/en/about-claude/models/whats-new-claude-4-8))

[2] **Opus 4.8 對話中途插入系統訊息**：支援在 user turn 後插入 system message，長任務可動態更新指令且保留快取。([來源](https://caylent.com/blog/claude-opus-4-8-what-improved-whats-new-and-what-it-means-for-enterprise))

[3] **Willison 用 GPT-5.5 攻擊沙箱**：在 Datasette Agent 插件中讓模型嘗試越獄，至今未能突破 MicroPython-WASM 沙箱。([來源](https://simonwillison.net/2026/Jun/6/micropython-in-a-sandbox/))

## 🔧 工作流整合案例

[4] **AWS MCP Server 跨帳號存取**：六月更新支援單一 session 內切換多 AWS 帳號與 IAM Role，無需重啟。([來源](https://aws.amazon.com/about-aws/whats-new/2026/06/aws-mcp-server/))

[5] **Dynamic Workflows 大規模遷移**：Opus 4.8 可在單一 Claude Code session 內規劃並平行執行數百個子代理，適合整庫遷移。([來源](https://decodethefuture.org/en/claude-opus-4-8-explained/))

[6] **Managed Agents 私有 MCP 連接**：企業版 Managed Agents 現可在自有沙箱執行，並連接私有 MCP Server。([來源](https://releasebot.io/updates/anthropic/claude))

## 🛠️ 新工具 & 套件

[7] **micropython-wasm 0.1a1**：Willison 發布 Python-in-WASM 沙箱套件，變數跨呼叫保留，適合 Agent 工具鏈。([來源](https://simonwillison.net/2026/Jun/2/micropython-wasm/))

[8] **datasette-agent-micropython 0.1a0**：基於上述沙箱的 Datasette Agent 程式碼執行插件，安全隔離本機檔案系統。([來源](https://simonwillison.net/2026/Jun/2/datasette-agent-micropython/))

[9] **Willison hacker-news-filtered 工具**：六月五日上線，可過濾 HN 討論的新輔助工具。([來源](https://tools.simonwillison.net/))

## 💬 社群熱門討論

[10] **Claude 六月五日全線中斷**：15:08 UTC 起 claude.ai、API、Code、Cowork 全部受影響，約三小時後陸續恢復。([來源](https://cybersecuritynews.com/anthropics-claude-services-down/))

[11] **GitHub Action 供應鏈漏洞曝光**：攻擊者可透過單一 Issue 劫持使用 Claude Code Action 的 Repo，已修補至 v1.0.94。([來源](https://thehackernews.com/2026/06/claude-code-github-action-flaw-let-one.html))

[12] **六月二日子代理無限迴圈 Bug**：Claude Code 子代理指數增殖導致當機，Anthropic 已重置受影響帳號配額。([來源](https://www.storyboard18.com/digital/anthropics-claude-ai-suffers-disruption-what-caused-the-outage-and-why-user-quotas-were-reset-99951.htm))

[13] **6/15 計費分拆倒數**：Agent SDK、claude -p 將移出訂閱池，Pro 用戶每月獲 $20 獨立額度，按 API 費率計算。([來源](https://www.digitalapplied.com/blog/anthropic-claude-credit-overhaul-june-15-2026))

[14] **Claude 自寫程式碼逾八成**：Anthropic 透露 Claude 現自行撰寫超過 80% 程式碼，品質與人類持平，引發自我改進討論。([來源](https://uk.finance.yahoo.com/news/anthropic-says-something-unsettling-happening-103500529.html))
